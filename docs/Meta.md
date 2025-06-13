# Meta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Node** | **string** |  | 
**Ms** | **int32** |  | 
**ApiBalance** | Pointer to **float32** |  | [optional] 

## Methods

### NewMeta

`func NewMeta(id string, node string, ms int32, ) *Meta`

NewMeta instantiates a new Meta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetaWithDefaults

`func NewMetaWithDefaults() *Meta`

NewMetaWithDefaults instantiates a new Meta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Meta) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Meta) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Meta) SetId(v string)`

SetId sets Id field to given value.


### GetNode

`func (o *Meta) GetNode() string`

GetNode returns the Node field if non-nil, zero value otherwise.

### GetNodeOk

`func (o *Meta) GetNodeOk() (*string, bool)`

GetNodeOk returns a tuple with the Node field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNode

`func (o *Meta) SetNode(v string)`

SetNode sets Node field to given value.


### GetMs

`func (o *Meta) GetMs() int32`

GetMs returns the Ms field if non-nil, zero value otherwise.

### GetMsOk

`func (o *Meta) GetMsOk() (*int32, bool)`

GetMsOk returns a tuple with the Ms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMs

`func (o *Meta) SetMs(v int32)`

SetMs sets Ms field to given value.


### GetApiBalance

`func (o *Meta) GetApiBalance() float32`

GetApiBalance returns the ApiBalance field if non-nil, zero value otherwise.

### GetApiBalanceOk

`func (o *Meta) GetApiBalanceOk() (*float32, bool)`

GetApiBalanceOk returns a tuple with the ApiBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiBalance

`func (o *Meta) SetApiBalance(v float32)`

SetApiBalance sets ApiBalance field to given value.

### HasApiBalance

`func (o *Meta) HasApiBalance() bool`

HasApiBalance returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


