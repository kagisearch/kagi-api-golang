# V1ResultInfobox

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**V1ResultInfoboxProps**](V1ResultInfoboxProps.md) |  | [optional] 

## Methods

### NewV1ResultInfobox

`func NewV1ResultInfobox(url string, title string, snippet string, ) *V1ResultInfobox`

NewV1ResultInfobox instantiates a new V1ResultInfobox object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultInfoboxWithDefaults

`func NewV1ResultInfoboxWithDefaults() *V1ResultInfobox`

NewV1ResultInfoboxWithDefaults instantiates a new V1ResultInfobox object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *V1ResultInfobox) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *V1ResultInfobox) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *V1ResultInfobox) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *V1ResultInfobox) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1ResultInfobox) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1ResultInfobox) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *V1ResultInfobox) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *V1ResultInfobox) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *V1ResultInfobox) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *V1ResultInfobox) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *V1ResultInfobox) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *V1ResultInfobox) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *V1ResultInfobox) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *V1ResultInfobox) GetImage() V1ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *V1ResultInfobox) GetImageOk() (*V1ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *V1ResultInfobox) SetImage(v V1ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *V1ResultInfobox) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *V1ResultInfobox) GetProps() V1ResultInfoboxProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *V1ResultInfobox) GetPropsOk() (*V1ResultInfoboxProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *V1ResultInfobox) SetProps(v V1ResultInfoboxProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *V1ResultInfobox) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


