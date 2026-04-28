# DatabaseBackupDeleteDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backups** | **[]string** | Backup filenames to delete | 

## Methods

### NewDatabaseBackupDeleteDto

`func NewDatabaseBackupDeleteDto(backups []string, ) *DatabaseBackupDeleteDto`

NewDatabaseBackupDeleteDto instantiates a new DatabaseBackupDeleteDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatabaseBackupDeleteDtoWithDefaults

`func NewDatabaseBackupDeleteDtoWithDefaults() *DatabaseBackupDeleteDto`

NewDatabaseBackupDeleteDtoWithDefaults instantiates a new DatabaseBackupDeleteDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackups

`func (o *DatabaseBackupDeleteDto) GetBackups() []string`

GetBackups returns the Backups field if non-nil, zero value otherwise.

### GetBackupsOk

`func (o *DatabaseBackupDeleteDto) GetBackupsOk() (*[]string, bool)`

GetBackupsOk returns a tuple with the Backups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackups

`func (o *DatabaseBackupDeleteDto) SetBackups(v []string)`

SetBackups sets Backups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


