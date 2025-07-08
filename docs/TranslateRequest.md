# TranslateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | [**TranslateRequestText**](TranslateRequestText.md) |  | 
**SourceLang** | Pointer to **string** | Source language code (ISO-639) or \&quot;auto\&quot; for automatic detection | [optional] [default to "auto"]
**TargetLang** | Pointer to **string** | Target language code (ISO-639) | [optional] [default to "en"]
**From** | Pointer to **string** | Legacy parameter for source language (use source_lang instead) | [optional] 
**To** | Pointer to **string** | Legacy parameter for target language (use target_lang instead) | [optional] 
**Context** | Pointer to **string** | Additional context to improve translation accuracy | [optional] 
**PreserveFormatting** | Pointer to **bool** | Whether to preserve original text formatting | [optional] [default to false]
**Formality** | Pointer to **string** | Level of formality in translation. All formality levels are supported for all language pairs. &#39;prefer_more&#39; is same as &#39;more&#39;, and &#39;prefer_less&#39; is same as &#39;less&#39; (included for backwards compatibility). | [optional] [default to "default"]
**SpeakerGender** | Pointer to **string** | Gender of the speaker for languages with gender-specific expressions | [optional] [default to "unknown"]
**AddresseeGender** | Pointer to **string** | Gender of the addressee for languages with gender-specific expressions | [optional] [default to "unknown"]
**TranslationStyle** | Pointer to **string** | Style of translation (natural for fluency, literal for exactness) | [optional] [default to "natural"]
**PredictedLanguage** | Pointer to **string** | Pre-detected source language (if available) | [optional] 
**Prediction** | Pointer to **string** | Pre-generated translation (if available) | [optional] 
**Stream** | Pointer to **bool** | Whether to stream the response as Server-Sent Events | [optional] [default to false]
**DictionaryLanguage** | Pointer to **string** | Language code for dictionary definitions (if not provided, the source language will be used) | [optional] 

## Methods

### NewTranslateRequest

`func NewTranslateRequest(text TranslateRequestText, ) *TranslateRequest`

NewTranslateRequest instantiates a new TranslateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateRequestWithDefaults

`func NewTranslateRequestWithDefaults() *TranslateRequest`

NewTranslateRequestWithDefaults instantiates a new TranslateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *TranslateRequest) GetText() TranslateRequestText`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TranslateRequest) GetTextOk() (*TranslateRequestText, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TranslateRequest) SetText(v TranslateRequestText)`

SetText sets Text field to given value.


### GetSourceLang

`func (o *TranslateRequest) GetSourceLang() string`

GetSourceLang returns the SourceLang field if non-nil, zero value otherwise.

### GetSourceLangOk

`func (o *TranslateRequest) GetSourceLangOk() (*string, bool)`

GetSourceLangOk returns a tuple with the SourceLang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceLang

`func (o *TranslateRequest) SetSourceLang(v string)`

SetSourceLang sets SourceLang field to given value.

### HasSourceLang

`func (o *TranslateRequest) HasSourceLang() bool`

HasSourceLang returns a boolean if a field has been set.

### GetTargetLang

`func (o *TranslateRequest) GetTargetLang() string`

GetTargetLang returns the TargetLang field if non-nil, zero value otherwise.

### GetTargetLangOk

`func (o *TranslateRequest) GetTargetLangOk() (*string, bool)`

GetTargetLangOk returns a tuple with the TargetLang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetLang

`func (o *TranslateRequest) SetTargetLang(v string)`

SetTargetLang sets TargetLang field to given value.

### HasTargetLang

`func (o *TranslateRequest) HasTargetLang() bool`

HasTargetLang returns a boolean if a field has been set.

### GetFrom

