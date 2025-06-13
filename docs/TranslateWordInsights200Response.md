# TranslateWordInsights200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MarkedTranslation** | Pointer to **string** | The translated text with markers (&lt;&lt;INSIGHT_N&gt;&gt;) indicating insight locations | [optional] 
**Insights** | Pointer to [**[]TranslateWordInsights200ResponseInsightsInner**](TranslateWordInsights200ResponseInsightsInner.md) |  | [optional] 

## Methods

### NewTranslateWordInsights200Response

`func NewTranslateWordInsights200Response() *TranslateWordInsights200Response`

NewTranslateWordInsights200Response instantiates a new TranslateWordInsights200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateWordInsights200ResponseWithDefaults

`func NewTranslateWordInsights200ResponseWithDefaults() *TranslateWordInsights200Response`

NewTranslateWordInsights200ResponseWithDefaults instantiates a new TranslateWordInsights200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMarkedTranslation

`func (o *TranslateWordInsights200Response) GetMarkedTranslation() string`

GetMarkedTranslation returns the MarkedTranslation field if non-nil, zero value otherwise.

### GetMarkedTranslationOk

`func (o *TranslateWordInsights200Response) GetMarkedTranslationOk() (*string, bool)`

GetMarkedTranslationOk returns a tuple with the MarkedTranslation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkedTranslation

`func (o *TranslateWordInsights200Response) SetMarkedTranslation(v string)`

SetMarkedTranslation sets MarkedTranslation field to given value.

### HasMarkedTranslation

`func (o *TranslateWordInsights200Response) HasMarkedTranslation() bool`

HasMarkedTranslation returns a boolean if a field has been set.

### GetInsights

`func (o *TranslateWordInsights200Response) GetInsights() []TranslateWordInsights200ResponseInsightsInner`

GetInsights returns the Insights field if non-nil, zero value otherwise.

### GetInsightsOk

`func (o *TranslateWordInsights200Response) GetInsightsOk() (*[]TranslateWordInsights200ResponseInsightsInner, bool)`

GetInsightsOk returns a tuple with the Insights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsights

`func (o *TranslateWordInsights200Response) SetInsights(v []TranslateWordInsights200ResponseInsightsInner)`

SetInsights sets Insights field to given value.

### HasInsights

`func (o *TranslateWordInsights200Response) HasInsights() bool`

HasInsights returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


