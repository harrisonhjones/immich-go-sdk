# SystemConfigSmtpDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether SMTP email notifications are enabled | 
**From** | **string** | Email address to send from | 
**ReplyTo** | **string** | Email address for replies | 
**Transport** | [**SystemConfigSmtpTransportDto**](SystemConfigSmtpTransportDto.md) |  | 

## Methods

### NewSystemConfigSmtpDto

`func NewSystemConfigSmtpDto(enabled bool, from string, replyTo string, transport SystemConfigSmtpTransportDto, ) *SystemConfigSmtpDto`

NewSystemConfigSmtpDto instantiates a new SystemConfigSmtpDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigSmtpDtoWithDefaults

`func NewSystemConfigSmtpDtoWithDefaults() *SystemConfigSmtpDto`

NewSystemConfigSmtpDtoWithDefaults instantiates a new SystemConfigSmtpDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *SystemConfigSmtpDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigSmtpDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigSmtpDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetFrom

`func (o *SystemConfigSmtpDto) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SystemConfigSmtpDto) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SystemConfigSmtpDto) SetFrom(v string)`

SetFrom sets From field to given value.


### GetReplyTo

`func (o *SystemConfigSmtpDto) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *SystemConfigSmtpDto) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *SystemConfigSmtpDto) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.


### GetTransport

`func (o *SystemConfigSmtpDto) GetTransport() SystemConfigSmtpTransportDto`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *SystemConfigSmtpDto) GetTransportOk() (*SystemConfigSmtpTransportDto, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *SystemConfigSmtpDto) SetTransport(v SystemConfigSmtpTransportDto)`

SetTransport sets Transport field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


