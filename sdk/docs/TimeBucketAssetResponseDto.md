# TimeBucketAssetResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | **[]string** | Array of city names extracted from EXIF GPS data | 
**Country** | **[]string** | Array of country names extracted from EXIF GPS data | 
**Duration** | **[]int32** | Array of video/gif durations in milliseconds (null for static images) | 
**FileCreatedAt** | **[]string** | Array of file creation timestamps in UTC | 
**Id** | **[]string** | Array of asset IDs in the time bucket | 
**IsFavorite** | **[]bool** | Array indicating whether each asset is favorited | 
**IsImage** | **[]bool** | Array indicating whether each asset is an image (false for videos) | 
**IsTrashed** | **[]bool** | Array indicating whether each asset is in the trash | 
**Latitude** | Pointer to **[]float32** | Array of latitude coordinates extracted from EXIF GPS data | [optional] 
**LivePhotoVideoId** | **[]string** | Array of live photo video asset IDs (null for non-live photos) | 
**LocalOffsetHours** | **[]float32** | Array of UTC offset hours at the time each photo was taken. Positive values are east of UTC, negative values are west of UTC. Values may be fractional (e.g., 5.5 for +05:30, -9.75 for -09:45). Applying this offset to &#39;fileCreatedAt&#39; will give you the time the photo was taken from the photographer&#39;s perspective. | 
**Longitude** | Pointer to **[]float32** | Array of longitude coordinates extracted from EXIF GPS data | [optional] 
**OwnerId** | **[]string** | Array of owner IDs for each asset | 
**ProjectionType** | **[]string** | Array of projection types for 360° content (e.g., \&quot;EQUIRECTANGULAR\&quot;, \&quot;CUBEFACE\&quot;, \&quot;CYLINDRICAL\&quot;) | 
**Ratio** | **[]float32** | Array of aspect ratios (width/height) for each asset | 
**Stack** | Pointer to **[][]string** | Array of stack information as [stackId, assetCount] tuples (null for non-stacked assets) | [optional] 
**Thumbhash** | **[]string** | Array of BlurHash strings for generating asset previews (base64 encoded) | 
**Visibility** | [**[]AssetVisibility**](AssetVisibility.md) | Array of visibility statuses for each asset (e.g., ARCHIVE, TIMELINE, HIDDEN, LOCKED) | 

## Methods

### NewTimeBucketAssetResponseDto

`func NewTimeBucketAssetResponseDto(city []*string, country []*string, duration []*int32, fileCreatedAt []string, id []string, isFavorite []bool, isImage []bool, isTrashed []bool, livePhotoVideoId []*string, localOffsetHours []float32, ownerId []string, projectionType []*string, ratio []float32, thumbhash []*string, visibility []AssetVisibility, ) *TimeBucketAssetResponseDto`

NewTimeBucketAssetResponseDto instantiates a new TimeBucketAssetResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeBucketAssetResponseDtoWithDefaults

`func NewTimeBucketAssetResponseDtoWithDefaults() *TimeBucketAssetResponseDto`

