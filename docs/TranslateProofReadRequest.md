# TranslateProofReadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Text content to proofread | 
**SourceLang** | Pointer to **string** | Source language code (ISO-639) or \&quot;auto\&quot; for automatic detection | [optional] [default to "auto"]
**ExplanationLanguage** | Pointer to **string** | Language code (ISO-639) for explanations and analysis. If not provided, explanations will be in the same language as the source text. | [optional] 
**Stream** | Pointer to **bool** | Whether to stream the response as Server-Sent Events | [optional] [default to false]

## Methods

### NewTranslateProofReadRequest

`func NewTranslateProofReadRequest(text string, ) *TranslateProofReadRequest`

NewTranslateProofReadRequest instantiates a new TranslateProofReadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateProofReadRequestWithDefaults

`func NewTranslateProofReadRequestWithDefaults() *TranslateProofReadRequest`

NewTranslateProofReadRequestWithDefaults instantiates a new TranslateProofReadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *TranslateProofReadRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TranslateProofReadRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TranslateProofReadRequest) SetText(v string)`

SetText sets Text field to given value.


### GetSourceLang

`func (o *TranslateProofReadRequest) GetSourceLang() string`

GetSourceLang returns the SourceLang field if non-nil, zero value otherwise.

### GetSourceLangOk

`func (o *TranslateProofReadRequest) GetSourceLangOk() (*string, bool)`

GetSourceLangOk returns a tuple with the SourceLang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceLang

`func (o *TranslateProofReadRequest) SetSourceLang(v string)`

SetSourceLang sets SourceLang field to given value.

### HasSourceLang

`func (o *TranslateProofReadRequest) HasSourceLang() bool`

HasSourceLang returns a boolean if a field has been set.

### GetExplanationLanguage

`func (o *TranslateProofReadRequest) GetExplanationLanguage() string`

GetExplanationLanguage returns the ExplanationLanguage field if non-nil, zero value otherwise.

### GetExplanationLanguageOk

`func (o *TranslateProofReadRequest) GetExplanationLanguageOk() (*string, bool)`

GetExplanationLanguageOk returns a tuple with the ExplanationLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplanationLanguage

`func (o *TranslateProofReadRequest) SetExplanationLanguage(v string)`

SetExplanationLanguage sets ExplanationLanguage field to given value.

### HasExplanationLanguage

`func (o *TranslateProofReadRequest) HasExplanationLanguage() bool`

HasExplanationLanguage returns a boolean if a field has been set.

### GetStream

`func (o *TranslateProofReadRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *TranslateProofReadRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *TranslateProofReadRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *TranslateProofReadRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


