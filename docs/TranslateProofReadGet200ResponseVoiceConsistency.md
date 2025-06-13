# TranslateProofReadGet200ResponseVoiceConsistency

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveVoicePercentage** | Pointer to **float32** | Approximate percentage of sentences using active voice | [optional] 
**PassiveVoicePercentage** | Pointer to **float32** | Approximate percentage of sentences using passive voice | [optional] 
**IsConsistent** | Pointer to **bool** | Whether the voice usage is consistent throughout | [optional] 
**Suggestion** | Pointer to **NullableString** | Optional suggestion about voice usage | [optional] 
**PassiveInstances** | Pointer to [**[]TranslateProofReadGet200ResponseVoiceConsistencyPassiveInstancesInner**](TranslateProofReadGet200ResponseVoiceConsistencyPassiveInstancesInner.md) |  | [optional] 
**Summary** | Pointer to **string** | Overall assessment of voice usage and its effectiveness | [optional] 

## Methods

### NewTranslateProofReadGet200ResponseVoiceConsistency

`func NewTranslateProofReadGet200ResponseVoiceConsistency() *TranslateProofReadGet200ResponseVoiceConsistency`

NewTranslateProofReadGet200ResponseVoiceConsistency instantiates a new TranslateProofReadGet200ResponseVoiceConsistency object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateProofReadGet200ResponseVoiceConsistencyWithDefaults

`func NewTranslateProofReadGet200ResponseVoiceConsistencyWithDefaults() *TranslateProofReadGet200ResponseVoiceConsistency`

NewTranslateProofReadGet200ResponseVoiceConsistencyWithDefaults instantiates a new TranslateProofReadGet200ResponseVoiceConsistency object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetActiveVoicePercentage() float32`

GetActiveVoicePercentage returns the ActiveVoicePercentage field if non-nil, zero value otherwise.

### GetActiveVoicePercentageOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetActiveVoicePercentageOk() (*float32, bool)`

GetActiveVoicePercentageOk returns a tuple with the ActiveVoicePercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetActiveVoicePercentage(v float32)`

SetActiveVoicePercentage sets ActiveVoicePercentage field to given value.

### HasActiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasActiveVoicePercentage() bool`

HasActiveVoicePercentage returns a boolean if a field has been set.

### GetPassiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetPassiveVoicePercentage() float32`

GetPassiveVoicePercentage returns the PassiveVoicePercentage field if non-nil, zero value otherwise.

### GetPassiveVoicePercentageOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetPassiveVoicePercentageOk() (*float32, bool)`

GetPassiveVoicePercentageOk returns a tuple with the PassiveVoicePercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetPassiveVoicePercentage(v float32)`

SetPassiveVoicePercentage sets PassiveVoicePercentage field to given value.

### HasPassiveVoicePercentage

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasPassiveVoicePercentage() bool`

HasPassiveVoicePercentage returns a boolean if a field has been set.

### GetIsConsistent

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetIsConsistent() bool`

GetIsConsistent returns the IsConsistent field if non-nil, zero value otherwise.

### GetIsConsistentOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetIsConsistentOk() (*bool, bool)`

GetIsConsistentOk returns a tuple with the IsConsistent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsConsistent

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetIsConsistent(v bool)`

SetIsConsistent sets IsConsistent field to given value.

### HasIsConsistent

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasIsConsistent() bool`

HasIsConsistent returns a boolean if a field has been set.

### GetSuggestion

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetSuggestion() string`

GetSuggestion returns the Suggestion field if non-nil, zero value otherwise.

### GetSuggestionOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetSuggestionOk() (*string, bool)`

GetSuggestionOk returns a tuple with the Suggestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestion

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetSuggestion(v string)`

SetSuggestion sets Suggestion field to given value.

### HasSuggestion

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasSuggestion() bool`

HasSuggestion returns a boolean if a field has been set.

### SetSuggestionNil

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetSuggestionNil(b bool)`

 SetSuggestionNil sets the value for Suggestion to be an explicit nil

### UnsetSuggestion
`func (o *TranslateProofReadGet200ResponseVoiceConsistency) UnsetSuggestion()`

UnsetSuggestion ensures that no value is present for Suggestion, not even an explicit nil
### GetPassiveInstances

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetPassiveInstances() []TranslateProofReadGet200ResponseVoiceConsistencyPassiveInstancesInner`

GetPassiveInstances returns the PassiveInstances field if non-nil, zero value otherwise.

### GetPassiveInstancesOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetPassiveInstancesOk() (*[]TranslateProofReadGet200ResponseVoiceConsistencyPassiveInstancesInner, bool)`

GetPassiveInstancesOk returns a tuple with the PassiveInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassiveInstances

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetPassiveInstances(v []TranslateProofReadGet200ResponseVoiceConsistencyPassiveInstancesInner)`

SetPassiveInstances sets PassiveInstances field to given value.

### HasPassiveInstances

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasPassiveInstances() bool`

HasPassiveInstances returns a boolean if a field has been set.

### GetSummary

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *TranslateProofReadGet200ResponseVoiceConsistency) HasSummary() bool`

HasSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


