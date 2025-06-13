# TranslateWordInsights200ResponseInsightsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Identifier matching the marker in marked_translation | [optional] 
**OriginalText** | Pointer to **string** | The original word or phrase from the translated text | [optional] 
**Variations** | Pointer to [**[]TranslateWordInsights200ResponseInsightsInnerVariationsInner**](TranslateWordInsights200ResponseInsightsInnerVariationsInner.md) | Alternative expressions with explanations | [optional] 
**Type** | Pointer to **string** | Category of the insight in the explanation language | [optional] 

## Methods

### NewTranslateWordInsights200ResponseInsightsInner

`func NewTranslateWordInsights200ResponseInsightsInner() *TranslateWordInsights200ResponseInsightsInner`

NewTranslateWordInsights200ResponseInsightsInner instantiates a new TranslateWordInsights200ResponseInsightsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateWordInsights200ResponseInsightsInnerWithDefaults

`func NewTranslateWordInsights200ResponseInsightsInnerWithDefaults() *TranslateWordInsights200ResponseInsightsInner`

NewTranslateWordInsights200ResponseInsightsInnerWithDefaults instantiates a new TranslateWordInsights200ResponseInsightsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TranslateWordInsights200ResponseInsightsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TranslateWordInsights200ResponseInsightsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TranslateWordInsights200ResponseInsightsInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TranslateWordInsights200ResponseInsightsInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOriginalText

`func (o *TranslateWordInsights200ResponseInsightsInner) GetOriginalText() string`

GetOriginalText returns the OriginalText field if non-nil, zero value otherwise.

### GetOriginalTextOk

`func (o *TranslateWordInsights200ResponseInsightsInner) GetOriginalTextOk() (*string, bool)`

GetOriginalTextOk returns a tuple with the OriginalText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalText

`func (o *TranslateWordInsights200ResponseInsightsInner) SetOriginalText(v string)`

SetOriginalText sets OriginalText field to given value.

### HasOriginalText

`func (o *TranslateWordInsights200ResponseInsightsInner) HasOriginalText() bool`

HasOriginalText returns a boolean if a field has been set.

### GetVariations

`func (o *TranslateWordInsights200ResponseInsightsInner) GetVariations() []TranslateWordInsights200ResponseInsightsInnerVariationsInner`

GetVariations returns the Variations field if non-nil, zero value otherwise.

### GetVariationsOk

`func (o *TranslateWordInsights200ResponseInsightsInner) GetVariationsOk() (*[]TranslateWordInsights200ResponseInsightsInnerVariationsInner, bool)`

GetVariationsOk returns a tuple with the Variations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariations

`func (o *TranslateWordInsights200ResponseInsightsInner) SetVariations(v []TranslateWordInsights200ResponseInsightsInnerVariationsInner)`

SetVariations sets Variations field to given value.

### HasVariations

`func (o *TranslateWordInsights200ResponseInsightsInner) HasVariations() bool`

HasVariations returns a boolean if a field has been set.

### GetType

`func (o *TranslateWordInsights200ResponseInsightsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TranslateWordInsights200ResponseInsightsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TranslateWordInsights200ResponseInsightsInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TranslateWordInsights200ResponseInsightsInner) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


