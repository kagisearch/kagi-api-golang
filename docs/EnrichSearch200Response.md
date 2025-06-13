# EnrichSearch200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Meta** | Pointer to [**Meta**](Meta.md) |  | [optional] 
**Data** | Pointer to [**[]SearchObject**](SearchObject.md) |  | [optional] 

## Methods

### NewEnrichSearch200Response

`func NewEnrichSearch200Response() *EnrichSearch200Response`

NewEnrichSearch200Response instantiates a new EnrichSearch200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnrichSearch200ResponseWithDefaults

`func NewEnrichSearch200ResponseWithDefaults() *EnrichSearch200Response`

NewEnrichSearch200ResponseWithDefaults instantiates a new EnrichSearch200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeta

`func (o *EnrichSearch200Response) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *EnrichSearch200Response) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *EnrichSearch200Response) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *EnrichSearch200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *EnrichSearch200Response) GetData() []SearchObject`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *EnrichSearch200Response) GetDataOk() (*[]SearchObject, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *EnrichSearch200Response) SetData(v []SearchObject)`

SetData sets Data field to given value.

### HasData

`func (o *EnrichSearch200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


