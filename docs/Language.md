# Language

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Language** | **string** | Language code in ISO format (e.g., EN, FR, DE) | 
**Name** | **string** | Human-readable language name | 
**SupportsFormality** | **bool** | Whether formality is supported for this language | 

## Methods

### NewLanguage

`func NewLanguage(language string, name string, supportsFormality bool, ) *Language`

NewLanguage instantiates a new Language object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLanguageWithDefaults

`func NewLanguageWithDefaults() *Language`

NewLanguageWithDefaults instantiates a new Language object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *Language) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Language) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Language) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetName

`func (o *Language) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Language) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Language) SetName(v string)`

SetName sets Name field to given value.


### GetSupportsFormality

`func (o *Language) GetSupportsFormality() bool`

GetSupportsFormality returns the SupportsFormality field if non-nil, zero value otherwise.

### GetSupportsFormalityOk

`func (o *Language) GetSupportsFormalityOk() (*bool, bool)`

GetSupportsFormalityOk returns a tuple with the SupportsFormality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsFormality

`func (o *Language) SetSupportsFormality(v bool)`

SetSupportsFormality sets SupportsFormality field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


