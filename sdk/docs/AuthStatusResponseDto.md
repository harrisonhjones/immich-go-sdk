# AuthStatusResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpiresAt** | Pointer to **string** | Session expiration date | [optional] 
**IsElevated** | **bool** | Is elevated session | 
**Password** | **bool** | Has password set | 
**PinCode** | **bool** | Has PIN code set | 
**PinExpiresAt** | Pointer to **string** | PIN expiration date | [optional] 

## Methods

### NewAuthStatusResponseDto

`func NewAuthStatusResponseDto(isElevated bool, password bool, pinCode bool, ) *AuthStatusResponseDto`

NewAuthStatusResponseDto instantiates a new AuthStatusResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthStatusResponseDtoWithDefaults

`func NewAuthStatusResponseDtoWithDefaults() *AuthStatusResponseDto`

NewAuthStatusResponseDtoWithDefaults instantiates a new AuthStatusResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpiresAt

`func (o *AuthStatusResponseDto) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AuthStatusResponseDto) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AuthStatusResponseDto) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *AuthStatusResponseDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetIsElevated

`func (o *AuthStatusResponseDto) GetIsElevated() bool`

GetIsElevated returns the IsElevated field if non-nil, zero value otherwise.

### GetIsElevatedOk

`func (o *AuthStatusResponseDto) GetIsElevatedOk() (*bool, bool)`

GetIsElevatedOk returns a tuple with the IsElevated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsElevated

`func (o *AuthStatusResponseDto) SetIsElevated(v bool)`

SetIsElevated sets IsElevated field to given value.


### GetPassword

`func (o *AuthStatusResponseDto) GetPassword() bool`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *AuthStatusResponseDto) GetPasswordOk() (*bool, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *AuthStatusResponseDto) SetPassword(v bool)`

SetPassword sets Password field to given value.


### GetPinCode

`func (o *AuthStatusResponseDto) GetPinCode() bool`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *AuthStatusResponseDto) GetPinCodeOk() (*bool, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *AuthStatusResponseDto) SetPinCode(v bool)`

SetPinCode sets PinCode field to given value.


### GetPinExpiresAt

`func (o *AuthStatusResponseDto) GetPinExpiresAt() string`

GetPinExpiresAt returns the PinExpiresAt field if non-nil, zero value otherwise.

### GetPinExpiresAtOk

`func (o *AuthStatusResponseDto) GetPinExpiresAtOk() (*string, bool)`

GetPinExpiresAtOk returns a tuple with the PinExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinExpiresAt

`func (o *AuthStatusResponseDto) SetPinExpiresAt(v string)`

SetPinExpiresAt sets PinExpiresAt field to given value.

### HasPinExpiresAt

`func (o *AuthStatusResponseDto) HasPinExpiresAt() bool`

HasPinExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


