# AssetResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checksum** | **string** | Base64 encoded SHA1 hash | 
**CreatedAt** | **time.Time** | The UTC timestamp when the asset was originally uploaded to Immich. | 
**DuplicateId** | Pointer to **NullableString** | Duplicate group ID | [optional] 
**Duration** | **NullableInt32** | Video/gif duration in milliseconds (null for static images) | 
**ExifInfo** | Pointer to [**ExifResponseDto**](ExifResponseDto.md) |  | [optional] 
**FileCreatedAt** | **time.Time** | The actual UTC timestamp when the file was created/captured, preserving timezone information. This is the authoritative timestamp for chronological sorting within timeline groups. Combined with timezone data, this can be used to determine the exact moment the photo was taken. | 
**FileModifiedAt** | **time.Time** | The UTC timestamp when the file was last modified on the filesystem. This reflects the last time the physical file was changed, which may be different from when the photo was originally taken. | 
**HasMetadata** | **bool** | Whether asset has metadata | 
**Height** | **NullableInt32** | Asset height | 
**Id** | **string** | Asset ID | 
**IsArchived** | **bool** | Is archived | 
**IsEdited** | **bool** | Is edited | 
**IsFavorite** | **bool** | Is favorite | 
**IsOffline** | **bool** | Is offline | 
**IsTrashed** | **bool** | Is trashed | 
**LibraryId** | Pointer to **NullableString** | Library ID | [optional] 
**LivePhotoVideoId** | Pointer to **NullableString** | Live photo video ID | [optional] 
**LocalDateTime** | **time.Time** | The local date and time when the photo/video was taken, derived from EXIF metadata. This represents the photographer&#39;s local time regardless of timezone, stored as a timezone-agnostic timestamp. Used for timeline grouping by \&quot;local\&quot; days and months. | 
**OriginalFileName** | **string** | Original file name | 
**OriginalMimeType** | Pointer to **string** | Original MIME type | [optional] 
**OriginalPath** | **string** | Original file path | 
**Owner** | Pointer to [**UserResponseDto**](UserResponseDto.md) |  | [optional] 
**OwnerId** | **string** | Owner user ID | 
**People** | Pointer to [**[]PersonWithFacesResponseDto**](PersonWithFacesResponseDto.md) |  | [optional] 
**Resized** | Pointer to **bool** | Is resized | [optional] 
**Stack** | Pointer to [**NullableAssetStackResponseDto**](AssetStackResponseDto.md) |  | [optional] 
**Tags** | Pointer to [**[]TagResponseDto**](TagResponseDto.md) |  | [optional] 
**Thumbhash** | **NullableString** | Thumbhash for thumbnail generation (base64) also used as the c query param for thumbnail cache busting. | 
**Type** | [**AssetTypeEnum**](AssetTypeEnum.md) |  | 
**UnassignedFaces** | Pointer to [**[]AssetFaceWithoutPersonResponseDto**](AssetFaceWithoutPersonResponseDto.md) |  | [optional] 
**UpdatedAt** | **time.Time** | The UTC timestamp when the asset record was last updated in the database. This is automatically maintained by the database and reflects when any field in the asset was last modified. | 
**Visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 
**Width** | **NullableInt32** | Asset width | 

## Methods

### NewAssetResponseDto

`func NewAssetResponseDto(checksum string, createdAt time.Time, duration NullableInt32, fileCreatedAt time.Time, fileModifiedAt time.Time, hasMetadata bool, height NullableInt32, id string, isArchived bool, isEdited bool, isFavorite bool, isOffline bool, isTrashed bool, localDateTime time.Time, originalFileName string, originalPath string, ownerId string, thumbhash NullableString, type_ AssetTypeEnum, updatedAt time.Time, visibility AssetVisibility, width NullableInt32, ) *AssetResponseDto`

NewAssetResponseDto instantiates a new AssetResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetResponseDtoWithDefaults

`func NewAssetResponseDtoWithDefaults() *AssetResponseDto`

NewAssetResponseDtoWithDefaults instantiates a new AssetResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksum

