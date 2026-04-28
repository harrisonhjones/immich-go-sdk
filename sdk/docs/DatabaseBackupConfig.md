# DatabaseBackupConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CronExpression** | **string** | Cron expression | 
**Enabled** | **bool** | Enabled | 
**KeepLastAmount** | **float32** | Keep last amount | 

## Methods

### NewDatabaseBackupConfig

`func NewDatabaseBackupConfig(cronExpression string, enabled bool, keepLastAmount float32, ) *DatabaseBackupConfig`

NewDatabaseBackupConfig instantiates a new DatabaseBackupConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDatabaseBackupConfigWithDefaults

`func NewDatabaseBackupConfigWithDefaults() *DatabaseBackupConfig`

NewDatabaseBackupConfigWithDefaults instantiates a new DatabaseBackupConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCronExpression

`func (o *DatabaseBackupConfig) GetCronExpression() string`

GetCronExpression returns the CronExpression field if non-nil, zero value otherwise.

### GetCronExpressionOk

`func (o *DatabaseBackupConfig) GetCronExpressionOk() (*string, bool)`

GetCronExpressionOk returns a tuple with the CronExpression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCronExpression

`func (o *DatabaseBackupConfig) SetCronExpression(v string)`

SetCronExpression sets CronExpression field to given value.


### GetEnabled

`func (o *DatabaseBackupConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DatabaseBackupConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DatabaseBackupConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetKeepLastAmount

`func (o *DatabaseBackupConfig) GetKeepLastAmount() float32`

GetKeepLastAmount returns the KeepLastAmount field if non-nil, zero value otherwise.

### GetKeepLastAmountOk

`func (o *DatabaseBackupConfig) GetKeepLastAmountOk() (*float32, bool)`

GetKeepLastAmountOk returns a tuple with the KeepLastAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepLastAmount

`func (o *DatabaseBackupConfig) SetKeepLastAmount(v float32)`

SetKeepLastAmount sets KeepLastAmount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


