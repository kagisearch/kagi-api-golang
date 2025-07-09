# TranslateDictionary200ResponseDefinition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Word** | Pointer to **string** | The word being defined (remains in word_language) | [optional] 
**PrimaryMeaning** | Pointer to [**TranslateDictionary200ResponseDefinitionPrimaryMeaning**](TranslateDictionary200ResponseDefinitionPrimaryMeaning.md) |  | [optional] 
**SecondaryMeanings** | Pointer to [**[]TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner**](TranslateDictionary200ResponseDefinitionSecondaryMeaningsInner.md) | Secondary or less common meanings | [optional] 
**Examples** | Pointer to **[]string** | Example sentences showing usage (remains in word_language, but includes translations in parentheses when word_language differs from definition_language) | [optional] 
**Pronunciation** | Pointer to **string** | Phonetic pronunciation of the word in its original language (if available) | [optional] 
**Etymology** | Pointer to **string** | Information about word origin (translated to definition_language if available) | [optional] 
**Notes** | Pointer to **string** | Brief usage notes, cultural context, or helpful tips for language learners (translated to definition_language) | [optional] 
**TemporalTrend** | Pointer to **string** | Optional usage trend indicator. Always in English as an enum value. Only provided when trend data is clear and meaningful. | [optional] 
**Gender** | Pointer to **string** | Grammatical gender for nouns in languages that have gender. Always in English as an enum value. Only included for nouns in gendered languages. | [optional] 
**Plural** | Pointer to **string** | Plural form of the word (remains in word_language). Only included for irregular or non-standard plurals. | [optional] 
**ConjugationNotes** | Pointer to **string** | Brief notes about verb conjugation irregularities (remains in word_language). Only included for verbs with notable irregularities. | [optional] 
**RelatedWords** | Pointer to **[]string** | Related words from the same root or word family (remains in word_language) | [optional] 

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

### GetNotes

`func (o *TranslateDictionary200ResponseDefinition) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *TranslateDictionary200ResponseDefinition) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *TranslateDictionary200ResponseDefinition) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *TranslateDictionary200ResponseDefinition) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetTemporalTrend

`func (o *TranslateDictionary200ResponseDefinition) GetTemporalTrend() string`

GetTemporalTrend returns the TemporalTrend field if non-nil, zero value otherwise.

### GetTemporalTrendOk

`func (o *TranslateDictionary200ResponseDefinition) GetTemporalTrendOk() (*string, bool)`

GetTemporalTrendOk returns a tuple with the TemporalTrend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemporalTrend

`func (o *TranslateDictionary200ResponseDefinition) SetTemporalTrend(v string)`

SetTemporalTrend sets TemporalTrend field to given value.

### HasTemporalTrend

`func (o *TranslateDictionary200ResponseDefinition) HasTemporalTrend() bool`

HasTemporalTrend returns a boolean if a field has been set.

### GetGender

`func (o *TranslateDictionary200ResponseDefinition) GetGender() string`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *TranslateDictionary200ResponseDefinition) GetGenderOk() (*string, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *TranslateDictionary200ResponseDefinition) SetGender(v string)`

SetGender sets Gender field to given value.

### HasGender

`func (o *TranslateDictionary200ResponseDefinition) HasGender() bool`

HasGender returns a boolean if a field has been set.

### GetPlural

`func (o *TranslateDictionary200ResponseDefinition) GetPlural() string`

GetPlural returns the Plural field if non-nil, zero value otherwise.

### GetPluralOk

`func (o *TranslateDictionary200ResponseDefinition) GetPluralOk() (*string, bool)`

GetPluralOk returns a tuple with the Plural field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlural

`func (o *TranslateDictionary200ResponseDefinition) SetPlural(v string)`

SetPlural sets Plural field to given value.

### HasPlural

`func (o *TranslateDictionary200ResponseDefinition) HasPlural() bool`

HasPlural returns a boolean if a field has been set.

### GetConjugationNotes

`func (o *TranslateDictionary200ResponseDefinition) GetConjugationNotes() string`

GetConjugationNotes returns the ConjugationNotes field if non-nil, zero value otherwise.

### GetConjugationNotesOk

`func (o *TranslateDictionary200ResponseDefinition) GetConjugationNotesOk() (*string, bool)`

GetConjugationNotesOk returns a tuple with the ConjugationNotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConjugationNotes

`func (o *TranslateDictionary200ResponseDefinition) SetConjugationNotes(v string)`

SetConjugationNotes sets ConjugationNotes field to given value.

### HasConjugationNotes

`func (o *TranslateDictionary200ResponseDefinition) HasConjugationNotes() bool`

HasConjugationNotes returns a boolean if a field has been set.

### GetRelatedWords

`func (o *TranslateDictionary200ResponseDefinition) GetRelatedWords() []string`

GetRelatedWords returns the RelatedWords field if non-nil, zero value otherwise.

### GetRelatedWordsOk

`func (o *TranslateDictionary200ResponseDefinition) GetRelatedWordsOk() (*[]string, bool)`

GetRelatedWordsOk returns a tuple with the RelatedWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedWords

`func (o *TranslateDictionary200ResponseDefinition) SetRelatedWords(v []string)`

SetRelatedWords sets RelatedWords field to given value.

### HasRelatedWords

`func (o *TranslateDictionary200ResponseDefinition) HasRelatedWords() bool`

HasRelatedWords returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


