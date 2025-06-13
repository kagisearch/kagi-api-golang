# TranslateProofReadGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CorrectedText** | Pointer to **string** | The proofread and corrected text | [optional] 
**DetectedLanguage** | Pointer to [**TranslateProofReadGet200ResponseDetectedLanguage**](TranslateProofReadGet200ResponseDetectedLanguage.md) |  | [optional] 
**Changes** | Pointer to [**[]TranslateProofReadGet200ResponseChangesInner**](TranslateProofReadGet200ResponseChangesInner.md) |  | [optional] 
**CorrectionsSummary** | Pointer to **string** | Overall explanation of corrections or acknowledgment of error-free text | [optional] 
**ToneAnalysis** | Pointer to [**TranslateProofReadGet200ResponseToneAnalysis**](TranslateProofReadGet200ResponseToneAnalysis.md) |  | [optional] 
**VoiceConsistency** | Pointer to [**TranslateProofReadGet200ResponseVoiceConsistency**](TranslateProofReadGet200ResponseVoiceConsistency.md) |  | [optional] 
**RepetitionDetection** | Pointer to [**TranslateProofReadGet200ResponseRepetitionDetection**](TranslateProofReadGet200ResponseRepetitionDetection.md) |  | [optional] 
**ExplanationLanguage** | Pointer to **string** | ISO code of the language used for explanations and analysis | [optional] 

## Methods

### NewTranslateProofReadGet200Response

`func NewTranslateProofReadGet200Response() *TranslateProofReadGet200Response`

NewTranslateProofReadGet200Response instantiates a new TranslateProofReadGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateProofReadGet200ResponseWithDefaults

`func NewTranslateProofReadGet200ResponseWithDefaults() *TranslateProofReadGet200Response`

NewTranslateProofReadGet200ResponseWithDefaults instantiates a new TranslateProofReadGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrectedText

`func (o *TranslateProofReadGet200Response) GetCorrectedText() string`

GetCorrectedText returns the CorrectedText field if non-nil, zero value otherwise.

### GetCorrectedTextOk

`func (o *TranslateProofReadGet200Response) GetCorrectedTextOk() (*string, bool)`

GetCorrectedTextOk returns a tuple with the CorrectedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrectedText

`func (o *TranslateProofReadGet200Response) SetCorrectedText(v string)`

SetCorrectedText sets CorrectedText field to given value.

### HasCorrectedText

`func (o *TranslateProofReadGet200Response) HasCorrectedText() bool`

HasCorrectedText returns a boolean if a field has been set.

### GetDetectedLanguage

`func (o *TranslateProofReadGet200Response) GetDetectedLanguage() TranslateProofReadGet200ResponseDetectedLanguage`

GetDetectedLanguage returns the DetectedLanguage field if non-nil, zero value otherwise.

### GetDetectedLanguageOk

`func (o *TranslateProofReadGet200Response) GetDetectedLanguageOk() (*TranslateProofReadGet200ResponseDetectedLanguage, bool)`

GetDetectedLanguageOk returns a tuple with the DetectedLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedLanguage

`func (o *TranslateProofReadGet200Response) SetDetectedLanguage(v TranslateProofReadGet200ResponseDetectedLanguage)`

SetDetectedLanguage sets DetectedLanguage field to given value.

### HasDetectedLanguage

`func (o *TranslateProofReadGet200Response) HasDetectedLanguage() bool`

HasDetectedLanguage returns a boolean if a field has been set.

### GetChanges

