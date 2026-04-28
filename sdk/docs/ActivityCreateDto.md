# ActivityCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumId** | **string** | Album ID | 
**AssetId** | Pointer to **string** | Asset ID (if activity is for an asset) | [optional] 
**Comment** | Pointer to **string** | Comment text (required if type is comment) | [optional] 
**Type** | [**ReactionType**](ReactionType.md) |  | 

## Methods

### NewActivityCreateDto

`func NewActivityCreateDto(albumId string, type_ ReactionType, ) *ActivityCreateDto`

NewActivityCreateDto instantiates a new ActivityCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityCreateDtoWithDefaults

`func NewActivityCreateDtoWithDefaults() *ActivityCreateDto`

NewActivityCreateDtoWithDefaults instantiates a new ActivityCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumId

`func (o *ActivityCreateDto) GetAlbumId() string`

GetAlbumId returns the AlbumId field if non-nil, zero value otherwise.

### GetAlbumIdOk

`func (o *ActivityCreateDto) GetAlbumIdOk() (*string, bool)`

GetAlbumIdOk returns a tuple with the AlbumId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumId

`func (o *ActivityCreateDto) SetAlbumId(v string)`

SetAlbumId sets AlbumId field to given value.


### GetAssetId

`func (o *ActivityCreateDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *ActivityCreateDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *ActivityCreateDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *ActivityCreateDto) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetComment

`func (o *ActivityCreateDto) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ActivityCreateDto) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ActivityCreateDto) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ActivityCreateDto) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetType

`func (o *ActivityCreateDto) GetType() ReactionType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ActivityCreateDto) GetTypeOk() (*ReactionType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ActivityCreateDto) SetType(v ReactionType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


