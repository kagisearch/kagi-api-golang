# V1Meta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Trace** | **string** |  | 
**Node** | **string** |  | 
**Ms** | **int32** |  | 
**Query** | Pointer to [**V1MetaQuery**](V1MetaQuery.md) |  | [optional] 

## Methods

### NewV1Meta

`func NewV1Meta(trace string, node string, ms int32, ) *V1Meta`

NewV1Meta instantiates a new V1Meta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1MetaWithDefaults

`func NewV1MetaWithDefaults() *V1Meta`

NewV1MetaWithDefaults instantiates a new V1Meta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrace

`func (o *V1Meta) GetTrace() string`

GetTrace returns the Trace field if non-nil, zero value otherwise.

### GetTraceOk

`func (o *V1Meta) GetTraceOk() (*string, bool)`

GetTraceOk returns a tuple with the Trace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrace

`func (o *V1Meta) SetTrace(v string)`

SetTrace sets Trace field to given value.


### GetNode

`func (o *V1Meta) GetNode() string`

GetNode returns the Node field if non-nil, zero value otherwise.

### GetNodeOk

`func (o *V1Meta) GetNodeOk() (*string, bool)`

GetNodeOk returns a tuple with the Node field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNode

`func (o *V1Meta) SetNode(v string)`

SetNode sets Node field to given value.


### GetMs

`func (o *V1Meta) GetMs() int32`

GetMs returns the Ms field if non-nil, zero value otherwise.

### GetMsOk

`func (o *V1Meta) GetMsOk() (*int32, bool)`

GetMsOk returns a tuple with the Ms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMs

`func (o *V1Meta) SetMs(v int32)`

SetMs sets Ms field to given value.


### GetQuery

`func (o *V1Meta) GetQuery() V1MetaQuery`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *V1Meta) GetQueryOk() (*V1MetaQuery, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *V1Meta) SetQuery(v V1MetaQuery)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *V1Meta) HasQuery() bool`

HasQuery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


