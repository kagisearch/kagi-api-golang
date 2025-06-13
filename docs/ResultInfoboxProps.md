# ResultInfoboxProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Infobox** | Pointer to [**[]ResultInfoboxPropsInfoboxInner**](ResultInfoboxPropsInfoboxInner.md) |  | [optional] 
**WikipediaSubtext** | Pointer to **string** |  | [optional] 
**WikipediaPageId** | Pointer to **int32** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**LanguageProbability** | Pointer to **float32** |  | [optional] 
**SortNormalizeUrl** | Pointer to **string** |  | [optional] 
**SortGroupId** | Pointer to **string** |  | [optional] 
**SourceHistory** | Pointer to **[]string** |  | [optional] 

## Methods

### NewResultInfoboxProps

`func NewResultInfoboxProps() *ResultInfoboxProps`

NewResultInfoboxProps instantiates a new ResultInfoboxProps object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultInfoboxPropsWithDefaults

`func NewResultInfoboxPropsWithDefaults() *ResultInfoboxProps`

NewResultInfoboxPropsWithDefaults instantiates a new ResultInfoboxProps object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInfobox

`func (o *ResultInfoboxProps) GetInfobox() []ResultInfoboxPropsInfoboxInner`

GetInfobox returns the Infobox field if non-nil, zero value otherwise.

### GetInfoboxOk

`func (o *ResultInfoboxProps) GetInfoboxOk() (*[]ResultInfoboxPropsInfoboxInner, bool)`

GetInfoboxOk returns a tuple with the Infobox field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfobox

`func (o *ResultInfoboxProps) SetInfobox(v []ResultInfoboxPropsInfoboxInner)`

SetInfobox sets Infobox field to given value.

### HasInfobox

`func (o *ResultInfoboxProps) HasInfobox() bool`

HasInfobox returns a boolean if a field has been set.

### GetWikipediaSubtext

`func (o *ResultInfoboxProps) GetWikipediaSubtext() string`

GetWikipediaSubtext returns the WikipediaSubtext field if non-nil, zero value otherwise.

### GetWikipediaSubtextOk

`func (o *ResultInfoboxProps) GetWikipediaSubtextOk() (*string, bool)`

GetWikipediaSubtextOk returns a tuple with the WikipediaSubtext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWikipediaSubtext

`func (o *ResultInfoboxProps) SetWikipediaSubtext(v string)`

SetWikipediaSubtext sets WikipediaSubtext field to given value.

### HasWikipediaSubtext

`func (o *ResultInfoboxProps) HasWikipediaSubtext() bool`

HasWikipediaSubtext returns a boolean if a field has been set.

### GetWikipediaPageId

`func (o *ResultInfoboxProps) GetWikipediaPageId() int32`

GetWikipediaPageId returns the WikipediaPageId field if non-nil, zero value otherwise.

### GetWikipediaPageIdOk

`func (o *ResultInfoboxProps) GetWikipediaPageIdOk() (*int32, bool)`

GetWikipediaPageIdOk returns a tuple with the WikipediaPageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWikipediaPageId

`func (o *ResultInfoboxProps) SetWikipediaPageId(v int32)`

SetWikipediaPageId sets WikipediaPageId field to given value.

### HasWikipediaPageId

`func (o *ResultInfoboxProps) HasWikipediaPageId() bool`

HasWikipediaPageId returns a boolean if a field has been set.

### GetLanguage

`func (o *ResultInfoboxProps) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ResultInfoboxProps) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ResultInfoboxProps) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *ResultInfoboxProps) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetLanguageProbability

`func (o *ResultInfoboxProps) GetLanguageProbability() float32`

GetLanguageProbability returns the LanguageProbability field if non-nil, zero value otherwise.

### GetLanguageProbabilityOk

`func (o *ResultInfoboxProps) GetLanguageProbabilityOk() (*float32, bool)`

GetLanguageProbabilityOk returns a tuple with the LanguageProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageProbability

`func (o *ResultInfoboxProps) SetLanguageProbability(v float32)`

SetLanguageProbability sets LanguageProbability field to given value.

### HasLanguageProbability

`func (o *ResultInfoboxProps) HasLanguageProbability() bool`

HasLanguageProbability returns a boolean if a field has been set.

### GetSortNormalizeUrl

`func (o *ResultInfoboxProps) GetSortNormalizeUrl() string`

GetSortNormalizeUrl returns the SortNormalizeUrl field if non-nil, zero value otherwise.

### GetSortNormalizeUrlOk

`func (o *ResultInfoboxProps) GetSortNormalizeUrlOk() (*string, bool)`

GetSortNormalizeUrlOk returns a tuple with the SortNormalizeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortNormalizeUrl

`func (o *ResultInfoboxProps) SetSortNormalizeUrl(v string)`

SetSortNormalizeUrl sets SortNormalizeUrl field to given value.

### HasSortNormalizeUrl

`func (o *ResultInfoboxProps) HasSortNormalizeUrl() bool`

HasSortNormalizeUrl returns a boolean if a field has been set.

### GetSortGroupId

`func (o *ResultInfoboxProps) GetSortGroupId() string`

GetSortGroupId returns the SortGroupId field if non-nil, zero value otherwise.

### GetSortGroupIdOk

`func (o *ResultInfoboxProps) GetSortGroupIdOk() (*string, bool)`

GetSortGroupIdOk returns a tuple with the SortGroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortGroupId

`func (o *ResultInfoboxProps) SetSortGroupId(v string)`

SetSortGroupId sets SortGroupId field to given value.

### HasSortGroupId

`func (o *ResultInfoboxProps) HasSortGroupId() bool`

HasSortGroupId returns a boolean if a field has been set.

### GetSourceHistory

`func (o *ResultInfoboxProps) GetSourceHistory() []string`

GetSourceHistory returns the SourceHistory field if non-nil, zero value otherwise.

### GetSourceHistoryOk

`func (o *ResultInfoboxProps) GetSourceHistoryOk() (*[]string, bool)`

GetSourceHistoryOk returns a tuple with the SourceHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceHistory

`func (o *ResultInfoboxProps) SetSourceHistory(v []string)`

SetSourceHistory sets SourceHistory field to given value.

### HasSourceHistory

`func (o *ResultInfoboxProps) HasSourceHistory() bool`

HasSourceHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


