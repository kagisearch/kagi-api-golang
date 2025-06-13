# ResultInfobox

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**ResultSearchImage**](ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**ResultInfoboxProps**](ResultInfoboxProps.md) |  | [optional] 

## Methods

### NewResultInfobox

`func NewResultInfobox(url string, title string, snippet string, ) *ResultInfobox`

NewResultInfobox instantiates a new ResultInfobox object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultInfoboxWithDefaults

`func NewResultInfoboxWithDefaults() *ResultInfobox`

NewResultInfoboxWithDefaults instantiates a new ResultInfobox object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ResultInfobox) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ResultInfobox) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ResultInfobox) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *ResultInfobox) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResultInfobox) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResultInfobox) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *ResultInfobox) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *ResultInfobox) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *ResultInfobox) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *ResultInfobox) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ResultInfobox) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ResultInfobox) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *ResultInfobox) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *ResultInfobox) GetImage() ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ResultInfobox) GetImageOk() (*ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ResultInfobox) SetImage(v ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ResultInfobox) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *ResultInfobox) GetProps() ResultInfoboxProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *ResultInfobox) GetPropsOk() (*ResultInfoboxProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *ResultInfobox) SetProps(v ResultInfoboxProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *ResultInfobox) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


