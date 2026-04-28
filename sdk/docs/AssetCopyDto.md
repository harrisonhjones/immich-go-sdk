# AssetCopyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Albums** | Pointer to **bool** | Copy album associations | [optional] [default to true]
**Favorite** | Pointer to **bool** | Copy favorite status | [optional] [default to true]
**SharedLinks** | Pointer to **bool** | Copy shared links | [optional] [default to true]
**Sidecar** | Pointer to **bool** | Copy sidecar file | [optional] [default to true]
**SourceId** | **string** | Source asset ID | 
**Stack** | Pointer to **bool** | Copy stack association | [optional] [default to true]
**TargetId** | **string** | Target asset ID | 

## Methods

### NewAssetCopyDto

`func NewAssetCopyDto(sourceId string, targetId string, ) *AssetCopyDto`

NewAssetCopyDto instantiates a new AssetCopyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetCopyDtoWithDefaults

`func NewAssetCopyDtoWithDefaults() *AssetCopyDto`

NewAssetCopyDtoWithDefaults instantiates a new AssetCopyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbums

`func (o *AssetCopyDto) GetAlbums() bool`

GetAlbums returns the Albums field if non-nil, zero value otherwise.

### GetAlbumsOk

`func (o *AssetCopyDto) GetAlbumsOk() (*bool, bool)`

GetAlbumsOk returns a tuple with the Albums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbums

`func (o *AssetCopyDto) SetAlbums(v bool)`

SetAlbums sets Albums field to given value.

### HasAlbums

`func (o *AssetCopyDto) HasAlbums() bool`

HasAlbums returns a boolean if a field has been set.

### GetFavorite

`func (o *AssetCopyDto) GetFavorite() bool`

GetFavorite returns the Favorite field if non-nil, zero value otherwise.

### GetFavoriteOk

`func (o *AssetCopyDto) GetFavoriteOk() (*bool, bool)`

GetFavoriteOk returns a tuple with the Favorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFavorite

`func (o *AssetCopyDto) SetFavorite(v bool)`

SetFavorite sets Favorite field to given value.

### HasFavorite

`func (o *AssetCopyDto) HasFavorite() bool`

HasFavorite returns a boolean if a field has been set.

### GetSharedLinks

`func (o *AssetCopyDto) GetSharedLinks() bool`

GetSharedLinks returns the SharedLinks field if non-nil, zero value otherwise.

### GetSharedLinksOk

`func (o *AssetCopyDto) GetSharedLinksOk() (*bool, bool)`

GetSharedLinksOk returns a tuple with the SharedLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedLinks

`func (o *AssetCopyDto) SetSharedLinks(v bool)`

SetSharedLinks sets SharedLinks field to given value.

### HasSharedLinks

`func (o *AssetCopyDto) HasSharedLinks() bool`

HasSharedLinks returns a boolean if a field has been set.

### GetSidecar

`func (o *AssetCopyDto) GetSidecar() bool`

GetSidecar returns the Sidecar field if non-nil, zero value otherwise.

### GetSidecarOk

`func (o *AssetCopyDto) GetSidecarOk() (*bool, bool)`

GetSidecarOk returns a tuple with the Sidecar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSidecar

`func (o *AssetCopyDto) SetSidecar(v bool)`

SetSidecar sets Sidecar field to given value.

### HasSidecar

`func (o *AssetCopyDto) HasSidecar() bool`

HasSidecar returns a boolean if a field has been set.

### GetSourceId

`func (o *AssetCopyDto) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *AssetCopyDto) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *AssetCopyDto) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetStack

`func (o *AssetCopyDto) GetStack() bool`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *AssetCopyDto) GetStackOk() (*bool, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *AssetCopyDto) SetStack(v bool)`

SetStack sets Stack field to given value.

### HasStack

`func (o *AssetCopyDto) HasStack() bool`

HasStack returns a boolean if a field has been set.

### GetTargetId

`func (o *AssetCopyDto) GetTargetId() string`

GetTargetId returns the TargetId field if non-nil, zero value otherwise.

### GetTargetIdOk

`func (o *AssetCopyDto) GetTargetIdOk() (*string, bool)`

GetTargetIdOk returns a tuple with the TargetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetId

`func (o *AssetCopyDto) SetTargetId(v string)`

SetTargetId sets TargetId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


