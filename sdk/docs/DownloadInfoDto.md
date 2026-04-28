# DownloadInfoDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumId** | Pointer to **string** | Album ID to download | [optional] 
**ArchiveSize** | Pointer to **int32** | Archive size limit in bytes | [optional] 
**AssetIds** | Pointer to **[]string** | Asset IDs to download | [optional] 
**UserId** | Pointer to **string** | User ID to download assets from | [optional] 

## Methods

### NewDownloadInfoDto

`func NewDownloadInfoDto() *DownloadInfoDto`

NewDownloadInfoDto instantiates a new DownloadInfoDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadInfoDtoWithDefaults

`func NewDownloadInfoDtoWithDefaults() *DownloadInfoDto`

NewDownloadInfoDtoWithDefaults instantiates a new DownloadInfoDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumId

`func (o *DownloadInfoDto) GetAlbumId() string`

GetAlbumId returns the AlbumId field if non-nil, zero value otherwise.

### GetAlbumIdOk

`func (o *DownloadInfoDto) GetAlbumIdOk() (*string, bool)`

GetAlbumIdOk returns a tuple with the AlbumId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumId

`func (o *DownloadInfoDto) SetAlbumId(v string)`

SetAlbumId sets AlbumId field to given value.

### HasAlbumId

`func (o *DownloadInfoDto) HasAlbumId() bool`

HasAlbumId returns a boolean if a field has been set.

### GetArchiveSize

`func (o *DownloadInfoDto) GetArchiveSize() int32`

GetArchiveSize returns the ArchiveSize field if non-nil, zero value otherwise.

### GetArchiveSizeOk

`func (o *DownloadInfoDto) GetArchiveSizeOk() (*int32, bool)`

GetArchiveSizeOk returns a tuple with the ArchiveSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveSize

`func (o *DownloadInfoDto) SetArchiveSize(v int32)`

SetArchiveSize sets ArchiveSize field to given value.

### HasArchiveSize

`func (o *DownloadInfoDto) HasArchiveSize() bool`

HasArchiveSize returns a boolean if a field has been set.

### GetAssetIds

`func (o *DownloadInfoDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *DownloadInfoDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *DownloadInfoDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.

### HasAssetIds

`func (o *DownloadInfoDto) HasAssetIds() bool`

HasAssetIds returns a boolean if a field has been set.

### GetUserId

`func (o *DownloadInfoDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *DownloadInfoDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *DownloadInfoDto) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *DownloadInfoDto) HasUserId() bool`

HasUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


