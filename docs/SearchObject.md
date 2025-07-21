# SearchObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**T** | Pointer to **int32** | This is always set to 0. It is used as a flag to identify if the result was a rearch result or a related searches object. | [optional] 
**Rank** | Pointer to **int32** | Order of resarch results, the highest rank is 1 and should identify results that match the search request better. | [optional] 
**Url** | **string** | URL of the resource identified in the search result. | 
**Title** | **string** | Title of the search result. This can be taken from the title of the html document, or the title of a media resource. | 
**Snippet** | Pointer to **string** | a short desciption, or summary, of the content. | [optional] 
**Published** | Pointer to **string** | the date the rearch result was created | [optional] 
**Thumbnail** | Pointer to [**SearchObjectThumbnail**](SearchObjectThumbnail.md) |  | [optional] 
**Image** | Pointer to [**SearchObjectImage**](SearchObjectImage.md) |  | [optional] 

## Methods

### NewSearchObject

`func NewSearchObject(url string, title string, ) *SearchObject`

NewSearchObject instantiates a new SearchObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchObjectWithDefaults

`func NewSearchObjectWithDefaults() *SearchObject`

NewSearchObjectWithDefaults instantiates a new SearchObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetT

`func (o *SearchObject) GetT() int32`

GetT returns the T field if non-nil, zero value otherwise.

### GetTOk

`func (o *SearchObject) GetTOk() (*int32, bool)`

GetTOk returns a tuple with the T field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetT

`func (o *SearchObject) SetT(v int32)`

SetT sets T field to given value.

### HasT

`func (o *SearchObject) HasT() bool`

HasT returns a boolean if a field has been set.

### GetRank

`func (o *SearchObject) GetRank() int32`

GetRank returns the Rank field if non-nil, zero value otherwise.

### GetRankOk

`func (o *SearchObject) GetRankOk() (*int32, bool)`

GetRankOk returns a tuple with the Rank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRank

`func (o *SearchObject) SetRank(v int32)`

SetRank sets Rank field to given value.

### HasRank

`func (o *SearchObject) HasRank() bool`

HasRank returns a boolean if a field has been set.

### GetUrl

`func (o *SearchObject) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SearchObject) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SearchObject) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *SearchObject) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SearchObject) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SearchObject) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *SearchObject) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *SearchObject) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *SearchObject) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *SearchObject) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetPublished

`func (o *SearchObject) GetPublished() string`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *SearchObject) GetPublishedOk() (*string, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *SearchObject) SetPublished(v string)`

SetPublished sets Published field to given value.

### HasPublished

`func (o *SearchObject) HasPublished() bool`

HasPublished returns a boolean if a field has been set.

### GetThumbnail

`func (o *SearchObject) GetThumbnail() SearchObjectThumbnail`

GetThumbnail returns the Thumbnail field if non-nil, zero value otherwise.

### GetThumbnailOk

`func (o *SearchObject) GetThumbnailOk() (*SearchObjectThumbnail, bool)`

GetThumbnailOk returns a tuple with the Thumbnail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnail

`func (o *SearchObject) SetThumbnail(v SearchObjectThumbnail)`

SetThumbnail sets Thumbnail field to given value.

### HasThumbnail

`func (o *SearchObject) HasThumbnail() bool`

HasThumbnail returns a boolean if a field has been set.

### GetImage

`func (o *SearchObject) GetImage() SearchObjectImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *SearchObject) GetImageOk() (*SearchObjectImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *SearchObject) SetImage(v SearchObjectImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *SearchObject) HasImage() bool`

HasImage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


