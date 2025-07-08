# TranslateDictionary200ResponseDefinition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Word** | Pointer to **string** | The word being defined | [optional] 
**PartOfSpeech** | Pointer to **[]string** | All parts of speech that apply to the word across all meanings | [optional] 
**UsageLevel** | Pointer to **[]string** | Register or context where the word is typically used (formal, informal, slang, technical, etc.) | [optional] 
**PrimaryMeaning** | Pointer to [**TranslateDictionary200ResponseDefinitionPrimaryMeaning**](TranslateDictionary200ResponseDefinitionPrimaryMeaning.md) |  | [optional] 
**SecondaryMeanings** | Pointer to [**[]TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner**](TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner.md) | Secondary or less common meanings | [optional] 
**Examples** | Pointer to **[]string** | Example sentences showing usage | [optional] 
**Pronunciation** | Pointer to **string** | Phonetic pronunciation (if available) | [optional] 
**Etymology** | Pointer to **string** | Information about word origin (if available) | [optional] 

## Methods

### NewTranslateDictionary200ResponseDefinition

`func NewTranslateDictionary200ResponseDefinition() *TranslateDictionary200ResponseDefinition`

NewTranslateDictionary200ResponseDefinition instantiates a new TranslateDictionary200ResponseDefinition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateDictionary200ResponseDefinitionWithDefaults

`func NewTranslateDictionary200ResponseDefinitionWithDefaults() *TranslateDictionary200ResponseDefinition`

NewTranslateDictionary200ResponseDefinitionWithDefaults instantiates a new TranslateDictionary200ResponseDefinition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWord

`func (o *TranslateDictionary200ResponseDefinition) GetWord() string`

GetWord returns the Word field if non-nil, zero value otherwise.

### GetWordOk

`func (o *TranslateDictionary200ResponseDefinition) GetWordOk() (*string, bool)`

GetWordOk returns a tuple with the Word field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWord

`func (o *TranslateDictionary200ResponseDefinition) SetWord(v string)`

SetWord sets Word field to given value.

### HasWord

`func (o *TranslateDictionary200ResponseDefinition) HasWord() bool`

HasWord returns a boolean if a field has been set.

### GetPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinition) GetPartOfSpeech() []string`

GetPartOfSpeech returns the PartOfSpeech field if non-nil, zero value otherwise.

### GetPartOfSpeechOk

`func (o *TranslateDictionary200ResponseDefinition) GetPartOfSpeechOk() (*[]string, bool)`

GetPartOfSpeechOk returns a tuple with the PartOfSpeech field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinition) SetPartOfSpeech(v []string)`

SetPartOfSpeech sets PartOfSpeech field to given value.

### HasPartOfSpeech

`func (o *TranslateDictionary200ResponseDefinition) HasPartOfSpeech() bool`

HasPartOfSpeech returns a boolean if a field has been set.

### GetUsageLevel

`func (o *TranslateDictionary200ResponseDefinition) GetUsageLevel() []string`

GetUsageLevel returns the UsageLevel field if non-nil, zero value otherwise.

### GetUsageLevelOk

`func (o *TranslateDictionary200ResponseDefinition) GetUsageLevelOk() (*[]string, bool)`

GetUsageLevelOk returns a tuple with the UsageLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageLevel

`func (o *TranslateDictionary200ResponseDefinition) SetUsageLevel(v []string)`

SetUsageLevel sets UsageLevel field to given value.

### HasUsageLevel

`func (o *TranslateDictionary200ResponseDefinition) HasUsageLevel() bool`

HasUsageLevel returns a boolean if a field has been set.

### GetPrimaryMeaning

`func (o *TranslateDictionary200ResponseDefinition) GetPrimaryMeaning() TranslateDictionary200ResponseDefinitionPrimaryMeaning`

GetPrimaryMeaning returns the PrimaryMeaning field if non-nil, zero value otherwise.

### GetPrimaryMeaningOk

`func (o *TranslateDictionary200ResponseDefinition) GetPrimaryMeaningOk() (*TranslateDictionary200ResponseDefinitionPrimaryMeaning, bool)`

GetPrimaryMeaningOk returns a tuple with the PrimaryMeaning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryMeaning

`func (o *TranslateDictionary200ResponseDefinition) SetPrimaryMeaning(v TranslateDictionary200ResponseDefinitionPrimaryMeaning)`

SetPrimaryMeaning sets PrimaryMeaning field to given value.

### HasPrimaryMeaning

`func (o *TranslateDictionary200ResponseDefinition) HasPrimaryMeaning() bool`

HasPrimaryMeaning returns a boolean if a field has been set.

### GetSecondaryMeanings

`func (o *TranslateDictionary200ResponseDefinition) GetSecondaryMeanings() []TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner`

GetSecondaryMeanings returns the SecondaryMeanings field if non-nil, zero value otherwise.

### GetSecondaryMeaningsOk

`func (o *TranslateDictionary200ResponseDefinition) GetSecondaryMeaningsOk() (*[]TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner, bool)`

GetSecondaryMeaningsOk returns a tuple with the SecondaryMeanings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryMeanings

`func (o *TranslateDictionary200ResponseDefinition) SetSecondaryMeanings(v []TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner)`

SetSecondaryMeanings sets SecondaryMeanings field to given value.

### HasSecondaryMeanings

`func (o *TranslateDictionary200ResponseDefinition) HasSecondaryMeanings() bool`

HasSecondaryMeanings returns a boolean if a field has been set.

### GetExamples

`func (o *TranslateDictionary200ResponseDefinition) GetExamples() []string`

GetExamples returns the Examples field if non-nil, zero value otherwise.

### GetExamplesOk

`func (o *TranslateDictionary200ResponseDefinition) GetExamplesOk() (*[]string, bool)`

GetExamplesOk returns a tuple with the Examples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExamples

`func (o *TranslateDictionary200ResponseDefinition) SetExamples(v []string)`

SetExamples sets Examples field to given value.

### HasExamples

`func (o *TranslateDictionary200ResponseDefinition) HasExamples() bool`

HasExamples returns a boolean if a field has been set.

### GetPronunciation

`func (o *TranslateDictionary200ResponseDefinition) GetPronunciation() string`

GetPronunciation returns the Pronunciation field if non-nil, zero value otherwise.

### GetPronunciationOk

`func (o *TranslateDictionary200ResponseDefinition) GetPronunciationOk() (*string, bool)`

GetPronunciationOk returns a tuple with the Pronunciation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPronunciation

`func (o *TranslateDictionary200ResponseDefinition) SetPronunciation(v string)`

SetPronunciation sets Pronunciation field to given value.

### HasPronunciation

`func (o *TranslateDictionary200ResponseDefinition) HasPronunciation() bool`

HasPronunciation returns a boolean if a field has been set.

### GetEtymology

`func (o *TranslateDictionary200ResponseDefinition) GetEtymology() string`

GetEtymology returns the Etymology field if non-nil, zero value otherwise.

### GetEtymologyOk

`func (o *TranslateDictionary200ResponseDefinition) GetEtymologyOk() (*string, bool)`

GetEtymologyOk returns a tuple with the Etymology field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEtymology

`func (o *TranslateDictionary200ResponseDefinition) SetEtymology(v string)`

SetEtymology sets Etymology field to given value.

### HasEtymology

`func (o *TranslateDictionary200ResponseDefinition) HasEtymology() bool`

HasEtymology returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


