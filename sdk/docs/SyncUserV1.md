# SyncUserV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | Pointer to [**NullableUserAvatarColor**](UserAvatarColor.md) |  | [optional] 
**DeletedAt** | **NullableTime** | User deleted at | 
**Email** | **string** | User email | 
**HasProfileImage** | **bool** | User has profile image | 
**Id** | **string** | User ID | 
**Name** | **string** | User name | 
**ProfileChangedAt** | **time.Time** | User profile changed at | 

## Methods

### NewSyncUserV1

`func NewSyncUserV1(deletedAt NullableTime, email string, hasProfileImage bool, id string, name string, profileChangedAt time.Time, ) *SyncUserV1`

NewSyncUserV1 instantiates a new SyncUserV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncUserV1WithDefaults

`func NewSyncUserV1WithDefaults() *SyncUserV1`

NewSyncUserV1WithDefaults instantiates a new SyncUserV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *SyncUserV1) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *SyncUserV1) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *SyncUserV1) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.

### HasAvatarColor

`func (o *SyncUserV1) HasAvatarColor() bool`

HasAvatarColor returns a boolean if a field has been set.

### SetAvatarColorNil

`func (o *SyncUserV1) SetAvatarColorNil(b bool)`

 SetAvatarColorNil sets the value for AvatarColor to be an explicit nil

### UnsetAvatarColor
`func (o *SyncUserV1) UnsetAvatarColor()`

UnsetAvatarColor ensures that no value is present for AvatarColor, not even an explicit nil
### GetDeletedAt

`func (o *SyncUserV1) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncUserV1) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncUserV1) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncUserV1) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncUserV1) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetEmail

`func (o *SyncUserV1) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SyncUserV1) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SyncUserV1) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetHasProfileImage

`func (o *SyncUserV1) GetHasProfileImage() bool`

GetHasProfileImage returns the HasProfileImage field if non-nil, zero value otherwise.

### GetHasProfileImageOk

`func (o *SyncUserV1) GetHasProfileImageOk() (*bool, bool)`

GetHasProfileImageOk returns a tuple with the HasProfileImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasProfileImage

`func (o *SyncUserV1) SetHasProfileImage(v bool)`

SetHasProfileImage sets HasProfileImage field to given value.


### GetId

`func (o *SyncUserV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncUserV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncUserV1) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *SyncUserV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SyncUserV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SyncUserV1) SetName(v string)`

SetName sets Name field to given value.


### GetProfileChangedAt

`func (o *SyncUserV1) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *SyncUserV1) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *SyncUserV1) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


