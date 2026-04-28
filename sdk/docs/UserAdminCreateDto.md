# UserAdminCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | Pointer to [**NullableUserAvatarColor**](UserAvatarColor.md) |  | [optional] 
**Email** | **string** | User email | 
**IsAdmin** | Pointer to **bool** | Grant admin privileges | [optional] 
**Name** | **string** | User name | 
**Notify** | Pointer to **bool** | Send notification email | [optional] 
**Password** | **string** | User password | 
**PinCode** | Pointer to **NullableString** | PIN code | [optional] 
**QuotaSizeInBytes** | Pointer to **NullableInt32** | Storage quota in bytes | [optional] 
**ShouldChangePassword** | Pointer to **bool** | Require password change on next login | [optional] 
**StorageLabel** | Pointer to **NullableString** | Storage label | [optional] 

## Methods

### NewUserAdminCreateDto

`func NewUserAdminCreateDto(email string, name string, password string, ) *UserAdminCreateDto`

NewUserAdminCreateDto instantiates a new UserAdminCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserAdminCreateDtoWithDefaults

`func NewUserAdminCreateDtoWithDefaults() *UserAdminCreateDto`

NewUserAdminCreateDtoWithDefaults instantiates a new UserAdminCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *UserAdminCreateDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *UserAdminCreateDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *UserAdminCreateDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.

### HasAvatarColor

`func (o *UserAdminCreateDto) HasAvatarColor() bool`

HasAvatarColor returns a boolean if a field has been set.

### SetAvatarColorNil

`func (o *UserAdminCreateDto) SetAvatarColorNil(b bool)`

 SetAvatarColorNil sets the value for AvatarColor to be an explicit nil

### UnsetAvatarColor
`func (o *UserAdminCreateDto) UnsetAvatarColor()`

UnsetAvatarColor ensures that no value is present for AvatarColor, not even an explicit nil
### GetEmail

`func (o *UserAdminCreateDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserAdminCreateDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserAdminCreateDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetIsAdmin

`func (o *UserAdminCreateDto) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *UserAdminCreateDto) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *UserAdminCreateDto) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.

### HasIsAdmin

`func (o *UserAdminCreateDto) HasIsAdmin() bool`

HasIsAdmin returns a boolean if a field has been set.

### GetName

`func (o *UserAdminCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserAdminCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserAdminCreateDto) SetName(v string)`

SetName sets Name field to given value.


### GetNotify

`func (o *UserAdminCreateDto) GetNotify() bool`

GetNotify returns the Notify field if non-nil, zero value otherwise.

### GetNotifyOk

`func (o *UserAdminCreateDto) GetNotifyOk() (*bool, bool)`

GetNotifyOk returns a tuple with the Notify field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotify

`func (o *UserAdminCreateDto) SetNotify(v bool)`

SetNotify sets Notify field to given value.

### HasNotify

`func (o *UserAdminCreateDto) HasNotify() bool`

HasNotify returns a boolean if a field has been set.

### GetPassword

`func (o *UserAdminCreateDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserAdminCreateDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserAdminCreateDto) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetPinCode

`func (o *UserAdminCreateDto) GetPinCode() string`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *UserAdminCreateDto) GetPinCodeOk() (*string, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *UserAdminCreateDto) SetPinCode(v string)`

SetPinCode sets PinCode field to given value.

### HasPinCode

`func (o *UserAdminCreateDto) HasPinCode() bool`

HasPinCode returns a boolean if a field has been set.

### SetPinCodeNil

`func (o *UserAdminCreateDto) SetPinCodeNil(b bool)`

 SetPinCodeNil sets the value for PinCode to be an explicit nil

### UnsetPinCode
`func (o *UserAdminCreateDto) UnsetPinCode()`

UnsetPinCode ensures that no value is present for PinCode, not even an explicit nil
### GetQuotaSizeInBytes

`func (o *UserAdminCreateDto) GetQuotaSizeInBytes() int32`

GetQuotaSizeInBytes returns the QuotaSizeInBytes field if non-nil, zero value otherwise.

### GetQuotaSizeInBytesOk

`func (o *UserAdminCreateDto) GetQuotaSizeInBytesOk() (*int32, bool)`

GetQuotaSizeInBytesOk returns a tuple with the QuotaSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaSizeInBytes

`func (o *UserAdminCreateDto) SetQuotaSizeInBytes(v int32)`

SetQuotaSizeInBytes sets QuotaSizeInBytes field to given value.

### HasQuotaSizeInBytes

`func (o *UserAdminCreateDto) HasQuotaSizeInBytes() bool`

HasQuotaSizeInBytes returns a boolean if a field has been set.

### SetQuotaSizeInBytesNil

`func (o *UserAdminCreateDto) SetQuotaSizeInBytesNil(b bool)`

 SetQuotaSizeInBytesNil sets the value for QuotaSizeInBytes to be an explicit nil

### UnsetQuotaSizeInBytes
`func (o *UserAdminCreateDto) UnsetQuotaSizeInBytes()`

UnsetQuotaSizeInBytes ensures that no value is present for QuotaSizeInBytes, not even an explicit nil
### GetShouldChangePassword

`func (o *UserAdminCreateDto) GetShouldChangePassword() bool`

GetShouldChangePassword returns the ShouldChangePassword field if non-nil, zero value otherwise.

### GetShouldChangePasswordOk

`func (o *UserAdminCreateDto) GetShouldChangePasswordOk() (*bool, bool)`

GetShouldChangePasswordOk returns a tuple with the ShouldChangePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldChangePassword

`func (o *UserAdminCreateDto) SetShouldChangePassword(v bool)`

SetShouldChangePassword sets ShouldChangePassword field to given value.

### HasShouldChangePassword

`func (o *UserAdminCreateDto) HasShouldChangePassword() bool`

HasShouldChangePassword returns a boolean if a field has been set.

### GetStorageLabel

`func (o *UserAdminCreateDto) GetStorageLabel() string`

GetStorageLabel returns the StorageLabel field if non-nil, zero value otherwise.

### GetStorageLabelOk

`func (o *UserAdminCreateDto) GetStorageLabelOk() (*string, bool)`

GetStorageLabelOk returns a tuple with the StorageLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageLabel

`func (o *UserAdminCreateDto) SetStorageLabel(v string)`

SetStorageLabel sets StorageLabel field to given value.

### HasStorageLabel

`func (o *UserAdminCreateDto) HasStorageLabel() bool`

HasStorageLabel returns a boolean if a field has been set.

### SetStorageLabelNil

`func (o *UserAdminCreateDto) SetStorageLabelNil(b bool)`

 SetStorageLabelNil sets the value for StorageLabel to be an explicit nil

### UnsetStorageLabel
`func (o *UserAdminCreateDto) UnsetStorageLabel()`

UnsetStorageLabel ensures that no value is present for StorageLabel, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


