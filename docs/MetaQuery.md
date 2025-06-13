# MetaQuery

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Raw** | Pointer to **string** |  | [optional] 
**Terms** | Pointer to **string** |  | [optional] 
**Fields** | Pointer to [**[]MetaQueryFieldsInner**](MetaQueryFieldsInner.md) |  | [optional] 
**Workflow** | Pointer to **string** |  | [optional] 

## Methods

### NewMetaQuery

`func NewMetaQuery() *MetaQuery`

NewMetaQuery instantiates a new MetaQuery object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetaQueryWithDefaults

`func NewMetaQueryWithDefaults() *MetaQuery`

NewMetaQueryWithDefaults instantiates a new MetaQuery object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRaw

`func (o *MetaQuery) GetRaw() string`

GetRaw returns the Raw field if non-nil, zero value otherwise.

### GetRawOk

`func (o *MetaQuery) GetRawOk() (*string, bool)`

GetRawOk returns a tuple with the Raw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaw

`func (o *MetaQuery) SetRaw(v string)`

SetRaw sets Raw field to given value.

### HasRaw

`func (o *MetaQuery) HasRaw() bool`

HasRaw returns a boolean if a field has been set.

### GetTerms

`func (o *MetaQuery) GetTerms() string`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *MetaQuery) GetTermsOk() (*string, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *MetaQuery) SetTerms(v string)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *MetaQuery) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetFields

`func (o *MetaQuery) GetFields() []MetaQueryFieldsInner`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *MetaQuery) GetFieldsOk() (*[]MetaQueryFieldsInner, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *MetaQuery) SetFields(v []MetaQueryFieldsInner)`

SetFields sets Fields field to given value.

### HasFields

`func (o *MetaQuery) HasFields() bool`

HasFields returns a boolean if a field has been set.

### GetWorkflow

`func (o *MetaQuery) GetWorkflow() string`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *MetaQuery) GetWorkflowOk() (*string, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *MetaQuery) SetWorkflow(v string)`

SetWorkflow sets Workflow field to given value.

### HasWorkflow

`func (o *MetaQuery) HasWorkflow() bool`

HasWorkflow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


