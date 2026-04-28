# AssetBulkUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DateTimeOriginal** | Pointer to **string** | Original date and time | [optional] 
**DateTimeRelative** | Pointer to **float32** | Relative time offset in seconds | [optional] 
**Description** | Pointer to **string** | Asset description | [optional] 
**DuplicateId** | Pointer to **NullableString** | Duplicate ID | [optional] 
**Ids** | **[]string** | Asset IDs to update | 
**IsFavorite** | Pointer to **bool** | Mark as favorite | [optional] 
**Latitude** | Pointer to **float32** | Latitude coordinate | [optional] 
**Longitude** | Pointer to **float32** | Longitude coordinate | [optional] 
**Rating** | Pointer to **NullableInt32** | Rating in range [1-5], or null for unrated | [optional] 
**TimeZone** | Pointer to **string** | Time zone (IANA timezone) | [optional] 
**Visibility** | Pointer to [**AssetVisibility**](AssetVisibility.md) |  | [optional] 

## Methods

### NewAssetBulkUpdateDto

`func NewAssetBulkUpdateDto(ids []string, ) *AssetBulkUpdateDto`

NewAssetBulkUpdateDto instantiates a new AssetBulkUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetBulkUpdateDtoWithDefaults

`func NewAssetBulkUpdateDtoWithDefaults() *AssetBulkUpdateDto`

NewAssetBulkUpdateDtoWithDefaults instantiates a new AssetBulkUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDateTimeOriginal

`func (o *AssetBulkUpdateDto) GetDateTimeOriginal() string`

GetDateTimeOriginal returns the DateTimeOriginal field if non-nil, zero value otherwise.

### GetDateTimeOriginalOk

`func (o *AssetBulkUpdateDto) GetDateTimeOriginalOk() (*string, bool)`

GetDateTimeOriginalOk returns a tuple with the DateTimeOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTimeOriginal

`func (o *AssetBulkUpdateDto) SetDateTimeOriginal(v string)`

SetDateTimeOriginal sets DateTimeOriginal field to given value.

### HasDateTimeOriginal

`func (o *AssetBulkUpdateDto) HasDateTimeOriginal() bool`

HasDateTimeOriginal returns a boolean if a field has been set.

### GetDateTimeRelative

`func (o *AssetBulkUpdateDto) GetDateTimeRelative() float32`

GetDateTimeRelative returns the DateTimeRelative field if non-nil, zero value otherwise.

### GetDateTimeRelativeOk

`func (o *AssetBulkUpdateDto) GetDateTimeRelativeOk() (*float32, bool)`

GetDateTimeRelativeOk returns a tuple with the DateTimeRelative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTimeRelative

`func (o *AssetBulkUpdateDto) SetDateTimeRelative(v float32)`

SetDateTimeRelative sets DateTimeRelative field to given value.

### HasDateTimeRelative

`func (o *AssetBulkUpdateDto) HasDateTimeRelative() bool`

HasDateTimeRelative returns a boolean if a field has been set.

### GetDescription

`func (o *AssetBulkUpdateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AssetBulkUpdateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AssetBulkUpdateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AssetBulkUpdateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDuplicateId

`func (o *AssetBulkUpdateDto) GetDuplicateId() string`

GetDuplicateId returns the DuplicateId field if non-nil, zero value otherwise.

### GetDuplicateIdOk

`func (o *AssetBulkUpdateDto) GetDuplicateIdOk() (*string, bool)`

GetDuplicateIdOk returns a tuple with the DuplicateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateId

`func (o *AssetBulkUpdateDto) SetDuplicateId(v string)`

SetDuplicateId sets DuplicateId field to given value.

### HasDuplicateId

`func (o *AssetBulkUpdateDto) HasDuplicateId() bool`

HasDuplicateId returns a boolean if a field has been set.

### SetDuplicateIdNil

`func (o *AssetBulkUpdateDto) SetDuplicateIdNil(b bool)`

 SetDuplicateIdNil sets the value for DuplicateId to be an explicit nil

### UnsetDuplicateId
`func (o *AssetBulkUpdateDto) UnsetDuplicateId()`

UnsetDuplicateId ensures that no value is present for DuplicateId, not even an explicit nil
### GetIds

`func (o *AssetBulkUpdateDto) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *AssetBulkUpdateDto) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *AssetBulkUpdateDto) SetIds(v []string)`

SetIds sets Ids field to given value.


### GetIsFavorite

`func (o *AssetBulkUpdateDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *AssetBulkUpdateDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *AssetBulkUpdateDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *AssetBulkUpdateDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetLatitude

`func (o *AssetBulkUpdateDto) GetLatitude() float32`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *AssetBulkUpdateDto) GetLatitudeOk() (*float32, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *AssetBulkUpdateDto) SetLatitude(v float32)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *AssetBulkUpdateDto) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### GetLongitude

`func (o *AssetBulkUpdateDto) GetLongitude() float32`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *AssetBulkUpdateDto) GetLongitudeOk() (*float32, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *AssetBulkUpdateDto) SetLongitude(v float32)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *AssetBulkUpdateDto) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### GetRating

`func (o *AssetBulkUpdateDto) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *AssetBulkUpdateDto) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *AssetBulkUpdateDto) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *AssetBulkUpdateDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *AssetBulkUpdateDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *AssetBulkUpdateDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetTimeZone

`func (o *AssetBulkUpdateDto) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *AssetBulkUpdateDto) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *AssetBulkUpdateDto) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.

### HasTimeZone

`func (o *AssetBulkUpdateDto) HasTimeZone() bool`

HasTimeZone returns a boolean if a field has been set.

### GetVisibility

`func (o *AssetBulkUpdateDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *AssetBulkUpdateDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *AssetBulkUpdateDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *AssetBulkUpdateDto) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


