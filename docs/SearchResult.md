# SearchResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The location of the result. This is the direct URL to the resource that matches the query | 
**Title** | **string** | This is the title of the resource. For HTML resources, it is the title in the header of the document. For Video resources, it is the name of the video that would be displayed on the video site | 
**Snippet** | Pointer to **string** | A short summary of the contents of the resource | [optional] 
**Time** | Pointer to **string** | A date for when the resource was last updated or created. | [optional] 
**Image** | Pointer to [**SearchResultImage**](SearchResultImage.md) |  | [optional] 
**Props** | Pointer to **map[string]interface{}** | Holds arbitrary result metadata | [optional] 

## Methods

### NewSearchResult

`func NewSearchResult(url string, title string, ) *SearchResult`

NewSearchResult instantiates a new SearchResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchResultWithDefaults

`func NewSearchResultWithDefaults() *SearchResult`

NewSearchResultWithDefaults instantiates a new SearchResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *SearchResult) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SearchResult) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SearchResult) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *SearchResult) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SearchResult) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SearchResult) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *SearchResult) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *SearchResult) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *SearchResult) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *SearchResult) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetTime

`func (o *SearchResult) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *SearchResult) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *SearchResult) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *SearchResult) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *SearchResult) GetImage() SearchResultImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *SearchResult) GetImageOk() (*SearchResultImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *SearchResult) SetImage(v SearchResultImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *SearchResult) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *SearchResult) GetProps() map[string]interface{}`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *SearchResult) GetPropsOk() (*map[string]interface{}, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *SearchResult) SetProps(v map[string]interface{})`

SetProps sets Props field to given value.

### HasProps

`func (o *SearchResult) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


