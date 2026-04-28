# SharedLinkCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumId** | Pointer to **string** | Album ID (for album sharing) | [optional] 
**AllowDownload** | Pointer to **bool** | Allow downloads | [optional] [default to true]
**AllowUpload** | Pointer to **bool** | Allow uploads | [optional] 
**AssetIds** | Pointer to **[]string** | Asset IDs (for individual assets) | [optional] 
**Description** | Pointer to **NullableString** | Link description | [optional] 
**ExpiresAt** | Pointer to **NullableTime** | Expiration date | [optional] 
**Password** | Pointer to **NullableString** | Link password | [optional] 
**ShowMetadata** | Pointer to **bool** | Show metadata | [optional] [default to true]
**Slug** | Pointer to **NullableString** | Custom URL slug | [optional] 
**Type** | [**SharedLinkType**](SharedLinkType.md) |  | 

## Methods

### NewSharedLinkCreateDto

`func NewSharedLinkCreateDto(type_ SharedLinkType, ) *SharedLinkCreateDto`

NewSharedLinkCreateDto instantiates a new SharedLinkCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSharedLinkCreateDtoWithDefaults

`func NewSharedLinkCreateDtoWithDefaults() *SharedLinkCreateDto`

NewSharedLinkCreateDtoWithDefaults instantiates a new SharedLinkCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumId

`func (o *SharedLinkCreateDto) GetAlbumId() string`

GetAlbumId returns the AlbumId field if non-nil, zero value otherwise.

### GetAlbumIdOk

`func (o *SharedLinkCreateDto) GetAlbumIdOk() (*string, bool)`

GetAlbumIdOk returns a tuple with the AlbumId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumId

`func (o *SharedLinkCreateDto) SetAlbumId(v string)`

SetAlbumId sets AlbumId field to given value.

### HasAlbumId

`func (o *SharedLinkCreateDto) HasAlbumId() bool`

HasAlbumId returns a boolean if a field has been set.

### GetAllowDownload

`func (o *SharedLinkCreateDto) GetAllowDownload() bool`

GetAllowDownload returns the AllowDownload field if non-nil, zero value otherwise.

### GetAllowDownloadOk

`func (o *SharedLinkCreateDto) GetAllowDownloadOk() (*bool, bool)`

GetAllowDownloadOk returns a tuple with the AllowDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDownload

`func (o *SharedLinkCreateDto) SetAllowDownload(v bool)`

SetAllowDownload sets AllowDownload field to given value.

### HasAllowDownload

`func (o *SharedLinkCreateDto) HasAllowDownload() bool`

HasAllowDownload returns a boolean if a field has been set.

### GetAllowUpload

`func (o *SharedLinkCreateDto) GetAllowUpload() bool`

GetAllowUpload returns the AllowUpload field if non-nil, zero value otherwise.

### GetAllowUploadOk

`func (o *SharedLinkCreateDto) GetAllowUploadOk() (*bool, bool)`

GetAllowUploadOk returns a tuple with the AllowUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowUpload

`func (o *SharedLinkCreateDto) SetAllowUpload(v bool)`

SetAllowUpload sets AllowUpload field to given value.

### HasAllowUpload

`func (o *SharedLinkCreateDto) HasAllowUpload() bool`

HasAllowUpload returns a boolean if a field has been set.

### GetAssetIds

`func (o *SharedLinkCreateDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *SharedLinkCreateDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *SharedLinkCreateDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.

### HasAssetIds

`func (o *SharedLinkCreateDto) HasAssetIds() bool`

HasAssetIds returns a boolean if a field has been set.

### GetDescription

`func (o *SharedLinkCreateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SharedLinkCreateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SharedLinkCreateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SharedLinkCreateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *SharedLinkCreateDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SharedLinkCreateDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExpiresAt

`func (o *SharedLinkCreateDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SharedLinkCreateDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SharedLinkCreateDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *SharedLinkCreateDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *SharedLinkCreateDto) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *SharedLinkCreateDto) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetPassword

`func (o *SharedLinkCreateDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SharedLinkCreateDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SharedLinkCreateDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *SharedLinkCreateDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *SharedLinkCreateDto) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *SharedLinkCreateDto) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetShowMetadata

`func (o *SharedLinkCreateDto) GetShowMetadata() bool`

GetShowMetadata returns the ShowMetadata field if non-nil, zero value otherwise.

### GetShowMetadataOk

`func (o *SharedLinkCreateDto) GetShowMetadataOk() (*bool, bool)`

GetShowMetadataOk returns a tuple with the ShowMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowMetadata

`func (o *SharedLinkCreateDto) SetShowMetadata(v bool)`

SetShowMetadata sets ShowMetadata field to given value.

### HasShowMetadata

`func (o *SharedLinkCreateDto) HasShowMetadata() bool`

HasShowMetadata returns a boolean if a field has been set.

### GetSlug

`func (o *SharedLinkCreateDto) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *SharedLinkCreateDto) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *SharedLinkCreateDto) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *SharedLinkCreateDto) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### SetSlugNil

`func (o *SharedLinkCreateDto) SetSlugNil(b bool)`

 SetSlugNil sets the value for Slug to be an explicit nil

### UnsetSlug
`func (o *SharedLinkCreateDto) UnsetSlug()`

UnsetSlug ensures that no value is present for Slug, not even an explicit nil
### GetType

`func (o *SharedLinkCreateDto) GetType() SharedLinkType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SharedLinkCreateDto) GetTypeOk() (*SharedLinkType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SharedLinkCreateDto) SetType(v SharedLinkType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


