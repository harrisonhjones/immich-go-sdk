# SyncAuthUserV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | Pointer to [**NullableUserAvatarColor**](UserAvatarColor.md) |  | [optional] 
**DeletedAt** | **NullableTime** | User deleted at | 
**Email** | **string** | User email | 
**HasProfileImage** | **bool** | User has profile image | 
**Id** | **string** | User ID | 
**IsAdmin** | **bool** | User is admin | 
**Name** | **string** | User name | 
**OauthId** | **string** | User OAuth ID | 
**PinCode** | **NullableString** | User pin code | 
**ProfileChangedAt** | **time.Time** | User profile changed at | 
**QuotaSizeInBytes** | **NullableInt32** | Quota size in bytes | 
**QuotaUsageInBytes** | **int32** | Quota usage in bytes | 
**StorageLabel** | **NullableString** | User storage label | 

## Methods

### NewSyncAuthUserV1

`func NewSyncAuthUserV1(deletedAt NullableTime, email string, hasProfileImage bool, id string, isAdmin bool, name string, oauthId string, pinCode NullableString, profileChangedAt time.Time, quotaSizeInBytes NullableInt32, quotaUsageInBytes int32, storageLabel NullableString, ) *SyncAuthUserV1`

NewSyncAuthUserV1 instantiates a new SyncAuthUserV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAuthUserV1WithDefaults

`func NewSyncAuthUserV1WithDefaults() *SyncAuthUserV1`

NewSyncAuthUserV1WithDefaults instantiates a new SyncAuthUserV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *SyncAuthUserV1) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *SyncAuthUserV1) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *SyncAuthUserV1) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.

### HasAvatarColor

`func (o *SyncAuthUserV1) HasAvatarColor() bool`

HasAvatarColor returns a boolean if a field has been set.

### SetAvatarColorNil

`func (o *SyncAuthUserV1) SetAvatarColorNil(b bool)`

 SetAvatarColorNil sets the value for AvatarColor to be an explicit nil

### UnsetAvatarColor
`func (o *SyncAuthUserV1) UnsetAvatarColor()`

UnsetAvatarColor ensures that no value is present for AvatarColor, not even an explicit nil
### GetDeletedAt

`func (o *SyncAuthUserV1) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncAuthUserV1) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncAuthUserV1) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncAuthUserV1) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncAuthUserV1) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetEmail

`func (o *SyncAuthUserV1) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SyncAuthUserV1) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SyncAuthUserV1) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetHasProfileImage

`func (o *SyncAuthUserV1) GetHasProfileImage() bool`

GetHasProfileImage returns the HasProfileImage field if non-nil, zero value otherwise.

### GetHasProfileImageOk

`func (o *SyncAuthUserV1) GetHasProfileImageOk() (*bool, bool)`

GetHasProfileImageOk returns a tuple with the HasProfileImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasProfileImage

`func (o *SyncAuthUserV1) SetHasProfileImage(v bool)`

SetHasProfileImage sets HasProfileImage field to given value.


### GetId

`func (o *SyncAuthUserV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAuthUserV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAuthUserV1) SetId(v string)`

SetId sets Id field to given value.


### GetIsAdmin

`func (o *SyncAuthUserV1) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *SyncAuthUserV1) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *SyncAuthUserV1) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.


### GetName

`func (o *SyncAuthUserV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SyncAuthUserV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SyncAuthUserV1) SetName(v string)`

SetName sets Name field to given value.


### GetOauthId

`func (o *SyncAuthUserV1) GetOauthId() string`

GetOauthId returns the OauthId field if non-nil, zero value otherwise.

### GetOauthIdOk

`func (o *SyncAuthUserV1) GetOauthIdOk() (*string, bool)`

GetOauthIdOk returns a tuple with the OauthId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthId

`func (o *SyncAuthUserV1) SetOauthId(v string)`

SetOauthId sets OauthId field to given value.


### GetPinCode

`func (o *SyncAuthUserV1) GetPinCode() string`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *SyncAuthUserV1) GetPinCodeOk() (*string, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *SyncAuthUserV1) SetPinCode(v string)`

SetPinCode sets PinCode field to given value.


### SetPinCodeNil

`func (o *SyncAuthUserV1) SetPinCodeNil(b bool)`

 SetPinCodeNil sets the value for PinCode to be an explicit nil

### UnsetPinCode
`func (o *SyncAuthUserV1) UnsetPinCode()`

UnsetPinCode ensures that no value is present for PinCode, not even an explicit nil
### GetProfileChangedAt

`func (o *SyncAuthUserV1) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *SyncAuthUserV1) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *SyncAuthUserV1) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.


### GetQuotaSizeInBytes

`func (o *SyncAuthUserV1) GetQuotaSizeInBytes() int32`

GetQuotaSizeInBytes returns the QuotaSizeInBytes field if non-nil, zero value otherwise.

### GetQuotaSizeInBytesOk

`func (o *SyncAuthUserV1) GetQuotaSizeInBytesOk() (*int32, bool)`

GetQuotaSizeInBytesOk returns a tuple with the QuotaSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaSizeInBytes

`func (o *SyncAuthUserV1) SetQuotaSizeInBytes(v int32)`

SetQuotaSizeInBytes sets QuotaSizeInBytes field to given value.


### SetQuotaSizeInBytesNil

`func (o *SyncAuthUserV1) SetQuotaSizeInBytesNil(b bool)`

 SetQuotaSizeInBytesNil sets the value for QuotaSizeInBytes to be an explicit nil

### UnsetQuotaSizeInBytes
`func (o *SyncAuthUserV1) UnsetQuotaSizeInBytes()`

UnsetQuotaSizeInBytes ensures that no value is present for QuotaSizeInBytes, not even an explicit nil
### GetQuotaUsageInBytes

`func (o *SyncAuthUserV1) GetQuotaUsageInBytes() int32`

GetQuotaUsageInBytes returns the QuotaUsageInBytes field if non-nil, zero value otherwise.

### GetQuotaUsageInBytesOk

`func (o *SyncAuthUserV1) GetQuotaUsageInBytesOk() (*int32, bool)`

GetQuotaUsageInBytesOk returns a tuple with the QuotaUsageInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaUsageInBytes

`func (o *SyncAuthUserV1) SetQuotaUsageInBytes(v int32)`

SetQuotaUsageInBytes sets QuotaUsageInBytes field to given value.


### GetStorageLabel

`func (o *SyncAuthUserV1) GetStorageLabel() string`

GetStorageLabel returns the StorageLabel field if non-nil, zero value otherwise.

### GetStorageLabelOk

`func (o *SyncAuthUserV1) GetStorageLabelOk() (*string, bool)`

GetStorageLabelOk returns a tuple with the StorageLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageLabel

`func (o *SyncAuthUserV1) SetStorageLabel(v string)`

SetStorageLabel sets StorageLabel field to given value.


### SetStorageLabelNil

`func (o *SyncAuthUserV1) SetStorageLabelNil(b bool)`

 SetStorageLabelNil sets the value for StorageLabel to be an explicit nil

### UnsetStorageLabel
`func (o *SyncAuthUserV1) UnsetStorageLabel()`

UnsetStorageLabel ensures that no value is present for StorageLabel, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


