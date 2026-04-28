# DatabaseBackupDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filename** | **string** | Backup filename | 
**Filesize** | **float32** | Backup file size | 
**Timezone** | **string** | Backup timezone | 

## Methods

### NewDatabaseBackupDto

`func NewDatabaseBackupDto(filename string, filesize float32, timezone string, ) *DatabaseBackupDto`

NewDatabaseBackupDto instantiates a new DatabaseBackupDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatabaseBackupDtoWithDefaults

`func NewDatabaseBackupDtoWithDefaults() *DatabaseBackupDto`

NewDatabaseBackupDtoWithDefaults instantiates a new DatabaseBackupDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilename

`func (o *DatabaseBackupDto) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *DatabaseBackupDto) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *DatabaseBackupDto) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetFilesize

`func (o *DatabaseBackupDto) GetFilesize() float32`

GetFilesize returns the Filesize field if non-nil, zero value otherwise.

### GetFilesizeOk

`func (o *DatabaseBackupDto) GetFilesizeOk() (*float32, bool)`

GetFilesizeOk returns a tuple with the Filesize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesize

`func (o *DatabaseBackupDto) SetFilesize(v float32)`

SetFilesize sets Filesize field to given value.


### GetTimezone

`func (o *DatabaseBackupDto) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *DatabaseBackupDto) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *DatabaseBackupDto) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


