# V1ResultWebArchive

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**V1ResultWebArchiveProps**](V1ResultWebArchiveProps.md) |  | [optional] 

## Methods

### NewV1ResultWebArchive

`func NewV1ResultWebArchive(url string, title string, snippet string, ) *V1ResultWebArchive`

NewV1ResultWebArchive instantiates a new V1ResultWebArchive object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultWebArchiveWithDefaults

`func NewV1ResultWebArchiveWithDefaults() *V1ResultWebArchive`

NewV1ResultWebArchiveWithDefaults instantiates a new V1ResultWebArchive object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *V1ResultWebArchive) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *V1ResultWebArchive) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *V1ResultWebArchive) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *V1ResultWebArchive) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1ResultWebArchive) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1ResultWebArchive) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *V1ResultWebArchive) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *V1ResultWebArchive) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *V1ResultWebArchive) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *V1ResultWebArchive) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *V1ResultWebArchive) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *V1ResultWebArchive) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *V1ResultWebArchive) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *V1ResultWebArchive) GetImage() V1ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *V1ResultWebArchive) GetImageOk() (*V1ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *V1ResultWebArchive) SetImage(v V1ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *V1ResultWebArchive) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *V1ResultWebArchive) GetProps() V1ResultWebArchiveProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *V1ResultWebArchive) GetPropsOk() (*V1ResultWebArchiveProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *V1ResultWebArchive) SetProps(v V1ResultWebArchiveProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *V1ResultWebArchive) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


