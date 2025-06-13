# V1ResultInfoboxProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Infobox** | Pointer to [**[]V1ResultInfoboxPropsInfoboxInner**](V1ResultInfoboxPropsInfoboxInner.md) |  | [optional] 
**WikipediaSubtext** | Pointer to **string** |  | [optional] 
**WikipediaPageId** | Pointer to **int32** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**LanguageProbability** | Pointer to **float32** |  | [optional] 
**SortNormalizeUrl** | Pointer to **string** |  | [optional] 
**SortGroupId** | Pointer to **string** |  | [optional] 
**SourceHistory** | Pointer to **[]string** |  | [optional] 

## Methods

### NewV1ResultInfoboxProps

`func NewV1ResultInfoboxProps() *V1ResultInfoboxProps`

NewV1ResultInfoboxProps instantiates a new V1ResultInfoboxProps object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1ResultInfoboxPropsWithDefaults

`func NewV1ResultInfoboxPropsWithDefaults() *V1ResultInfoboxProps`

NewV1ResultInfoboxPropsWithDefaults instantiates a new V1ResultInfoboxProps object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInfobox

`func (o *V1ResultInfoboxProps) GetInfobox() []V1ResultInfoboxPropsInfoboxInner`

GetInfobox returns the Infobox field if non-nil, zero value otherwise.

### GetInfoboxOk

`func (o *V1ResultInfoboxProps) GetInfoboxOk() (*[]V1ResultInfoboxPropsInfoboxInner, bool)`

GetInfoboxOk returns a tuple with the Infobox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfobox

`func (o *V1ResultInfoboxProps) SetInfobox(v []V1ResultInfoboxPropsInfoboxInner)`

SetInfobox sets Infobox field to given value.

### HasInfobox

`func (o *V1ResultInfoboxProps) HasInfobox() bool`

HasInfobox returns a boolean if a field has been set.

### GetWikipediaSubtext

`func (o *V1ResultInfoboxProps) GetWikipediaSubtext() string`

GetWikipediaSubtext returns the WikipediaSubtext field if non-nil, zero value otherwise.

### GetWikipediaSubtextOk

`func (o *V1ResultInfoboxProps) GetWikipediaSubtextOk() (*string, bool)`

GetWikipediaSubtextOk returns a tuple with the WikipediaSubtext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWikipediaSubtext

`func (o *V1ResultInfoboxProps) SetWikipediaSubtext(v string)`

SetWikipediaSubtext sets WikipediaSubtext field to given value.

### HasWikipediaSubtext

`func (o *V1ResultInfoboxProps) HasWikipediaSubtext() bool`

HasWikipediaSubtext returns a boolean if a field has been set.

### GetWikipediaPageId

`func (o *V1ResultInfoboxProps) GetWikipediaPageId() int32`

GetWikipediaPageId returns the WikipediaPageId field if non-nil, zero value otherwise.

### GetWikipediaPageIdOk

`func (o *V1ResultInfoboxProps) GetWikipediaPageIdOk() (*int32, bool)`

GetWikipediaPageIdOk returns a tuple with the WikipediaPageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWikipediaPageId

`func (o *V1ResultInfoboxProps) SetWikipediaPageId(v int32)`

SetWikipediaPageId sets WikipediaPageId field to given value.

### HasWikipediaPageId

`func (o *V1ResultInfoboxProps) HasWikipediaPageId() bool`

HasWikipediaPageId returns a boolean if a field has been set.

### GetLanguage

`func (o *V1ResultInfoboxProps) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *V1ResultInfoboxProps) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *V1ResultInfoboxProps) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *V1ResultInfoboxProps) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetLanguageProbability

`func (o *V1ResultInfoboxProps) GetLanguageProbability() float32`

GetLanguageProbability returns the LanguageProbability field if non-nil, zero value otherwise.

### GetLanguageProbabilityOk

`func (o *V1ResultInfoboxProps) GetLanguageProbabilityOk() (*float32, bool)`

GetLanguageProbabilityOk returns a tuple with the LanguageProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageProbability

`func (o *V1ResultInfoboxProps) SetLanguageProbability(v float32)`

SetLanguageProbability sets LanguageProbability field to given value.

### HasLanguageProbability

`func (o *V1ResultInfoboxProps) HasLanguageProbability() bool`

HasLanguageProbability returns a boolean if a field has been set.

### GetSortNormalizeUrl

`func (o *V1ResultInfoboxProps) GetSortNormalizeUrl() string`

GetSortNormalizeUrl returns the SortNormalizeUrl field if non-nil, zero value otherwise.

### GetSortNormalizeUrlOk

`func (o *V1ResultInfoboxProps) GetSortNormalizeUrlOk() (*string, bool)`

GetSortNormalizeUrlOk returns a tuple with the SortNormalizeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortNormalizeUrl

`func (o *V1ResultInfoboxProps) SetSortNormalizeUrl(v string)`

SetSortNormalizeUrl sets SortNormalizeUrl field to given value.

### HasSortNormalizeUrl

`func (o *V1ResultInfoboxProps) HasSortNormalizeUrl() bool`

HasSortNormalizeUrl returns a boolean if a field has been set.

### GetSortGroupId

`func (o *V1ResultInfoboxProps) GetSortGroupId() string`

GetSortGroupId returns the SortGroupId field if non-nil, zero value otherwise.

### GetSortGroupIdOk

`func (o *V1ResultInfoboxProps) GetSortGroupIdOk() (*string, bool)`

GetSortGroupIdOk returns a tuple with the SortGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortGroupId

`func (o *V1ResultInfoboxProps) SetSortGroupId(v string)`

SetSortGroupId sets SortGroupId field to given value.

### HasSortGroupId

`func (o *V1ResultInfoboxProps) HasSortGroupId() bool`

HasSortGroupId returns a boolean if a field has been set.

### GetSourceHistory

`func (o *V1ResultInfoboxProps) GetSourceHistory() []string`

GetSourceHistory returns the SourceHistory field if non-nil, zero value otherwise.

### GetSourceHistoryOk

`func (o *V1ResultInfoboxProps) GetSourceHistoryOk() (*[]string, bool)`

GetSourceHistoryOk returns a tuple with the SourceHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceHistory

`func (o *V1ResultInfoboxProps) SetSourceHistory(v []string)`

SetSourceHistory sets SourceHistory field to given value.

### HasSourceHistory

`func (o *V1ResultInfoboxProps) HasSourceHistory() bool`

HasSourceHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


