# V1ResultSearchProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ThumbnailImage** | Pointer to [**V1ResultSearchPropsThumbnailImage**](V1ResultSearchPropsThumbnailImage.md) |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**LanguageProbability** | Pointer to **float32** |  | [optional] 
**Paywalled** | Pointer to **bool** |  | [optional] 
**SortNormalizeUrl** | Pointer to **string** |  | [optional] 
**SortGroupId** | Pointer to **string** |  | [optional] 
**SourceHistory** | Pointer to **[]string** |  | [optional] 

## Methods

### NewV1ResultSearchProps

`func NewV1ResultSearchProps() *V1ResultSearchProps`

NewV1ResultSearchProps instantiates a new V1ResultSearchProps object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultSearchPropsWithDefaults

`func NewV1ResultSearchPropsWithDefaults() *V1ResultSearchProps`

NewV1ResultSearchPropsWithDefaults instantiates a new V1ResultSearchProps object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetThumbnailImage

`func (o *V1ResultSearchProps) GetThumbnailImage() V1ResultSearchPropsThumbnailImage`

GetThumbnailImage returns the ThumbnailImage field if non-nil, zero value otherwise.

### GetThumbnailImageOk

`func (o *V1ResultSearchProps) GetThumbnailImageOk() (*V1ResultSearchPropsThumbnailImage, bool)`

GetThumbnailImageOk returns a tuple with the ThumbnailImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailImage

`func (o *V1ResultSearchProps) SetThumbnailImage(v V1ResultSearchPropsThumbnailImage)`

SetThumbnailImage sets ThumbnailImage field to given value.

### HasThumbnailImage

`func (o *V1ResultSearchProps) HasThumbnailImage() bool`

HasThumbnailImage returns a boolean if a field has been set.

### GetLanguage

`func (o *V1ResultSearchProps) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *V1ResultSearchProps) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *V1ResultSearchProps) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *V1ResultSearchProps) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetLanguageProbability

`func (o *V1ResultSearchProps) GetLanguageProbability() float32`

GetLanguageProbability returns the LanguageProbability field if non-nil, zero value otherwise.

### GetLanguageProbabilityOk

`func (o *V1ResultSearchProps) GetLanguageProbabilityOk() (*float32, bool)`

GetLanguageProbabilityOk returns a tuple with the LanguageProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageProbability

`func (o *V1ResultSearchProps) SetLanguageProbability(v float32)`

SetLanguageProbability sets LanguageProbability field to given value.

### HasLanguageProbability

`func (o *V1ResultSearchProps) HasLanguageProbability() bool`

HasLanguageProbability returns a boolean if a field has been set.

### GetPaywalled

`func (o *V1ResultSearchProps) GetPaywalled() bool`

GetPaywalled returns the Paywalled field if non-nil, zero value otherwise.

### GetPaywalledOk

`func (o *V1ResultSearchProps) GetPaywalledOk() (*bool, bool)`

GetPaywalledOk returns a tuple with the Paywalled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaywalled

`func (o *V1ResultSearchProps) SetPaywalled(v bool)`

SetPaywalled sets Paywalled field to given value.

### HasPaywalled

`func (o *V1ResultSearchProps) HasPaywalled() bool`

HasPaywalled returns a boolean if a field has been set.

### GetSortNormalizeUrl

`func (o *V1ResultSearchProps) GetSortNormalizeUrl() string`

GetSortNormalizeUrl returns the SortNormalizeUrl field if non-nil, zero value otherwise.

### GetSortNormalizeUrlOk

`func (o *V1ResultSearchProps) GetSortNormalizeUrlOk() (*string, bool)`

GetSortNormalizeUrlOk returns a tuple with the SortNormalizeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortNormalizeUrl

`func (o *V1ResultSearchProps) SetSortNormalizeUrl(v string)`

SetSortNormalizeUrl sets SortNormalizeUrl field to given value.

### HasSortNormalizeUrl

`func (o *V1ResultSearchProps) HasSortNormalizeUrl() bool`

HasSortNormalizeUrl returns a boolean if a field has been set.

### GetSortGroupId

`func (o *V1ResultSearchProps) GetSortGroupId() string`

GetSortGroupId returns the SortGroupId field if non-nil, zero value otherwise.

### GetSortGroupIdOk

`func (o *V1ResultSearchProps) GetSortGroupIdOk() (*string, bool)`

GetSortGroupIdOk returns a tuple with the SortGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortGroupId

`func (o *V1ResultSearchProps) SetSortGroupId(v string)`

SetSortGroupId sets SortGroupId field to given value.

### HasSortGroupId

`func (o *V1ResultSearchProps) HasSortGroupId() bool`

HasSortGroupId returns a boolean if a field has been set.

### GetSourceHistory

`func (o *V1ResultSearchProps) GetSourceHistory() []string`

GetSourceHistory returns the SourceHistory field if non-nil, zero value otherwise.

### GetSourceHistoryOk

`func (o *V1ResultSearchProps) GetSourceHistoryOk() (*[]string, bool)`

GetSourceHistoryOk returns a tuple with the SourceHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceHistory

`func (o *V1ResultSearchProps) SetSourceHistory(v []string)`

SetSourceHistory sets SourceHistory field to given value.

### HasSourceHistory

`func (o *V1ResultSearchProps) HasSourceHistory() bool`

HasSourceHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


