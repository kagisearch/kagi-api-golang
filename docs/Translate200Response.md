# Translate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Translation** | Pointer to **string** | Translated text | [optional] 
**DetectedLanguage** | Pointer to [**Translate200ResponseOneOfDetectedLanguage**](Translate200ResponseOneOfDetectedLanguage.md) |  | [optional] 
**Definition** | Pointer to [**Translate200ResponseOneOfDefinition**](Translate200ResponseOneOfDefinition.md) |  | [optional] 
**Snippets** | Pointer to **[]string** | Array of translated text snippets (for batch translation). The order matches the input array and preserves context between snippets. | [optional] 

## Methods

### NewTranslate200Response

`func NewTranslate200Response() *Translate200Response`

NewTranslate200Response instantiates a new Translate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslate200ResponseWithDefaults

`func NewTranslate200ResponseWithDefaults() *Translate200Response`

NewTranslate200ResponseWithDefaults instantiates a new Translate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTranslation

`func (o *Translate200Response) GetTranslation() string`

GetTranslation returns the Translation field if non-nil, zero value otherwise.

### GetTranslationOk

`func (o *Translate200Response) GetTranslationOk() (*string, bool)`

GetTranslationOk returns a tuple with the Translation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslation

`func (o *Translate200Response) SetTranslation(v string)`

SetTranslation sets Translation field to given value.

### HasTranslation

`func (o *Translate200Response) HasTranslation() bool`

HasTranslation returns a boolean if a field has been set.

### GetDetectedLanguage

`func (o *Translate200Response) GetDetectedLanguage() Translate200ResponseOneOfDetectedLanguage`

GetDetectedLanguage returns the DetectedLanguage field if non-nil, zero value otherwise.

### GetDetectedLanguageOk

`func (o *Translate200Response) GetDetectedLanguageOk() (*Translate200ResponseOneOfDetectedLanguage, bool)`

GetDetectedLanguageOk returns a tuple with the DetectedLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedLanguage

`func (o *Translate200Response) SetDetectedLanguage(v Translate200ResponseOneOfDetectedLanguage)`

SetDetectedLanguage sets DetectedLanguage field to given value.

### HasDetectedLanguage

`func (o *Translate200Response) HasDetectedLanguage() bool`

HasDetectedLanguage returns a boolean if a field has been set.

### GetDefinition

`func (o *Translate200Response) GetDefinition() Translate200ResponseOneOfDefinition`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *Translate200Response) GetDefinitionOk() (*Translate200ResponseOneOfDefinition, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *Translate200Response) SetDefinition(v Translate200ResponseOneOfDefinition)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *Translate200Response) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetSnippets

`func (o *Translate200Response) GetSnippets() []string`

GetSnippets returns the Snippets field if non-nil, zero value otherwise.

### GetSnippetsOk

`func (o *Translate200Response) GetSnippetsOk() (*[]string, bool)`

GetSnippetsOk returns a tuple with the Snippets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippets

`func (o *Translate200Response) SetSnippets(v []string)`

SetSnippets sets Snippets field to given value.

### HasSnippets

`func (o *Translate200Response) HasSnippets() bool`

HasSnippets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


