# SearchAlbumResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | Number of albums in this page | 
**Facets** | [**[]SearchFacetResponseDto**](SearchFacetResponseDto.md) |  | 
**Items** | [**[]AlbumResponseDto**](AlbumResponseDto.md) |  | 
**Total** | **int32** | Total number of matching albums | 

## Methods

### NewSearchAlbumResponseDto

`func NewSearchAlbumResponseDto(count int32, facets []SearchFacetResponseDto, items []AlbumResponseDto, total int32, ) *SearchAlbumResponseDto`

NewSearchAlbumResponseDto instantiates a new SearchAlbumResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchAlbumResponseDtoWithDefaults

`func NewSearchAlbumResponseDtoWithDefaults() *SearchAlbumResponseDto`

NewSearchAlbumResponseDtoWithDefaults instantiates a new SearchAlbumResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *SearchAlbumResponseDto) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SearchAlbumResponseDto) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SearchAlbumResponseDto) SetCount(v int32)`

SetCount sets Count field to given value.


### GetFacets

`func (o *SearchAlbumResponseDto) GetFacets() []SearchFacetResponseDto`

GetFacets returns the Facets field if non-nil, zero value otherwise.

### GetFacetsOk

`func (o *SearchAlbumResponseDto) GetFacetsOk() (*[]SearchFacetResponseDto, bool)`

GetFacetsOk returns a tuple with the Facets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacets

`func (o *SearchAlbumResponseDto) SetFacets(v []SearchFacetResponseDto)`

SetFacets sets Facets field to given value.


### GetItems

`func (o *SearchAlbumResponseDto) GetItems() []AlbumResponseDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SearchAlbumResponseDto) GetItemsOk() (*[]AlbumResponseDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SearchAlbumResponseDto) SetItems(v []AlbumResponseDto)`

SetItems sets Items field to given value.


### GetTotal

`func (o *SearchAlbumResponseDto) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SearchAlbumResponseDto) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SearchAlbumResponseDto) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


