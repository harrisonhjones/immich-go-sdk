# SearchAssetResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | Number of assets in this page | 
**Facets** | [**[]SearchFacetResponseDto**](SearchFacetResponseDto.md) |  | 
**Items** | [**[]AssetResponseDto**](AssetResponseDto.md) |  | 
**NextPage** | **NullableString** | Next page token | 
**Total** | **int32** | Total number of matching assets | 

## Methods

### NewSearchAssetResponseDto

`func NewSearchAssetResponseDto(count int32, facets []SearchFacetResponseDto, items []AssetResponseDto, nextPage NullableString, total int32, ) *SearchAssetResponseDto`

NewSearchAssetResponseDto instantiates a new SearchAssetResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchAssetResponseDtoWithDefaults

`func NewSearchAssetResponseDtoWithDefaults() *SearchAssetResponseDto`

NewSearchAssetResponseDtoWithDefaults instantiates a new SearchAssetResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *SearchAssetResponseDto) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SearchAssetResponseDto) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SearchAssetResponseDto) SetCount(v int32)`

SetCount sets Count field to given value.


### GetFacets

`func (o *SearchAssetResponseDto) GetFacets() []SearchFacetResponseDto`

GetFacets returns the Facets field if non-nil, zero value otherwise.

### GetFacetsOk

`func (o *SearchAssetResponseDto) GetFacetsOk() (*[]SearchFacetResponseDto, bool)`

GetFacetsOk returns a tuple with the Facets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacets

`func (o *SearchAssetResponseDto) SetFacets(v []SearchFacetResponseDto)`

SetFacets sets Facets field to given value.


### GetItems

`func (o *SearchAssetResponseDto) GetItems() []AssetResponseDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SearchAssetResponseDto) GetItemsOk() (*[]AssetResponseDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SearchAssetResponseDto) SetItems(v []AssetResponseDto)`

SetItems sets Items field to given value.


### GetNextPage

`func (o *SearchAssetResponseDto) GetNextPage() string`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *SearchAssetResponseDto) GetNextPageOk() (*string, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *SearchAssetResponseDto) SetNextPage(v string)`

SetNextPage sets NextPage field to given value.


### SetNextPageNil

`func (o *SearchAssetResponseDto) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *SearchAssetResponseDto) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetTotal

`func (o *SearchAssetResponseDto) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchAssetResponseDto) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchAssetResponseDto) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


