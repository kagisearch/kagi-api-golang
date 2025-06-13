# Search200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meta** | Pointer to [**Meta**](Meta.md) |  | [optional] 
**Data** | Pointer to [**Search200ResponseData**](Search200ResponseData.md) |  | [optional] 

## Methods

### NewSearch200Response

`func NewSearch200Response() *Search200Response`

NewSearch200Response instantiates a new Search200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearch200ResponseWithDefaults

`func NewSearch200ResponseWithDefaults() *Search200Response`

NewSearch200ResponseWithDefaults instantiates a new Search200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeta

`func (o *Search200Response) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *Search200Response) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *Search200Response) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *Search200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *Search200Response) GetData() Search200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Search200Response) GetDataOk() (*Search200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Search200Response) SetData(v Search200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *Search200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


