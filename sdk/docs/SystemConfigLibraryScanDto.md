# SystemConfigLibraryScanDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CronExpression** | **string** | Cron expression | 
**Enabled** | **bool** | Enabled | 

## Methods

### NewSystemConfigLibraryScanDto

`func NewSystemConfigLibraryScanDto(cronExpression string, enabled bool, ) *SystemConfigLibraryScanDto`

NewSystemConfigLibraryScanDto instantiates a new SystemConfigLibraryScanDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigLibraryScanDtoWithDefaults

`func NewSystemConfigLibraryScanDtoWithDefaults() *SystemConfigLibraryScanDto`

NewSystemConfigLibraryScanDtoWithDefaults instantiates a new SystemConfigLibraryScanDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCronExpression

`func (o *SystemConfigLibraryScanDto) GetCronExpression() string`

GetCronExpression returns the CronExpression field if non-nil, zero value otherwise.

### GetCronExpressionOk

`func (o *SystemConfigLibraryScanDto) GetCronExpressionOk() (*string, bool)`

GetCronExpressionOk returns a tuple with the CronExpression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCronExpression

`func (o *SystemConfigLibraryScanDto) SetCronExpression(v string)`

SetCronExpression sets CronExpression field to given value.


### GetEnabled

`func (o *SystemConfigLibraryScanDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigLibraryScanDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigLibraryScanDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


