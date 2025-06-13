# SearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** | The search query to perform. | 
**Workflow** | Pointer to **string** | Can be used to filter result output to a single category. | [optional] [default to "search"]

## Methods

### NewSearchRequest

`func NewSearchRequest(query string, ) *SearchRequest`

NewSearchRequest instantiates a new SearchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestWithDefaults

`func NewSearchRequestWithDefaults() *SearchRequest`

NewSearchRequestWithDefaults instantiates a new SearchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *SearchRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SearchRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SearchRequest) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetWorkflow

`func (o *SearchRequest) GetWorkflow() string`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *SearchRequest) GetWorkflowOk() (*string, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *SearchRequest) SetWorkflow(v string)`

SetWorkflow sets Workflow field to given value.

### HasWorkflow

`func (o *SearchRequest) HasWorkflow() bool`

HasWorkflow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


