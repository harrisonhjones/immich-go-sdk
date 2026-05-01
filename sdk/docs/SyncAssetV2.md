# SyncAssetV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checksum** | **string** | Checksum | 
**DeletedAt** | **NullableTime** | Deleted at | 
**Duration** | **NullableInt32** | Duration | 
**FileCreatedAt** | **NullableTime** | File created at | 
**FileModifiedAt** | **NullableTime** | File modified at | 
**Height** | **NullableInt32** | Asset height | 
**Id** | **string** | Asset ID | 
**IsEdited** | **bool** | Is edited | 
**IsFavorite** | **bool** | Is favorite | 
**LibraryId** | **NullableString** | Library ID | 
**LivePhotoVideoId** | **NullableString** | Live photo video ID | 
**LocalDateTime** | **NullableTime** | Local date time | 
**OriginalFileName** | **string** | Original file name | 
**OwnerId** | **string** | Owner ID | 
**StackId** | **NullableString** | Stack ID | 
**Thumbhash** | **NullableString** | Thumbhash | 
**Type** | [**AssetTypeEnum**](AssetTypeEnum.md) |  | 
**Visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 
**Width** | **NullableInt32** | Asset width | 

## Methods

### NewSyncAssetV2

`func NewSyncAssetV2(checksum string, deletedAt NullableTime, duration NullableInt32, fileCreatedAt NullableTime, fileModifiedAt NullableTime, height NullableInt32, id string, isEdited bool, isFavorite bool, libraryId NullableString, livePhotoVideoId NullableString, localDateTime NullableTime, originalFileName string, ownerId string, stackId NullableString, thumbhash NullableString, type_ AssetTypeEnum, visibility AssetVisibility, width NullableInt32, ) *SyncAssetV2`

NewSyncAssetV2 instantiates a new SyncAssetV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetV2WithDefaults

`func NewSyncAssetV2WithDefaults() *SyncAssetV2`

NewSyncAssetV2WithDefaults instantiates a new SyncAssetV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksum

`func (o *SyncAssetV2) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *SyncAssetV2) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *SyncAssetV2) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.


### GetDeletedAt

`func (o *SyncAssetV2) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncAssetV2) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncAssetV2) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncAssetV2) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncAssetV2) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetDuration

`func (o *SyncAssetV2) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *SyncAssetV2) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *SyncAssetV2) SetDuration(v int32)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *SyncAssetV2) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *SyncAssetV2) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetFileCreatedAt

`func (o *SyncAssetV2) GetFileCreatedAt() time.Time`

GetFileCreatedAt returns the FileCreatedAt field if non-nil, zero value otherwise.

### GetFileCreatedAtOk

`func (o *SyncAssetV2) GetFileCreatedAtOk() (*time.Time, bool)`

GetFileCreatedAtOk returns a tuple with the FileCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCreatedAt

`func (o *SyncAssetV2) SetFileCreatedAt(v time.Time)`

SetFileCreatedAt sets FileCreatedAt field to given value.


### SetFileCreatedAtNil

`func (o *SyncAssetV2) SetFileCreatedAtNil(b bool)`

 SetFileCreatedAtNil sets the value for FileCreatedAt to be an explicit nil

### UnsetFileCreatedAt
`func (o *SyncAssetV2) UnsetFileCreatedAt()`

UnsetFileCreatedAt ensures that no value is present for FileCreatedAt, not even an explicit nil
### GetFileModifiedAt

`func (o *SyncAssetV2) GetFileModifiedAt() time.Time`

GetFileModifiedAt returns the FileModifiedAt field if non-nil, zero value otherwise.

### GetFileModifiedAtOk

`func (o *SyncAssetV2) GetFileModifiedAtOk() (*time.Time, bool)`

GetFileModifiedAtOk returns a tuple with the FileModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileModifiedAt

`func (o *SyncAssetV2) SetFileModifiedAt(v time.Time)`

SetFileModifiedAt sets FileModifiedAt field to given value.


### SetFileModifiedAtNil

`func (o *SyncAssetV2) SetFileModifiedAtNil(b bool)`

 SetFileModifiedAtNil sets the value for FileModifiedAt to be an explicit nil

### UnsetFileModifiedAt
`func (o *SyncAssetV2) UnsetFileModifiedAt()`

UnsetFileModifiedAt ensures that no value is present for FileModifiedAt, not even an explicit nil
### GetHeight

`func (o *SyncAssetV2) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *SyncAssetV2) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *SyncAssetV2) SetHeight(v int32)`

SetHeight sets Height field to given value.


### SetHeightNil

`func (o *SyncAssetV2) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *SyncAssetV2) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetId

`func (o *SyncAssetV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAssetV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAssetV2) SetId(v string)`

SetId sets Id field to given value.


### GetIsEdited

`func (o *SyncAssetV2) GetIsEdited() bool`

GetIsEdited returns the IsEdited field if non-nil, zero value otherwise.

### GetIsEditedOk

`func (o *SyncAssetV2) GetIsEditedOk() (*bool, bool)`

GetIsEditedOk returns a tuple with the IsEdited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEdited

`func (o *SyncAssetV2) SetIsEdited(v bool)`

SetIsEdited sets IsEdited field to given value.


### GetIsFavorite

`func (o *SyncAssetV2) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *SyncAssetV2) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *SyncAssetV2) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.


### GetLibraryId

`func (o *SyncAssetV2) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *SyncAssetV2) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *SyncAssetV2) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.


### SetLibraryIdNil

`func (o *SyncAssetV2) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *SyncAssetV2) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetLivePhotoVideoId

`func (o *SyncAssetV2) GetLivePhotoVideoId() string`

GetLivePhotoVideoId returns the LivePhotoVideoId field if non-nil, zero value otherwise.

### GetLivePhotoVideoIdOk

`func (o *SyncAssetV2) GetLivePhotoVideoIdOk() (*string, bool)`

GetLivePhotoVideoIdOk returns a tuple with the LivePhotoVideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivePhotoVideoId

`func (o *SyncAssetV2) SetLivePhotoVideoId(v string)`

SetLivePhotoVideoId sets LivePhotoVideoId field to given value.


### SetLivePhotoVideoIdNil

`func (o *SyncAssetV2) SetLivePhotoVideoIdNil(b bool)`

 SetLivePhotoVideoIdNil sets the value for LivePhotoVideoId to be an explicit nil

### UnsetLivePhotoVideoId
`func (o *SyncAssetV2) UnsetLivePhotoVideoId()`

UnsetLivePhotoVideoId ensures that no value is present for LivePhotoVideoId, not even an explicit nil
### GetLocalDateTime

`func (o *SyncAssetV2) GetLocalDateTime() time.Time`

GetLocalDateTime returns the LocalDateTime field if non-nil, zero value otherwise.

### GetLocalDateTimeOk

`func (o *SyncAssetV2) GetLocalDateTimeOk() (*time.Time, bool)`

GetLocalDateTimeOk returns a tuple with the LocalDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalDateTime

`func (o *SyncAssetV2) SetLocalDateTime(v time.Time)`

SetLocalDateTime sets LocalDateTime field to given value.


### SetLocalDateTimeNil

`func (o *SyncAssetV2) SetLocalDateTimeNil(b bool)`

 SetLocalDateTimeNil sets the value for LocalDateTime to be an explicit nil

### UnsetLocalDateTime
`func (o *SyncAssetV2) UnsetLocalDateTime()`

UnsetLocalDateTime ensures that no value is present for LocalDateTime, not even an explicit nil
### GetOriginalFileName

`func (o *SyncAssetV2) GetOriginalFileName() string`

GetOriginalFileName returns the OriginalFileName field if non-nil, zero value otherwise.

### GetOriginalFileNameOk

`func (o *SyncAssetV2) GetOriginalFileNameOk() (*string, bool)`

GetOriginalFileNameOk returns a tuple with the OriginalFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFileName

`func (o *SyncAssetV2) SetOriginalFileName(v string)`

SetOriginalFileName sets OriginalFileName field to given value.


### GetOwnerId

`func (o *SyncAssetV2) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *SyncAssetV2) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *SyncAssetV2) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetStackId

`func (o *SyncAssetV2) GetStackId() string`

GetStackId returns the StackId field if non-nil, zero value otherwise.

### GetStackIdOk

`func (o *SyncAssetV2) GetStackIdOk() (*string, bool)`

GetStackIdOk returns a tuple with the StackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackId

`func (o *SyncAssetV2) SetStackId(v string)`

SetStackId sets StackId field to given value.


### SetStackIdNil

`func (o *SyncAssetV2) SetStackIdNil(b bool)`

 SetStackIdNil sets the value for StackId to be an explicit nil

### UnsetStackId
`func (o *SyncAssetV2) UnsetStackId()`

UnsetStackId ensures that no value is present for StackId, not even an explicit nil
### GetThumbhash

`func (o *SyncAssetV2) GetThumbhash() string`

GetThumbhash returns the Thumbhash field if non-nil, zero value otherwise.

### GetThumbhashOk

`func (o *SyncAssetV2) GetThumbhashOk() (*string, bool)`

GetThumbhashOk returns a tuple with the Thumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbhash

`func (o *SyncAssetV2) SetThumbhash(v string)`

SetThumbhash sets Thumbhash field to given value.


### SetThumbhashNil

`func (o *SyncAssetV2) SetThumbhashNil(b bool)`

 SetThumbhashNil sets the value for Thumbhash to be an explicit nil

### UnsetThumbhash
`func (o *SyncAssetV2) UnsetThumbhash()`

UnsetThumbhash ensures that no value is present for Thumbhash, not even an explicit nil
### GetType

`func (o *SyncAssetV2) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SyncAssetV2) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SyncAssetV2) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.


### GetVisibility

`func (o *SyncAssetV2) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *SyncAssetV2) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *SyncAssetV2) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.


### GetWidth

`func (o *SyncAssetV2) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *SyncAssetV2) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *SyncAssetV2) SetWidth(v int32)`

SetWidth sets Width field to given value.


### SetWidthNil

`func (o *SyncAssetV2) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *SyncAssetV2) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


