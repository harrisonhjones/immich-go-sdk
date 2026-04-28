# UserPreferencesUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Albums** | Pointer to [**AlbumsUpdate**](AlbumsUpdate.md) |  | [optional] 
**Avatar** | Pointer to [**AvatarUpdate**](AvatarUpdate.md) |  | [optional] 
**Cast** | Pointer to [**CastUpdate**](CastUpdate.md) |  | [optional] 
**Download** | Pointer to [**DownloadUpdate**](DownloadUpdate.md) |  | [optional] 
**EmailNotifications** | Pointer to [**EmailNotificationsUpdate**](EmailNotificationsUpdate.md) |  | [optional] 
**Folders** | Pointer to [**FoldersUpdate**](FoldersUpdate.md) |  | [optional] 
**Memories** | Pointer to [**MemoriesUpdate**](MemoriesUpdate.md) |  | [optional] 
**People** | Pointer to [**PeopleUpdate**](PeopleUpdate.md) |  | [optional] 
**Purchase** | Pointer to [**PurchaseUpdate**](PurchaseUpdate.md) |  | [optional] 
**Ratings** | Pointer to [**RatingsUpdate**](RatingsUpdate.md) |  | [optional] 
**SharedLinks** | Pointer to [**SharedLinksUpdate**](SharedLinksUpdate.md) |  | [optional] 
**Tags** | Pointer to [**TagsUpdate**](TagsUpdate.md) |  | [optional] 

## Methods

### NewUserPreferencesUpdateDto

`func NewUserPreferencesUpdateDto() *UserPreferencesUpdateDto`

NewUserPreferencesUpdateDto instantiates a new UserPreferencesUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserPreferencesUpdateDtoWithDefaults

`func NewUserPreferencesUpdateDtoWithDefaults() *UserPreferencesUpdateDto`

NewUserPreferencesUpdateDtoWithDefaults instantiates a new UserPreferencesUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbums

`func (o *UserPreferencesUpdateDto) GetAlbums() AlbumsUpdate`

GetAlbums returns the Albums field if non-nil, zero value otherwise.

### GetAlbumsOk

`func (o *UserPreferencesUpdateDto) GetAlbumsOk() (*AlbumsUpdate, bool)`

GetAlbumsOk returns a tuple with the Albums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbums

`func (o *UserPreferencesUpdateDto) SetAlbums(v AlbumsUpdate)`

SetAlbums sets Albums field to given value.

### HasAlbums

`func (o *UserPreferencesUpdateDto) HasAlbums() bool`

HasAlbums returns a boolean if a field has been set.

### GetAvatar

`func (o *UserPreferencesUpdateDto) GetAvatar() AvatarUpdate`

GetAvatar returns the Avatar field if non-nil, zero value otherwise.

### GetAvatarOk

`func (o *UserPreferencesUpdateDto) GetAvatarOk() (*AvatarUpdate, bool)`

GetAvatarOk returns a tuple with the Avatar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatar

`func (o *UserPreferencesUpdateDto) SetAvatar(v AvatarUpdate)`

SetAvatar sets Avatar field to given value.

### HasAvatar

`func (o *UserPreferencesUpdateDto) HasAvatar() bool`

HasAvatar returns a boolean if a field has been set.

### GetCast

`func (o *UserPreferencesUpdateDto) GetCast() CastUpdate`

GetCast returns the Cast field if non-nil, zero value otherwise.

### GetCastOk

`func (o *UserPreferencesUpdateDto) GetCastOk() (*CastUpdate, bool)`

GetCastOk returns a tuple with the Cast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCast

`func (o *UserPreferencesUpdateDto) SetCast(v CastUpdate)`

SetCast sets Cast field to given value.

### HasCast

`func (o *UserPreferencesUpdateDto) HasCast() bool`

HasCast returns a boolean if a field has been set.

### GetDownload

`func (o *UserPreferencesUpdateDto) GetDownload() DownloadUpdate`

GetDownload returns the Download field if non-nil, zero value otherwise.

### GetDownloadOk

`func (o *UserPreferencesUpdateDto) GetDownloadOk() (*DownloadUpdate, bool)`

GetDownloadOk returns a tuple with the Download field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownload

`func (o *UserPreferencesUpdateDto) SetDownload(v DownloadUpdate)`

SetDownload sets Download field to given value.

### HasDownload

`func (o *UserPreferencesUpdateDto) HasDownload() bool`

HasDownload returns a boolean if a field has been set.

### GetEmailNotifications

`func (o *UserPreferencesUpdateDto) GetEmailNotifications() EmailNotificationsUpdate`

GetEmailNotifications returns the EmailNotifications field if non-nil, zero value otherwise.

### GetEmailNotificationsOk

