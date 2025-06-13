# TranslateProofReadGet200ResponseChangesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Original** | Pointer to **string** | Original text segment with the error | [optional] 
**Correction** | Pointer to **string** | Corrected text segment | [optional] 
**Explanation** | Pointer to **string** | Brief explanation of why this change was necessary | [optional] 
**Types** | Pointer to **[]string** | Array of correction types/reasons that explain why the change was necessary (e.g., grammar, spelling, punctuation, word_choice, style, typography, formatting, clarity, etc.) | [optional] 
**Severity** | Pointer to **string** | Importance of this correction | [optional] 

## Methods

### NewTranslateProofReadGet200ResponseChangesInner

`func NewTranslateProofReadGet200ResponseChangesInner() *TranslateProofReadGet200ResponseChangesInner`

NewTranslateProofReadGet200ResponseChangesInner instantiates a new TranslateProofReadGet200ResponseChangesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateProofReadGet200ResponseChangesInnerWithDefaults

`func NewTranslateProofReadGet200ResponseChangesInnerWithDefaults() *TranslateProofReadGet200ResponseChangesInner`

NewTranslateProofReadGet200ResponseChangesInnerWithDefaults instantiates a new TranslateProofReadGet200ResponseChangesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOriginal

`func (o *TranslateProofReadGet200ResponseChangesInner) GetOriginal() string`

GetOriginal returns the Original field if non-nil, zero value otherwise.

### GetOriginalOk

`func (o *TranslateProofReadGet200ResponseChangesInner) GetOriginalOk() (*string, bool)`

GetOriginalOk returns a tuple with the Original field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginal

`func (o *TranslateProofReadGet200ResponseChangesInner) SetOriginal(v string)`

SetOriginal sets Original field to given value.

### HasOriginal

`func (o *TranslateProofReadGet200ResponseChangesInner) HasOriginal() bool`

HasOriginal returns a boolean if a field has been set.

### GetCorrection

`func (o *TranslateProofReadGet200ResponseChangesInner) GetCorrection() string`

GetCorrection returns the Correction field if non-nil, zero value otherwise.

### GetCorrectionOk

`func (o *TranslateProofReadGet200ResponseChangesInner) GetCorrectionOk() (*string, bool)`

GetCorrectionOk returns a tuple with the Correction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrection

`func (o *TranslateProofReadGet200ResponseChangesInner) SetCorrection(v string)`

SetCorrection sets Correction field to given value.

### HasCorrection

`func (o *TranslateProofReadGet200ResponseChangesInner) HasCorrection() bool`

HasCorrection returns a boolean if a field has been set.

### GetExplanation

`func (o *TranslateProofReadGet200ResponseChangesInner) GetExplanation() string`

GetExplanation returns the Explanation field if non-nil, zero value otherwise.

### GetExplanationOk

`func (o *TranslateProofReadGet200ResponseChangesInner) GetExplanationOk() (*string, bool)`

GetExplanationOk returns a tuple with the Explanation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplanation

`func (o *TranslateProofReadGet200ResponseChangesInner) SetExplanation(v string)`

SetExplanation sets Explanation field to given value.

### HasExplanation

`func (o *TranslateProofReadGet200ResponseChangesInner) HasExplanation() bool`

HasExplanation returns a boolean if a field has been set.

### GetTypes

`func (o *TranslateProofReadGet200ResponseChangesInner) GetTypes() []string`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *TranslateProofReadGet200ResponseChangesInner) GetTypesOk() (*[]string, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *TranslateProofReadGet200ResponseChangesInner) SetTypes(v []string)`

SetTypes sets Types field to given value.

### HasTypes

`func (o *TranslateProofReadGet200ResponseChangesInner) HasTypes() bool`

HasTypes returns a boolean if a field has been set.

### GetSeverity

`func (o *TranslateProofReadGet200ResponseChangesInner) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *TranslateProofReadGet200ResponseChangesInner) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *TranslateProofReadGet200ResponseChangesInner) SetSeverity(v string)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *TranslateProofReadGet200ResponseChangesInner) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


