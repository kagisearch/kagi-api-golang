# V1ResultSearch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | Pointer to **string** |  | [optional] 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**V1ResultSearchProps**](V1ResultSearchProps.md) |  | [optional] 

## Methods

### NewV1ResultSearch

`func NewV1ResultSearch(url string, title string, ) *V1ResultSearch`

NewV1ResultSearch instantiates a new V1ResultSearch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultSearchWithDefaults

`func NewV1ResultSearchWithDefaults() *V1ResultSearch`

NewV1ResultSearchWithDefaults instantiates a new V1ResultSearch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *V1ResultSearch) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *V1ResultSearch) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *V1ResultSearch) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *V1ResultSearch) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1ResultSearch) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1ResultSearch) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *V1ResultSearch) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *V1ResultSearch) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *V1ResultSearch) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *V1ResultSearch) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetTime

`func (o *V1ResultSearch) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *V1ResultSearch) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *V1ResultSearch) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *V1ResultSearch) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *V1ResultSearch) GetImage() V1ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *V1ResultSearch) GetImageOk() (*V1ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *V1ResultSearch) SetImage(v V1ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *V1ResultSearch) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *V1ResultSearch) GetProps() V1ResultSearchProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *V1ResultSearch) GetPropsOk() (*V1ResultSearchProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *V1ResultSearch) SetProps(v V1ResultSearchProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *V1ResultSearch) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


