# AddUsersDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumUsers** | [**[]AlbumUserAddDto**](AlbumUserAddDto.md) | Album users to add | 

## Methods

### NewAddUsersDto

`func NewAddUsersDto(albumUsers []AlbumUserAddDto, ) *AddUsersDto`

NewAddUsersDto instantiates a new AddUsersDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddUsersDtoWithDefaults

`func NewAddUsersDtoWithDefaults() *AddUsersDto`

NewAddUsersDtoWithDefaults instantiates a new AddUsersDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumUsers

`func (o *AddUsersDto) GetAlbumUsers() []AlbumUserAddDto`

GetAlbumUsers returns the AlbumUsers field if non-nil, zero value otherwise.

### GetAlbumUsersOk

`func (o *AddUsersDto) GetAlbumUsersOk() (*[]AlbumUserAddDto, bool)`

GetAlbumUsersOk returns a tuple with the AlbumUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumUsers

`func (o *AddUsersDto) SetAlbumUsers(v []AlbumUserAddDto)`

SetAlbumUsers sets AlbumUsers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


