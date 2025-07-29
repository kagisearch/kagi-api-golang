# SearchRequestLens

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SitesIncluded** | Pointer to **[]string** | A list of domains to restrict the search to. | [optional] 
**SitesExcluded** | Pointer to **[]string** | A list of domains to restrict the search to. | [optional] 
**KeywordsIncluded** | Pointer to **[]string** | A list of keywords to filter results on, such that every result *must* contain these terms. | [optional] 
**KeywordsExcluded** | Pointer to **[]string** | A list of keywords to filter results on, such that any result containing these terms is removed. | [optional] 
**FileType** | Pointer to **string** | A specific file type to search for. (e.g., &#x60;pdf&#x60;) | [optional] 
**TimeAfter** | Pointer to **string** | Filters for web pages that have been updated or published *after* the given date (&#x60;YYYY-MM-DD&#x60;). | [optional] 
**TimeBefore** | Pointer to **string** | Filters for web pages that have been updated or published *before* the given date (&#x60;YYYY-MM-DD&#x60;). | [optional] 
**TimeRelative** | Pointer to **string** | Filters for web pages that have been updated or published in the given interval, relative to today&#39;s date. | [optional] 
**SearchRegion** | Pointer to **string** | Requests results localized to a specific region. Can be any valid [ISO-3166-1 Alpha-2 country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements), or the special value &#x60;no_region&#x60;, that will try to get the most general results possible. | [optional] 

## Methods

### NewSearchRequestLens

`func NewSearchRequestLens() *SearchRequestLens`

NewSearchRequestLens instantiates a new SearchRequestLens object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestLensWithDefaults

`func NewSearchRequestLensWithDefaults() *SearchRequestLens`

NewSearchRequestLensWithDefaults instantiates a new SearchRequestLens object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSitesIncluded

`func (o *SearchRequestLens) GetSitesIncluded() []string`

GetSitesIncluded returns the SitesIncluded field if non-nil, zero value otherwise.

### GetSitesIncludedOk

`func (o *SearchRequestLens) GetSitesIncludedOk() (*[]string, bool)`

GetSitesIncludedOk returns a tuple with the SitesIncluded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSitesIncluded

`func (o *SearchRequestLens) SetSitesIncluded(v []string)`

SetSitesIncluded sets SitesIncluded field to given value.

### HasSitesIncluded

`func (o *SearchRequestLens) HasSitesIncluded() bool`

HasSitesIncluded returns a boolean if a field has been set.

### GetSitesExcluded

`func (o *SearchRequestLens) GetSitesExcluded() []string`

GetSitesExcluded returns the SitesExcluded field if non-nil, zero value otherwise.

### GetSitesExcludedOk

`func (o *SearchRequestLens) GetSitesExcludedOk() (*[]string, bool)`

GetSitesExcludedOk returns a tuple with the SitesExcluded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSitesExcluded

`func (o *SearchRequestLens) SetSitesExcluded(v []string)`

SetSitesExcluded sets SitesExcluded field to given value.

### HasSitesExcluded

`func (o *SearchRequestLens) HasSitesExcluded() bool`

HasSitesExcluded returns a boolean if a field has been set.

### GetKeywordsIncluded

`func (o *SearchRequestLens) GetKeywordsIncluded() []string`

GetKeywordsIncluded returns the KeywordsIncluded field if non-nil, zero value otherwise.

### GetKeywordsIncludedOk

`func (o *SearchRequestLens) GetKeywordsIncludedOk() (*[]string, bool)`

GetKeywordsIncludedOk returns a tuple with the KeywordsIncluded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywordsIncluded

`func (o *SearchRequestLens) SetKeywordsIncluded(v []string)`

SetKeywordsIncluded sets KeywordsIncluded field to given value.

### HasKeywordsIncluded

`func (o *SearchRequestLens) HasKeywordsIncluded() bool`

HasKeywordsIncluded returns a boolean if a field has been set.

### GetKeywordsExcluded

`func (o *SearchRequestLens) GetKeywordsExcluded() []string`

GetKeywordsExcluded returns the KeywordsExcluded field if non-nil, zero value otherwise.

### GetKeywordsExcludedOk

`func (o *SearchRequestLens) GetKeywordsExcludedOk() (*[]string, bool)`

GetKeywordsExcludedOk returns a tuple with the KeywordsExcluded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywordsExcluded

`func (o *SearchRequestLens) SetKeywordsExcluded(v []string)`

SetKeywordsExcluded sets KeywordsExcluded field to given value.

### HasKeywordsExcluded

`func (o *SearchRequestLens) HasKeywordsExcluded() bool`

HasKeywordsExcluded returns a boolean if a field has been set.

### GetFileType

`func (o *SearchRequestLens) GetFileType() string`

GetFileType returns the FileType field if non-nil, zero value otherwise.

### GetFileTypeOk

`func (o *SearchRequestLens) GetFileTypeOk() (*string, bool)`

GetFileTypeOk returns a tuple with the FileType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileType

`func (o *SearchRequestLens) SetFileType(v string)`

SetFileType sets FileType field to given value.

### HasFileType

`func (o *SearchRequestLens) HasFileType() bool`

HasFileType returns a boolean if a field has been set.

### GetTimeAfter

`func (o *SearchRequestLens) GetTimeAfter() string`

GetTimeAfter returns the TimeAfter field if non-nil, zero value otherwise.

### GetTimeAfterOk

`func (o *SearchRequestLens) GetTimeAfterOk() (*string, bool)`

GetTimeAfterOk returns a tuple with the TimeAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeAfter

`func (o *SearchRequestLens) SetTimeAfter(v string)`

SetTimeAfter sets TimeAfter field to given value.

### HasTimeAfter

`func (o *SearchRequestLens) HasTimeAfter() bool`

HasTimeAfter returns a boolean if a field has been set.

### GetTimeBefore

`func (o *SearchRequestLens) GetTimeBefore() string`

GetTimeBefore returns the TimeBefore field if non-nil, zero value otherwise.

### GetTimeBeforeOk

`func (o *SearchRequestLens) GetTimeBeforeOk() (*string, bool)`

GetTimeBeforeOk returns a tuple with the TimeBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeBefore

`func (o *SearchRequestLens) SetTimeBefore(v string)`

SetTimeBefore sets TimeBefore field to given value.

### HasTimeBefore

`func (o *SearchRequestLens) HasTimeBefore() bool`

HasTimeBefore returns a boolean if a field has been set.

### GetTimeRelative

`func (o *SearchRequestLens) GetTimeRelative() string`

GetTimeRelative returns the TimeRelative field if non-nil, zero value otherwise.

### GetTimeRelativeOk

`func (o *SearchRequestLens) GetTimeRelativeOk() (*string, bool)`

GetTimeRelativeOk returns a tuple with the TimeRelative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeRelative

`func (o *SearchRequestLens) SetTimeRelative(v string)`

SetTimeRelative sets TimeRelative field to given value.

### HasTimeRelative

`func (o *SearchRequestLens) HasTimeRelative() bool`

HasTimeRelative returns a boolean if a field has been set.

### GetSearchRegion

`func (o *SearchRequestLens) GetSearchRegion() string`

GetSearchRegion returns the SearchRegion field if non-nil, zero value otherwise.

### GetSearchRegionOk

`func (o *SearchRequestLens) GetSearchRegionOk() (*string, bool)`

GetSearchRegionOk returns a tuple with the SearchRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchRegion

`func (o *SearchRequestLens) SetSearchRegion(v string)`

SetSearchRegion sets SearchRegion field to given value.

### HasSearchRegion

`func (o *SearchRequestLens) HasSearchRegion() bool`

HasSearchRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


