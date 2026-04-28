# DownloadArchiveInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetIds** | **[]string** | Asset IDs in this archive | 
**Size** | **int32** | Archive size in bytes | 

## Methods

### NewDownloadArchiveInfo

`func NewDownloadArchiveInfo(assetIds []string, size int32, ) *DownloadArchiveInfo`

NewDownloadArchiveInfo instantiates a new DownloadArchiveInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadArchiveInfoWithDefaults

`func NewDownloadArchiveInfoWithDefaults() *DownloadArchiveInfo`

NewDownloadArchiveInfoWithDefaults instantiates a new DownloadArchiveInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetIds

`func (o *DownloadArchiveInfo) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *DownloadArchiveInfo) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *DownloadArchiveInfo) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.


### GetSize

`func (o *DownloadArchiveInfo) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *DownloadArchiveInfo) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *DownloadArchiveInfo) SetSize(v int32)`

SetSize sets Size field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


