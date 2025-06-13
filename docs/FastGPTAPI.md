# \FastGPTAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FastGPT**](FastGPTAPI.md#FastGPT) | **Post** /fastgpt | Answer a query.



## FastGPT

> FastGPT200Response FastGPT(ctx).FastGPTRequest(fastGPTRequest).Execute()

Answer a query.



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
	fastGPTRequest := *openapiclient.NewFastGPTRequest("Query_example") // FastGPTRequest | Contains the query to process.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FastGPTAPI.FastGPT(context.Background()).FastGPTRequest(fastGPTRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FastGPTAPI.FastGPT``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FastGPT`: FastGPT200Response
	fmt.Fprintf(os.Stdout, "Response from `FastGPTAPI.FastGPT`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFastGPTRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fastGPTRequest** | [**FastGPTRequest**](FastGPTRequest.md) | Contains the query to process. | 

### Return type

[**FastGPT200Response**](FastGPT200Response.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

