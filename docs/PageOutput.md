# PageOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL of the extracted page | 
**Markdown** | Pointer to **NullableString** | Extracted markdown content of the page. Will be absent if extraction fails. | [optional] 
**Error** | Pointer to **string** | If extraction fails, a string describing the reason why. | [optional] 

## Methods

### NewPageOutput

`func NewPageOutput(url string, ) *PageOutput`

NewPageOutput instantiates a new PageOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPageOutputWithDefaults

`func NewPageOutputWithDefaults() *PageOutput`

NewPageOutputWithDefaults instantiates a new PageOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *PageOutput) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *PageOutput) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *PageOutput) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetMarkdown

`func (o *PageOutput) GetMarkdown() string`

GetMarkdown returns the Markdown field if non-nil, zero value otherwise.

### GetMarkdownOk

`func (o *PageOutput) GetMarkdownOk() (*string, bool)`

GetMarkdownOk returns a tuple with the Markdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdown

`func (o *PageOutput) SetMarkdown(v string)`

SetMarkdown sets Markdown field to given value.

### HasMarkdown

`func (o *PageOutput) HasMarkdown() bool`

HasMarkdown returns a boolean if a field has been set.

### SetMarkdownNil

`func (o *PageOutput) SetMarkdownNil(b bool)`

 SetMarkdownNil sets the value for Markdown to be an explicit nil

### UnsetMarkdown
`func (o *PageOutput) UnsetMarkdown()`

UnsetMarkdown ensures that no value is present for Markdown, not even an explicit nil
### GetError

`func (o *PageOutput) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PageOutput) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PageOutput) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PageOutput) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


