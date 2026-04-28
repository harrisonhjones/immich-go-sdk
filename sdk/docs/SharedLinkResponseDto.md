# SharedLinkResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Album** | Pointer to [**AlbumResponseDto**](AlbumResponseDto.md) |  | [optional] 
**AllowDownload** | **bool** | Allow downloads | 
**AllowUpload** | **bool** | Allow uploads | 
**Assets** | [**[]AssetResponseDto**](AssetResponseDto.md) |  | 
**CreatedAt** | **time.Time** | Creation date | 
**Description** | **NullableString** | Link description | 
**ExpiresAt** | **NullableTime** | Expiration date | 
**Id** | **string** | Shared link ID | 
**Key** | **string** | Encryption key (base64url) | 
**Password** | **NullableString** | Has password | 
**ShowMetadata** | **bool** | Show metadata | 
**Slug** | **NullableString** | Custom URL slug | 
**Type** | [**SharedLinkType**](SharedLinkType.md) |  | 
**UserId** | **string** | Owner user ID | 

## Methods

### NewSharedLinkResponseDto

`func NewSharedLinkResponseDto(allowDownload bool, allowUpload bool, assets []AssetResponseDto, createdAt time.Time, description NullableString, expiresAt NullableTime, id string, key string, password NullableString, showMetadata bool, slug NullableString, type_ SharedLinkType, userId string, ) *SharedLinkResponseDto`

NewSharedLinkResponseDto instantiates a new SharedLinkResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSharedLinkResponseDtoWithDefaults

`func NewSharedLinkResponseDtoWithDefaults() *SharedLinkResponseDto`

NewSharedLinkResponseDtoWithDefaults instantiates a new SharedLinkResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbum

`func (o *SharedLinkResponseDto) GetAlbum() AlbumResponseDto`

GetAlbum returns the Album field if non-nil, zero value otherwise.

### GetAlbumOk

`func (o *SharedLinkResponseDto) GetAlbumOk() (*AlbumResponseDto, bool)`

GetAlbumOk returns a tuple with the Album field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbum

`func (o *SharedLinkResponseDto) SetAlbum(v AlbumResponseDto)`

SetAlbum sets Album field to given value.

### HasAlbum

`func (o *SharedLinkResponseDto) HasAlbum() bool`

HasAlbum returns a boolean if a field has been set.

### GetAllowDownload

`func (o *SharedLinkResponseDto) GetAllowDownload() bool`

GetAllowDownload returns the AllowDownload field if non-nil, zero value otherwise.

### GetAllowDownloadOk

`func (o *SharedLinkResponseDto) GetAllowDownloadOk() (*bool, bool)`

GetAllowDownloadOk returns a tuple with the AllowDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDownload

`func (o *SharedLinkResponseDto) SetAllowDownload(v bool)`

SetAllowDownload sets AllowDownload field to given value.


### GetAllowUpload

`func (o *SharedLinkResponseDto) GetAllowUpload() bool`

GetAllowUpload returns the AllowUpload field if non-nil, zero value otherwise.

### GetAllowUploadOk

`func (o *SharedLinkResponseDto) GetAllowUploadOk() (*bool, bool)`

GetAllowUploadOk returns a tuple with the AllowUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowUpload

`func (o *SharedLinkResponseDto) SetAllowUpload(v bool)`

SetAllowUpload sets AllowUpload field to given value.


### GetAssets

`func (o *SharedLinkResponseDto) GetAssets() []AssetResponseDto`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *SharedLinkResponseDto) GetAssetsOk() (*[]AssetResponseDto, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *SharedLinkResponseDto) SetAssets(v []AssetResponseDto)`

SetAssets sets Assets field to given value.


### GetCreatedAt

`func (o *SharedLinkResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SharedLinkResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SharedLinkResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *SharedLinkResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SharedLinkResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SharedLinkResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *SharedLinkResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SharedLinkResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExpiresAt

`func (o *SharedLinkResponseDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SharedLinkResponseDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SharedLinkResponseDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *SharedLinkResponseDto) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *SharedLinkResponseDto) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetId

`func (o *SharedLinkResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SharedLinkResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SharedLinkResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetKey

`func (o *SharedLinkResponseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *SharedLinkResponseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *SharedLinkResponseDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetPassword

`func (o *SharedLinkResponseDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SharedLinkResponseDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SharedLinkResponseDto) SetPassword(v string)`

SetPassword sets Password field to given value.


### SetPasswordNil

`func (o *SharedLinkResponseDto) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *SharedLinkResponseDto) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetShowMetadata

`func (o *SharedLinkResponseDto) GetShowMetadata() bool`

GetShowMetadata returns the ShowMetadata field if non-nil, zero value otherwise.

### GetShowMetadataOk

`func (o *SharedLinkResponseDto) GetShowMetadataOk() (*bool, bool)`

GetShowMetadataOk returns a tuple with the ShowMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowMetadata

`func (o *SharedLinkResponseDto) SetShowMetadata(v bool)`

SetShowMetadata sets ShowMetadata field to given value.


### GetSlug

`func (o *SharedLinkResponseDto) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *SharedLinkResponseDto) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *SharedLinkResponseDto) SetSlug(v string)`

SetSlug sets Slug field to given value.


### SetSlugNil

`func (o *SharedLinkResponseDto) SetSlugNil(b bool)`

 SetSlugNil sets the value for Slug to be an explicit nil

### UnsetSlug
`func (o *SharedLinkResponseDto) UnsetSlug()`

UnsetSlug ensures that no value is present for Slug, not even an explicit nil
### GetType

`func (o *SharedLinkResponseDto) GetType() SharedLinkType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SharedLinkResponseDto) GetTypeOk() (*SharedLinkType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SharedLinkResponseDto) SetType(v SharedLinkType)`

SetType sets Type field to given value.


### GetUserId

`func (o *SharedLinkResponseDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SharedLinkResponseDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SharedLinkResponseDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