`func (o *UserPreferencesUpdateDto) GetEmailNotificationsOk() (*EmailNotificationsUpdate, bool)`

GetEmailNotificationsOk returns a tuple with the EmailNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailNotifications

`func (o *UserPreferencesUpdateDto) SetEmailNotifications(v EmailNotificationsUpdate)`

SetEmailNotifications sets EmailNotifications field to given value.

### HasEmailNotifications

`func (o *UserPreferencesUpdateDto) HasEmailNotifications() bool`

HasEmailNotifications returns a boolean if a field has been set.

### GetFolders

`func (o *UserPreferencesUpdateDto) GetFolders() FoldersUpdate`

GetFolders returns the Folders field if non-nil, zero value otherwise.

### GetFoldersOk

`func (o *UserPreferencesUpdateDto) GetFoldersOk() (*FoldersUpdate, bool)`

GetFoldersOk returns a tuple with the Folders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolders

`func (o *UserPreferencesUpdateDto) SetFolders(v FoldersUpdate)`

SetFolders sets Folders field to given value.

### HasFolders

`func (o *UserPreferencesUpdateDto) HasFolders() bool`

HasFolders returns a boolean if a field has been set.

### GetMemories

`func (o *UserPreferencesUpdateDto) GetMemories() MemoriesUpdate`

GetMemories returns the Memories field if non-nil, zero value otherwise.

### GetMemoriesOk

`func (o *UserPreferencesUpdateDto) GetMemoriesOk() (*MemoriesUpdate, bool)`

GetMemoriesOk returns a tuple with the Memories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemories

`func (o *UserPreferencesUpdateDto) SetMemories(v MemoriesUpdate)`

SetMemories sets Memories field to given value.

### HasMemories

`func (o *UserPreferencesUpdateDto) HasMemories() bool`

HasMemories returns a boolean if a field has been set.

### GetPeople

`func (o *UserPreferencesUpdateDto) GetPeople() PeopleUpdate`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *UserPreferencesUpdateDto) GetPeopleOk() (*PeopleUpdate, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *UserPreferencesUpdateDto) SetPeople(v PeopleUpdate)`

SetPeople sets People field to given value.

### HasPeople

`func (o *UserPreferencesUpdateDto) HasPeople() bool`

HasPeople returns a boolean if a field has been set.

### GetPurchase

`func (o *UserPreferencesUpdateDto) GetPurchase() PurchaseUpdate`

GetPurchase returns the Purchase field if non-nil, zero value otherwise.

### GetPurchaseOk

`func (o *UserPreferencesUpdateDto) GetPurchaseOk() (*PurchaseUpdate, bool)`

GetPurchaseOk returns a tuple with the Purchase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchase

`func (o *UserPreferencesUpdateDto) SetPurchase(v PurchaseUpdate)`

SetPurchase sets Purchase field to given value.

### HasPurchase

`func (o *UserPreferencesUpdateDto) HasPurchase() bool`

HasPurchase returns a boolean if a field has been set.

### GetRatings

`func (o *UserPreferencesUpdateDto) GetRatings() RatingsUpdate`

GetRatings returns the Ratings field if non-nil, zero value otherwise.

### GetRatingsOk

`func (o *UserPreferencesUpdateDto) GetRatingsOk() (*RatingsUpdate, bool)`

GetRatingsOk returns a tuple with the Ratings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatings

`func (o *UserPreferencesUpdateDto) SetRatings(v RatingsUpdate)`

SetRatings sets Ratings field to given value.

### HasRatings

`func (o *UserPreferencesUpdateDto) HasRatings() bool`

HasRatings returns a boolean if a field has been set.

### GetSharedLinks

`func (o *UserPreferencesUpdateDto) GetSharedLinks() SharedLinksUpdate`

GetSharedLinks returns the SharedLinks field if non-nil, zero value otherwise.

### GetSharedLinksOk

`func (o *UserPreferencesUpdateDto) GetSharedLinksOk() (*SharedLinksUpdate, bool)`

GetSharedLinksOk returns a tuple with the SharedLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedLinks

`func (o *UserPreferencesUpdateDto) SetSharedLinks(v SharedLinksUpdate)`

SetSharedLinks sets SharedLinks field to given value.

### HasSharedLinks

`func (o *UserPreferencesUpdateDto) HasSharedLinks() bool`

HasSharedLinks returns a boolean if a field has been set.

### GetTags

`func (o *UserPreferencesUpdateDto) GetTags() TagsUpdate`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UserPreferencesUpdateDto) GetTagsOk() (*TagsUpdate, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UserPreferencesUpdateDto) SetTags(v TagsUpdate)`

SetTags sets Tags field to given value.

### HasTags

`func (o *UserPreferencesUpdateDto) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


