# ResultSearch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | Pointer to **string** |  | [optional] 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**ResultSearchImage**](ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**ResultSearchProps**](ResultSearchProps.md) |  | [optional] 

## Methods

### NewResultSearch

`func NewResultSearch(url string, title string, ) *ResultSearch`

NewResultSearch instantiates a new ResultSearch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultSearchWithDefaults

`func NewResultSearchWithDefaults() *ResultSearch`

NewResultSearchWithDefaults instantiates a new ResultSearch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ResultSearch) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ResultSearch) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ResultSearch) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *ResultSearch) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResultSearch) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResultSearch) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *ResultSearch) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *ResultSearch) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *ResultSearch) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *ResultSearch) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetTime

`func (o *ResultSearch) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ResultSearch) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ResultSearch) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *ResultSearch) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *ResultSearch) GetImage() ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ResultSearch) GetImageOk() (*ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ResultSearch) SetImage(v ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ResultSearch) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *ResultSearch) GetProps() ResultSearchProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *ResultSearch) GetPropsOk() (*ResultSearchProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *ResultSearch) SetProps(v ResultSearchProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *ResultSearch) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


