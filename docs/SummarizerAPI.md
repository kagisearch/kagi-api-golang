# \SummarizerAPI

All URIs are relative to *https://kagi.com/api/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SummarizeText**](SummarizerAPI.md#SummarizeText) | **Post** /summarize | Upload text to summarize.
[**SummarizeURL**](SummarizerAPI.md#SummarizeURL) | **Get** /summarize | Get a summary for a URL



## SummarizeText

> Summary SummarizeText(ctx).UploadText(uploadText).Engine(engine).SummaryType(summaryType).TargetLanguage(targetLanguage).Cache(cache).Execute()

Upload text to summarize.

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
	uploadText := *openapiclient.NewUploadText("Text_example") // UploadText | Text to summarize
	engine := "engine_example" // string | Different summarization engines are provided that will give you choices over the \"flavor\" of the summarization text. (optional) (default to "cecil")
	summaryType := "summaryType_example" // string | Different summary types are provided that control the structure of the summary output. (optional) (default to "summary")
	targetLanguage := "targetLanguage_example" // string | The summarizer can translate the output into a desired language, using the table of supported language codes below.  If no language is specified, the document's original language is allowed to influence the summarizer's output. Specifying a language will add an explicit translation step, to translate the summary to the desired language.  For example, if a document is mostly written in Spanish, the summary output may itself be in Spanish or contain Spanish passages. Specifying \"EN\" will ensure all passages are translated as English.  (optional)
	cache := true // bool | Whether to allow cached requests & responses. (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SummarizerAPI.SummarizeText(context.Background()).UploadText(uploadText).Engine(engine).SummaryType(summaryType).TargetLanguage(targetLanguage).Cache(cache).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SummarizerAPI.SummarizeText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SummarizeText`: Summary
	fmt.Fprintf(os.Stdout, "Response from `SummarizerAPI.SummarizeText`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSummarizeTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uploadText** | [**UploadText**](UploadText.md) | Text to summarize | 
 **engine** | **string** | Different summarization engines are provided that will give you choices over the \&quot;flavor\&quot; of the summarization text. | [default to &quot;cecil&quot;]
 **summaryType** | **string** | Different summary types are provided that control the structure of the summary output. | [default to &quot;summary&quot;]
 **targetLanguage** | **string** | The summarizer can translate the output into a desired language, using the table of supported language codes below.  If no language is specified, the document&#39;s original language is allowed to influence the summarizer&#39;s output. Specifying a language will add an explicit translation step, to translate the summary to the desired language.  For example, if a document is mostly written in Spanish, the summary output may itself be in Spanish or contain Spanish passages. Specifying \&quot;EN\&quot; will ensure all passages are translated as English.  | 
 **cache** | **bool** | Whether to allow cached requests &amp; responses. | [default to true]

### Return type

[**Summary**](Summary.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: application/json, x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SummarizeURL

> Summary SummarizeURL(ctx).Url(url).Engine(engine).SummaryType(summaryType).TargetLanguage(targetLanguage).Cache(cache).Execute()

Get a summary for a URL

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
	url := "url_example" // string | A URL to a document to summarize.
	engine := "engine_example" // string | Different summarization engines are provided that will give you choices over the \"flavor\" of the summarization text. (optional) (default to "cecil")
	summaryType := "summaryType_example" // string | Different summary types are provided that control the structure of the summary output. (optional) (default to "summary")
	targetLanguage := "targetLanguage_example" // string | The summarizer can translate the output into a desired language, using the table of supported language codes below.  If no language is specified, the document's original language is allowed to influence the summarizer's output. Specifying a language will add an explicit translation step, to translate the summary to the desired language.  For example, if a document is mostly written in Spanish, the summary output may itself be in Spanish or contain Spanish passages. Specifying \"EN\" will ensure all passages are translated as English.  (optional)
	cache := true // bool | Whether to allow cached requests & responses. (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SummarizerAPI.SummarizeURL(context.Background()).Url(url).Engine(engine).SummaryType(summaryType).TargetLanguage(targetLanguage).Cache(cache).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SummarizerAPI.SummarizeURL``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SummarizeURL`: Summary
	fmt.Fprintf(os.Stdout, "Response from `SummarizerAPI.SummarizeURL`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSummarizeURLRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **url** | **string** | A URL to a document to summarize. | 
 **engine** | **string** | Different summarization engines are provided that will give you choices over the \&quot;flavor\&quot; of the summarization text. | [default to &quot;cecil&quot;]
 **summaryType** | **string** | Different summary types are provided that control the structure of the summary output. | [default to &quot;summary&quot;]
 **targetLanguage** | **string** | The summarizer can translate the output into a desired language, using the table of supported language codes below.  If no language is specified, the document&#39;s original language is allowed to influence the summarizer&#39;s output. Specifying a language will add an explicit translation step, to translate the summary to the desired language.  For example, if a document is mostly written in Spanish, the summary output may itself be in Spanish or contain Spanish passages. Specifying \&quot;EN\&quot; will ensure all passages are translated as English.  | 
 **cache** | **bool** | Whether to allow cached requests &amp; responses. | [default to true]

### Return type

[**Summary**](Summary.md)

### Authorization

[kagi](../README.md#kagi)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

