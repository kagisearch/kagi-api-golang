# SearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** | The search query to perform. | 
**Workflow** | Pointer to **string** | Can be used to filter result output to a single category. | [optional] [default to "search"]
**LensId** | Pointer to **string** | A lens ID, as shown on https://kagi.com/settings/lenses when a lens is set to be shareable. Can be just the ID portion of the URL (&#x60;https://kagi.com/lenses/ID&#x60;), or the full URL. | [optional] 
**Lens** | Pointer to [**SearchRequestLens**](SearchRequestLens.md) |  | [optional] 
**Timeout** | Pointer to **float32** | Number of seconds to allow for collecting search results. Lower values will return results more quickly, but may be lower quality or inconsistent between calls. If omitted, will use the latest recommended value by Kagi. | [optional] 

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

### GetLensId

`func (o *SearchRequest) GetLensId() string`

GetLensId returns the LensId field if non-nil, zero value otherwise.

### GetLensIdOk

`func (o *SearchRequest) GetLensIdOk() (*string, bool)`

GetLensIdOk returns a tuple with the LensId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensId

`func (o *SearchRequest) SetLensId(v string)`

SetLensId sets LensId field to given value.

### HasLensId

`func (o *SearchRequest) HasLensId() bool`

HasLensId returns a boolean if a field has been set.

### GetLens

`func (o *SearchRequest) GetLens() SearchRequestLens`

GetLens returns the Lens field if non-nil, zero value otherwise.

### GetLensOk

`func (o *SearchRequest) GetLensOk() (*SearchRequestLens, bool)`

GetLensOk returns a tuple with the Lens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLens

`func (o *SearchRequest) SetLens(v SearchRequestLens)`

SetLens sets Lens field to given value.

### HasLens

`func (o *SearchRequest) HasLens() bool`

HasLens returns a boolean if a field has been set.

### GetTimeout

`func (o *SearchRequest) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *SearchRequest) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *SearchRequest) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *SearchRequest) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


