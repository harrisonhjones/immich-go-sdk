# SearchResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Albums** | [**SearchAlbumResponseDto**](SearchAlbumResponseDto.md) |  | 
**Assets** | [**SearchAssetResponseDto**](SearchAssetResponseDto.md) |  | 

## Methods

### NewSearchResponseDto

`func NewSearchResponseDto(albums SearchAlbumResponseDto, assets SearchAssetResponseDto, ) *SearchResponseDto`

NewSearchResponseDto instantiates a new SearchResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchResponseDtoWithDefaults

`func NewSearchResponseDtoWithDefaults() *SearchResponseDto`

NewSearchResponseDtoWithDefaults instantiates a new SearchResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbums

`func (o *SearchResponseDto) GetAlbums() SearchAlbumResponseDto`

GetAlbums returns the Albums field if non-nil, zero value otherwise.

### GetAlbumsOk

`func (o *SearchResponseDto) GetAlbumsOk() (*SearchAlbumResponseDto, bool)`

GetAlbumsOk returns a tuple with the Albums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbums

`func (o *SearchResponseDto) SetAlbums(v SearchAlbumResponseDto)`

SetAlbums sets Albums field to given value.


### GetAssets

`func (o *SearchResponseDto) GetAssets() SearchAssetResponseDto`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *SearchResponseDto) GetAssetsOk() (*SearchAssetResponseDto, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *SearchResponseDto) SetAssets(v SearchAssetResponseDto)`

SetAssets sets Assets field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


