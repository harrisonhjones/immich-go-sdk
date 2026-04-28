# AlbumResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumName** | **string** | Album name | 
**AlbumThumbnailAssetId** | **NullableString** | Thumbnail asset ID | 
**AlbumUsers** | [**[]AlbumUserResponseDto**](AlbumUserResponseDto.md) | First entry is always the album owner. Second entry is the auth user, if it differs from the owner. The rest are ordered alphabetically. | 
**AssetCount** | **int32** | Number of assets | 
**ContributorCounts** | Pointer to [**[]ContributorCountResponseDto**](ContributorCountResponseDto.md) |  | [optional] 
**CreatedAt** | **time.Time** | Creation date | 
**Description** | **string** | Album description | 
**EndDate** | Pointer to **time.Time** | End date (latest asset) | [optional] 
**HasSharedLink** | **bool** | Has shared link | 
**Id** | **string** | Album ID | 
**IsActivityEnabled** | **bool** | Activity feed enabled | 
**LastModifiedAssetTimestamp** | Pointer to **time.Time** | Last modified asset timestamp | [optional] 
**Order** | Pointer to [**AssetOrder**](AssetOrder.md) |  | [optional] 
**Shared** | **bool** | Is shared album | 
**StartDate** | Pointer to **time.Time** | Start date (earliest asset) | [optional] 
**UpdatedAt** | **time.Time** | Last update date | 

## Methods

### NewAlbumResponseDto

`func NewAlbumResponseDto(albumName string, albumThumbnailAssetId NullableString, albumUsers []AlbumUserResponseDto, assetCount int32, createdAt time.Time, description string, hasSharedLink bool, id string, isActivityEnabled bool, shared bool, updatedAt time.Time, ) *AlbumResponseDto`

NewAlbumResponseDto instantiates a new AlbumResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlbumResponseDtoWithDefaults

`func NewAlbumResponseDtoWithDefaults() *AlbumResponseDto`

NewAlbumResponseDtoWithDefaults instantiates a new AlbumResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumName

`func (o *AlbumResponseDto) GetAlbumName() string`

GetAlbumName returns the AlbumName field if non-nil, zero value otherwise.

### GetAlbumNameOk

`func (o *AlbumResponseDto) GetAlbumNameOk() (*string, bool)`

GetAlbumNameOk returns a tuple with the AlbumName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumName

`func (o *AlbumResponseDto) SetAlbumName(v string)`

SetAlbumName sets AlbumName field to given value.


### GetAlbumThumbnailAssetId

`func (o *AlbumResponseDto) GetAlbumThumbnailAssetId() string`

GetAlbumThumbnailAssetId returns the AlbumThumbnailAssetId field if non-nil, zero value otherwise.

### GetAlbumThumbnailAssetIdOk

`func (o *AlbumResponseDto) GetAlbumThumbnailAssetIdOk() (*string, bool)`

GetAlbumThumbnailAssetIdOk returns a tuple with the AlbumThumbnailAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumThumbnailAssetId

`func (o *AlbumResponseDto) SetAlbumThumbnailAssetId(v string)`

SetAlbumThumbnailAssetId sets AlbumThumbnailAssetId field to given value.


### SetAlbumThumbnailAssetIdNil

`func (o *AlbumResponseDto) SetAlbumThumbnailAssetIdNil(b bool)`

 SetAlbumThumbnailAssetIdNil sets the value for AlbumThumbnailAssetId to be an explicit nil

### UnsetAlbumThumbnailAssetId
`func (o *AlbumResponseDto) UnsetAlbumThumbnailAssetId()`

UnsetAlbumThumbnailAssetId ensures that no value is present for AlbumThumbnailAssetId, not even an explicit nil
### GetAlbumUsers

`func (o *AlbumResponseDto) GetAlbumUsers() []AlbumUserResponseDto`

GetAlbumUsers returns the AlbumUsers field if non-nil, zero value otherwise.

### GetAlbumUsersOk

`func (o *AlbumResponseDto) GetAlbumUsersOk() (*[]AlbumUserResponseDto, bool)`

GetAlbumUsersOk returns a tuple with the AlbumUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumUsers

`func (o *AlbumResponseDto) SetAlbumUsers(v []AlbumUserResponseDto)`

SetAlbumUsers sets AlbumUsers field to given value.


### GetAssetCount

`func (o *AlbumResponseDto) GetAssetCount() int32`

