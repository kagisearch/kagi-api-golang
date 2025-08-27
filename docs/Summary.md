# Summary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meta** | Pointer to [**Meta**](Meta.md) |  | [optional] 
**Data** | Pointer to [**SummaryData**](SummaryData.md) |  | [optional] 

## Methods

### NewSummary

`func NewSummary() *Summary`

NewSummary instantiates a new Summary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSummaryWithDefaults

`func NewSummaryWithDefaults() *Summary`

NewSummaryWithDefaults instantiates a new Summary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeta

`func (o *Summary) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *Summary) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *Summary) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *Summary) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *Summary) GetData() SummaryData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Summary) GetDataOk() (*SummaryData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Summary) SetData(v SummaryData)`

SetData sets Data field to given value.

### HasData

`func (o *Summary) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


