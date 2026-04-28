# UserResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | [**UserAvatarColor**](UserAvatarColor.md) |  | 
**Email** | **string** | User email | 
**Id** | **string** | User ID | 
**Name** | **string** | User name | 
**ProfileChangedAt** | **time.Time** | Profile change date | 
**ProfileImagePath** | **string** | Profile image path | 

## Methods

### NewUserResponseDto

`func NewUserResponseDto(avatarColor UserAvatarColor, email string, id string, name string, profileChangedAt time.Time, profileImagePath string, ) *UserResponseDto`

NewUserResponseDto instantiates a new UserResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserResponseDtoWithDefaults

`func NewUserResponseDtoWithDefaults() *UserResponseDto`

NewUserResponseDtoWithDefaults instantiates a new UserResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *UserResponseDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *UserResponseDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *UserResponseDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.


### GetEmail

`func (o *UserResponseDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserResponseDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserResponseDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetId

`func (o *UserResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *UserResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetProfileChangedAt

`func (o *UserResponseDto) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *UserResponseDto) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *UserResponseDto) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.


### GetProfileImagePath

`func (o *UserResponseDto) GetProfileImagePath() string`

GetProfileImagePath returns the ProfileImagePath field if non-nil, zero value otherwise.

### GetProfileImagePathOk

`func (o *UserResponseDto) GetProfileImagePathOk() (*string, bool)`

GetProfileImagePathOk returns a tuple with the ProfileImagePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileImagePath

`func (o *UserResponseDto) SetProfileImagePath(v string)`

SetProfileImagePath sets ProfileImagePath field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


