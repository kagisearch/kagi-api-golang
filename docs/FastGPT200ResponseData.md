# FastGPT200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Output** | Pointer to **string** |  | [optional] 
**Tokens** | Pointer to **int32** |  | [optional] 
**References** | Pointer to [**[]SearchObject**](SearchObject.md) |  | [optional] 

## Methods

### NewFastGPT200ResponseData

`func NewFastGPT200ResponseData() *FastGPT200ResponseData`

NewFastGPT200ResponseData instantiates a new FastGPT200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFastGPT200ResponseDataWithDefaults

`func NewFastGPT200ResponseDataWithDefaults() *FastGPT200ResponseData`

NewFastGPT200ResponseDataWithDefaults instantiates a new FastGPT200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutput

`func (o *FastGPT200ResponseData) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *FastGPT200ResponseData) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *FastGPT200ResponseData) SetOutput(v string)`

SetOutput sets Output field to given value.

### HasOutput

`func (o *FastGPT200ResponseData) HasOutput() bool`

HasOutput returns a boolean if a field has been set.

### GetTokens

`func (o *FastGPT200ResponseData) GetTokens() int32`

GetTokens returns the Tokens field if non-nil, zero value otherwise.

### GetTokensOk

`func (o *FastGPT200ResponseData) GetTokensOk() (*int32, bool)`

GetTokensOk returns a tuple with the Tokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokens

`func (o *FastGPT200ResponseData) SetTokens(v int32)`

SetTokens sets Tokens field to given value.

### HasTokens

`func (o *FastGPT200ResponseData) HasTokens() bool`

HasTokens returns a boolean if a field has been set.

### GetReferences

`func (o *FastGPT200ResponseData) GetReferences() []SearchObject`

GetReferences returns the References field if non-nil, zero value otherwise.

### GetReferencesOk

`func (o *FastGPT200ResponseData) GetReferencesOk() (*[]SearchObject, bool)`

GetReferencesOk returns a tuple with the References field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferences

`func (o *FastGPT200ResponseData) SetReferences(v []SearchObject)`

SetReferences sets References field to given value.

### HasReferences

`func (o *FastGPT200ResponseData) HasReferences() bool`

HasReferences returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


