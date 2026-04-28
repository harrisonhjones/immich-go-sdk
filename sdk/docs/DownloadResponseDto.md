# DownloadResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archives** | [**[]DownloadArchiveInfo**](DownloadArchiveInfo.md) | Archive information | 
**TotalSize** | **int32** | Total size in bytes | 

## Methods

### NewDownloadResponseDto

`func NewDownloadResponseDto(archives []DownloadArchiveInfo, totalSize int32, ) *DownloadResponseDto`

NewDownloadResponseDto instantiates a new DownloadResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadResponseDtoWithDefaults

`func NewDownloadResponseDtoWithDefaults() *DownloadResponseDto`

NewDownloadResponseDtoWithDefaults instantiates a new DownloadResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchives

`func (o *DownloadResponseDto) GetArchives() []DownloadArchiveInfo`

GetArchives returns the Archives field if non-nil, zero value otherwise.

### GetArchivesOk

`func (o *DownloadResponseDto) GetArchivesOk() (*[]DownloadArchiveInfo, bool)`

GetArchivesOk returns a tuple with the Archives field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchives

`func (o *DownloadResponseDto) SetArchives(v []DownloadArchiveInfo)`

SetArchives sets Archives field to given value.


### GetTotalSize

`func (o *DownloadResponseDto) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *DownloadResponseDto) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *DownloadResponseDto) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


