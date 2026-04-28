# SystemConfigSmtpTransportDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Host** | **string** | SMTP server hostname | 
**IgnoreCert** | **bool** | Whether to ignore SSL certificate errors | 
**Password** | **string** | SMTP password | 
**Port** | **int32** | SMTP server port | 
**Secure** | **bool** | Whether to use secure connection (TLS/SSL) | 
**Username** | **string** | SMTP username | 

## Methods

### NewSystemConfigSmtpTransportDto

`func NewSystemConfigSmtpTransportDto(host string, ignoreCert bool, password string, port int32, secure bool, username string, ) *SystemConfigSmtpTransportDto`

NewSystemConfigSmtpTransportDto instantiates a new SystemConfigSmtpTransportDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigSmtpTransportDtoWithDefaults

`func NewSystemConfigSmtpTransportDtoWithDefaults() *SystemConfigSmtpTransportDto`

NewSystemConfigSmtpTransportDtoWithDefaults instantiates a new SystemConfigSmtpTransportDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHost

`func (o *SystemConfigSmtpTransportDto) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *SystemConfigSmtpTransportDto) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *SystemConfigSmtpTransportDto) SetHost(v string)`

SetHost sets Host field to given value.


### GetIgnoreCert

`func (o *SystemConfigSmtpTransportDto) GetIgnoreCert() bool`

GetIgnoreCert returns the IgnoreCert field if non-nil, zero value otherwise.

### GetIgnoreCertOk

`func (o *SystemConfigSmtpTransportDto) GetIgnoreCertOk() (*bool, bool)`

GetIgnoreCertOk returns a tuple with the IgnoreCert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnoreCert

`func (o *SystemConfigSmtpTransportDto) SetIgnoreCert(v bool)`

SetIgnoreCert sets IgnoreCert field to given value.


### GetPassword

`func (o *SystemConfigSmtpTransportDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SystemConfigSmtpTransportDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SystemConfigSmtpTransportDto) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetPort

`func (o *SystemConfigSmtpTransportDto) GetPort() int32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *SystemConfigSmtpTransportDto) GetPortOk() (*int32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *SystemConfigSmtpTransportDto) SetPort(v int32)`

SetPort sets Port field to given value.


### GetSecure

`func (o *SystemConfigSmtpTransportDto) GetSecure() bool`

GetSecure returns the Secure field if non-nil, zero value otherwise.

### GetSecureOk

`func (o *SystemConfigSmtpTransportDto) GetSecureOk() (*bool, bool)`

GetSecureOk returns a tuple with the Secure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecure

`func (o *SystemConfigSmtpTransportDto) SetSecure(v bool)`

SetSecure sets Secure field to given value.


### GetUsername

`func (o *SystemConfigSmtpTransportDto) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *SystemConfigSmtpTransportDto) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *SystemConfigSmtpTransportDto) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


