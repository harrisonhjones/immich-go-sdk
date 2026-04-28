# AlbumUserResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | [**AlbumUserRole**](AlbumUserRole.md) |  | 
**User** | [**UserResponseDto**](UserResponseDto.md) |  | 

## Methods

### NewAlbumUserResponseDto

`func NewAlbumUserResponseDto(role AlbumUserRole, user UserResponseDto, ) *AlbumUserResponseDto`

NewAlbumUserResponseDto instantiates a new AlbumUserResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlbumUserResponseDtoWithDefaults

`func NewAlbumUserResponseDtoWithDefaults() *AlbumUserResponseDto`

NewAlbumUserResponseDtoWithDefaults instantiates a new AlbumUserResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *AlbumUserResponseDto) GetRole() AlbumUserRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AlbumUserResponseDto) GetRoleOk() (*AlbumUserRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AlbumUserResponseDto) SetRole(v AlbumUserRole)`

SetRole sets Role field to given value.


### GetUser

`func (o *AlbumUserResponseDto) GetUser() UserResponseDto`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *AlbumUserResponseDto) GetUserOk() (*UserResponseDto, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *AlbumUserResponseDto) SetUser(v UserResponseDto)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


