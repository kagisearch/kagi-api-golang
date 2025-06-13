# \SearchAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SuperSearch**](SearchAPI.md#SuperSearch) | **Get** /search | Perform a search of the web.



## SuperSearch

> SuperSearch200Response SuperSearch(ctx).SuperSearchRequest(superSearchRequest).Execute()

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
	superSearchRequest := *openapiclient.NewSuperSearchRequest("Query_example") // SuperSearchRequest | Contains the search query to run

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SuperSearch(context.Background()).SuperSearchRequest(superSearchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SuperSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuperSearch`: SuperSearch200Response
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SuperSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSuperSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **superSearchRequest** | [**SuperSearchRequest**](SuperSearchRequest.md) | Contains the search query to run | 

### Return type

[**SuperSearch200Response**](SuperSearch200Response.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

