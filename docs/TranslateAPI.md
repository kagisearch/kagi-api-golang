# \TranslateAPI

All URIs are relative to *https://kagi.com/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Translate**](TranslateAPI.md#Translate) | **Post** /api/translate | Text Translation
[**TranslateAlternatives**](TranslateAPI.md#TranslateAlternatives) | **Post** /alternative-translations | Alternative Translations
[**TranslateDetect**](TranslateAPI.md#TranslateDetect) | **Post** /api/detect | Language Detection
[**TranslateDictionary**](TranslateAPI.md#TranslateDictionary) | **Post** /api/dictionary | Dictionary
[**TranslateListLanguages**](TranslateAPI.md#TranslateListLanguages) | **Get** /api/list-languages | List Supported Languages
[**TranslateRomanize**](TranslateAPI.md#TranslateRomanize) | **Get** /api/romanize | Text Romanization
[**TranslateWordInsights**](TranslateAPI.md#TranslateWordInsights) | **Post** /api/word-insights | Word Insights



## Translate

> Translate200Response Translate(ctx).TranslateRequest(translateRequest).Execute()

Text Translation



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kagisearch/kagi-api-golang"
)

func main() {
	translateRequest := *openapiclient.NewTranslateRequest(openapiclient.translate_request_text{ArrayOfString: new([]string)}) // TranslateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TranslateAPI.Translate(context.Background()).TranslateRequest(translateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TranslateAPI.Translate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Translate`: Translate200Response
	fmt.Fprintf(os.Stdout, "Response from `TranslateAPI.Translate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranslateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **translateRequest** | [**TranslateRequest**](TranslateRequest.md) |  | 

### Return type

[**Translate200Response**](Translate200Response.md)

### Authorization

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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
	openapiclient "github.com/kagisearch/kagi-api-golang"
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

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranslateDetect

> TranslateDetect200Response TranslateDetect(ctx).TranslateDetectRequest(translateDetectRequest).Execute()

Language Detection



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/kagisearch/kagi-api-golang"
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
	// response from `TranslateDetect`: TranslateDetect200Response
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

[**TranslateDetect200Response**](TranslateDetect200Response.md)

### Authorization

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: application/json
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
	openapiclient "github.com/kagisearch/kagi-api-golang"
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

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/plain

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
	openapiclient "github.com/kagisearch/kagi-api-golang"
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

[kagi-translate](../README.md#kagi-translate)

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
	openapiclient "github.com/kagisearch/kagi-api-golang"
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

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: Not defined
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
	openapiclient "github.com/kagisearch/kagi-api-golang"
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

[kagi-translate](../README.md#kagi-translate)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

