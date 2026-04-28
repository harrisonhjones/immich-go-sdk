# UserPreferencesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Albums** | [**AlbumsResponse**](AlbumsResponse.md) |  | 
**Cast** | [**CastResponse**](CastResponse.md) |  | 
**Download** | [**DownloadResponse**](DownloadResponse.md) |  | 
**EmailNotifications** | [**EmailNotificationsResponse**](EmailNotificationsResponse.md) |  | 
**Folders** | [**FoldersResponse**](FoldersResponse.md) |  | 
**Memories** | [**MemoriesResponse**](MemoriesResponse.md) |  | 
**People** | [**PeopleResponse**](PeopleResponse.md) |  | 
**Purchase** | [**PurchaseResponse**](PurchaseResponse.md) |  | 
**Ratings** | [**RatingsResponse**](RatingsResponse.md) |  | 
**SharedLinks** | [**SharedLinksResponse**](SharedLinksResponse.md) |  | 
**Tags** | [**TagsResponse**](TagsResponse.md) |  | 

## Methods

### NewUserPreferencesResponseDto

`func NewUserPreferencesResponseDto(albums AlbumsResponse, cast CastResponse, download DownloadResponse, emailNotifications EmailNotificationsResponse, folders FoldersResponse, memories MemoriesResponse, people PeopleResponse, purchase PurchaseResponse, ratings RatingsResponse, sharedLinks SharedLinksResponse, tags TagsResponse, ) *UserPreferencesResponseDto`

NewUserPreferencesResponseDto instantiates a new UserPreferencesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserPreferencesResponseDtoWithDefaults

`func NewUserPreferencesResponseDtoWithDefaults() *UserPreferencesResponseDto`

NewUserPreferencesResponseDtoWithDefaults instantiates a new UserPreferencesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbums

`func (o *UserPreferencesResponseDto) GetAlbums() AlbumsResponse`

GetAlbums returns the Albums field if non-nil, zero value otherwise.

### GetAlbumsOk

`func (o *UserPreferencesResponseDto) GetAlbumsOk() (*AlbumsResponse, bool)`

GetAlbumsOk returns a tuple with the Albums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbums

`func (o *UserPreferencesResponseDto) SetAlbums(v AlbumsResponse)`

SetAlbums sets Albums field to given value.


### GetCast

`func (o *UserPreferencesResponseDto) GetCast() CastResponse`

GetCast returns the Cast field if non-nil, zero value otherwise.

### GetCastOk

`func (o *UserPreferencesResponseDto) GetCastOk() (*CastResponse, bool)`

GetCastOk returns a tuple with the Cast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCast

`func (o *UserPreferencesResponseDto) SetCast(v CastResponse)`

SetCast sets Cast field to given value.


### GetDownload

`func (o *UserPreferencesResponseDto) GetDownload() DownloadResponse`

GetDownload returns the Download field if non-nil, zero value otherwise.

### GetDownloadOk

`func (o *UserPreferencesResponseDto) GetDownloadOk() (*DownloadResponse, bool)`

GetDownloadOk returns a tuple with the Download field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownload

`func (o *UserPreferencesResponseDto) SetDownload(v DownloadResponse)`

SetDownload sets Download field to given value.


### GetEmailNotifications

`func (o *UserPreferencesResponseDto) GetEmailNotifications() EmailNotificationsResponse`

GetEmailNotifications returns the EmailNotifications field if non-nil, zero value otherwise.

### GetEmailNotificationsOk

`func (o *UserPreferencesResponseDto) GetEmailNotificationsOk() (*EmailNotificationsResponse, bool)`

GetEmailNotificationsOk returns a tuple with the EmailNotifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailNotifications

`func (o *UserPreferencesResponseDto) SetEmailNotifications(v EmailNotificationsResponse)`

SetEmailNotifications sets EmailNotifications field to given value.


### GetFolders

`func (o *UserPreferencesResponseDto) GetFolders() FoldersResponse`

GetFolders returns the Folders field if non-nil, zero value otherwise.

### GetFoldersOk

`func (o *UserPreferencesResponseDto) GetFoldersOk() (*FoldersResponse, bool)`

GetFoldersOk returns a tuple with the Folders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolders

`func (o *UserPreferencesResponseDto) SetFolders(v FoldersResponse)`

SetFolders sets Folders field to given value.


### GetMemories

`func (o *UserPreferencesResponseDto) GetMemories() MemoriesResponse`

GetMemories returns the Memories field if non-nil, zero value otherwise.

### GetMemoriesOk

`func (o *UserPreferencesResponseDto) GetMemoriesOk() (*MemoriesResponse, bool)`

GetMemoriesOk returns a tuple with the Memories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemories

`func (o *UserPreferencesResponseDto) SetMemories(v MemoriesResponse)`

SetMemories sets Memories field to given value.


### GetPeople

`func (o *UserPreferencesResponseDto) GetPeople() PeopleResponse`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *UserPreferencesResponseDto) GetPeopleOk() (*PeopleResponse, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *UserPreferencesResponseDto) SetPeople(v PeopleResponse)`

SetPeople sets People field to given value.


### GetPurchase

`func (o *UserPreferencesResponseDto) GetPurchase() PurchaseResponse`

GetPurchase returns the Purchase field if non-nil, zero value otherwise.

### GetPurchaseOk

`func (o *UserPreferencesResponseDto) GetPurchaseOk() (*PurchaseResponse, bool)`

GetPurchaseOk returns a tuple with the Purchase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchase

`func (o *UserPreferencesResponseDto) SetPurchase(v PurchaseResponse)`

SetPurchase sets Purchase field to given value.


### GetRatings

`func (o *UserPreferencesResponseDto) GetRatings() RatingsResponse`

GetRatings returns the Ratings field if non-nil, zero value otherwise.

### GetRatingsOk

`func (o *UserPreferencesResponseDto) GetRatingsOk() (*RatingsResponse, bool)`

GetRatingsOk returns a tuple with the Ratings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatings

`func (o *UserPreferencesResponseDto) SetRatings(v RatingsResponse)`

SetRatings sets Ratings field to given value.


### GetSharedLinks

`func (o *UserPreferencesResponseDto) GetSharedLinks() SharedLinksResponse`

GetSharedLinks returns the SharedLinks field if non-nil, zero value otherwise.

### GetSharedLinksOk

`func (o *UserPreferencesResponseDto) GetSharedLinksOk() (*SharedLinksResponse, bool)`

GetSharedLinksOk returns a tuple with the SharedLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedLinks

`func (o *UserPreferencesResponseDto) SetSharedLinks(v SharedLinksResponse)`

SetSharedLinks sets SharedLinks field to given value.


### GetTags

`func (o *UserPreferencesResponseDto) GetTags() TagsResponse`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UserPreferencesResponseDto) GetTagsOk() (*TagsResponse, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UserPreferencesResponseDto) SetTags(v TagsResponse)`

SetTags sets Tags field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


