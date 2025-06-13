# Search200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**T** | **int32** |  | 
**Rank** | Pointer to **int32** |  | [optional] 
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | Pointer to **string** |  | [optional] 
**Published** | Pointer to **string** |  | [optional] 
**Thumbnail** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**Image** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**List** | **[]string** |  | 

## Methods

### NewSearch200ResponseDataInner

`func NewSearch200ResponseDataInner(t int32, url string, title string, list []string, ) *Search200ResponseDataInner`

NewSearch200ResponseDataInner instantiates a new Search200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearch200ResponseDataInnerWithDefaults

`func NewSearch200ResponseDataInnerWithDefaults() *Search200ResponseDataInner`

NewSearch200ResponseDataInnerWithDefaults instantiates a new Search200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetT

`func (o *Search200ResponseDataInner) GetT() int32`

GetT returns the T field if non-nil, zero value otherwise.

### GetTOk

`func (o *Search200ResponseDataInner) GetTOk() (*int32, bool)`

GetTOk returns a tuple with the T field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetT

`func (o *Search200ResponseDataInner) SetT(v int32)`

SetT sets T field to given value.


### GetRank

`func (o *Search200ResponseDataInner) GetRank() int32`

GetRank returns the Rank field if non-nil, zero value otherwise.

### GetRankOk

`func (o *Search200ResponseDataInner) GetRankOk() (*int32, bool)`

GetRankOk returns a tuple with the Rank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRank

`func (o *Search200ResponseDataInner) SetRank(v int32)`

SetRank sets Rank field to given value.

### HasRank

`func (o *Search200ResponseDataInner) HasRank() bool`

HasRank returns a boolean if a field has been set.

### GetUrl

`func (o *Search200ResponseDataInner) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Search200ResponseDataInner) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Search200ResponseDataInner) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *Search200ResponseDataInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Search200ResponseDataInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Search200ResponseDataInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *Search200ResponseDataInner) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *Search200ResponseDataInner) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *Search200ResponseDataInner) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *Search200ResponseDataInner) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetPublished

`func (o *Search200ResponseDataInner) GetPublished() string`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *Search200ResponseDataInner) GetPublishedOk() (*string, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *Search200ResponseDataInner) SetPublished(v string)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *Search200ResponseDataInner) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetThumbnail

`func (o *Search200ResponseDataInner) GetThumbnail() V1ResultSearchImage`

GetThumbnail returns the Thumbnail field if non-nil, zero value otherwise.

### GetThumbnailOk

`func (o *Search200ResponseDataInner) GetThumbnailOk() (*V1ResultSearchImage, bool)`

GetThumbnailOk returns a tuple with the Thumbnail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnail

`func (o *Search200ResponseDataInner) SetThumbnail(v V1ResultSearchImage)`

SetThumbnail sets Thumbnail field to given value.

### HasThumbnail

`func (o *Search200ResponseDataInner) HasThumbnail() bool`

HasThumbnail returns a boolean if a field has been set.

### GetImage

`func (o *Search200ResponseDataInner) GetImage() V1ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Search200ResponseDataInner) GetImageOk() (*V1ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Search200ResponseDataInner) SetImage(v V1ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *Search200ResponseDataInner) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetList

`func (o *Search200ResponseDataInner) GetList() []string`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *Search200ResponseDataInner) GetListOk() (*[]string, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *Search200ResponseDataInner) SetList(v []string)`

SetList sets List field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


