# MaintenanceDetectInstallStorageFolderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Files** | **float32** | Number of files in the folder | 
**Folder** | [**StorageFolder**](StorageFolder.md) |  | 
**Readable** | **bool** | Whether the folder is readable | 
**Writable** | **bool** | Whether the folder is writable | 

## Methods

### NewMaintenanceDetectInstallStorageFolderDto

`func NewMaintenanceDetectInstallStorageFolderDto(files float32, folder StorageFolder, readable bool, writable bool, ) *MaintenanceDetectInstallStorageFolderDto`

NewMaintenanceDetectInstallStorageFolderDto instantiates a new MaintenanceDetectInstallStorageFolderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMaintenanceDetectInstallStorageFolderDtoWithDefaults

`func NewMaintenanceDetectInstallStorageFolderDtoWithDefaults() *MaintenanceDetectInstallStorageFolderDto`

NewMaintenanceDetectInstallStorageFolderDtoWithDefaults instantiates a new MaintenanceDetectInstallStorageFolderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFiles

`func (o *MaintenanceDetectInstallStorageFolderDto) GetFiles() float32`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *MaintenanceDetectInstallStorageFolderDto) GetFilesOk() (*float32, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *MaintenanceDetectInstallStorageFolderDto) SetFiles(v float32)`

SetFiles sets Files field to given value.


### GetFolder

`func (o *MaintenanceDetectInstallStorageFolderDto) GetFolder() StorageFolder`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *MaintenanceDetectInstallStorageFolderDto) GetFolderOk() (*StorageFolder, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *MaintenanceDetectInstallStorageFolderDto) SetFolder(v StorageFolder)`

SetFolder sets Folder field to given value.


### GetReadable

`func (o *MaintenanceDetectInstallStorageFolderDto) GetReadable() bool`

GetReadable returns the Readable field if non-nil, zero value otherwise.

### GetReadableOk

`func (o *MaintenanceDetectInstallStorageFolderDto) GetReadableOk() (*bool, bool)`

GetReadableOk returns a tuple with the Readable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadable

`func (o *MaintenanceDetectInstallStorageFolderDto) SetReadable(v bool)`

SetReadable sets Readable field to given value.


### GetWritable

`func (o *MaintenanceDetectInstallStorageFolderDto) GetWritable() bool`

GetWritable returns the Writable field if non-nil, zero value otherwise.

### GetWritableOk

`func (o *MaintenanceDetectInstallStorageFolderDto) GetWritableOk() (*bool, bool)`

GetWritableOk returns a tuple with the Writable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWritable

`func (o *MaintenanceDetectInstallStorageFolderDto) SetWritable(v bool)`

SetWritable sets Writable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


