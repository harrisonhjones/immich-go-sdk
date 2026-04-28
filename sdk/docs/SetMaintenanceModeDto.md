# SetMaintenanceModeDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**MaintenanceAction**](MaintenanceAction.md) |  | 
**RestoreBackupFilename** | Pointer to **string** | Restore backup filename | [optional] 

## Methods

### NewSetMaintenanceModeDto

`func NewSetMaintenanceModeDto(action MaintenanceAction, ) *SetMaintenanceModeDto`

NewSetMaintenanceModeDto instantiates a new SetMaintenanceModeDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetMaintenanceModeDtoWithDefaults

`func NewSetMaintenanceModeDtoWithDefaults() *SetMaintenanceModeDto`

NewSetMaintenanceModeDtoWithDefaults instantiates a new SetMaintenanceModeDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *SetMaintenanceModeDto) GetAction() MaintenanceAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *SetMaintenanceModeDto) GetActionOk() (*MaintenanceAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *SetMaintenanceModeDto) SetAction(v MaintenanceAction)`

SetAction sets Action field to given value.


### GetRestoreBackupFilename

`func (o *SetMaintenanceModeDto) GetRestoreBackupFilename() string`

GetRestoreBackupFilename returns the RestoreBackupFilename field if non-nil, zero value otherwise.

### GetRestoreBackupFilenameOk

`func (o *SetMaintenanceModeDto) GetRestoreBackupFilenameOk() (*string, bool)`

GetRestoreBackupFilenameOk returns a tuple with the RestoreBackupFilename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestoreBackupFilename

`func (o *SetMaintenanceModeDto) SetRestoreBackupFilename(v string)`

SetRestoreBackupFilename sets RestoreBackupFilename field to given value.

### HasRestoreBackupFilename

`func (o *SetMaintenanceModeDto) HasRestoreBackupFilename() bool`

HasRestoreBackupFilename returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


