# UserUpdateMeDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | Pointer to [**NullableUserAvatarColor**](UserAvatarColor.md) |  | [optional] 
**Email** | Pointer to **string** | User email | [optional] 
**Name** | Pointer to **string** | User name | [optional] 
**Password** | Pointer to **string** | User password (deprecated, use change password endpoint) | [optional] 

## Methods

### NewUserUpdateMeDto

`func NewUserUpdateMeDto() *UserUpdateMeDto`

NewUserUpdateMeDto instantiates a new UserUpdateMeDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserUpdateMeDtoWithDefaults

`func NewUserUpdateMeDtoWithDefaults() *UserUpdateMeDto`

NewUserUpdateMeDtoWithDefaults instantiates a new UserUpdateMeDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *UserUpdateMeDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *UserUpdateMeDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *UserUpdateMeDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.

### HasAvatarColor

`func (o *UserUpdateMeDto) HasAvatarColor() bool`

HasAvatarColor returns a boolean if a field has been set.

### SetAvatarColorNil

`func (o *UserUpdateMeDto) SetAvatarColorNil(b bool)`

 SetAvatarColorNil sets the value for AvatarColor to be an explicit nil

### UnsetAvatarColor
`func (o *UserUpdateMeDto) UnsetAvatarColor()`

UnsetAvatarColor ensures that no value is present for AvatarColor, not even an explicit nil
### GetEmail

`func (o *UserUpdateMeDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserUpdateMeDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserUpdateMeDto) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *UserUpdateMeDto) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetName

`func (o *UserUpdateMeDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserUpdateMeDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserUpdateMeDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UserUpdateMeDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPassword

`func (o *UserUpdateMeDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserUpdateMeDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserUpdateMeDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UserUpdateMeDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


