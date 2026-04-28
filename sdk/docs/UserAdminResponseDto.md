# UserAdminResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | [**UserAvatarColor**](UserAvatarColor.md) |  | 
**CreatedAt** | **time.Time** | Creation date | 
**DeletedAt** | **NullableTime** | Deletion date | 
**Email** | **string** | User email | 
**Id** | **string** | User ID | 
**IsAdmin** | **bool** | Is admin user | 
**License** | [**NullableUserLicense**](UserLicense.md) |  | 
**Name** | **string** | User name | 
**OauthId** | **string** | OAuth ID | 
**ProfileChangedAt** | **time.Time** | Profile change date | 
**ProfileImagePath** | **string** | Profile image path | 
**QuotaSizeInBytes** | **NullableInt32** | Storage quota in bytes | 
**QuotaUsageInBytes** | **NullableInt32** | Storage usage in bytes | 
**ShouldChangePassword** | **bool** | Require password change on next login | 
**Status** | [**UserStatus**](UserStatus.md) |  | 
**StorageLabel** | **NullableString** | Storage label | 
**UpdatedAt** | **time.Time** | Last update date | 

## Methods

### NewUserAdminResponseDto

`func NewUserAdminResponseDto(avatarColor UserAvatarColor, createdAt time.Time, deletedAt NullableTime, email string, id string, isAdmin bool, license NullableUserLicense, name string, oauthId string, profileChangedAt time.Time, profileImagePath string, quotaSizeInBytes NullableInt32, quotaUsageInBytes NullableInt32, shouldChangePassword bool, status UserStatus, storageLabel NullableString, updatedAt time.Time, ) *UserAdminResponseDto`

NewUserAdminResponseDto instantiates a new UserAdminResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserAdminResponseDtoWithDefaults

`func NewUserAdminResponseDtoWithDefaults() *UserAdminResponseDto`

NewUserAdminResponseDtoWithDefaults instantiates a new UserAdminResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *UserAdminResponseDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *UserAdminResponseDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *UserAdminResponseDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.


### GetCreatedAt

`func (o *UserAdminResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UserAdminResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UserAdminResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeletedAt

`func (o *UserAdminResponseDto) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *UserAdminResponseDto) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *UserAdminResponseDto) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *UserAdminResponseDto) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *UserAdminResponseDto) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetEmail

