# AlbumUserAddDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to [**AlbumUserRole**](AlbumUserRole.md) |  | [optional] 
**UserId** | **string** | User ID | 

## Methods

### NewAlbumUserAddDto

`func NewAlbumUserAddDto(userId string, ) *AlbumUserAddDto`

NewAlbumUserAddDto instantiates a new AlbumUserAddDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlbumUserAddDtoWithDefaults

`func NewAlbumUserAddDtoWithDefaults() *AlbumUserAddDto`

NewAlbumUserAddDtoWithDefaults instantiates a new AlbumUserAddDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *AlbumUserAddDto) GetRole() AlbumUserRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AlbumUserAddDto) GetRoleOk() (*AlbumUserRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AlbumUserAddDto) SetRole(v AlbumUserRole)`

SetRole sets Role field to given value.

### HasRole

`func (o *AlbumUserAddDto) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetUserId

`func (o *AlbumUserAddDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AlbumUserAddDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AlbumUserAddDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


