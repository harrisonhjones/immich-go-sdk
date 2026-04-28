# DownloadArchiveDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetIds** | **[]string** | Asset IDs | 
**Edited** | Pointer to **bool** | Download edited asset if available | [optional] 

## Methods

### NewDownloadArchiveDto

`func NewDownloadArchiveDto(assetIds []string, ) *DownloadArchiveDto`

NewDownloadArchiveDto instantiates a new DownloadArchiveDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDownloadArchiveDtoWithDefaults

`func NewDownloadArchiveDtoWithDefaults() *DownloadArchiveDto`

NewDownloadArchiveDtoWithDefaults instantiates a new DownloadArchiveDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetIds

`func (o *DownloadArchiveDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *DownloadArchiveDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *DownloadArchiveDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.


### GetEdited

`func (o *DownloadArchiveDto) GetEdited() bool`

GetEdited returns the Edited field if non-nil, zero value otherwise.

### GetEditedOk

`func (o *DownloadArchiveDto) GetEditedOk() (*bool, bool)`

GetEditedOk returns a tuple with the Edited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdited

`func (o *DownloadArchiveDto) SetEdited(v bool)`

SetEdited sets Edited field to given value.

### HasEdited

`func (o *DownloadArchiveDto) HasEdited() bool`

HasEdited returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


