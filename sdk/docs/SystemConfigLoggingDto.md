# SystemConfigLoggingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Enabled | 
**Level** | [**LogLevel**](LogLevel.md) |  | 

## Methods

### NewSystemConfigLoggingDto

`func NewSystemConfigLoggingDto(enabled bool, level LogLevel, ) *SystemConfigLoggingDto`

NewSystemConfigLoggingDto instantiates a new SystemConfigLoggingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigLoggingDtoWithDefaults

`func NewSystemConfigLoggingDtoWithDefaults() *SystemConfigLoggingDto`

NewSystemConfigLoggingDtoWithDefaults instantiates a new SystemConfigLoggingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *SystemConfigLoggingDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigLoggingDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigLoggingDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetLevel

`func (o *SystemConfigLoggingDto) GetLevel() LogLevel`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *SystemConfigLoggingDto) GetLevelOk() (*LogLevel, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *SystemConfigLoggingDto) SetLevel(v LogLevel)`

SetLevel sets Level field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


