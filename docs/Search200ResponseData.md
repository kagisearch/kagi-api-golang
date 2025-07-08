# Search200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Search** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Image** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Video** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Podcast** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**PodcastCreator** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**News** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**AdjacentQuestion** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**DirectAnswer** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**InterestingNews** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**InterestingFinds** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Infobox** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Code** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**PackageTracking** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**PublicRecords** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Weather** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**RelatedSearch** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**Listicle** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 
**WebArchive** | Pointer to [**[]SearchResult**](SearchResult.md) |  | [optional] 

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

`func (o *Search200ResponseData) GetSearch() []SearchResult`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *Search200ResponseData) GetSearchOk() (*[]SearchResult, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *Search200ResponseData) SetSearch(v []SearchResult)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *Search200ResponseData) HasSearch() bool`

HasSearch returns a boolean if a field has been set.

### GetImage

`func (o *Search200ResponseData) GetImage() []SearchResult`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Search200ResponseData) GetImageOk() (*[]SearchResult, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Search200ResponseData) SetImage(v []SearchResult)`

SetImage sets Image field to given value.

### HasImage

`func (o *Search200ResponseData) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetVideo

`func (o *Search200ResponseData) GetVideo() []SearchResult`

GetVideo returns the Video field if non-nil, zero value otherwise.

### GetVideoOk

`func (o *Search200ResponseData) GetVideoOk() (*[]SearchResult, bool)`

GetVideoOk returns a tuple with the Video field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideo

`func (o *Search200ResponseData) SetVideo(v []SearchResult)`

SetVideo sets Video field to given value.

### HasVideo

`func (o *Search200ResponseData) HasVideo() bool`

HasVideo returns a boolean if a field has been set.

### GetPodcast

`func (o *Search200ResponseData) GetPodcast() []SearchResult`

GetPodcast returns the Podcast field if non-nil, zero value otherwise.

### GetPodcastOk

`func (o *Search200ResponseData) GetPodcastOk() (*[]SearchResult, bool)`

GetPodcastOk returns a tuple with the Podcast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPodcast

`func (o *Search200ResponseData) SetPodcast(v []SearchResult)`

SetPodcast sets Podcast field to given value.

### HasPodcast

`func (o *Search200ResponseData) HasPodcast() bool`

HasPodcast returns a boolean if a field has been set.

### GetPodcastCreator

`func (o *Search200ResponseData) GetPodcastCreator() []SearchResult`

GetPodcastCreator returns the PodcastCreator field if non-nil, zero value otherwise.

### GetPodcastCreatorOk

`func (o *Search200ResponseData) GetPodcastCreatorOk() (*[]SearchResult, bool)`

GetPodcastCreatorOk returns a tuple with the PodcastCreator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPodcastCreator

`func (o *Search200ResponseData) SetPodcastCreator(v []SearchResult)`

SetPodcastCreator sets PodcastCreator field to given value.

### HasPodcastCreator

`func (o *Search200ResponseData) HasPodcastCreator() bool`

HasPodcastCreator returns a boolean if a field has been set.

### GetNews

`func (o *Search200ResponseData) GetNews() []SearchResult`

GetNews returns the News field if non-nil, zero value otherwise.

### GetNewsOk

`func (o *Search200ResponseData) GetNewsOk() (*[]SearchResult, bool)`

GetNewsOk returns a tuple with the News field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNews

`func (o *Search200ResponseData) SetNews(v []SearchResult)`

SetNews sets News field to given value.

### HasNews

`func (o *Search200ResponseData) HasNews() bool`

HasNews returns a boolean if a field has been set.

### GetAdjacentQuestion

`func (o *Search200ResponseData) GetAdjacentQuestion() []SearchResult`

GetAdjacentQuestion returns the AdjacentQuestion field if non-nil, zero value otherwise.

### GetAdjacentQuestionOk

`func (o *Search200ResponseData) GetAdjacentQuestionOk() (*[]SearchResult, bool)`

GetAdjacentQuestionOk returns a tuple with the AdjacentQuestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjacentQuestion

`func (o *Search200ResponseData) SetAdjacentQuestion(v []SearchResult)`

SetAdjacentQuestion sets AdjacentQuestion field to given value.

### HasAdjacentQuestion

`func (o *Search200ResponseData) HasAdjacentQuestion() bool`

HasAdjacentQuestion returns a boolean if a field has been set.

### GetDirectAnswer

`func (o *Search200ResponseData) GetDirectAnswer() []SearchResult`

GetDirectAnswer returns the DirectAnswer field if non-nil, zero value otherwise.

### GetDirectAnswerOk

`func (o *Search200ResponseData) GetDirectAnswerOk() (*[]SearchResult, bool)`

GetDirectAnswerOk returns a tuple with the DirectAnswer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectAnswer

`func (o *Search200ResponseData) SetDirectAnswer(v []SearchResult)`

SetDirectAnswer sets DirectAnswer field to given value.

### HasDirectAnswer

`func (o *Search200ResponseData) HasDirectAnswer() bool`

HasDirectAnswer returns a boolean if a field has been set.

### GetInterestingNews

`func (o *Search200ResponseData) GetInterestingNews() []SearchResult`

GetInterestingNews returns the InterestingNews field if non-nil, zero value otherwise.

### GetInterestingNewsOk

`func (o *Search200ResponseData) GetInterestingNewsOk() (*[]SearchResult, bool)`

GetInterestingNewsOk returns a tuple with the InterestingNews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterestingNews

`func (o *Search200ResponseData) SetInterestingNews(v []SearchResult)`

SetInterestingNews sets InterestingNews field to given value.

### HasInterestingNews

`func (o *Search200ResponseData) HasInterestingNews() bool`

HasInterestingNews returns a boolean if a field has been set.

### GetInterestingFinds

`func (o *Search200ResponseData) GetInterestingFinds() []SearchResult`

GetInterestingFinds returns the InterestingFinds field if non-nil, zero value otherwise.

### GetInterestingFindsOk

`func (o *Search200ResponseData) GetInterestingFindsOk() (*[]SearchResult, bool)`

GetInterestingFindsOk returns a tuple with the InterestingFinds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterestingFinds

`func (o *Search200ResponseData) SetInterestingFinds(v []SearchResult)`

SetInterestingFinds sets InterestingFinds field to given value.

### HasInterestingFinds

`func (o *Search200ResponseData) HasInterestingFinds() bool`

HasInterestingFinds returns a boolean if a field has been set.

### GetInfobox

`func (o *Search200ResponseData) GetInfobox() []SearchResult`

GetInfobox returns the Infobox field if non-nil, zero value otherwise.

### GetInfoboxOk

`func (o *Search200ResponseData) GetInfoboxOk() (*[]SearchResult, bool)`

GetInfoboxOk returns a tuple with the Infobox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfobox

`func (o *Search200ResponseData) SetInfobox(v []SearchResult)`

SetInfobox sets Infobox field to given value.

### HasInfobox

`func (o *Search200ResponseData) HasInfobox() bool`

HasInfobox returns a boolean if a field has been set.

### GetCode

`func (o *Search200ResponseData) GetCode() []SearchResult`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Search200ResponseData) GetCodeOk() (*[]SearchResult, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Search200ResponseData) SetCode(v []SearchResult)`

