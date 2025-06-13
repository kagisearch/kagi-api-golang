# TranslateListLanguagesPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Type of languages to return (&#39;source&#39; or &#39;target&#39;) | [optional] 
**Locale** | Pointer to **string** | Locale code to use for language names (e.g., &#39;en&#39;, &#39;de&#39;, &#39;fr&#39;) | [optional] 

## Methods

### NewTranslateListLanguagesPostRequest

`func NewTranslateListLanguagesPostRequest() *TranslateListLanguagesPostRequest`

NewTranslateListLanguagesPostRequest instantiates a new TranslateListLanguagesPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateListLanguagesPostRequestWithDefaults

`func NewTranslateListLanguagesPostRequestWithDefaults() *TranslateListLanguagesPostRequest`

NewTranslateListLanguagesPostRequestWithDefaults instantiates a new TranslateListLanguagesPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TranslateListLanguagesPostRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TranslateListLanguagesPostRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TranslateListLanguagesPostRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TranslateListLanguagesPostRequest) HasType() bool`

HasType returns a boolean if a field has been set.

### GetLocale

`func (o *TranslateListLanguagesPostRequest) GetLocale() string`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *TranslateListLanguagesPostRequest) GetLocaleOk() (*string, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *TranslateListLanguagesPostRequest) SetLocale(v string)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *TranslateListLanguagesPostRequest) HasLocale() bool`

HasLocale returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


