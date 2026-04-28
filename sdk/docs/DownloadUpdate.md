# DownloadUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchiveSize** | Pointer to **int32** | Maximum archive size in bytes | [optional] 
**IncludeEmbeddedVideos** | Pointer to **bool** | Whether to include embedded videos in downloads | [optional] 

## Methods

### NewDownloadUpdate

`func NewDownloadUpdate() *DownloadUpdate`

NewDownloadUpdate instantiates a new DownloadUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadUpdateWithDefaults

`func NewDownloadUpdateWithDefaults() *DownloadUpdate`

NewDownloadUpdateWithDefaults instantiates a new DownloadUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchiveSize

`func (o *DownloadUpdate) GetArchiveSize() int32`

GetArchiveSize returns the ArchiveSize field if non-nil, zero value otherwise.

### GetArchiveSizeOk

`func (o *DownloadUpdate) GetArchiveSizeOk() (*int32, bool)`

GetArchiveSizeOk returns a tuple with the ArchiveSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveSize

`func (o *DownloadUpdate) SetArchiveSize(v int32)`

SetArchiveSize sets ArchiveSize field to given value.

### HasArchiveSize

`func (o *DownloadUpdate) HasArchiveSize() bool`

HasArchiveSize returns a boolean if a field has been set.

### GetIncludeEmbeddedVideos

`func (o *DownloadUpdate) GetIncludeEmbeddedVideos() bool`

GetIncludeEmbeddedVideos returns the IncludeEmbeddedVideos field if non-nil, zero value otherwise.

### GetIncludeEmbeddedVideosOk

`func (o *DownloadUpdate) GetIncludeEmbeddedVideosOk() (*bool, bool)`

GetIncludeEmbeddedVideosOk returns a tuple with the IncludeEmbeddedVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeEmbeddedVideos

`func (o *DownloadUpdate) SetIncludeEmbeddedVideos(v bool)`

SetIncludeEmbeddedVideos sets IncludeEmbeddedVideos field to given value.

### HasIncludeEmbeddedVideos

`func (o *DownloadUpdate) HasIncludeEmbeddedVideos() bool`

HasIncludeEmbeddedVideos returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


