# ResultAdjacentQuestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Title** | **string** |  | 
**Snippet** | **string** |  | 
**Time** | Pointer to **string** |  | [optional] 
**Image** | Pointer to [**ResultSearchImage**](ResultSearchImage.md) |  | [optional] 
**Props** | Pointer to [**ResultAdjacentQuestionProps**](ResultAdjacentQuestionProps.md) |  | [optional] 

## Methods

### NewResultAdjacentQuestion

`func NewResultAdjacentQuestion(url string, title string, snippet string, ) *ResultAdjacentQuestion`

NewResultAdjacentQuestion instantiates a new ResultAdjacentQuestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultAdjacentQuestionWithDefaults

`func NewResultAdjacentQuestionWithDefaults() *ResultAdjacentQuestion`

NewResultAdjacentQuestionWithDefaults instantiates a new ResultAdjacentQuestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ResultAdjacentQuestion) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ResultAdjacentQuestion) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ResultAdjacentQuestion) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetTitle

`func (o *ResultAdjacentQuestion) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResultAdjacentQuestion) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResultAdjacentQuestion) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *ResultAdjacentQuestion) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *ResultAdjacentQuestion) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *ResultAdjacentQuestion) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTime

`func (o *ResultAdjacentQuestion) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ResultAdjacentQuestion) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ResultAdjacentQuestion) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *ResultAdjacentQuestion) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetImage

`func (o *ResultAdjacentQuestion) GetImage() ResultSearchImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ResultAdjacentQuestion) GetImageOk() (*ResultSearchImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ResultAdjacentQuestion) SetImage(v ResultSearchImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *ResultAdjacentQuestion) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProps

`func (o *ResultAdjacentQuestion) GetProps() ResultAdjacentQuestionProps`

GetProps returns the Props field if non-nil, zero value otherwise.

### GetPropsOk

`func (o *ResultAdjacentQuestion) GetPropsOk() (*ResultAdjacentQuestionProps, bool)`

GetPropsOk returns a tuple with the Props field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProps

`func (o *ResultAdjacentQuestion) SetProps(v ResultAdjacentQuestionProps)`

SetProps sets Props field to given value.

### HasProps

`func (o *ResultAdjacentQuestion) HasProps() bool`

HasProps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


