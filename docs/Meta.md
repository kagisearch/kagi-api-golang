# Meta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Trace** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Node** | **string** |  | 
**Ms** | **int32** |  | 
**Query** | Pointer to [**MetaQuery**](MetaQuery.md) |  | [optional] 

## Methods

### NewMeta

`func NewMeta(node string, ms int32, ) *Meta`

NewMeta instantiates a new Meta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetaWithDefaults

`func NewMetaWithDefaults() *Meta`

NewMetaWithDefaults instantiates a new Meta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrace

`func (o *Meta) GetTrace() string`

GetTrace returns the Trace field if non-nil, zero value otherwise.

### GetTraceOk

`func (o *Meta) GetTraceOk() (*string, bool)`

GetTraceOk returns a tuple with the Trace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrace

`func (o *Meta) SetTrace(v string)`

SetTrace sets Trace field to given value.

### HasTrace

`func (o *Meta) HasTrace() bool`

HasTrace returns a boolean if a field has been set.

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

### HasId

`func (o *Meta) HasId() bool`

HasId returns a boolean if a field has been set.

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


### GetQuery

`func (o *Meta) GetQuery() MetaQuery`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *Meta) GetQueryOk() (*MetaQuery, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *Meta) SetQuery(v MetaQuery)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *Meta) HasQuery() bool`

HasQuery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


