# SessionCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceOS** | Pointer to **string** | Device OS | [optional] 
**DeviceType** | Pointer to **string** | Device type | [optional] 
**Duration** | Pointer to **int32** | Session duration in seconds | [optional] 

## Methods

### NewSessionCreateDto

`func NewSessionCreateDto() *SessionCreateDto`

NewSessionCreateDto instantiates a new SessionCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionCreateDtoWithDefaults

`func NewSessionCreateDtoWithDefaults() *SessionCreateDto`

NewSessionCreateDtoWithDefaults instantiates a new SessionCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceOS

`func (o *SessionCreateDto) GetDeviceOS() string`

GetDeviceOS returns the DeviceOS field if non-nil, zero value otherwise.

### GetDeviceOSOk

`func (o *SessionCreateDto) GetDeviceOSOk() (*string, bool)`

GetDeviceOSOk returns a tuple with the DeviceOS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceOS

`func (o *SessionCreateDto) SetDeviceOS(v string)`

SetDeviceOS sets DeviceOS field to given value.

### HasDeviceOS

`func (o *SessionCreateDto) HasDeviceOS() bool`

HasDeviceOS returns a boolean if a field has been set.

### GetDeviceType

`func (o *SessionCreateDto) GetDeviceType() string`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *SessionCreateDto) GetDeviceTypeOk() (*string, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *SessionCreateDto) SetDeviceType(v string)`

SetDeviceType sets DeviceType field to given value.

### HasDeviceType

`func (o *SessionCreateDto) HasDeviceType() bool`

HasDeviceType returns a boolean if a field has been set.

### GetDuration

`func (o *SessionCreateDto) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *SessionCreateDto) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *SessionCreateDto) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *SessionCreateDto) HasDuration() bool`

HasDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


