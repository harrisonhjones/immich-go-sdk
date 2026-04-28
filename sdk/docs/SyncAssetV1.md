# SyncAssetV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checksum** | **string** | Checksum | 
**DeletedAt** | **NullableTime** | Deleted at | 
**Duration** | **NullableString** | Duration | 
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

### NewSyncAssetV1

`func NewSyncAssetV1(checksum string, deletedAt NullableTime, duration NullableString, fileCreatedAt NullableTime, fileModifiedAt NullableTime, height NullableInt32, id string, isEdited bool, isFavorite bool, libraryId NullableString, livePhotoVideoId NullableString, localDateTime NullableTime, originalFileName string, ownerId string, stackId NullableString, thumbhash NullableString, type_ AssetTypeEnum, visibility AssetVisibility, width NullableInt32, ) *SyncAssetV1`

NewSyncAssetV1 instantiates a new SyncAssetV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetV1WithDefaults

`func NewSyncAssetV1WithDefaults() *SyncAssetV1`

NewSyncAssetV1WithDefaults instantiates a new SyncAssetV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksum

`func (o *SyncAssetV1) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *SyncAssetV1) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *SyncAssetV1) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.


### GetDeletedAt

`func (o *SyncAssetV1) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncAssetV1) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncAssetV1) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncAssetV1) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncAssetV1) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetDuration

`func (o *SyncAssetV1) GetDuration() string`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *SyncAssetV1) GetDurationOk() (*string, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *SyncAssetV1) SetDuration(v string)`

SetDuration sets Duration field to given value.


### SetDurationNil

`func (o *SyncAssetV1) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *SyncAssetV1) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetFileCreatedAt

`func (o *SyncAssetV1) GetFileCreatedAt() time.Time`

GetFileCreatedAt returns the FileCreatedAt field if non-nil, zero value otherwise.

### GetFileCreatedAtOk

`func (o *SyncAssetV1) GetFileCreatedAtOk() (*time.Time, bool)`

GetFileCreatedAtOk returns a tuple with the FileCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCreatedAt

`func (o *SyncAssetV1) SetFileCreatedAt(v time.Time)`

SetFileCreatedAt sets FileCreatedAt field to given value.


### SetFileCreatedAtNil

`func (o *SyncAssetV1) SetFileCreatedAtNil(b bool)`

 SetFileCreatedAtNil sets the value for FileCreatedAt to be an explicit nil

### UnsetFileCreatedAt
`func (o *SyncAssetV1) UnsetFileCreatedAt()`

UnsetFileCreatedAt ensures that no value is present for FileCreatedAt, not even an explicit nil
### GetFileModifiedAt

`func (o *SyncAssetV1) GetFileModifiedAt() time.Time`

GetFileModifiedAt returns the FileModifiedAt field if non-nil, zero value otherwise.

### GetFileModifiedAtOk

`func (o *SyncAssetV1) GetFileModifiedAtOk() (*time.Time, bool)`

GetFileModifiedAtOk returns a tuple with the FileModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileModifiedAt

`func (o *SyncAssetV1) SetFileModifiedAt(v time.Time)`

SetFileModifiedAt sets FileModifiedAt field to given value.


### SetFileModifiedAtNil

`func (o *SyncAssetV1) SetFileModifiedAtNil(b bool)`

 SetFileModifiedAtNil sets the value for FileModifiedAt to be an explicit nil

### UnsetFileModifiedAt
`func (o *SyncAssetV1) UnsetFileModifiedAt()`

UnsetFileModifiedAt ensures that no value is present for FileModifiedAt, not even an explicit nil
### GetHeight

`func (o *SyncAssetV1) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *SyncAssetV1) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *SyncAssetV1) SetHeight(v int32)`

SetHeight sets Height field to given value.


### SetHeightNil

`func (o *SyncAssetV1) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *SyncAssetV1) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetId

`func (o *SyncAssetV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAssetV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAssetV1) SetId(v string)`

SetId sets Id field to given value.


### GetIsEdited

`func (o *SyncAssetV1) GetIsEdited() bool`

GetIsEdited returns the IsEdited field if non-nil, zero value otherwise.

### GetIsEditedOk

`func (o *SyncAssetV1) GetIsEditedOk() (*bool, bool)`

GetIsEditedOk returns a tuple with the IsEdited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEdited

`func (o *SyncAssetV1) SetIsEdited(v bool)`

SetIsEdited sets IsEdited field to given value.


### GetIsFavorite

`func (o *SyncAssetV1) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *SyncAssetV1) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *SyncAssetV1) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.


### GetLibraryId

`func (o *SyncAssetV1) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *SyncAssetV1) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *SyncAssetV1) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.


### SetLibraryIdNil

`func (o *SyncAssetV1) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *SyncAssetV1) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetLivePhotoVideoId

