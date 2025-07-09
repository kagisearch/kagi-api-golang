# TranslateDictionaryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Word** | **string** | The word to look up | 
**WordLanguage** | Pointer to **string** | Language code (ISO-639) of the word, or \&quot;auto\&quot; for automatic detection | [optional] [default to "en"]
**DefinitionLanguage** | Pointer to **string** | Language code (ISO-639) for the definition output | [optional] [default to "en"]
**Stream** | Pointer to **bool** | Whether to return a streaming response with fields sent as they become available | [optional] [default to false]
**Nsfw** | Pointer to **bool** | Whether to allow NSFW/inappropriate content. If false, returns empty definition for inappropriate words | [optional] [default to true]
**Model** | Pointer to **string** | Optional model identifier. Can be either a model name (e.g., \&quot;gpt-4o\&quot;, \&quot;claude-35-sonnet\&quot;, \&quot;gemini-flash-2.0\&quot;) or a model constant (e.g., \&quot;ANTHROPIC_CLAUDE_35_SONNET\&quot;, \&quot;OPENAI_GPT4O\&quot;). See model-selection.ts for full list. | [optional] 

## Methods

### NewTranslateDictionaryRequest

`func NewTranslateDictionaryRequest(word string, ) *TranslateDictionaryRequest`

NewTranslateDictionaryRequest instantiates a new TranslateDictionaryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslateDictionaryRequestWithDefaults

`func NewTranslateDictionaryRequestWithDefaults() *TranslateDictionaryRequest`

NewTranslateDictionaryRequestWithDefaults instantiates a new TranslateDictionaryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWord

`func (o *TranslateDictionaryRequest) GetWord() string`

GetWord returns the Word field if non-nil, zero value otherwise.

### GetWordOk

`func (o *TranslateDictionaryRequest) GetWordOk() (*string, bool)`

GetWordOk returns a tuple with the Word field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWord

`func (o *TranslateDictionaryRequest) SetWord(v string)`

SetWord sets Word field to given value.


### GetWordLanguage

`func (o *TranslateDictionaryRequest) GetWordLanguage() string`

GetWordLanguage returns the WordLanguage field if non-nil, zero value otherwise.

### GetWordLanguageOk

`func (o *TranslateDictionaryRequest) GetWordLanguageOk() (*string, bool)`

GetWordLanguageOk returns a tuple with the WordLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWordLanguage

`func (o *TranslateDictionaryRequest) SetWordLanguage(v string)`

SetWordLanguage sets WordLanguage field to given value.

### HasWordLanguage

`func (o *TranslateDictionaryRequest) HasWordLanguage() bool`

HasWordLanguage returns a boolean if a field has been set.

### GetDefinitionLanguage

`func (o *TranslateDictionaryRequest) GetDefinitionLanguage() string`

GetDefinitionLanguage returns the DefinitionLanguage field if non-nil, zero value otherwise.

### GetDefinitionLanguageOk

`func (o *TranslateDictionaryRequest) GetDefinitionLanguageOk() (*string, bool)`

GetDefinitionLanguageOk returns a tuple with the DefinitionLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinitionLanguage

`func (o *TranslateDictionaryRequest) SetDefinitionLanguage(v string)`

SetDefinitionLanguage sets DefinitionLanguage field to given value.

### HasDefinitionLanguage

`func (o *TranslateDictionaryRequest) HasDefinitionLanguage() bool`

HasDefinitionLanguage returns a boolean if a field has been set.

### GetStream

`func (o *TranslateDictionaryRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *TranslateDictionaryRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *TranslateDictionaryRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *TranslateDictionaryRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetNsfw

`func (o *TranslateDictionaryRequest) GetNsfw() bool`

GetNsfw returns the Nsfw field if non-nil, zero value otherwise.

### GetNsfwOk

`func (o *TranslateDictionaryRequest) GetNsfwOk() (*bool, bool)`

GetNsfwOk returns a tuple with the Nsfw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNsfw

`func (o *TranslateDictionaryRequest) SetNsfw(v bool)`

SetNsfw sets Nsfw field to given value.

### HasNsfw

`func (o *TranslateDictionaryRequest) HasNsfw() bool`

HasNsfw returns a boolean if a field has been set.

### GetModel

`func (o *TranslateDictionaryRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *TranslateDictionaryRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *TranslateDictionaryRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *TranslateDictionaryRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


