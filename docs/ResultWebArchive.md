# ResultWebArchive

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**ResultSearchImage**](ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**ResultWebArchiveProps**](ResultWebArchiveProps.md) |  | [optional] 

## Methods

### NewResultWebArchive

`func NewResultWebArchive(url string, title string, snippet string, ) *ResultWebArchive`

NewResultWebArchive instantiates a new ResultWebArchive object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultWebArchiveWithDefaults

`func NewResultWebArchiveWithDefaults() *ResultWebArchive`

NewResultWebArchiveWithDefaults instantiates a new ResultWebArchive object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ResultWebArchive) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ResultWebArchive) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ResultWebArchive) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *ResultWebArchive) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResultWebArchive) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResultWebArchive) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *ResultWebArchive) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *ResultWebArchive) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *ResultWebArchive) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *ResultWebArchive) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ResultWebArchive) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ResultWebArchive) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *ResultWebArchive) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *ResultWebArchive) GetImage() ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ResultWebArchive) GetImageOk() (*ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ResultWebArchive) SetImage(v ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ResultWebArchive) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *ResultWebArchive) GetProps() ResultWebArchiveProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *ResultWebArchive) GetPropsOk() (*ResultWebArchiveProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *ResultWebArchive) SetProps(v ResultWebArchiveProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *ResultWebArchive) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


