# SystemConfigNotificationsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Smtp** | [**SystemConfigSmtpDto**](SystemConfigSmtpDto.md) |  | 

## Methods

### NewSystemConfigNotificationsDto

`func NewSystemConfigNotificationsDto(smtp SystemConfigSmtpDto, ) *SystemConfigNotificationsDto`

NewSystemConfigNotificationsDto instantiates a new SystemConfigNotificationsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigNotificationsDtoWithDefaults

`func NewSystemConfigNotificationsDtoWithDefaults() *SystemConfigNotificationsDto`

NewSystemConfigNotificationsDtoWithDefaults instantiates a new SystemConfigNotificationsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSmtp

`func (o *SystemConfigNotificationsDto) GetSmtp() SystemConfigSmtpDto`

GetSmtp returns the Smtp field if non-nil, zero value otherwise.

### GetSmtpOk

`func (o *SystemConfigNotificationsDto) GetSmtpOk() (*SystemConfigSmtpDto, bool)`

GetSmtpOk returns a tuple with the Smtp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtp

`func (o *SystemConfigNotificationsDto) SetSmtp(v SystemConfigSmtpDto)`

SetSmtp sets Smtp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


