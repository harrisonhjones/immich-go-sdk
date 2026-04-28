# DatabaseBackupListResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backups** | [**[]DatabaseBackupDto**](DatabaseBackupDto.md) | List of backups | 

## Methods

### NewDatabaseBackupListResponseDto

`func NewDatabaseBackupListResponseDto(backups []DatabaseBackupDto, ) *DatabaseBackupListResponseDto`

NewDatabaseBackupListResponseDto instantiates a new DatabaseBackupListResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatabaseBackupListResponseDtoWithDefaults

`func NewDatabaseBackupListResponseDtoWithDefaults() *DatabaseBackupListResponseDto`

NewDatabaseBackupListResponseDtoWithDefaults instantiates a new DatabaseBackupListResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackups

`func (o *DatabaseBackupListResponseDto) GetBackups() []DatabaseBackupDto`

GetBackups returns the Backups field if non-nil, zero value otherwise.

### GetBackupsOk

`func (o *DatabaseBackupListResponseDto) GetBackupsOk() (*[]DatabaseBackupDto, bool)`

GetBackupsOk returns a tuple with the Backups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackups

`func (o *DatabaseBackupListResponseDto) SetBackups(v []DatabaseBackupDto)`

SetBackups sets Backups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