`func (o *TranslateRequest) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *TranslateRequest) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *TranslateRequest) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *TranslateRequest) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *TranslateRequest) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *TranslateRequest) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *TranslateRequest) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *TranslateRequest) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetContext

`func (o *TranslateRequest) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *TranslateRequest) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *TranslateRequest) SetContext(v string)`

SetContext sets Context field to given value.

### HasContext

`func (o *TranslateRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetPreserveFormatting

`func (o *TranslateRequest) GetPreserveFormatting() bool`

GetPreserveFormatting returns the PreserveFormatting field if non-nil, zero value otherwise.

### GetPreserveFormattingOk

`func (o *TranslateRequest) GetPreserveFormattingOk() (*bool, bool)`

GetPreserveFormattingOk returns a tuple with the PreserveFormatting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveFormatting

`func (o *TranslateRequest) SetPreserveFormatting(v bool)`

SetPreserveFormatting sets PreserveFormatting field to given value.

### HasPreserveFormatting

`func (o *TranslateRequest) HasPreserveFormatting() bool`

HasPreserveFormatting returns a boolean if a field has been set.

### GetFormality

`func (o *TranslateRequest) GetFormality() string`

GetFormality returns the Formality field if non-nil, zero value otherwise.

### GetFormalityOk

`func (o *TranslateRequest) GetFormalityOk() (*string, bool)`

GetFormalityOk returns a tuple with the Formality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormality

`func (o *TranslateRequest) SetFormality(v string)`

SetFormality sets Formality field to given value.

### HasFormality

`func (o *TranslateRequest) HasFormality() bool`

HasFormality returns a boolean if a field has been set.

### GetSpeakerGender

`func (o *TranslateRequest) GetSpeakerGender() string`

GetSpeakerGender returns the SpeakerGender field if non-nil, zero value otherwise.

### GetSpeakerGenderOk

`func (o *TranslateRequest) GetSpeakerGenderOk() (*string, bool)`

GetSpeakerGenderOk returns a tuple with the SpeakerGender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeakerGender

`func (o *TranslateRequest) SetSpeakerGender(v string)`

SetSpeakerGender sets SpeakerGender field to given value.

### HasSpeakerGender

`func (o *TranslateRequest) HasSpeakerGender() bool`

HasSpeakerGender returns a boolean if a field has been set.

### GetAddresseeGender

`func (o *TranslateRequest) GetAddresseeGender() string`

GetAddresseeGender returns the AddresseeGender field if non-nil, zero value otherwise.

### GetAddresseeGenderOk

`func (o *TranslateRequest) GetAddresseeGenderOk() (*string, bool)`

GetAddresseeGenderOk returns a tuple with the AddresseeGender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddresseeGender

`func (o *TranslateRequest) SetAddresseeGender(v string)`

SetAddresseeGender sets AddresseeGender field to given value.

### HasAddresseeGender

`func (o *TranslateRequest) HasAddresseeGender() bool`

HasAddresseeGender returns a boolean if a field has been set.

### GetTranslationStyle

`func (o *TranslateRequest) GetTranslationStyle() string`

GetTranslationStyle returns the TranslationStyle field if non-nil, zero value otherwise.

### GetTranslationStyleOk

`func (o *TranslateRequest) GetTranslationStyleOk() (*string, bool)`

GetTranslationStyleOk returns a tuple with the TranslationStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslationStyle

`func (o *TranslateRequest) SetTranslationStyle(v string)`

SetTranslationStyle sets TranslationStyle field to given value.

### HasTranslationStyle

`func (o *TranslateRequest) HasTranslationStyle() bool`

HasTranslationStyle returns a boolean if a field has been set.

### GetPredictedLanguage

`func (o *TranslateRequest) GetPredictedLanguage() string`

GetPredictedLanguage returns the PredictedLanguage field if non-nil, zero value otherwise.

### GetPredictedLanguageOk

`func (o *TranslateRequest) GetPredictedLanguageOk() (*string, bool)`

GetPredictedLanguageOk returns a tuple with the PredictedLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredictedLanguage

`func (o *TranslateRequest) SetPredictedLanguage(v string)`

SetPredictedLanguage sets PredictedLanguage field to given value.

### HasPredictedLanguage

`func (o *TranslateRequest) HasPredictedLanguage() bool`

HasPredictedLanguage returns a boolean if a field has been set.

### GetPrediction

`func (o *TranslateRequest) GetPrediction() string`

GetPrediction returns the Prediction field if non-nil, zero value otherwise.

### GetPredictionOk

`func (o *TranslateRequest) GetPredictionOk() (*string, bool)`

GetPredictionOk returns a tuple with the Prediction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrediction

`func (o *TranslateRequest) SetPrediction(v string)`

SetPrediction sets Prediction field to given value.

### HasPrediction

`func (o *TranslateRequest) HasPrediction() bool`

HasPrediction returns a boolean if a field has been set.

### GetStream

`func (o *TranslateRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *TranslateRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *TranslateRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *TranslateRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetDictionaryLanguage

`func (o *TranslateRequest) GetDictionaryLanguage() string`

GetDictionaryLanguage returns the DictionaryLanguage field if non-nil, zero value otherwise.

### GetDictionaryLanguageOk

`func (o *TranslateRequest) GetDictionaryLanguageOk() (*string, bool)`

GetDictionaryLanguageOk returns a tuple with the DictionaryLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDictionaryLanguage

`func (o *TranslateRequest) SetDictionaryLanguage(v string)`

SetDictionaryLanguage sets DictionaryLanguage field to given value.

### HasDictionaryLanguage

`func (o *TranslateRequest) HasDictionaryLanguage() bool`

HasDictionaryLanguage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


