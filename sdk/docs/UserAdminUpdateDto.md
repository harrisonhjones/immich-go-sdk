# UserAdminUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | Pointer to [**NullableUserAvatarColor**](UserAvatarColor.md) |  | [optional] 
**Email** | Pointer to **string** | User email | [optional] 
**IsAdmin** | Pointer to **bool** | Grant admin privileges | [optional] 
**Name** | Pointer to **string** | User name | [optional] 
**Password** | Pointer to **string** | User password | [optional] 
**PinCode** | Pointer to **NullableString** | PIN code | [optional] 
**QuotaSizeInBytes** | Pointer to **NullableInt32** | Storage quota in bytes | [optional] 
**ShouldChangePassword** | Pointer to **bool** | Require password change on next login | [optional] 
**StorageLabel** | Pointer to **NullableString** | Storage label | [optional] 

## Methods

### NewUserAdminUpdateDto

`func NewUserAdminUpdateDto() *UserAdminUpdateDto`

NewUserAdminUpdateDto instantiates a new UserAdminUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserAdminUpdateDtoWithDefaults

`func NewUserAdminUpdateDtoWithDefaults() *UserAdminUpdateDto`

NewUserAdminUpdateDtoWithDefaults instantiates a new UserAdminUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *UserAdminUpdateDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *UserAdminUpdateDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *UserAdminUpdateDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.

### HasAvatarColor

`func (o *UserAdminUpdateDto) HasAvatarColor() bool`

HasAvatarColor returns a boolean if a field has been set.

### SetAvatarColorNil

`func (o *UserAdminUpdateDto) SetAvatarColorNil(b bool)`

 SetAvatarColorNil sets the value for AvatarColor to be an explicit nil

### UnsetAvatarColor
`func (o *UserAdminUpdateDto) UnsetAvatarColor()`

UnsetAvatarColor ensures that no value is present for AvatarColor, not even an explicit nil
### GetEmail

`func (o *UserAdminUpdateDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserAdminUpdateDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserAdminUpdateDto) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UserAdminUpdateDto) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetIsAdmin

`func (o *UserAdminUpdateDto) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *UserAdminUpdateDto) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *UserAdminUpdateDto) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.

### HasIsAdmin

`func (o *UserAdminUpdateDto) HasIsAdmin() bool`

HasIsAdmin returns a boolean if a field has been set.

### GetName

`func (o *UserAdminUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserAdminUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserAdminUpdateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UserAdminUpdateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPassword

`func (o *UserAdminUpdateDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserAdminUpdateDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserAdminUpdateDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UserAdminUpdateDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPinCode

`func (o *UserAdminUpdateDto) GetPinCode() string`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *UserAdminUpdateDto) GetPinCodeOk() (*string, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *UserAdminUpdateDto) SetPinCode(v string)`

SetPinCode sets PinCode field to given value.

### HasPinCode

`func (o *UserAdminUpdateDto) HasPinCode() bool`

HasPinCode returns a boolean if a field has been set.

### SetPinCodeNil

`func (o *UserAdminUpdateDto) SetPinCodeNil(b bool)`

 SetPinCodeNil sets the value for PinCode to be an explicit nil

### UnsetPinCode
`func (o *UserAdminUpdateDto) UnsetPinCode()`

UnsetPinCode ensures that no value is present for PinCode, not even an explicit nil
### GetQuotaSizeInBytes

`func (o *UserAdminUpdateDto) GetQuotaSizeInBytes() int32`

GetQuotaSizeInBytes returns the QuotaSizeInBytes field if non-nil, zero value otherwise.

### GetQuotaSizeInBytesOk

`func (o *UserAdminUpdateDto) GetQuotaSizeInBytesOk() (*int32, bool)`

GetQuotaSizeInBytesOk returns a tuple with the QuotaSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaSizeInBytes

`func (o *UserAdminUpdateDto) SetQuotaSizeInBytes(v int32)`

SetQuotaSizeInBytes sets QuotaSizeInBytes field to given value.

### HasQuotaSizeInBytes

`func (o *UserAdminUpdateDto) HasQuotaSizeInBytes() bool`

HasQuotaSizeInBytes returns a boolean if a field has been set.

### SetQuotaSizeInBytesNil

`func (o *UserAdminUpdateDto) SetQuotaSizeInBytesNil(b bool)`

 SetQuotaSizeInBytesNil sets the value for QuotaSizeInBytes to be an explicit nil

### UnsetQuotaSizeInBytes
`func (o *UserAdminUpdateDto) UnsetQuotaSizeInBytes()`

UnsetQuotaSizeInBytes ensures that no value is present for QuotaSizeInBytes, not even an explicit nil
### GetShouldChangePassword

`func (o *UserAdminUpdateDto) GetShouldChangePassword() bool`

GetShouldChangePassword returns the ShouldChangePassword field if non-nil, zero value otherwise.

### GetShouldChangePasswordOk

`func (o *UserAdminUpdateDto) GetShouldChangePasswordOk() (*bool, bool)`

GetShouldChangePasswordOk returns a tuple with the ShouldChangePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldChangePassword

`func (o *UserAdminUpdateDto) SetShouldChangePassword(v bool)`

SetShouldChangePassword sets ShouldChangePassword field to given value.

### HasShouldChangePassword

`func (o *UserAdminUpdateDto) HasShouldChangePassword() bool`

HasShouldChangePassword returns a boolean if a field has been set.

### GetStorageLabel

`func (o *UserAdminUpdateDto) GetStorageLabel() string`

GetStorageLabel returns the StorageLabel field if non-nil, zero value otherwise.

### GetStorageLabelOk

`func (o *UserAdminUpdateDto) GetStorageLabelOk() (*string, bool)`

GetStorageLabelOk returns a tuple with the StorageLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageLabel

`func (o *UserAdminUpdateDto) SetStorageLabel(v string)`

SetStorageLabel sets StorageLabel field to given value.

### HasStorageLabel

`func (o *UserAdminUpdateDto) HasStorageLabel() bool`

HasStorageLabel returns a boolean if a field has been set.

### SetStorageLabelNil

`func (o *UserAdminUpdateDto) SetStorageLabelNil(b bool)`

 SetStorageLabelNil sets the value for StorageLabel to be an explicit nil

### UnsetStorageLabel
`func (o *UserAdminUpdateDto) UnsetStorageLabel()`

UnsetStorageLabel ensures that no value is present for StorageLabel, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


