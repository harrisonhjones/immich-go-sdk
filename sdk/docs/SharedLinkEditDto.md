# SharedLinkEditDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowDownload** | Pointer to **bool** | Allow downloads | [optional] 
**AllowUpload** | Pointer to **bool** | Allow uploads | [optional] 
**ChangeExpiryTime** | Pointer to **bool** | Whether to change the expiry time. Few clients cannot send null to set the expiryTime to never. Setting this flag and not sending expiryAt is considered as null instead. Clients that can send null values can ignore this. | [optional] 
**Description** | Pointer to **NullableString** | Link description | [optional] 
**ExpiresAt** | Pointer to **NullableTime** | Expiration date | [optional] 
**Password** | Pointer to **NullableString** | Link password | [optional] 
**ShowMetadata** | Pointer to **bool** | Show metadata | [optional] 
**Slug** | Pointer to **NullableString** | Custom URL slug | [optional] 

## Methods

### NewSharedLinkEditDto

`func NewSharedLinkEditDto() *SharedLinkEditDto`

NewSharedLinkEditDto instantiates a new SharedLinkEditDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSharedLinkEditDtoWithDefaults

`func NewSharedLinkEditDtoWithDefaults() *SharedLinkEditDto`

NewSharedLinkEditDtoWithDefaults instantiates a new SharedLinkEditDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowDownload

`func (o *SharedLinkEditDto) GetAllowDownload() bool`

GetAllowDownload returns the AllowDownload field if non-nil, zero value otherwise.

### GetAllowDownloadOk

`func (o *SharedLinkEditDto) GetAllowDownloadOk() (*bool, bool)`

GetAllowDownloadOk returns a tuple with the AllowDownload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDownload

`func (o *SharedLinkEditDto) SetAllowDownload(v bool)`

SetAllowDownload sets AllowDownload field to given value.

### HasAllowDownload

`func (o *SharedLinkEditDto) HasAllowDownload() bool`

HasAllowDownload returns a boolean if a field has been set.

### GetAllowUpload

`func (o *SharedLinkEditDto) GetAllowUpload() bool`

GetAllowUpload returns the AllowUpload field if non-nil, zero value otherwise.

### GetAllowUploadOk

`func (o *SharedLinkEditDto) GetAllowUploadOk() (*bool, bool)`

GetAllowUploadOk returns a tuple with the AllowUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowUpload

`func (o *SharedLinkEditDto) SetAllowUpload(v bool)`

SetAllowUpload sets AllowUpload field to given value.

### HasAllowUpload

`func (o *SharedLinkEditDto) HasAllowUpload() bool`

HasAllowUpload returns a boolean if a field has been set.

### GetChangeExpiryTime

`func (o *SharedLinkEditDto) GetChangeExpiryTime() bool`

GetChangeExpiryTime returns the ChangeExpiryTime field if non-nil, zero value otherwise.

### GetChangeExpiryTimeOk

`func (o *SharedLinkEditDto) GetChangeExpiryTimeOk() (*bool, bool)`

GetChangeExpiryTimeOk returns a tuple with the ChangeExpiryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeExpiryTime

`func (o *SharedLinkEditDto) SetChangeExpiryTime(v bool)`

SetChangeExpiryTime sets ChangeExpiryTime field to given value.

### HasChangeExpiryTime

`func (o *SharedLinkEditDto) HasChangeExpiryTime() bool`

HasChangeExpiryTime returns a boolean if a field has been set.

### GetDescription

`func (o *SharedLinkEditDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SharedLinkEditDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SharedLinkEditDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SharedLinkEditDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *SharedLinkEditDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SharedLinkEditDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExpiresAt

`func (o *SharedLinkEditDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SharedLinkEditDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SharedLinkEditDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *SharedLinkEditDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *SharedLinkEditDto) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *SharedLinkEditDto) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetPassword

`func (o *SharedLinkEditDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SharedLinkEditDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SharedLinkEditDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *SharedLinkEditDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *SharedLinkEditDto) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *SharedLinkEditDto) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil
### GetShowMetadata

`func (o *SharedLinkEditDto) GetShowMetadata() bool`

GetShowMetadata returns the ShowMetadata field if non-nil, zero value otherwise.

### GetShowMetadataOk

`func (o *SharedLinkEditDto) GetShowMetadataOk() (*bool, bool)`

GetShowMetadataOk returns a tuple with the ShowMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowMetadata

`func (o *SharedLinkEditDto) SetShowMetadata(v bool)`

SetShowMetadata sets ShowMetadata field to given value.

### HasShowMetadata

`func (o *SharedLinkEditDto) HasShowMetadata() bool`

HasShowMetadata returns a boolean if a field has been set.

### GetSlug

`func (o *SharedLinkEditDto) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *SharedLinkEditDto) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *SharedLinkEditDto) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *SharedLinkEditDto) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### SetSlugNil

`func (o *SharedLinkEditDto) SetSlugNil(b bool)`

 SetSlugNil sets the value for Slug to be an explicit nil

### UnsetSlug
`func (o *SharedLinkEditDto) UnsetSlug()`

UnsetSlug ensures that no value is present for Slug, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