`func (o *TranslateProofReadGet200Response) GetChanges() []TranslateProofReadGet200ResponseChangesInner`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *TranslateProofReadGet200Response) GetChangesOk() (*[]TranslateProofReadGet200ResponseChangesInner, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *TranslateProofReadGet200Response) SetChanges(v []TranslateProofReadGet200ResponseChangesInner)`

SetChanges sets Changes field to given value.

### HasChanges

`func (o *TranslateProofReadGet200Response) HasChanges() bool`

HasChanges returns a boolean if a field has been set.

### GetCorrectionsSummary

`func (o *TranslateProofReadGet200Response) GetCorrectionsSummary() string`

GetCorrectionsSummary returns the CorrectionsSummary field if non-nil, zero value otherwise.

### GetCorrectionsSummaryOk

`func (o *TranslateProofReadGet200Response) GetCorrectionsSummaryOk() (*string, bool)`

GetCorrectionsSummaryOk returns a tuple with the CorrectionsSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrectionsSummary

`func (o *TranslateProofReadGet200Response) SetCorrectionsSummary(v string)`

SetCorrectionsSummary sets CorrectionsSummary field to given value.

### HasCorrectionsSummary

`func (o *TranslateProofReadGet200Response) HasCorrectionsSummary() bool`

HasCorrectionsSummary returns a boolean if a field has been set.

### GetToneAnalysis

`func (o *TranslateProofReadGet200Response) GetToneAnalysis() TranslateProofReadGet200ResponseToneAnalysis`

GetToneAnalysis returns the ToneAnalysis field if non-nil, zero value otherwise.

### GetToneAnalysisOk

`func (o *TranslateProofReadGet200Response) GetToneAnalysisOk() (*TranslateProofReadGet200ResponseToneAnalysis, bool)`

GetToneAnalysisOk returns a tuple with the ToneAnalysis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneAnalysis

`func (o *TranslateProofReadGet200Response) SetToneAnalysis(v TranslateProofReadGet200ResponseToneAnalysis)`

SetToneAnalysis sets ToneAnalysis field to given value.

### HasToneAnalysis

`func (o *TranslateProofReadGet200Response) HasToneAnalysis() bool`

HasToneAnalysis returns a boolean if a field has been set.

### GetVoiceConsistency

`func (o *TranslateProofReadGet200Response) GetVoiceConsistency() TranslateProofReadGet200ResponseVoiceConsistency`

GetVoiceConsistency returns the VoiceConsistency field if non-nil, zero value otherwise.

### GetVoiceConsistencyOk

`func (o *TranslateProofReadGet200Response) GetVoiceConsistencyOk() (*TranslateProofReadGet200ResponseVoiceConsistency, bool)`

GetVoiceConsistencyOk returns a tuple with the VoiceConsistency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoiceConsistency

`func (o *TranslateProofReadGet200Response) SetVoiceConsistency(v TranslateProofReadGet200ResponseVoiceConsistency)`

SetVoiceConsistency sets VoiceConsistency field to given value.

### HasVoiceConsistency

`func (o *TranslateProofReadGet200Response) HasVoiceConsistency() bool`

HasVoiceConsistency returns a boolean if a field has been set.

### GetRepetitionDetection

`func (o *TranslateProofReadGet200Response) GetRepetitionDetection() TranslateProofReadGet200ResponseRepetitionDetection`

GetRepetitionDetection returns the RepetitionDetection field if non-nil, zero value otherwise.

### GetRepetitionDetectionOk

`func (o *TranslateProofReadGet200Response) GetRepetitionDetectionOk() (*TranslateProofReadGet200ResponseRepetitionDetection, bool)`

GetRepetitionDetectionOk returns a tuple with the RepetitionDetection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepetitionDetection

`func (o *TranslateProofReadGet200Response) SetRepetitionDetection(v TranslateProofReadGet200ResponseRepetitionDetection)`

SetRepetitionDetection sets RepetitionDetection field to given value.

### HasRepetitionDetection

`func (o *TranslateProofReadGet200Response) HasRepetitionDetection() bool`

HasRepetitionDetection returns a boolean if a field has been set.

### GetExplanationLanguage

`func (o *TranslateProofReadGet200Response) GetExplanationLanguage() string`

GetExplanationLanguage returns the ExplanationLanguage field if non-nil, zero value otherwise.

### GetExplanationLanguageOk

`func (o *TranslateProofReadGet200Response) GetExplanationLanguageOk() (*string, bool)`

GetExplanationLanguageOk returns a tuple with the ExplanationLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplanationLanguage

`func (o *TranslateProofReadGet200Response) SetExplanationLanguage(v string)`

SetExplanationLanguage sets ExplanationLanguage field to given value.

### HasExplanationLanguage

`func (o *TranslateProofReadGet200Response) HasExplanationLanguage() bool`

HasExplanationLanguage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


