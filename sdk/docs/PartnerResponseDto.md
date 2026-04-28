# PartnerResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarColor** | [**UserAvatarColor**](UserAvatarColor.md) |  | 
**Email** | **string** | User email | 
**Id** | **string** | User ID | 
**InTimeline** | Pointer to **bool** | Show in timeline | [optional] 
**Name** | **string** | User name | 
**ProfileChangedAt** | **time.Time** | Profile change date | 
**ProfileImagePath** | **string** | Profile image path | 

## Methods

### NewPartnerResponseDto

`func NewPartnerResponseDto(avatarColor UserAvatarColor, email string, id string, name string, profileChangedAt time.Time, profileImagePath string, ) *PartnerResponseDto`

NewPartnerResponseDto instantiates a new PartnerResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerResponseDtoWithDefaults

`func NewPartnerResponseDtoWithDefaults() *PartnerResponseDto`

NewPartnerResponseDtoWithDefaults instantiates a new PartnerResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarColor

`func (o *PartnerResponseDto) GetAvatarColor() UserAvatarColor`

GetAvatarColor returns the AvatarColor field if non-nil, zero value otherwise.

### GetAvatarColorOk

`func (o *PartnerResponseDto) GetAvatarColorOk() (*UserAvatarColor, bool)`

GetAvatarColorOk returns a tuple with the AvatarColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarColor

`func (o *PartnerResponseDto) SetAvatarColor(v UserAvatarColor)`

SetAvatarColor sets AvatarColor field to given value.


### GetEmail

`func (o *PartnerResponseDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PartnerResponseDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PartnerResponseDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetId

`func (o *PartnerResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartnerResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartnerResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetInTimeline

`func (o *PartnerResponseDto) GetInTimeline() bool`

GetInTimeline returns the InTimeline field if non-nil, zero value otherwise.

### GetInTimelineOk

`func (o *PartnerResponseDto) GetInTimelineOk() (*bool, bool)`

GetInTimelineOk returns a tuple with the InTimeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInTimeline

`func (o *PartnerResponseDto) SetInTimeline(v bool)`

SetInTimeline sets InTimeline field to given value.

### HasInTimeline

`func (o *PartnerResponseDto) HasInTimeline() bool`

HasInTimeline returns a boolean if a field has been set.

### GetName

`func (o *PartnerResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartnerResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartnerResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetProfileChangedAt

`func (o *PartnerResponseDto) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *PartnerResponseDto) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *PartnerResponseDto) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.


### GetProfileImagePath

`func (o *PartnerResponseDto) GetProfileImagePath() string`

GetProfileImagePath returns the ProfileImagePath field if non-nil, zero value otherwise.

### GetProfileImagePathOk

`func (o *PartnerResponseDto) GetProfileImagePathOk() (*string, bool)`

GetProfileImagePathOk returns a tuple with the ProfileImagePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileImagePath

`func (o *PartnerResponseDto) SetProfileImagePath(v string)`

SetProfileImagePath sets ProfileImagePath field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


