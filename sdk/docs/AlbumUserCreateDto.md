# AlbumUserCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | [**AlbumUserRole**](AlbumUserRole.md) |  | 
**UserId** | **string** | User ID | 

## Methods

### NewAlbumUserCreateDto

`func NewAlbumUserCreateDto(role AlbumUserRole, userId string, ) *AlbumUserCreateDto`

NewAlbumUserCreateDto instantiates a new AlbumUserCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlbumUserCreateDtoWithDefaults

`func NewAlbumUserCreateDtoWithDefaults() *AlbumUserCreateDto`

NewAlbumUserCreateDtoWithDefaults instantiates a new AlbumUserCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *AlbumUserCreateDto) GetRole() AlbumUserRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AlbumUserCreateDto) GetRoleOk() (*AlbumUserRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AlbumUserCreateDto) SetRole(v AlbumUserRole)`

SetRole sets Role field to given value.


### GetUserId

`func (o *AlbumUserCreateDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AlbumUserCreateDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AlbumUserCreateDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