`func (o *UserAdminResponseDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserAdminResponseDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserAdminResponseDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetId

`func (o *UserAdminResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserAdminResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserAdminResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsAdmin

`func (o *UserAdminResponseDto) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *UserAdminResponseDto) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *UserAdminResponseDto) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.


### GetLicense

`func (o *UserAdminResponseDto) GetLicense() UserLicense`

GetLicense returns the License field if non-nil, zero value otherwise.

### GetLicenseOk

`func (o *UserAdminResponseDto) GetLicenseOk() (*UserLicense, bool)`

GetLicenseOk returns a tuple with the License field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicense

`func (o *UserAdminResponseDto) SetLicense(v UserLicense)`

SetLicense sets License field to given value.


### SetLicenseNil

`func (o *UserAdminResponseDto) SetLicenseNil(b bool)`

 SetLicenseNil sets the value for License to be an explicit nil

### UnsetLicense
`func (o *UserAdminResponseDto) UnsetLicense()`

UnsetLicense ensures that no value is present for License, not even an explicit nil
### GetName

`func (o *UserAdminResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserAdminResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserAdminResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetOauthId

`func (o *UserAdminResponseDto) GetOauthId() string`

GetOauthId returns the OauthId field if non-nil, zero value otherwise.

### GetOauthIdOk

`func (o *UserAdminResponseDto) GetOauthIdOk() (*string, bool)`

GetOauthIdOk returns a tuple with the OauthId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthId

`func (o *UserAdminResponseDto) SetOauthId(v string)`

SetOauthId sets OauthId field to given value.


### GetProfileChangedAt

`func (o *UserAdminResponseDto) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *UserAdminResponseDto) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *UserAdminResponseDto) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.


### GetProfileImagePath

`func (o *UserAdminResponseDto) GetProfileImagePath() string`

GetProfileImagePath returns the ProfileImagePath field if non-nil, zero value otherwise.

### GetProfileImagePathOk

`func (o *UserAdminResponseDto) GetProfileImagePathOk() (*string, bool)`

GetProfileImagePathOk returns a tuple with the ProfileImagePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileImagePath

`func (o *UserAdminResponseDto) SetProfileImagePath(v string)`

SetProfileImagePath sets ProfileImagePath field to given value.


### GetQuotaSizeInBytes

`func (o *UserAdminResponseDto) GetQuotaSizeInBytes() int32`

GetQuotaSizeInBytes returns the QuotaSizeInBytes field if non-nil, zero value otherwise.

### GetQuotaSizeInBytesOk

`func (o *UserAdminResponseDto) GetQuotaSizeInBytesOk() (*int32, bool)`

GetQuotaSizeInBytesOk returns a tuple with the QuotaSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaSizeInBytes

`func (o *UserAdminResponseDto) SetQuotaSizeInBytes(v int32)`

SetQuotaSizeInBytes sets QuotaSizeInBytes field to given value.


### SetQuotaSizeInBytesNil

`func (o *UserAdminResponseDto) SetQuotaSizeInBytesNil(b bool)`

 SetQuotaSizeInBytesNil sets the value for QuotaSizeInBytes to be an explicit nil

### UnsetQuotaSizeInBytes
`func (o *UserAdminResponseDto) UnsetQuotaSizeInBytes()`

UnsetQuotaSizeInBytes ensures that no value is present for QuotaSizeInBytes, not even an explicit nil
### GetQuotaUsageInBytes

`func (o *UserAdminResponseDto) GetQuotaUsageInBytes() int32`

GetQuotaUsageInBytes returns the QuotaUsageInBytes field if non-nil, zero value otherwise.

### GetQuotaUsageInBytesOk

`func (o *UserAdminResponseDto) GetQuotaUsageInBytesOk() (*int32, bool)`

GetQuotaUsageInBytesOk returns a tuple with the QuotaUsageInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaUsageInBytes

`func (o *UserAdminResponseDto) SetQuotaUsageInBytes(v int32)`

SetQuotaUsageInBytes sets QuotaUsageInBytes field to given value.


### SetQuotaUsageInBytesNil

`func (o *UserAdminResponseDto) SetQuotaUsageInBytesNil(b bool)`

 SetQuotaUsageInBytesNil sets the value for QuotaUsageInBytes to be an explicit nil

### UnsetQuotaUsageInBytes
`func (o *UserAdminResponseDto) UnsetQuotaUsageInBytes()`

UnsetQuotaUsageInBytes ensures that no value is present for QuotaUsageInBytes, not even an explicit nil
### GetShouldChangePassword

`func (o *UserAdminResponseDto) GetShouldChangePassword() bool`

GetShouldChangePassword returns the ShouldChangePassword field if non-nil, zero value otherwise.

### GetShouldChangePasswordOk

`func (o *UserAdminResponseDto) GetShouldChangePasswordOk() (*bool, bool)`

GetShouldChangePasswordOk returns a tuple with the ShouldChangePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldChangePassword

`func (o *UserAdminResponseDto) SetShouldChangePassword(v bool)`

SetShouldChangePassword sets ShouldChangePassword field to given value.


### GetStatus

`func (o *UserAdminResponseDto) GetStatus() UserStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UserAdminResponseDto) GetStatusOk() (*UserStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UserAdminResponseDto) SetStatus(v UserStatus)`

SetStatus sets Status field to given value.


### GetStorageLabel

`func (o *UserAdminResponseDto) GetStorageLabel() string`

GetStorageLabel returns the StorageLabel field if non-nil, zero value otherwise.

### GetStorageLabelOk

`func (o *UserAdminResponseDto) GetStorageLabelOk() (*string, bool)`

GetStorageLabelOk returns a tuple with the StorageLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageLabel

`func (o *UserAdminResponseDto) SetStorageLabel(v string)`

SetStorageLabel sets StorageLabel field to given value.


### SetStorageLabelNil

`func (o *UserAdminResponseDto) SetStorageLabelNil(b bool)`

 SetStorageLabelNil sets the value for StorageLabel to be an explicit nil

### UnsetStorageLabel
`func (o *UserAdminResponseDto) UnsetStorageLabel()`

UnsetStorageLabel ensures that no value is present for StorageLabel, not even an explicit nil
### GetUpdatedAt

`func (o *UserAdminResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *UserAdminResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *UserAdminResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