`func (o *AssetResponseDto) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *AssetResponseDto) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *AssetResponseDto) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.


### GetCreatedAt

`func (o *AssetResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AssetResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AssetResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDuplicateId

`func (o *AssetResponseDto) GetDuplicateId() string`

GetDuplicateId returns the DuplicateId field if non-nil, zero value otherwise.

### GetDuplicateIdOk

`func (o *AssetResponseDto) GetDuplicateIdOk() (*string, bool)`

GetDuplicateIdOk returns a tuple with the DuplicateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateId

`func (o *AssetResponseDto) SetDuplicateId(v string)`

SetDuplicateId sets DuplicateId field to given value.

### HasDuplicateId

`func (o *AssetResponseDto) HasDuplicateId() bool`

HasDuplicateId returns a boolean if a field has been set.

### SetDuplicateIdNil

`func (o *AssetResponseDto) SetDuplicateIdNil(b bool)`

 SetDuplicateIdNil sets the value for DuplicateId to be an explicit nil

### UnsetDuplicateId
`func (o *AssetResponseDto) UnsetDuplicateId()`

UnsetDuplicateId ensures that no value is present for DuplicateId, not even an explicit nil
### GetDuration

`func (o *AssetResponseDto) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *AssetResponseDto) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *AssetResponseDto) SetDuration(v int32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *AssetResponseDto) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *AssetResponseDto) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetExifInfo

`func (o *AssetResponseDto) GetExifInfo() ExifResponseDto`

GetExifInfo returns the ExifInfo field if non-nil, zero value otherwise.

### GetExifInfoOk

`func (o *AssetResponseDto) GetExifInfoOk() (*ExifResponseDto, bool)`

GetExifInfoOk returns a tuple with the ExifInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExifInfo

`func (o *AssetResponseDto) SetExifInfo(v ExifResponseDto)`

SetExifInfo sets ExifInfo field to given value.

### HasExifInfo

`func (o *AssetResponseDto) HasExifInfo() bool`

HasExifInfo returns a boolean if a field has been set.

### GetFileCreatedAt

`func (o *AssetResponseDto) GetFileCreatedAt() time.Time`

GetFileCreatedAt returns the FileCreatedAt field if non-nil, zero value otherwise.

### GetFileCreatedAtOk

`func (o *AssetResponseDto) GetFileCreatedAtOk() (*time.Time, bool)`

GetFileCreatedAtOk returns a tuple with the FileCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCreatedAt

`func (o *AssetResponseDto) SetFileCreatedAt(v time.Time)`

SetFileCreatedAt sets FileCreatedAt field to given value.


### GetFileModifiedAt

`func (o *AssetResponseDto) GetFileModifiedAt() time.Time`

GetFileModifiedAt returns the FileModifiedAt field if non-nil, zero value otherwise.

### GetFileModifiedAtOk

`func (o *AssetResponseDto) GetFileModifiedAtOk() (*time.Time, bool)`

GetFileModifiedAtOk returns a tuple with the FileModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileModifiedAt

`func (o *AssetResponseDto) SetFileModifiedAt(v time.Time)`

SetFileModifiedAt sets FileModifiedAt field to given value.


### GetHasMetadata

`func (o *AssetResponseDto) GetHasMetadata() bool`

GetHasMetadata returns the HasMetadata field if non-nil, zero value otherwise.

### GetHasMetadataOk

`func (o *AssetResponseDto) GetHasMetadataOk() (*bool, bool)`

GetHasMetadataOk returns a tuple with the HasMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMetadata

`func (o *AssetResponseDto) SetHasMetadata(v bool)`

SetHasMetadata sets HasMetadata field to given value.


### GetHeight

`func (o *AssetResponseDto) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *AssetResponseDto) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *AssetResponseDto) SetHeight(v int32)`

SetHeight sets Height field to given value.


### SetHeightNil

`func (o *AssetResponseDto) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *AssetResponseDto) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetId

`func (o *AssetResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsArchived

`func (o *AssetResponseDto) GetIsArchived() bool`

GetIsArchived returns the IsArchived field if non-nil, zero value otherwise.

### GetIsArchivedOk

`func (o *AssetResponseDto) GetIsArchivedOk() (*bool, bool)`

GetIsArchivedOk returns a tuple with the IsArchived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsArchived

`func (o *AssetResponseDto) SetIsArchived(v bool)`

SetIsArchived sets IsArchived field to given value.


### GetIsEdited

`func (o *AssetResponseDto) GetIsEdited() bool`

GetIsEdited returns the IsEdited field if non-nil, zero value otherwise.

### GetIsEditedOk

`func (o *AssetResponseDto) GetIsEditedOk() (*bool, bool)`

GetIsEditedOk returns a tuple with the IsEdited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEdited

`func (o *AssetResponseDto) SetIsEdited(v bool)`

SetIsEdited sets IsEdited field to given value.


### GetIsFavorite

`func (o *AssetResponseDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *AssetResponseDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *AssetResponseDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.


### GetIsOffline

`func (o *AssetResponseDto) GetIsOffline() bool`

GetIsOffline returns the IsOffline field if non-nil, zero value otherwise.

### GetIsOfflineOk

`func (o *AssetResponseDto) GetIsOfflineOk() (*bool, bool)`

GetIsOfflineOk returns a tuple with the IsOffline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOffline

`func (o *AssetResponseDto) SetIsOffline(v bool)`

SetIsOffline sets IsOffline field to given value.


### GetIsTrashed

`func (o *AssetResponseDto) GetIsTrashed() bool`

GetIsTrashed returns the IsTrashed field if non-nil, zero value otherwise.

### GetIsTrashedOk

`func (o *AssetResponseDto) GetIsTrashedOk() (*bool, bool)`

GetIsTrashedOk returns a tuple with the IsTrashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrashed

`func (o *AssetResponseDto) SetIsTrashed(v bool)`

SetIsTrashed sets IsTrashed field to given value.


### GetLibraryId

`func (o *AssetResponseDto) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *AssetResponseDto) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *AssetResponseDto) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.

### HasLibraryId

`func (o *AssetResponseDto) HasLibraryId() bool`

HasLibraryId returns a boolean if a field has been set.

### SetLibraryIdNil

`func (o *AssetResponseDto) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *AssetResponseDto) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetLivePhotoVideoId

`func (o *AssetResponseDto) GetLivePhotoVideoId() string`

GetLivePhotoVideoId returns the LivePhotoVideoId field if non-nil, zero value otherwise.

### GetLivePhotoVideoIdOk

`func (o *AssetResponseDto) GetLivePhotoVideoIdOk() (*string, bool)`

GetLivePhotoVideoIdOk returns a tuple with the LivePhotoVideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivePhotoVideoId

`func (o *AssetResponseDto) SetLivePhotoVideoId(v string)`

SetLivePhotoVideoId sets LivePhotoVideoId field to given value.

### HasLivePhotoVideoId

`func (o *AssetResponseDto) HasLivePhotoVideoId() bool`

HasLivePhotoVideoId returns a boolean if a field has been set.

### SetLivePhotoVideoIdNil

`func (o *AssetResponseDto) SetLivePhotoVideoIdNil(b bool)`

 SetLivePhotoVideoIdNil sets the value for LivePhotoVideoId to be an explicit nil

### UnsetLivePhotoVideoId
`func (o *AssetResponseDto) UnsetLivePhotoVideoId()`

UnsetLivePhotoVideoId ensures that no value is present for LivePhotoVideoId, not even an explicit nil
### GetLocalDateTime

`func (o *AssetResponseDto) GetLocalDateTime() time.Time`

GetLocalDateTime returns the LocalDateTime field if non-nil, zero value otherwise.

### GetLocalDateTimeOk

`func (o *AssetResponseDto) GetLocalDateTimeOk() (*time.Time, bool)`

GetLocalDateTimeOk returns a tuple with the LocalDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalDateTime

`func (o *AssetResponseDto) SetLocalDateTime(v time.Time)`

SetLocalDateTime sets LocalDateTime field to given value.


### GetOriginalFileName

`func (o *AssetResponseDto) GetOriginalFileName() string`

GetOriginalFileName returns the OriginalFileName field if non-nil, zero value otherwise.

### GetOriginalFileNameOk

`func (o *AssetResponseDto) GetOriginalFileNameOk() (*string, bool)`

GetOriginalFileNameOk returns a tuple with the OriginalFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFileName

`func (o *AssetResponseDto) SetOriginalFileName(v string)`

SetOriginalFileName sets OriginalFileName field to given value.


### GetOriginalMimeType

`func (o *AssetResponseDto) GetOriginalMimeType() string`

GetOriginalMimeType returns the OriginalMimeType field if non-nil, zero value otherwise.

### GetOriginalMimeTypeOk

`func (o *AssetResponseDto) GetOriginalMimeTypeOk() (*string, bool)`

GetOriginalMimeTypeOk returns a tuple with the OriginalMimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalMimeType

`func (o *AssetResponseDto) SetOriginalMimeType(v string)`

SetOriginalMimeType sets OriginalMimeType field to given value.

### HasOriginalMimeType

`func (o *AssetResponseDto) HasOriginalMimeType() bool`

HasOriginalMimeType returns a boolean if a field has been set.

### GetOriginalPath

`func (o *AssetResponseDto) GetOriginalPath() string`

GetOriginalPath returns the OriginalPath field if non-nil, zero value otherwise.

### GetOriginalPathOk

`func (o *AssetResponseDto) GetOriginalPathOk() (*string, bool)`

GetOriginalPathOk returns a tuple with the OriginalPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPath

`func (o *AssetResponseDto) SetOriginalPath(v string)`

SetOriginalPath sets OriginalPath field to given value.


### GetOwner

`func (o *AssetResponseDto) GetOwner() UserResponseDto`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *AssetResponseDto) GetOwnerOk() (*UserResponseDto, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *AssetResponseDto) SetOwner(v UserResponseDto)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *AssetResponseDto) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### GetOwnerId

`func (o *AssetResponseDto) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *AssetResponseDto) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *AssetResponseDto) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetPeople

`func (o *AssetResponseDto) GetPeople() []PersonWithFacesResponseDto`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *AssetResponseDto) GetPeopleOk() (*[]PersonWithFacesResponseDto, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *AssetResponseDto) SetPeople(v []PersonWithFacesResponseDto)`

SetPeople sets People field to given value.

### HasPeople

`func (o *AssetResponseDto) HasPeople() bool`

HasPeople returns a boolean if a field has been set.

### GetResized

`func (o *AssetResponseDto) GetResized() bool`

GetResized returns the Resized field if non-nil, zero value otherwise.

### GetResizedOk

`func (o *AssetResponseDto) GetResizedOk() (*bool, bool)`

GetResizedOk returns a tuple with the Resized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResized

`func (o *AssetResponseDto) SetResized(v bool)`

SetResized sets Resized field to given value.

### HasResized

`func (o *AssetResponseDto) HasResized() bool`

HasResized returns a boolean if a field has been set.

### GetStack

`func (o *AssetResponseDto) GetStack() AssetStackResponseDto`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *AssetResponseDto) GetStackOk() (*AssetStackResponseDto, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *AssetResponseDto) SetStack(v AssetStackResponseDto)`

SetStack sets Stack field to given value.

### HasStack

`func (o *AssetResponseDto) HasStack() bool`

HasStack returns a boolean if a field has been set.

### SetStackNil

`func (o *AssetResponseDto) SetStackNil(b bool)`

 SetStackNil sets the value for Stack to be an explicit nil

### UnsetStack
`func (o *AssetResponseDto) UnsetStack()`

UnsetStack ensures that no value is present for Stack, not even an explicit nil
### GetTags

`func (o *AssetResponseDto) GetTags() []TagResponseDto`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *AssetResponseDto) GetTagsOk() (*[]TagResponseDto, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *AssetResponseDto) SetTags(v []TagResponseDto)`

SetTags sets Tags field to given value.

### HasTags

`func (o *AssetResponseDto) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetThumbhash

`func (o *AssetResponseDto) GetThumbhash() string`

GetThumbhash returns the Thumbhash field if non-nil, zero value otherwise.

### GetThumbhashOk

`func (o *AssetResponseDto) GetThumbhashOk() (*string, bool)`

GetThumbhashOk returns a tuple with the Thumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbhash

`func (o *AssetResponseDto) SetThumbhash(v string)`

SetThumbhash sets Thumbhash field to given value.


### SetThumbhashNil

`func (o *AssetResponseDto) SetThumbhashNil(b bool)`

 SetThumbhashNil sets the value for Thumbhash to be an explicit nil

### UnsetThumbhash
`func (o *AssetResponseDto) UnsetThumbhash()`

UnsetThumbhash ensures that no value is present for Thumbhash, not even an explicit nil
### GetType

`func (o *AssetResponseDto) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AssetResponseDto) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AssetResponseDto) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.


### GetUnassignedFaces

`func (o *AssetResponseDto) GetUnassignedFaces() []AssetFaceWithoutPersonResponseDto`

GetUnassignedFaces returns the UnassignedFaces field if non-nil, zero value otherwise.

### GetUnassignedFacesOk

`func (o *AssetResponseDto) GetUnassignedFacesOk() (*[]AssetFaceWithoutPersonResponseDto, bool)`

GetUnassignedFacesOk returns a tuple with the UnassignedFaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnassignedFaces

`func (o *AssetResponseDto) SetUnassignedFaces(v []AssetFaceWithoutPersonResponseDto)`

SetUnassignedFaces sets UnassignedFaces field to given value.

### HasUnassignedFaces

`func (o *AssetResponseDto) HasUnassignedFaces() bool`

HasUnassignedFaces returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *AssetResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AssetResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AssetResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVisibility

`func (o *AssetResponseDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *AssetResponseDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *AssetResponseDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.


### GetWidth

`func (o *AssetResponseDto) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *AssetResponseDto) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *AssetResponseDto) SetWidth(v int32)`

SetWidth sets Width field to given value.


### SetWidthNil

`func (o *AssetResponseDto) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *AssetResponseDto) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


