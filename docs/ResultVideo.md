# ResultVideo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | Pointer to **string** |  | [optional] 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**ResultSearchImage**](ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**ResultVideoProps**](ResultVideoProps.md) |  | [optional] 

## Methods

### NewResultVideo

`func NewResultVideo(url string, title string, ) *ResultVideo`

NewResultVideo instantiates a new ResultVideo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultVideoWithDefaults

`func NewResultVideoWithDefaults() *ResultVideo`

NewResultVideoWithDefaults instantiates a new ResultVideo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ResultVideo) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ResultVideo) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ResultVideo) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *ResultVideo) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResultVideo) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResultVideo) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *ResultVideo) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *ResultVideo) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *ResultVideo) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *ResultVideo) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetTime

`func (o *ResultVideo) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ResultVideo) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ResultVideo) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *ResultVideo) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *ResultVideo) GetImage() ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ResultVideo) GetImageOk() (*ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ResultVideo) SetImage(v ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ResultVideo) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *ResultVideo) GetProps() ResultVideoProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *ResultVideo) GetPropsOk() (*ResultVideoProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *ResultVideo) SetProps(v ResultVideoProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *ResultVideo) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


