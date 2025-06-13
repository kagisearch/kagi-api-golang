# \SearchAPI

All URIs are relative to *https://kagi.com/api/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Search**](SearchAPI.md#Search) | **Get** /search | Perform a search.
[**SuperSearch**](SearchAPI.md#SuperSearch) | **Get** /v1/search | Perform a super charged search.



## Search

> Search200Response Search(ctx).Q(q).Limit(limit).Execute()

Perform a search.

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
	q := "q_example" // string | A query used to perform the search.
	limit := int32(56) // int32 | Limit number of search results. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.Search(context.Background()).Q(q).Limit(limit).Execute()
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
 **q** | **string** | A query used to perform the search. | 
 **limit** | **int32** | Limit number of search results. | 

### Return type

[**Search200Response**](Search200Response.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuperSearch

> SuperSearch200Response SuperSearch(ctx).SuperSearchRequest(superSearchRequest).Execute()

Perform a super charged search.

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

