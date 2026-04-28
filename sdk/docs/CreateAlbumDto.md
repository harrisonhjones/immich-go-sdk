# CreateAlbumDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumName** | **string** | Album name | 
**AlbumUsers** | Pointer to [**[]AlbumUserCreateDto**](AlbumUserCreateDto.md) | Album users | [optional] 
**AssetIds** | Pointer to **[]string** | Initial asset IDs | [optional] 
**Description** | Pointer to **string** | Album description | [optional] 

## Methods

### NewCreateAlbumDto

`func NewCreateAlbumDto(albumName string, ) *CreateAlbumDto`

NewCreateAlbumDto instantiates a new CreateAlbumDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlbumDtoWithDefaults

`func NewCreateAlbumDtoWithDefaults() *CreateAlbumDto`

NewCreateAlbumDtoWithDefaults instantiates a new CreateAlbumDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumName

`func (o *CreateAlbumDto) GetAlbumName() string`

GetAlbumName returns the AlbumName field if non-nil, zero value otherwise.

### GetAlbumNameOk

`func (o *CreateAlbumDto) GetAlbumNameOk() (*string, bool)`

GetAlbumNameOk returns a tuple with the AlbumName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumName

`func (o *CreateAlbumDto) SetAlbumName(v string)`

SetAlbumName sets AlbumName field to given value.


### GetAlbumUsers

`func (o *CreateAlbumDto) GetAlbumUsers() []AlbumUserCreateDto`

GetAlbumUsers returns the AlbumUsers field if non-nil, zero value otherwise.

### GetAlbumUsersOk

`func (o *CreateAlbumDto) GetAlbumUsersOk() (*[]AlbumUserCreateDto, bool)`

GetAlbumUsersOk returns a tuple with the AlbumUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumUsers

`func (o *CreateAlbumDto) SetAlbumUsers(v []AlbumUserCreateDto)`

SetAlbumUsers sets AlbumUsers field to given value.

### HasAlbumUsers

`func (o *CreateAlbumDto) HasAlbumUsers() bool`

HasAlbumUsers returns a boolean if a field has been set.

### GetAssetIds

`func (o *CreateAlbumDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *CreateAlbumDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *CreateAlbumDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.

### HasAssetIds

`func (o *CreateAlbumDto) HasAssetIds() bool`

HasAssetIds returns a boolean if a field has been set.

### GetDescription

`func (o *CreateAlbumDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAlbumDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAlbumDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAlbumDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


