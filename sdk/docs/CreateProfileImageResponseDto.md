# CreateProfileImageResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProfileChangedAt** | **time.Time** | Profile image change date | 
**ProfileImagePath** | **string** | Profile image file path | 
**UserId** | **string** | User ID | 

## Methods

### NewCreateProfileImageResponseDto

`func NewCreateProfileImageResponseDto(profileChangedAt time.Time, profileImagePath string, userId string, ) *CreateProfileImageResponseDto`

NewCreateProfileImageResponseDto instantiates a new CreateProfileImageResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProfileImageResponseDtoWithDefaults

`func NewCreateProfileImageResponseDtoWithDefaults() *CreateProfileImageResponseDto`

NewCreateProfileImageResponseDtoWithDefaults instantiates a new CreateProfileImageResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProfileChangedAt

`func (o *CreateProfileImageResponseDto) GetProfileChangedAt() time.Time`

GetProfileChangedAt returns the ProfileChangedAt field if non-nil, zero value otherwise.

### GetProfileChangedAtOk

`func (o *CreateProfileImageResponseDto) GetProfileChangedAtOk() (*time.Time, bool)`

GetProfileChangedAtOk returns a tuple with the ProfileChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileChangedAt

`func (o *CreateProfileImageResponseDto) SetProfileChangedAt(v time.Time)`

SetProfileChangedAt sets ProfileChangedAt field to given value.


### GetProfileImagePath

`func (o *CreateProfileImageResponseDto) GetProfileImagePath() string`

GetProfileImagePath returns the ProfileImagePath field if non-nil, zero value otherwise.

### GetProfileImagePathOk

`func (o *CreateProfileImageResponseDto) GetProfileImagePathOk() (*string, bool)`

GetProfileImagePathOk returns a tuple with the ProfileImagePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileImagePath

`func (o *CreateProfileImageResponseDto) SetProfileImagePath(v string)`

SetProfileImagePath sets ProfileImagePath field to given value.


### GetUserId

`func (o *CreateProfileImageResponseDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateProfileImageResponseDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateProfileImageResponseDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


