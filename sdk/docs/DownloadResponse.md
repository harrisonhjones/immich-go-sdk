# DownloadResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchiveSize** | **int32** | Maximum archive size in bytes | 
**IncludeEmbeddedVideos** | **bool** | Whether to include embedded videos in downloads | 

## Methods

### NewDownloadResponse

`func NewDownloadResponse(archiveSize int32, includeEmbeddedVideos bool, ) *DownloadResponse`

NewDownloadResponse instantiates a new DownloadResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadResponseWithDefaults

`func NewDownloadResponseWithDefaults() *DownloadResponse`

NewDownloadResponseWithDefaults instantiates a new DownloadResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchiveSize

`func (o *DownloadResponse) GetArchiveSize() int32`

GetArchiveSize returns the ArchiveSize field if non-nil, zero value otherwise.

### GetArchiveSizeOk

`func (o *DownloadResponse) GetArchiveSizeOk() (*int32, bool)`

GetArchiveSizeOk returns a tuple with the ArchiveSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchiveSize

`func (o *DownloadResponse) SetArchiveSize(v int32)`

SetArchiveSize sets ArchiveSize field to given value.


### GetIncludeEmbeddedVideos

`func (o *DownloadResponse) GetIncludeEmbeddedVideos() bool`

GetIncludeEmbeddedVideos returns the IncludeEmbeddedVideos field if non-nil, zero value otherwise.

### GetIncludeEmbeddedVideosOk

`func (o *DownloadResponse) GetIncludeEmbeddedVideosOk() (*bool, bool)`

GetIncludeEmbeddedVideosOk returns a tuple with the IncludeEmbeddedVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeEmbeddedVideos

`func (o *DownloadResponse) SetIncludeEmbeddedVideos(v bool)`

SetIncludeEmbeddedVideos sets IncludeEmbeddedVideos field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