NewTimeBucketAssetResponseDtoWithDefaults instantiates a new TimeBucketAssetResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *TimeBucketAssetResponseDto) GetCity() []*string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *TimeBucketAssetResponseDto) GetCityOk() (*[]*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *TimeBucketAssetResponseDto) SetCity(v []*string)`

SetCity sets City field to given value.


### GetCountry

`func (o *TimeBucketAssetResponseDto) GetCountry() []*string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *TimeBucketAssetResponseDto) GetCountryOk() (*[]*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *TimeBucketAssetResponseDto) SetCountry(v []*string)`

SetCountry sets Country field to given value.


### GetDuration

`func (o *TimeBucketAssetResponseDto) GetDuration() []*int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TimeBucketAssetResponseDto) GetDurationOk() (*[]*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TimeBucketAssetResponseDto) SetDuration(v []*int32)`

SetDuration sets Duration field to given value.


### GetFileCreatedAt

`func (o *TimeBucketAssetResponseDto) GetFileCreatedAt() []string`

GetFileCreatedAt returns the FileCreatedAt field if non-nil, zero value otherwise.

### GetFileCreatedAtOk

`func (o *TimeBucketAssetResponseDto) GetFileCreatedAtOk() (*[]string, bool)`

GetFileCreatedAtOk returns a tuple with the FileCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCreatedAt

`func (o *TimeBucketAssetResponseDto) SetFileCreatedAt(v []string)`

SetFileCreatedAt sets FileCreatedAt field to given value.


### GetId

`func (o *TimeBucketAssetResponseDto) GetId() []string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TimeBucketAssetResponseDto) GetIdOk() (*[]string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TimeBucketAssetResponseDto) SetId(v []string)`

SetId sets Id field to given value.


### GetIsFavorite

`func (o *TimeBucketAssetResponseDto) GetIsFavorite() []bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *TimeBucketAssetResponseDto) GetIsFavoriteOk() (*[]bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *TimeBucketAssetResponseDto) SetIsFavorite(v []bool)`

SetIsFavorite sets IsFavorite field to given value.


### GetIsImage

`func (o *TimeBucketAssetResponseDto) GetIsImage() []bool`

GetIsImage returns the IsImage field if non-nil, zero value otherwise.

### GetIsImageOk

`func (o *TimeBucketAssetResponseDto) GetIsImageOk() (*[]bool, bool)`

GetIsImageOk returns a tuple with the IsImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsImage

`func (o *TimeBucketAssetResponseDto) SetIsImage(v []bool)`

SetIsImage sets IsImage field to given value.


### GetIsTrashed

`func (o *TimeBucketAssetResponseDto) GetIsTrashed() []bool`

GetIsTrashed returns the IsTrashed field if non-nil, zero value otherwise.

### GetIsTrashedOk

`func (o *TimeBucketAssetResponseDto) GetIsTrashedOk() (*[]bool, bool)`

GetIsTrashedOk returns a tuple with the IsTrashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrashed

`func (o *TimeBucketAssetResponseDto) SetIsTrashed(v []bool)`

SetIsTrashed sets IsTrashed field to given value.


### GetLatitude

`func (o *TimeBucketAssetResponseDto) GetLatitude() []*float32`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *TimeBucketAssetResponseDto) GetLatitudeOk() (*[]*float32, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *TimeBucketAssetResponseDto) SetLatitude(v []*float32)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *TimeBucketAssetResponseDto) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### GetLivePhotoVideoId

`func (o *TimeBucketAssetResponseDto) GetLivePhotoVideoId() []*string`

GetLivePhotoVideoId returns the LivePhotoVideoId field if non-nil, zero value otherwise.

### GetLivePhotoVideoIdOk

`func (o *TimeBucketAssetResponseDto) GetLivePhotoVideoIdOk() (*[]*string, bool)`

GetLivePhotoVideoIdOk returns a tuple with the LivePhotoVideoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivePhotoVideoId

`func (o *TimeBucketAssetResponseDto) SetLivePhotoVideoId(v []*string)`

SetLivePhotoVideoId sets LivePhotoVideoId field to given value.


### GetLocalOffsetHours

`func (o *TimeBucketAssetResponseDto) GetLocalOffsetHours() []float32`

GetLocalOffsetHours returns the LocalOffsetHours field if non-nil, zero value otherwise.

### GetLocalOffsetHoursOk

`func (o *TimeBucketAssetResponseDto) GetLocalOffsetHoursOk() (*[]float32, bool)`

GetLocalOffsetHoursOk returns a tuple with the LocalOffsetHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalOffsetHours

`func (o *TimeBucketAssetResponseDto) SetLocalOffsetHours(v []float32)`

SetLocalOffsetHours sets LocalOffsetHours field to given value.


### GetLongitude

`func (o *TimeBucketAssetResponseDto) GetLongitude() []*float32`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *TimeBucketAssetResponseDto) GetLongitudeOk() (*[]*float32, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *TimeBucketAssetResponseDto) SetLongitude(v []*float32)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *TimeBucketAssetResponseDto) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### GetOwnerId

`func (o *TimeBucketAssetResponseDto) GetOwnerId() []string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *TimeBucketAssetResponseDto) GetOwnerIdOk() (*[]string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *TimeBucketAssetResponseDto) SetOwnerId(v []string)`

SetOwnerId sets OwnerId field to given value.


### GetProjectionType

`func (o *TimeBucketAssetResponseDto) GetProjectionType() []*string`

GetProjectionType returns the ProjectionType field if non-nil, zero value otherwise.

### GetProjectionTypeOk

`func (o *TimeBucketAssetResponseDto) GetProjectionTypeOk() (*[]*string, bool)`

GetProjectionTypeOk returns a tuple with the ProjectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionType

`func (o *TimeBucketAssetResponseDto) SetProjectionType(v []*string)`

SetProjectionType sets ProjectionType field to given value.


### GetRatio

`func (o *TimeBucketAssetResponseDto) GetRatio() []float32`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *TimeBucketAssetResponseDto) GetRatioOk() (*[]float32, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *TimeBucketAssetResponseDto) SetRatio(v []float32)`

SetRatio sets Ratio field to given value.


### GetStack

`func (o *TimeBucketAssetResponseDto) GetStack() []*[]string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *TimeBucketAssetResponseDto) GetStackOk() (*[]*[]string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *TimeBucketAssetResponseDto) SetStack(v []*[]string)`

SetStack sets Stack field to given value.

### HasStack

`func (o *TimeBucketAssetResponseDto) HasStack() bool`

HasStack returns a boolean if a field has been set.

### GetThumbhash

`func (o *TimeBucketAssetResponseDto) GetThumbhash() []*string`

GetThumbhash returns the Thumbhash field if non-nil, zero value otherwise.

### GetThumbhashOk

`func (o *TimeBucketAssetResponseDto) GetThumbhashOk() (*[]*string, bool)`

GetThumbhashOk returns a tuple with the Thumbhash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbhash

`func (o *TimeBucketAssetResponseDto) SetThumbhash(v []*string)`

SetThumbhash sets Thumbhash field to given value.


### GetVisibility

`func (o *TimeBucketAssetResponseDto) GetVisibility() []AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *TimeBucketAssetResponseDto) GetVisibilityOk() (*[]AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *TimeBucketAssetResponseDto) SetVisibility(v []AssetVisibility)`

SetVisibility sets Visibility field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


