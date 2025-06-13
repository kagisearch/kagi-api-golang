# \SearchAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Search**](SearchAPI.md#Search) | **Get** /search | Perform a search of the web.



## Search

> Search200Response Search(ctx).SearchRequest(searchRequest).Execute()

Perform a search of the web.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kagisearch/api-clients/out/go"
)

func main() {
	searchRequest := *openapiclient.NewSearchRequest("Query_example") // SearchRequest | Contains the search query to run

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.Search(context.Background()).SearchRequest(searchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.Search``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Search`: Search200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.Search`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchRequest** | [**SearchRequest**](SearchRequest.md) | Contains the search query to run | 

### Return type

[**Search200Response**](Search200Response.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

