# ChangePasswordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvalidateSessions** | Pointer to **bool** | Invalidate all other sessions | [optional] [default to false]
**NewPassword** | **string** | New password (min 8 characters) | 
**Password** | **string** | Current password | 

## Methods

### NewChangePasswordDto

`func NewChangePasswordDto(newPassword string, password string, ) *ChangePasswordDto`

NewChangePasswordDto instantiates a new ChangePasswordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangePasswordDtoWithDefaults

`func NewChangePasswordDtoWithDefaults() *ChangePasswordDto`

NewChangePasswordDtoWithDefaults instantiates a new ChangePasswordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvalidateSessions

`func (o *ChangePasswordDto) GetInvalidateSessions() bool`

GetInvalidateSessions returns the InvalidateSessions field if non-nil, zero value otherwise.

### GetInvalidateSessionsOk

`func (o *ChangePasswordDto) GetInvalidateSessionsOk() (*bool, bool)`

GetInvalidateSessionsOk returns a tuple with the InvalidateSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidateSessions

`func (o *ChangePasswordDto) SetInvalidateSessions(v bool)`

SetInvalidateSessions sets InvalidateSessions field to given value.

### HasInvalidateSessions

`func (o *ChangePasswordDto) HasInvalidateSessions() bool`

HasInvalidateSessions returns a boolean if a field has been set.

### GetNewPassword

`func (o *ChangePasswordDto) GetNewPassword() string`

GetNewPassword returns the NewPassword field if non-nil, zero value otherwise.

### GetNewPasswordOk

`func (o *ChangePasswordDto) GetNewPasswordOk() (*string, bool)`

GetNewPasswordOk returns a tuple with the NewPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPassword

`func (o *ChangePasswordDto) SetNewPassword(v string)`

SetNewPassword sets NewPassword field to given value.


### GetPassword

`func (o *ChangePasswordDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ChangePasswordDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ChangePasswordDto) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


