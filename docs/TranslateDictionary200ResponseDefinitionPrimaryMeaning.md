# TranslateDictionary200ResponseDefinitionPrimaryMeaning

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Definition** | Pointer to **string** | The text of the primary definition (translated to definition_language) | [optional] 
**PartOfSpeech** | Pointer to **[]string** | The part(s) of speech that apply to this specific meaning (translated to definition_language) | [optional] 
**UsageLevel** | Pointer to **[]string** | Register or context where this specific meaning is used (formal, informal, slang, technical, etc.) - translated to definition_language | [optional] 
**Dialect** | Pointer to **[]string** | Specific dialects where this meaning is used (e.g., \&quot;US\&quot;, \&quot;UK\&quot;, \&quot;Australian\&quot;) | [optional] 
**Synonyms** | Pointer to **[]string** | List of synonyms for this meaning, ordered from strongest/closest to least similar (remains in word_language) | [optional] 

## Methods

### NewTranslateDictionary200ResponseDefinitionPrimaryMeaning

`func NewTranslateDictionary200ResponseDefinitionPrimaryMeaning() *TranslateDictionary200ResponseDefinitionPrimaryMeaning`

NewTranslateDictionary200ResponseDefinitionPrimaryMeaning instantiates a new TranslateDictionary200ResponseDefinitionPrimaryMeaning object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateDictionary200ResponseDefinitionPrimaryMeaningWithDefaults

`func NewTranslateDictionary200ResponseDefinitionPrimaryMeaningWithDefaults() *TranslateDictionary200ResponseDefinitionPrimaryMeaning`

NewTranslateDictionary200ResponseDefinitionPrimaryMeaningWithDefaults instantiates a new TranslateDictionary200ResponseDefinitionPrimaryMeaning object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefinition

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetDefinition() string`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetDefinitionOk() (*string, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) SetDefinition(v string)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetPartOfSpeech() []string`

GetPartOfSpeech returns the PartOfSpeech field if non-nil, zero value otherwise.

### GetPartOfSpeechOk

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetPartOfSpeechOk() (*[]string, bool)`

GetPartOfSpeechOk returns a tuple with the PartOfSpeech field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) SetPartOfSpeech(v []string)`

SetPartOfSpeech sets PartOfSpeech field to given value.

### HasPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) HasPartOfSpeech() bool`

HasPartOfSpeech returns a boolean if a field has been set.

### GetUsageLevel

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetUsageLevel() []string`

GetUsageLevel returns the UsageLevel field if non-nil, zero value otherwise.

### GetUsageLevelOk

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetUsageLevelOk() (*[]string, bool)`

GetUsageLevelOk returns a tuple with the UsageLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageLevel

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) SetUsageLevel(v []string)`

SetUsageLevel sets UsageLevel field to given value.

### HasUsageLevel

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) HasUsageLevel() bool`

HasUsageLevel returns a boolean if a field has been set.

### GetDialect

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetDialect() []string`

GetDialect returns the Dialect field if non-nil, zero value otherwise.

### GetDialectOk

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetDialectOk() (*[]string, bool)`

GetDialectOk returns a tuple with the Dialect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDialect

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) SetDialect(v []string)`

SetDialect sets Dialect field to given value.

### HasDialect

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) HasDialect() bool`

HasDialect returns a boolean if a field has been set.

### GetSynonyms

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetSynonyms() []string`

GetSynonyms returns the Synonyms field if non-nil, zero value otherwise.

### GetSynonymsOk

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) GetSynonymsOk() (*[]string, bool)`

GetSynonymsOk returns a tuple with the Synonyms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynonyms

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) SetSynonyms(v []string)`

SetSynonyms sets Synonyms field to given value.

### HasSynonyms

`func (o *TranslateDictionary200ResponseDefinitionPrimaryMeaning) HasSynonyms() bool`

HasSynonyms returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


