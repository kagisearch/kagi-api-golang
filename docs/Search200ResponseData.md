# Search200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Search** | Pointer to [**[]ResultSearch**](ResultSearch.md) |  | [optional] 
**Video** | Pointer to [**[]ResultVideo**](ResultVideo.md) |  | [optional] 
**AdjacentQuestion** | Pointer to [**[]ResultAdjacentQuestion**](ResultAdjacentQuestion.md) |  | [optional] 
**Infobox** | Pointer to [**[]ResultInfobox**](ResultInfobox.md) |  | [optional] 
**WebArchive** | Pointer to [**[]ResultWebArchive**](ResultWebArchive.md) |  | [optional] 

## Methods

### NewSearch200ResponseData

`func NewSearch200ResponseData() *Search200ResponseData`

NewSearch200ResponseData instantiates a new Search200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearch200ResponseDataWithDefaults

`func NewSearch200ResponseDataWithDefaults() *Search200ResponseData`

NewSearch200ResponseDataWithDefaults instantiates a new Search200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSearch

`func (o *Search200ResponseData) GetSearch() []ResultSearch`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *Search200ResponseData) GetSearchOk() (*[]ResultSearch, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *Search200ResponseData) SetSearch(v []ResultSearch)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *Search200ResponseData) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### GetVideo

`func (o *Search200ResponseData) GetVideo() []ResultVideo`

GetVideo returns the Video field if non-nil, zero value otherwise.

### GetVideoOk

`func (o *Search200ResponseData) GetVideoOk() (*[]ResultVideo, bool)`

GetVideoOk returns a tuple with the Video field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideo

`func (o *Search200ResponseData) SetVideo(v []ResultVideo)`

SetVideo sets Video field to given value.

### HasVideo

`func (o *Search200ResponseData) HasVideo() bool`

HasVideo returns a boolean if a field has been set.

### GetAdjacentQuestion

`func (o *Search200ResponseData) GetAdjacentQuestion() []ResultAdjacentQuestion`

GetAdjacentQuestion returns the AdjacentQuestion field if non-nil, zero value otherwise.

### GetAdjacentQuestionOk

`func (o *Search200ResponseData) GetAdjacentQuestionOk() (*[]ResultAdjacentQuestion, bool)`

GetAdjacentQuestionOk returns a tuple with the AdjacentQuestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjacentQuestion

`func (o *Search200ResponseData) SetAdjacentQuestion(v []ResultAdjacentQuestion)`

SetAdjacentQuestion sets AdjacentQuestion field to given value.

### HasAdjacentQuestion

`func (o *Search200ResponseData) HasAdjacentQuestion() bool`

HasAdjacentQuestion returns a boolean if a field has been set.

### GetInfobox

`func (o *Search200ResponseData) GetInfobox() []ResultInfobox`

GetInfobox returns the Infobox field if non-nil, zero value otherwise.

### GetInfoboxOk

`func (o *Search200ResponseData) GetInfoboxOk() (*[]ResultInfobox, bool)`

GetInfoboxOk returns a tuple with the Infobox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfobox

`func (o *Search200ResponseData) SetInfobox(v []ResultInfobox)`

SetInfobox sets Infobox field to given value.

### HasInfobox

`func (o *Search200ResponseData) HasInfobox() bool`

HasInfobox returns a boolean if a field has been set.

### GetWebArchive

`func (o *Search200ResponseData) GetWebArchive() []ResultWebArchive`

GetWebArchive returns the WebArchive field if non-nil, zero value otherwise.

### GetWebArchiveOk

`func (o *Search200ResponseData) GetWebArchiveOk() (*[]ResultWebArchive, bool)`

GetWebArchiveOk returns a tuple with the WebArchive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebArchive

`func (o *Search200ResponseData) SetWebArchive(v []ResultWebArchive)`

SetWebArchive sets WebArchive field to given value.

### HasWebArchive

`func (o *Search200ResponseData) HasWebArchive() bool`

HasWebArchive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


