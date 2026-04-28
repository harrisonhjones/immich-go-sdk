# SyncAlbumUserV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumId** | **string** | Album ID | 
**Role** | [**AlbumUserRole**](AlbumUserRole.md) |  | 
**UserId** | **string** | User ID | 

## Methods

### NewSyncAlbumUserV1

`func NewSyncAlbumUserV1(albumId string, role AlbumUserRole, userId string, ) *SyncAlbumUserV1`

NewSyncAlbumUserV1 instantiates a new SyncAlbumUserV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAlbumUserV1WithDefaults

`func NewSyncAlbumUserV1WithDefaults() *SyncAlbumUserV1`

NewSyncAlbumUserV1WithDefaults instantiates a new SyncAlbumUserV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumId

`func (o *SyncAlbumUserV1) GetAlbumId() string`

GetAlbumId returns the AlbumId field if non-nil, zero value otherwise.

### GetAlbumIdOk

`func (o *SyncAlbumUserV1) GetAlbumIdOk() (*string, bool)`

GetAlbumIdOk returns a tuple with the AlbumId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumId

`func (o *SyncAlbumUserV1) SetAlbumId(v string)`

SetAlbumId sets AlbumId field to given value.


### GetRole

`func (o *SyncAlbumUserV1) GetRole() AlbumUserRole`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *SyncAlbumUserV1) GetRoleOk() (*AlbumUserRole, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *SyncAlbumUserV1) SetRole(v AlbumUserRole)`

SetRole sets Role field to given value.


### GetUserId

`func (o *SyncAlbumUserV1) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SyncAlbumUserV1) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SyncAlbumUserV1) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