`func (o *SyncAssetV1) GetLivePhotoVideoId() string`

GetLivePhotoVideoId returns the LivePhotoVideoId field if non-nil, zero value otherwise.

### GetLivePhotoVideoIdOk

`func (o *SyncAssetV1) GetLivePhotoVideoIdOk() (*string, bool)`

GetLivePhotoVideoIdOk returns a tuple with the LivePhotoVideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivePhotoVideoId

`func (o *SyncAssetV1) SetLivePhotoVideoId(v string)`

SetLivePhotoVideoId sets LivePhotoVideoId field to given value.


### SetLivePhotoVideoIdNil

`func (o *SyncAssetV1) SetLivePhotoVideoIdNil(b bool)`

 SetLivePhotoVideoIdNil sets the value for LivePhotoVideoId to be an explicit nil

### UnsetLivePhotoVideoId
`func (o *SyncAssetV1) UnsetLivePhotoVideoId()`

UnsetLivePhotoVideoId ensures that no value is present for LivePhotoVideoId, not even an explicit nil
### GetLocalDateTime

`func (o *SyncAssetV1) GetLocalDateTime() time.Time`

GetLocalDateTime returns the LocalDateTime field if non-nil, zero value otherwise.

### GetLocalDateTimeOk

`func (o *SyncAssetV1) GetLocalDateTimeOk() (*time.Time, bool)`

GetLocalDateTimeOk returns a tuple with the LocalDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalDateTime

`func (o *SyncAssetV1) SetLocalDateTime(v time.Time)`

SetLocalDateTime sets LocalDateTime field to given value.


### SetLocalDateTimeNil

`func (o *SyncAssetV1) SetLocalDateTimeNil(b bool)`

 SetLocalDateTimeNil sets the value for LocalDateTime to be an explicit nil

### UnsetLocalDateTime
`func (o *SyncAssetV1) UnsetLocalDateTime()`

UnsetLocalDateTime ensures that no value is present for LocalDateTime, not even an explicit nil
### GetOriginalFileName

`func (o *SyncAssetV1) GetOriginalFileName() string`

GetOriginalFileName returns the OriginalFileName field if non-nil, zero value otherwise.

### GetOriginalFileNameOk

`func (o *SyncAssetV1) GetOriginalFileNameOk() (*string, bool)`

GetOriginalFileNameOk returns a tuple with the OriginalFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFileName

`func (o *SyncAssetV1) SetOriginalFileName(v string)`

SetOriginalFileName sets OriginalFileName field to given value.


### GetOwnerId

`func (o *SyncAssetV1) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *SyncAssetV1) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *SyncAssetV1) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetStackId

`func (o *SyncAssetV1) GetStackId() string`

GetStackId returns the StackId field if non-nil, zero value otherwise.

### GetStackIdOk

`func (o *SyncAssetV1) GetStackIdOk() (*string, bool)`

GetStackIdOk returns a tuple with the StackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStackId

`func (o *SyncAssetV1) SetStackId(v string)`

SetStackId sets StackId field to given value.


### SetStackIdNil

`func (o *SyncAssetV1) SetStackIdNil(b bool)`

 SetStackIdNil sets the value for StackId to be an explicit nil

### UnsetStackId
`func (o *SyncAssetV1) UnsetStackId()`

UnsetStackId ensures that no value is present for StackId, not even an explicit nil
### GetThumbhash

`func (o *SyncAssetV1) GetThumbhash() string`

GetThumbhash returns the Thumbhash field if non-nil, zero value otherwise.

### GetThumbhashOk

`func (o *SyncAssetV1) GetThumbhashOk() (*string, bool)`

GetThumbhashOk returns a tuple with the Thumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbhash

`func (o *SyncAssetV1) SetThumbhash(v string)`

SetThumbhash sets Thumbhash field to given value.


### SetThumbhashNil

`func (o *SyncAssetV1) SetThumbhashNil(b bool)`

 SetThumbhashNil sets the value for Thumbhash to be an explicit nil

### UnsetThumbhash
`func (o *SyncAssetV1) UnsetThumbhash()`

UnsetThumbhash ensures that no value is present for Thumbhash, not even an explicit nil
### GetType

`func (o *SyncAssetV1) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SyncAssetV1) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SyncAssetV1) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.


### GetVisibility

`func (o *SyncAssetV1) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *SyncAssetV1) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *SyncAssetV1) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.


### GetWidth

`func (o *SyncAssetV1) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *SyncAssetV1) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *SyncAssetV1) SetWidth(v int32)`

SetWidth sets Width field to given value.


### SetWidthNil

`func (o *SyncAssetV1) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *SyncAssetV1) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


