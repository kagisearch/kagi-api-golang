# SummaryData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Output** | Pointer to **string** | Contains the summary text. | [optional] 
**Tokens** | Pointer to **int32** | A count of how many tokens were used to perform the summary. | [optional] 

## Methods

### NewSummaryData

`func NewSummaryData() *SummaryData`

NewSummaryData instantiates a new SummaryData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSummaryDataWithDefaults

`func NewSummaryDataWithDefaults() *SummaryData`

NewSummaryDataWithDefaults instantiates a new SummaryData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutput

`func (o *SummaryData) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *SummaryData) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *SummaryData) SetOutput(v string)`

SetOutput sets Output field to given value.

### HasOutput

`func (o *SummaryData) HasOutput() bool`

HasOutput returns a boolean if a field has been set.

### GetTokens

`func (o *SummaryData) GetTokens() int32`

GetTokens returns the Tokens field if non-nil, zero value otherwise.

### GetTokensOk

`func (o *SummaryData) GetTokensOk() (*int32, bool)`

GetTokensOk returns a tuple with the Tokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokens

`func (o *SummaryData) SetTokens(v int32)`

SetTokens sets Tokens field to given value.

### HasTokens

`func (o *SummaryData) HasTokens() bool`

HasTokens returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


