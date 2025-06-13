# V1ResultAdjacentQuestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**V1ResultSearchImage**](V1ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**V1ResultAdjacentQuestionProps**](V1ResultAdjacentQuestionProps.md) |  | [optional] 

## Methods

### NewV1ResultAdjacentQuestion

`func NewV1ResultAdjacentQuestion(url string, title string, snippet string, ) *V1ResultAdjacentQuestion`

NewV1ResultAdjacentQuestion instantiates a new V1ResultAdjacentQuestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultAdjacentQuestionWithDefaults

`func NewV1ResultAdjacentQuestionWithDefaults() *V1ResultAdjacentQuestion`

NewV1ResultAdjacentQuestionWithDefaults instantiates a new V1ResultAdjacentQuestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *V1ResultAdjacentQuestion) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *V1ResultAdjacentQuestion) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *V1ResultAdjacentQuestion) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *V1ResultAdjacentQuestion) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1ResultAdjacentQuestion) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1ResultAdjacentQuestion) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *V1ResultAdjacentQuestion) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *V1ResultAdjacentQuestion) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *V1ResultAdjacentQuestion) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *V1ResultAdjacentQuestion) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *V1ResultAdjacentQuestion) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *V1ResultAdjacentQuestion) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *V1ResultAdjacentQuestion) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *V1ResultAdjacentQuestion) GetImage() V1ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *V1ResultAdjacentQuestion) GetImageOk() (*V1ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *V1ResultAdjacentQuestion) SetImage(v V1ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *V1ResultAdjacentQuestion) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *V1ResultAdjacentQuestion) GetProps() V1ResultAdjacentQuestionProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *V1ResultAdjacentQuestion) GetPropsOk() (*V1ResultAdjacentQuestionProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *V1ResultAdjacentQuestion) SetProps(v V1ResultAdjacentQuestionProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *V1ResultAdjacentQuestion) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


