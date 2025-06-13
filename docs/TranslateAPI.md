# \TranslateAPI

All URIs are relative to *https://kagi.com/api/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TranslateAlternatives**](TranslateAPI.md#TranslateAlternatives) | **Post** /alternative-translations | Alternative Translations
[**TranslateDetect**](TranslateAPI.md#TranslateDetect) | **Post** /api/detect | Language Detection
[**TranslateDetectGet**](TranslateAPI.md#TranslateDetectGet) | **Get** /api/detect | Language Detection API
[**TranslateDictionary**](TranslateAPI.md#TranslateDictionary) | **Post** /api/dictionary | Dictionary
[**TranslateFile**](TranslateAPI.md#TranslateFile) | **Post** /api/translate-file | File Translation
[**TranslateListLanguages**](TranslateAPI.md#TranslateListLanguages) | **Get** /api/list-languages | List Supported Languages
[**TranslateListLanguagesPost**](TranslateAPI.md#TranslateListLanguagesPost) | **Post** /api/list-languages | List Supported Languages API (POST method)
[**TranslateProofRead**](TranslateAPI.md#TranslateProofRead) | **Post** /api/proofread | Text Proofreading
[**TranslateProofReadGet**](TranslateAPI.md#TranslateProofReadGet) | **Get** /api/proofread | Text Proofreading API
[**TranslateRomanize**](TranslateAPI.md#TranslateRomanize) | **Get** /api/romanize | Text Romanization
[**TranslateSpeech**](TranslateAPI.md#TranslateSpeech) | **Get** /api/speech | Text-to-Speech
[**TranslateTextAlignments**](TranslateAPI.md#TranslateTextAlignments) | **Post** /api/text-alignments | Text Alignments
[**TranslateTransacribe**](TranslateAPI.md#TranslateTransacribe) | **Post** /api/transcribe | Audio Transcription
[**TranslateWordInsights**](TranslateAPI.md#TranslateWordInsights) | **Post** /api/word-insights | Word Insights



## TranslateAlternatives

> TranslateAlternatives200Response TranslateAlternatives(ctx).OriginalText(originalText).ExistingTranslation(existingTranslation).TargetLang(targetLang).SourceLang(sourceLang).TargetExplanationLanguage(targetExplanationLanguage).TranslationOptions(translationOptions).PartialTranslation(partialTranslation).Execute()

Alternative Translations



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
	originalText := "originalText_example" // string | Original text to translate. In partial mode, this serves as context for the phrase (may be ignored if not relevant).
	existingTranslation := "existingTranslation_example" // string | In standard mode: existing full translation of the original text. In partial mode: the specific phrase you want alternative ways to express.
	targetLang := "targetLang_example" // string | Target language code (ISO-639) for the translations
	sourceLang := "sourceLang_example" // string | Source language code (ISO-639) of the original text. Helps provide more accurate alternatives by understanding language-specific nuances. (optional)
	targetExplanationLanguage := "targetExplanationLanguage_example" // string | Language code (ISO-639) for the explanations (optional) (default to "en")
	translationOptions := "translationOptions_example" // string | JSON string with translation customization options: - `formality`: Controls formality level [\\\"default\\\", \\\"more\\\", \\\"less\\\"] - `speaker_gender`: Gender of the speaker [\\\"unknown\\\", \\\"feminine\\\", \\\"masculine\\\", \\\"neutral\\\"] - `addressee_gender`: Gender of the person being addressed [\\\"unknown\\\", \\\"feminine\\\", \\\"masculine\\\", \\\"neutral\\\"] - `style`: Translation style [\\\"natural\\\", \\\"literal\\\"] - `context`: Additional context to inform translation (string)  (optional)
	partialTranslation := "partialTranslation_example" // string | Mode switch: 'false' for standard mode (full translation alternatives), 'true' for partial mode (alternative ways to phrase a specific part) (optional) (default to "false")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateAlternatives(context.Background()).OriginalText(originalText).ExistingTranslation(existingTranslation).TargetLang(targetLang).SourceLang(sourceLang).TargetExplanationLanguage(targetExplanationLanguage).TranslationOptions(translationOptions).PartialTranslation(partialTranslation).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateAlternatives``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateAlternatives`: TranslateAlternatives200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateAlternatives`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateAlternativesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **originalText** | **string** | Original text to translate. In partial mode, this serves as context for the phrase (may be ignored if not relevant). | 
 **existingTranslation** | **string** | In standard mode: existing full translation of the original text. In partial mode: the specific phrase you want alternative ways to express. | 
 **targetLang** | **string** | Target language code (ISO-639) for the translations | 
 **sourceLang** | **string** | Source language code (ISO-639) of the original text. Helps provide more accurate alternatives by understanding language-specific nuances. | 
 **targetExplanationLanguage** | **string** | Language code (ISO-639) for the explanations | [default to &quot;en&quot;]
 **translationOptions** | **string** | JSON string with translation customization options: - &#x60;formality&#x60;: Controls formality level [\\\&quot;default\\\&quot;, \\\&quot;more\\\&quot;, \\\&quot;less\\\&quot;] - &#x60;speaker_gender&#x60;: Gender of the speaker [\\\&quot;unknown\\\&quot;, \\\&quot;feminine\\\&quot;, \\\&quot;masculine\\\&quot;, \\\&quot;neutral\\\&quot;] - &#x60;addressee_gender&#x60;: Gender of the person being addressed [\\\&quot;unknown\\\&quot;, \\\&quot;feminine\\\&quot;, \\\&quot;masculine\\\&quot;, \\\&quot;neutral\\\&quot;] - &#x60;style&#x60;: Translation style [\\\&quot;natural\\\&quot;, \\\&quot;literal\\\&quot;] - &#x60;context&#x60;: Additional context to inform translation (string)  | 
 **partialTranslation** | **string** | Mode switch: &#39;false&#39; for standard mode (full translation alternatives), &#39;true&#39; for partial mode (alternative ways to phrase a specific part) | [default to &quot;false&quot;]

### Return type

[**TranslateAlternatives200Response**](TranslateAlternatives200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateDetect

> TranslateDetectGet200Response TranslateDetect(ctx).TranslateDetectRequest(translateDetectRequest).Execute()

Language Detection



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
	translateDetectRequest := *openapiclient.NewTranslateDetectRequest("Text_example") // TranslateDetectRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateDetect(context.Background()).TranslateDetectRequest(translateDetectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateDetect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateDetect`: TranslateDetectGet200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateDetect`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateDetectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **translateDetectRequest** | [**TranslateDetectRequest**](TranslateDetectRequest.md) |  | 

### Return type

[**TranslateDetectGet200Response**](TranslateDetectGet200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateDetectGet

> TranslateDetectGet200Response TranslateDetectGet(ctx).Text(text).Execute()

Language Detection API



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
	text := "Hello world" // string | Text to detect language from

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateDetectGet(context.Background()).Text(text).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateDetectGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateDetectGet`: TranslateDetectGet200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateDetectGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateDetectGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | **string** | Text to detect language from | 

### Return type

[**TranslateDetectGet200Response**](TranslateDetectGet200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateDictionary

> TranslateDictionary200Response TranslateDictionary(ctx).TranslateDictionaryRequest(translateDictionaryRequest).Execute()

Dictionary



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
	translateDictionaryRequest := *openapiclient.NewTranslateDictionaryRequest("Word_example") // TranslateDictionaryRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateDictionary(context.Background()).TranslateDictionaryRequest(translateDictionaryRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateDictionary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateDictionary`: TranslateDictionary200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateDictionary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateDictionaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **translateDictionaryRequest** | [**TranslateDictionaryRequest**](TranslateDictionaryRequest.md) |  | 

### Return type

[**TranslateDictionary200Response**](TranslateDictionary200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateFile

> *os.File TranslateFile(ctx).File(file).From(from).To(to).IsMultiLanguage(isMultiLanguage).AdditionalLanguages(additionalLanguages).Execute()

File Translation



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
	file := os.NewFile(1234, "some_file") // *os.File | The file to translate. Supported formats include: - Microsoft Word (.doc, .docx) - Text (.txt) - CSV spreadsheets (.csv) - Markdown (.md) 
	from := "from_example" // string | Source language code (ISO-639) or \\\"auto\\\" for automatic detection (optional) (default to "auto")
	to := "to_example" // string | Target language code (ISO-639) (optional) (default to "en")
	isMultiLanguage := true // bool | If true, creates a file with multiple languages side by side (optional)
	additionalLanguages := []string{"Inner_example"} // []string | Additional target languages for multi-language translation (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateFile(context.Background()).File(file).From(from).To(to).IsMultiLanguage(isMultiLanguage).AdditionalLanguages(additionalLanguages).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateFile`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateFile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | The file to translate. Supported formats include: - Microsoft Word (.doc, .docx) - Text (.txt) - CSV spreadsheets (.csv) - Markdown (.md)  | 
 **from** | **string** | Source language code (ISO-639) or \\\&quot;auto\\\&quot; for automatic detection | [default to &quot;auto&quot;]
 **to** | **string** | Target language code (ISO-639) | [default to &quot;en&quot;]
 **isMultiLanguage** | **bool** | If true, creates a file with multiple languages side by side | 
 **additionalLanguages** | **[]string** | Additional target languages for multi-language translation | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateListLanguages

> []TranslateListLanguages200ResponseInner TranslateListLanguages(ctx).Type_(type_).Locale(locale).Execute()

List Supported Languages



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
	type_ := "type__example" // string | Type of languages to return ('source' or 'target') (optional)
	locale := "locale_example" // string | Locale code to use for language names (e.g., 'en', 'de', 'fr') (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateListLanguages(context.Background()).Type_(type_).Locale(locale).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateListLanguages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateListLanguages`: []TranslateListLanguages200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateListLanguages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateListLanguagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **string** | Type of languages to return (&#39;source&#39; or &#39;target&#39;) | 
 **locale** | **string** | Locale code to use for language names (e.g., &#39;en&#39;, &#39;de&#39;, &#39;fr&#39;) | 

### Return type

[**[]TranslateListLanguages200ResponseInner**](TranslateListLanguages200ResponseInner.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateListLanguagesPost

> []Language TranslateListLanguagesPost(ctx).TranslateListLanguagesPostRequest(translateListLanguagesPostRequest).Execute()

List Supported Languages API (POST method)



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
	translateListLanguagesPostRequest := *openapiclient.NewTranslateListLanguagesPostRequest() // TranslateListLanguagesPostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateListLanguagesPost(context.Background()).TranslateListLanguagesPostRequest(translateListLanguagesPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateListLanguagesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateListLanguagesPost`: []Language
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateListLanguagesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateListLanguagesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **translateListLanguagesPostRequest** | [**TranslateListLanguagesPostRequest**](TranslateListLanguagesPostRequest.md) |  | 

### Return type

[**[]Language**](Language.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateProofRead

> TranslateProofReadGet200Response TranslateProofRead(ctx).TranslateProofReadRequest(translateProofReadRequest).Execute()

Text Proofreading



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
	translateProofReadRequest := *openapiclient.NewTranslateProofReadRequest("Text_example") // TranslateProofReadRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateProofRead(context.Background()).TranslateProofReadRequest(translateProofReadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateProofRead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateProofRead`: TranslateProofReadGet200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateProofRead`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateProofReadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **translateProofReadRequest** | [**TranslateProofReadRequest**](TranslateProofReadRequest.md) |  | 

### Return type

[**TranslateProofReadGet200Response**](TranslateProofReadGet200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateProofReadGet

> TranslateProofReadGet200Response TranslateProofReadGet(ctx).Text(text).SourceLang(sourceLang).ExplanationLanguage(explanationLanguage).Stream(stream).Execute()

Text Proofreading API



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
	text := "text_example" // string | Text content to proofread
	sourceLang := "sourceLang_example" // string | Source language code (ISO-639) or \"auto\" for automatic detection (optional)
	explanationLanguage := "explanationLanguage_example" // string | Language code (ISO-639) for explanations and analysis. If not provided, explanations will be in the same language as the source text. (optional)
	stream := true // bool | Whether to stream the response as Server-Sent Events (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateProofReadGet(context.Background()).Text(text).SourceLang(sourceLang).ExplanationLanguage(explanationLanguage).Stream(stream).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateProofReadGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateProofReadGet`: TranslateProofReadGet200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateProofReadGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateProofReadGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | **string** | Text content to proofread | 
 **sourceLang** | **string** | Source language code (ISO-639) or \&quot;auto\&quot; for automatic detection | 
 **explanationLanguage** | **string** | Language code (ISO-639) for explanations and analysis. If not provided, explanations will be in the same language as the source text. | 
 **stream** | **bool** | Whether to stream the response as Server-Sent Events | 

### Return type

[**TranslateProofReadGet200Response**](TranslateProofReadGet200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateRomanize

> TranslateRomanize200Response TranslateRomanize(ctx).Text(text).Language(language).Execute()

Text Romanization



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
	text := "こんにちは" // string | Text to romanize
	language := "ja" // string | Language code (ISO-639) of the source text

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateRomanize(context.Background()).Text(text).Language(language).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateRomanize``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateRomanize`: TranslateRomanize200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateRomanize`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateRomanizeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | **string** | Text to romanize | 
 **language** | **string** | Language code (ISO-639) of the source text | 

### Return type

[**TranslateRomanize200Response**](TranslateRomanize200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateSpeech

> *os.File TranslateSpeech(ctx).Text(text).Language(language).Voice(voice).Raw(raw).Execute()

Text-to-Speech



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
	text := "Hello, how are you today?" // string | Text to convert to speech
	language := "en" // string | Language code (ISO-639) for speech synthesis. The API supports a wide range of languages and automatically applies appropriate voice prompts for each language. (optional)
	voice := "coral" // string | Voice to use for speech synthesis (optional) (default to "coral")
	raw := true // bool | If true, returns the raw audio stream without WAV header processing (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateSpeech(context.Background()).Text(text).Language(language).Voice(voice).Raw(raw).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateSpeech``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateSpeech`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateSpeech`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateSpeechRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **text** | **string** | Text to convert to speech | 
 **language** | **string** | Language code (ISO-639) for speech synthesis. The API supports a wide range of languages and automatically applies appropriate voice prompts for each language. | 
 **voice** | **string** | Voice to use for speech synthesis | [default to &quot;coral&quot;]
 **raw** | **bool** | If true, returns the raw audio stream without WAV header processing | [default to false]

### Return type

[***os.File**](*os.File.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: audio/x-wav, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateTextAlignments

> TranslateTextAlignments200Response TranslateTextAlignments(ctx).SourceText(sourceText).TargetText(targetText).Execute()

Text Alignments



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
	sourceText := "sourceText_example" // string | Source text to align
	targetText := "targetText_example" // string | Target text to align with the source

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateTextAlignments(context.Background()).SourceText(sourceText).TargetText(targetText).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateTextAlignments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateTextAlignments`: TranslateTextAlignments200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateTextAlignments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateTextAlignmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sourceText** | **string** | Source text to align | 
 **targetText** | **string** | Target text to align with the source | 

### Return type

[**TranslateTextAlignments200Response**](TranslateTextAlignments200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateTransacribe

> TranslateTransacribe200Response TranslateTransacribe(ctx).Body(body).Language(language).Execute()

Audio Transcription



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
	body := os.NewFile(1234, "some_file") // *os.File | 
	language := "en" // string | Language code (ISO-639) of the audio content. Use \"auto\" for automatic language detection. Specifying the correct language can improve transcription accuracy.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateTransacribe(context.Background()).Body(body).Language(language).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateTransacribe``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateTransacribe`: TranslateTransacribe200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateTransacribe`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateTransacribeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | ***os.File** |  | 
 **language** | **string** | Language code (ISO-639) of the audio content. Use \&quot;auto\&quot; for automatic language detection. Specifying the correct language can improve transcription accuracy.  | 

### Return type

[**TranslateTransacribe200Response**](TranslateTransacribe200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: audio/*
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateWordInsights

> TranslateWordInsights200Response TranslateWordInsights(ctx).OriginalText(originalText).TranslatedText(translatedText).TargetExplanationLanguage(targetExplanationLanguage).TranslationOptions(translationOptions).Execute()

Word Insights



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
	originalText := "originalText_example" // string | Source text that was translated
	translatedText := "translatedText_example" // string | Translated text to analyze for linguistic insights
	targetExplanationLanguage := "targetExplanationLanguage_example" // string | Language code (ISO-639) for the explanations and type labels (optional) (default to "en")
	translationOptions := "translationOptions_example" // string | Optional JSON string with translation options that provide context for the insights. Can include formality, gender preferences, and style.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.TranslateWordInsights(context.Background()).OriginalText(originalText).TranslatedText(translatedText).TargetExplanationLanguage(targetExplanationLanguage).TranslationOptions(translationOptions).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.TranslateWordInsights``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranslateWordInsights`: TranslateWordInsights200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.TranslateWordInsights`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateWordInsightsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **originalText** | **string** | Source text that was translated | 
 **translatedText** | **string** | Translated text to analyze for linguistic insights | 
 **targetExplanationLanguage** | **string** | Language code (ISO-639) for the explanations and type labels | [default to &quot;en&quot;]
 **translationOptions** | **string** | Optional JSON string with translation options that provide context for the insights. Can include formality, gender preferences, and style.  | 

### Return type

[**TranslateWordInsights200Response**](TranslateWordInsights200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