GetAssetCount returns the AssetCount field if non-nil, zero value otherwise.

### GetAssetCountOk

`func (o *AlbumResponseDto) GetAssetCountOk() (*int32, bool)`

GetAssetCountOk returns a tuple with the AssetCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCount

`func (o *AlbumResponseDto) SetAssetCount(v int32)`

SetAssetCount sets AssetCount field to given value.


### GetContributorCounts

`func (o *AlbumResponseDto) GetContributorCounts() []ContributorCountResponseDto`

GetContributorCounts returns the ContributorCounts field if non-nil, zero value otherwise.

### GetContributorCountsOk

`func (o *AlbumResponseDto) GetContributorCountsOk() (*[]ContributorCountResponseDto, bool)`

GetContributorCountsOk returns a tuple with the ContributorCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContributorCounts

`func (o *AlbumResponseDto) SetContributorCounts(v []ContributorCountResponseDto)`

SetContributorCounts sets ContributorCounts field to given value.

### HasContributorCounts

`func (o *AlbumResponseDto) HasContributorCounts() bool`

HasContributorCounts returns a boolean if a field has been set.

### GetCreatedAt

`func (o *AlbumResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AlbumResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AlbumResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *AlbumResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AlbumResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AlbumResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEndDate

`func (o *AlbumResponseDto) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *AlbumResponseDto) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *AlbumResponseDto) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *AlbumResponseDto) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetHasSharedLink

`func (o *AlbumResponseDto) GetHasSharedLink() bool`

GetHasSharedLink returns the HasSharedLink field if non-nil, zero value otherwise.

### GetHasSharedLinkOk

`func (o *AlbumResponseDto) GetHasSharedLinkOk() (*bool, bool)`

GetHasSharedLinkOk returns a tuple with the HasSharedLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasSharedLink

`func (o *AlbumResponseDto) SetHasSharedLink(v bool)`

SetHasSharedLink sets HasSharedLink field to given value.


### GetId

`func (o *AlbumResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AlbumResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AlbumResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsActivityEnabled

`func (o *AlbumResponseDto) GetIsActivityEnabled() bool`

GetIsActivityEnabled returns the IsActivityEnabled field if non-nil, zero value otherwise.

### GetIsActivityEnabledOk

`func (o *AlbumResponseDto) GetIsActivityEnabledOk() (*bool, bool)`

GetIsActivityEnabledOk returns a tuple with the IsActivityEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActivityEnabled

`func (o *AlbumResponseDto) SetIsActivityEnabled(v bool)`

SetIsActivityEnabled sets IsActivityEnabled field to given value.


### GetLastModifiedAssetTimestamp

`func (o *AlbumResponseDto) GetLastModifiedAssetTimestamp() time.Time`

GetLastModifiedAssetTimestamp returns the LastModifiedAssetTimestamp field if non-nil, zero value otherwise.

### GetLastModifiedAssetTimestampOk

`func (o *AlbumResponseDto) GetLastModifiedAssetTimestampOk() (*time.Time, bool)`

GetLastModifiedAssetTimestampOk returns a tuple with the LastModifiedAssetTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifiedAssetTimestamp

`func (o *AlbumResponseDto) SetLastModifiedAssetTimestamp(v time.Time)`

SetLastModifiedAssetTimestamp sets LastModifiedAssetTimestamp field to given value.

### HasLastModifiedAssetTimestamp

`func (o *AlbumResponseDto) HasLastModifiedAssetTimestamp() bool`

HasLastModifiedAssetTimestamp returns a boolean if a field has been set.

### GetOrder

`func (o *AlbumResponseDto) GetOrder() AssetOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *AlbumResponseDto) GetOrderOk() (*AssetOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *AlbumResponseDto) SetOrder(v AssetOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *AlbumResponseDto) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetShared

`func (o *AlbumResponseDto) GetShared() bool`

GetShared returns the Shared field if non-nil, zero value otherwise.

### GetSharedOk

`func (o *AlbumResponseDto) GetSharedOk() (*bool, bool)`

GetSharedOk returns a tuple with the Shared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShared

`func (o *AlbumResponseDto) SetShared(v bool)`

SetShared sets Shared field to given value.


### GetStartDate

`func (o *AlbumResponseDto) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *AlbumResponseDto) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *AlbumResponseDto) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *AlbumResponseDto) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *AlbumResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AlbumResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AlbumResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


