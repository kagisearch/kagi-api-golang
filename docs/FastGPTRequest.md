# FastGPTRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** |  | [optional] 
**Cache** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewFastGPTRequest

`func NewFastGPTRequest() *FastGPTRequest`

NewFastGPTRequest instantiates a new FastGPTRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFastGPTRequestWithDefaults

`func NewFastGPTRequestWithDefaults() *FastGPTRequest`

NewFastGPTRequestWithDefaults instantiates a new FastGPTRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FastGPTRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FastGPTRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FastGPTRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FastGPTRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetCache

`func (o *FastGPTRequest) GetCache() bool`

GetCache returns the Cache field if non-nil, zero value otherwise.

### GetCacheOk

`func (o *FastGPTRequest) GetCacheOk() (*bool, bool)`

GetCacheOk returns a tuple with the Cache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCache

`func (o *FastGPTRequest) SetCache(v bool)`

SetCache sets Cache field to given value.

### HasCache

`func (o *FastGPTRequest) HasCache() bool`

HasCache returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


