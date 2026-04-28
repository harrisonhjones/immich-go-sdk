# UpdateAssetDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DateTimeOriginal** | Pointer to **string** | Original date and time | [optional] 
**Description** | Pointer to **string** | Asset description | [optional] 
**IsFavorite** | Pointer to **bool** | Mark as favorite | [optional] 
**Latitude** | Pointer to **float32** | Latitude coordinate | [optional] 
**LivePhotoVideoId** | Pointer to **NullableString** | Live photo video ID | [optional] 
**Longitude** | Pointer to **float32** | Longitude coordinate | [optional] 
**Rating** | Pointer to **NullableInt32** | Rating in range [1-5], or null for unrated | [optional] 
**Visibility** | Pointer to [**AssetVisibility**](AssetVisibility.md) |  | [optional] 

## Methods

### NewUpdateAssetDto

`func NewUpdateAssetDto() *UpdateAssetDto`

NewUpdateAssetDto instantiates a new UpdateAssetDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAssetDtoWithDefaults

`func NewUpdateAssetDtoWithDefaults() *UpdateAssetDto`

NewUpdateAssetDtoWithDefaults instantiates a new UpdateAssetDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDateTimeOriginal

`func (o *UpdateAssetDto) GetDateTimeOriginal() string`

GetDateTimeOriginal returns the DateTimeOriginal field if non-nil, zero value otherwise.

### GetDateTimeOriginalOk

`func (o *UpdateAssetDto) GetDateTimeOriginalOk() (*string, bool)`

GetDateTimeOriginalOk returns a tuple with the DateTimeOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTimeOriginal

`func (o *UpdateAssetDto) SetDateTimeOriginal(v string)`

SetDateTimeOriginal sets DateTimeOriginal field to given value.

### HasDateTimeOriginal

`func (o *UpdateAssetDto) HasDateTimeOriginal() bool`

HasDateTimeOriginal returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateAssetDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAssetDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAssetDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAssetDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsFavorite

`func (o *UpdateAssetDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *UpdateAssetDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *UpdateAssetDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *UpdateAssetDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetLatitude

`func (o *UpdateAssetDto) GetLatitude() float32`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *UpdateAssetDto) GetLatitudeOk() (*float32, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *UpdateAssetDto) SetLatitude(v float32)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *UpdateAssetDto) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### GetLivePhotoVideoId

`func (o *UpdateAssetDto) GetLivePhotoVideoId() string`

GetLivePhotoVideoId returns the LivePhotoVideoId field if non-nil, zero value otherwise.

### GetLivePhotoVideoIdOk

`func (o *UpdateAssetDto) GetLivePhotoVideoIdOk() (*string, bool)`

GetLivePhotoVideoIdOk returns a tuple with the LivePhotoVideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivePhotoVideoId

`func (o *UpdateAssetDto) SetLivePhotoVideoId(v string)`

SetLivePhotoVideoId sets LivePhotoVideoId field to given value.

### HasLivePhotoVideoId

`func (o *UpdateAssetDto) HasLivePhotoVideoId() bool`

HasLivePhotoVideoId returns a boolean if a field has been set.

### SetLivePhotoVideoIdNil

`func (o *UpdateAssetDto) SetLivePhotoVideoIdNil(b bool)`

 SetLivePhotoVideoIdNil sets the value for LivePhotoVideoId to be an explicit nil

### UnsetLivePhotoVideoId
`func (o *UpdateAssetDto) UnsetLivePhotoVideoId()`

UnsetLivePhotoVideoId ensures that no value is present for LivePhotoVideoId, not even an explicit nil
### GetLongitude

`func (o *UpdateAssetDto) GetLongitude() float32`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *UpdateAssetDto) GetLongitudeOk() (*float32, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *UpdateAssetDto) SetLongitude(v float32)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *UpdateAssetDto) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### GetRating

`func (o *UpdateAssetDto) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *UpdateAssetDto) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *UpdateAssetDto) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *UpdateAssetDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *UpdateAssetDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *UpdateAssetDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetVisibility

`func (o *UpdateAssetDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *UpdateAssetDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *UpdateAssetDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *UpdateAssetDto) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


