# ResultSearchProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ThumbnailImage** | Pointer to [**ResultSearchPropsThumbnailImage**](ResultSearchPropsThumbnailImage.md) |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**LanguageProbability** | Pointer to **float32** |  | [optional] 
**Paywalled** | Pointer to **bool** |  | [optional] 
**SortNormalizeUrl** | Pointer to **string** |  | [optional] 
**SortGroupId** | Pointer to **string** |  | [optional] 
**SourceHistory** | Pointer to **[]string** |  | [optional] 

## Methods

### NewResultSearchProps

`func NewResultSearchProps() *ResultSearchProps`

NewResultSearchProps instantiates a new ResultSearchProps object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultSearchPropsWithDefaults

`func NewResultSearchPropsWithDefaults() *ResultSearchProps`

NewResultSearchPropsWithDefaults instantiates a new ResultSearchProps object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetThumbnailImage

`func (o *ResultSearchProps) GetThumbnailImage() ResultSearchPropsThumbnailImage`

GetThumbnailImage returns the ThumbnailImage field if non-nil, zero value otherwise.

### GetThumbnailImageOk

`func (o *ResultSearchProps) GetThumbnailImageOk() (*ResultSearchPropsThumbnailImage, bool)`

GetThumbnailImageOk returns a tuple with the ThumbnailImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailImage

`func (o *ResultSearchProps) SetThumbnailImage(v ResultSearchPropsThumbnailImage)`

SetThumbnailImage sets ThumbnailImage field to given value.

### HasThumbnailImage

`func (o *ResultSearchProps) HasThumbnailImage() bool`

HasThumbnailImage returns a boolean if a field has been set.

### GetLanguage

`func (o *ResultSearchProps) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ResultSearchProps) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ResultSearchProps) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *ResultSearchProps) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetLanguageProbability

`func (o *ResultSearchProps) GetLanguageProbability() float32`

GetLanguageProbability returns the LanguageProbability field if non-nil, zero value otherwise.

### GetLanguageProbabilityOk

`func (o *ResultSearchProps) GetLanguageProbabilityOk() (*float32, bool)`

GetLanguageProbabilityOk returns a tuple with the LanguageProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageProbability

`func (o *ResultSearchProps) SetLanguageProbability(v float32)`

SetLanguageProbability sets LanguageProbability field to given value.

### HasLanguageProbability

`func (o *ResultSearchProps) HasLanguageProbability() bool`

HasLanguageProbability returns a boolean if a field has been set.

### GetPaywalled

`func (o *ResultSearchProps) GetPaywalled() bool`

GetPaywalled returns the Paywalled field if non-nil, zero value otherwise.

### GetPaywalledOk

`func (o *ResultSearchProps) GetPaywalledOk() (*bool, bool)`

GetPaywalledOk returns a tuple with the Paywalled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaywalled

`func (o *ResultSearchProps) SetPaywalled(v bool)`

SetPaywalled sets Paywalled field to given value.

### HasPaywalled

`func (o *ResultSearchProps) HasPaywalled() bool`

HasPaywalled returns a boolean if a field has been set.

### GetSortNormalizeUrl

`func (o *ResultSearchProps) GetSortNormalizeUrl() string`

GetSortNormalizeUrl returns the SortNormalizeUrl field if non-nil, zero value otherwise.

### GetSortNormalizeUrlOk

`func (o *ResultSearchProps) GetSortNormalizeUrlOk() (*string, bool)`

GetSortNormalizeUrlOk returns a tuple with the SortNormalizeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortNormalizeUrl

`func (o *ResultSearchProps) SetSortNormalizeUrl(v string)`

SetSortNormalizeUrl sets SortNormalizeUrl field to given value.

### HasSortNormalizeUrl

`func (o *ResultSearchProps) HasSortNormalizeUrl() bool`

HasSortNormalizeUrl returns a boolean if a field has been set.

### GetSortGroupId

`func (o *ResultSearchProps) GetSortGroupId() string`

GetSortGroupId returns the SortGroupId field if non-nil, zero value otherwise.

### GetSortGroupIdOk

`func (o *ResultSearchProps) GetSortGroupIdOk() (*string, bool)`

GetSortGroupIdOk returns a tuple with the SortGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortGroupId

`func (o *ResultSearchProps) SetSortGroupId(v string)`

SetSortGroupId sets SortGroupId field to given value.

### HasSortGroupId

`func (o *ResultSearchProps) HasSortGroupId() bool`

HasSortGroupId returns a boolean if a field has been set.

### GetSourceHistory

`func (o *ResultSearchProps) GetSourceHistory() []string`

GetSourceHistory returns the SourceHistory field if non-nil, zero value otherwise.

### GetSourceHistoryOk

`func (o *ResultSearchProps) GetSourceHistoryOk() (*[]string, bool)`

GetSourceHistoryOk returns a tuple with the SourceHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceHistory

`func (o *ResultSearchProps) SetSourceHistory(v []string)`

SetSourceHistory sets SourceHistory field to given value.

### HasSourceHistory

`func (o *ResultSearchProps) HasSourceHistory() bool`

HasSourceHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