SetCode sets Code field to given value.

### HasCode

`func (o *Search200ResponseData) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetPackageTracking

`func (o *Search200ResponseData) GetPackageTracking() []SearchResult`

GetPackageTracking returns the PackageTracking field if non-nil, zero value otherwise.

### GetPackageTrackingOk

`func (o *Search200ResponseData) GetPackageTrackingOk() (*[]SearchResult, bool)`

GetPackageTrackingOk returns a tuple with the PackageTracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageTracking

`func (o *Search200ResponseData) SetPackageTracking(v []SearchResult)`

SetPackageTracking sets PackageTracking field to given value.

### HasPackageTracking

`func (o *Search200ResponseData) HasPackageTracking() bool`

HasPackageTracking returns a boolean if a field has been set.

### GetPublicRecords

`func (o *Search200ResponseData) GetPublicRecords() []SearchResult`

GetPublicRecords returns the PublicRecords field if non-nil, zero value otherwise.

### GetPublicRecordsOk

`func (o *Search200ResponseData) GetPublicRecordsOk() (*[]SearchResult, bool)`

GetPublicRecordsOk returns a tuple with the PublicRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicRecords

`func (o *Search200ResponseData) SetPublicRecords(v []SearchResult)`

SetPublicRecords sets PublicRecords field to given value.

### HasPublicRecords

`func (o *Search200ResponseData) HasPublicRecords() bool`

HasPublicRecords returns a boolean if a field has been set.

### GetWeather

`func (o *Search200ResponseData) GetWeather() []SearchResult`

GetWeather returns the Weather field if non-nil, zero value otherwise.

### GetWeatherOk

`func (o *Search200ResponseData) GetWeatherOk() (*[]SearchResult, bool)`

GetWeatherOk returns a tuple with the Weather field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeather

`func (o *Search200ResponseData) SetWeather(v []SearchResult)`

SetWeather sets Weather field to given value.

### HasWeather

`func (o *Search200ResponseData) HasWeather() bool`

HasWeather returns a boolean if a field has been set.

### GetRelatedSearch

`func (o *Search200ResponseData) GetRelatedSearch() []SearchResult`

GetRelatedSearch returns the RelatedSearch field if non-nil, zero value otherwise.

### GetRelatedSearchOk

`func (o *Search200ResponseData) GetRelatedSearchOk() (*[]SearchResult, bool)`

GetRelatedSearchOk returns a tuple with the RelatedSearch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedSearch

`func (o *Search200ResponseData) SetRelatedSearch(v []SearchResult)`

SetRelatedSearch sets RelatedSearch field to given value.

### HasRelatedSearch

`func (o *Search200ResponseData) HasRelatedSearch() bool`

HasRelatedSearch returns a boolean if a field has been set.

### GetListicle

`func (o *Search200ResponseData) GetListicle() []SearchResult`

GetListicle returns the Listicle field if non-nil, zero value otherwise.

### GetListicleOk

`func (o *Search200ResponseData) GetListicleOk() (*[]SearchResult, bool)`

GetListicleOk returns a tuple with the Listicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetListicle

`func (o *Search200ResponseData) SetListicle(v []SearchResult)`

SetListicle sets Listicle field to given value.

### HasListicle

`func (o *Search200ResponseData) HasListicle() bool`

HasListicle returns a boolean if a field has been set.

### GetWebArchive

`func (o *Search200ResponseData) GetWebArchive() []SearchResult`

GetWebArchive returns the WebArchive field if non-nil, zero value otherwise.

### GetWebArchiveOk

`func (o *Search200ResponseData) GetWebArchiveOk() (*[]SearchResult, bool)`

GetWebArchiveOk returns a tuple with the WebArchive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebArchive

`func (o *Search200ResponseData) SetWebArchive(v []SearchResult)`

SetWebArchive sets WebArchive field to given value.

### HasWebArchive

`func (o *Search200ResponseData) HasWebArchive() bool`

HasWebArchive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


