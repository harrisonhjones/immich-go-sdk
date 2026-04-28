# SystemConfigBackupsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Database** | [**DatabaseBackupConfig**](DatabaseBackupConfig.md) |  | 

## Methods

### NewSystemConfigBackupsDto

`func NewSystemConfigBackupsDto(database DatabaseBackupConfig, ) *SystemConfigBackupsDto`

NewSystemConfigBackupsDto instantiates a new SystemConfigBackupsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigBackupsDtoWithDefaults

`func NewSystemConfigBackupsDtoWithDefaults() *SystemConfigBackupsDto`

NewSystemConfigBackupsDtoWithDefaults instantiates a new SystemConfigBackupsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatabase

`func (o *SystemConfigBackupsDto) GetDatabase() DatabaseBackupConfig`

GetDatabase returns the Database field if non-nil, zero value otherwise.

### GetDatabaseOk

`func (o *SystemConfigBackupsDto) GetDatabaseOk() (*DatabaseBackupConfig, bool)`

GetDatabaseOk returns a tuple with the Database field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabase

`func (o *SystemConfigBackupsDto) SetDatabase(v DatabaseBackupConfig)`

SetDatabase sets Database field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


