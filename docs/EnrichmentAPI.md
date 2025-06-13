# \EnrichmentAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EnrichSearch**](EnrichmentAPI.md#EnrichSearch) | **Get** /enrich/{type} | Get enriched search results



## EnrichSearch

> EnrichSearch200Response EnrichSearch(ctx, type_).Q(q).Execute()

Get enriched search results

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
	q := "steve jobs" // string | Query to enrich
	type_ := "type__example" // string | Enrich with 'web' results or 'news' results (default to "web")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnrichmentAPI.EnrichSearch(context.Background(), type_).Q(q).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnrichmentAPI.EnrichSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnrichSearch`: EnrichSearch200Response
	fmt.Fprintf(os.Stdout, "Response from `EnrichmentAPI.EnrichSearch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**type_** | **string** | Enrich with &#39;web&#39; results or &#39;news&#39; results | [default to &quot;web&quot;]

### Other Parameters

Other parameters are passed through a pointer to a apiEnrichSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **string** | Query to enrich | 


### Return type

[**EnrichSearch200Response**](EnrichSearch200Response.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

