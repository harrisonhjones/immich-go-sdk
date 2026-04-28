# SyncAssetExifV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**City** | **NullableString** | City | 
**Country** | **NullableString** | Country | 
**DateTimeOriginal** | **NullableTime** | Date time original | 
**Description** | **NullableString** | Description | 
**ExifImageHeight** | **NullableInt32** | Exif image height | 
**ExifImageWidth** | **NullableInt32** | Exif image width | 
**ExposureTime** | **NullableString** | Exposure time | 
**FNumber** | **NullableFloat64** | F number | 
**FileSizeInByte** | **NullableInt32** | File size in byte | 
**FocalLength** | **NullableFloat64** | Focal length | 
**Fps** | **NullableFloat64** | FPS | 
**Iso** | **NullableInt32** | ISO | 
**Latitude** | **NullableFloat64** | Latitude | 
**LensModel** | **NullableString** | Lens model | 
**Longitude** | **NullableFloat64** | Longitude | 
**Make** | **NullableString** | Make | 
**Model** | **NullableString** | Model | 
**ModifyDate** | **NullableTime** | Modify date | 
**Orientation** | **NullableString** | Orientation | 
**ProfileDescription** | **NullableString** | Profile description | 
**ProjectionType** | **NullableString** | Projection type | 
**Rating** | **NullableInt32** | Rating | 
**State** | **NullableString** | State | 
**TimeZone** | **NullableString** | Time zone | 

## Methods

### NewSyncAssetExifV1

`func NewSyncAssetExifV1(assetId string, city NullableString, country NullableString, dateTimeOriginal NullableTime, description NullableString, exifImageHeight NullableInt32, exifImageWidth NullableInt32, exposureTime NullableString, fNumber NullableFloat64, fileSizeInByte NullableInt32, focalLength NullableFloat64, fps NullableFloat64, iso NullableInt32, latitude NullableFloat64, lensModel NullableString, longitude NullableFloat64, make NullableString, model NullableString, modifyDate NullableTime, orientation NullableString, profileDescription NullableString, projectionType NullableString, rating NullableInt32, state NullableString, timeZone NullableString, ) *SyncAssetExifV1`

NewSyncAssetExifV1 instantiates a new SyncAssetExifV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetExifV1WithDefaults

`func NewSyncAssetExifV1WithDefaults() *SyncAssetExifV1`

NewSyncAssetExifV1WithDefaults instantiates a new SyncAssetExifV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *SyncAssetExifV1) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *SyncAssetExifV1) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *SyncAssetExifV1) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetCity

`func (o *SyncAssetExifV1) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *SyncAssetExifV1) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *SyncAssetExifV1) SetCity(v string)`

SetCity sets City field to given value.


### SetCityNil

`func (o *SyncAssetExifV1) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *SyncAssetExifV1) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *SyncAssetExifV1) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SyncAssetExifV1) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SyncAssetExifV1) SetCountry(v string)`

SetCountry sets Country field to given value.


### SetCountryNil

`func (o *SyncAssetExifV1) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *SyncAssetExifV1) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDateTimeOriginal

`func (o *SyncAssetExifV1) GetDateTimeOriginal() time.Time`

GetDateTimeOriginal returns the DateTimeOriginal field if non-nil, zero value otherwise.

### GetDateTimeOriginalOk

`func (o *SyncAssetExifV1) GetDateTimeOriginalOk() (*time.Time, bool)`

GetDateTimeOriginalOk returns a tuple with the DateTimeOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTimeOriginal

`func (o *SyncAssetExifV1) SetDateTimeOriginal(v time.Time)`

SetDateTimeOriginal sets DateTimeOriginal field to given value.


### SetDateTimeOriginalNil

`func (o *SyncAssetExifV1) SetDateTimeOriginalNil(b bool)`

 SetDateTimeOriginalNil sets the value for DateTimeOriginal to be an explicit nil

### UnsetDateTimeOriginal
`func (o *SyncAssetExifV1) UnsetDateTimeOriginal()`

UnsetDateTimeOriginal ensures that no value is present for DateTimeOriginal, not even an explicit nil
### GetDescription

`func (o *SyncAssetExifV1) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SyncAssetExifV1) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SyncAssetExifV1) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *SyncAssetExifV1) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SyncAssetExifV1) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExifImageHeight

`func (o *SyncAssetExifV1) GetExifImageHeight() int32`

GetExifImageHeight returns the ExifImageHeight field if non-nil, zero value otherwise.

### GetExifImageHeightOk

`func (o *SyncAssetExifV1) GetExifImageHeightOk() (*int32, bool)`

GetExifImageHeightOk returns a tuple with the ExifImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExifImageHeight

`func (o *SyncAssetExifV1) SetExifImageHeight(v int32)`

SetExifImageHeight sets ExifImageHeight field to given value.


### SetExifImageHeightNil

`func (o *SyncAssetExifV1) SetExifImageHeightNil(b bool)`

 SetExifImageHeightNil sets the value for ExifImageHeight to be an explicit nil

### UnsetExifImageHeight
`func (o *SyncAssetExifV1) UnsetExifImageHeight()`

UnsetExifImageHeight ensures that no value is present for ExifImageHeight, not even an explicit nil
### GetExifImageWidth

`func (o *SyncAssetExifV1) GetExifImageWidth() int32`

GetExifImageWidth returns the ExifImageWidth field if non-nil, zero value otherwise.

### GetExifImageWidthOk

`func (o *SyncAssetExifV1) GetExifImageWidthOk() (*int32, bool)`

GetExifImageWidthOk returns a tuple with the ExifImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExifImageWidth

`func (o *SyncAssetExifV1) SetExifImageWidth(v int32)`

SetExifImageWidth sets ExifImageWidth field to given value.


### SetExifImageWidthNil

`func (o *SyncAssetExifV1) SetExifImageWidthNil(b bool)`

 SetExifImageWidthNil sets the value for ExifImageWidth to be an explicit nil

### UnsetExifImageWidth
`func (o *SyncAssetExifV1) UnsetExifImageWidth()`

UnsetExifImageWidth ensures that no value is present for ExifImageWidth, not even an explicit nil
### GetExposureTime

`func (o *SyncAssetExifV1) GetExposureTime() string`

GetExposureTime returns the ExposureTime field if non-nil, zero value otherwise.

### GetExposureTimeOk

`func (o *SyncAssetExifV1) GetExposureTimeOk() (*string, bool)`

GetExposureTimeOk returns a tuple with the ExposureTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExposureTime

`func (o *SyncAssetExifV1) SetExposureTime(v string)`

SetExposureTime sets ExposureTime field to given value.


### SetExposureTimeNil

`func (o *SyncAssetExifV1) SetExposureTimeNil(b bool)`

 SetExposureTimeNil sets the value for ExposureTime to be an explicit nil

### UnsetExposureTime
`func (o *SyncAssetExifV1) UnsetExposureTime()`

UnsetExposureTime ensures that no value is present for ExposureTime, not even an explicit nil
### GetFNumber

`func (o *SyncAssetExifV1) GetFNumber() float64`

GetFNumber returns the FNumber field if non-nil, zero value otherwise.

### GetFNumberOk

`func (o *SyncAssetExifV1) GetFNumberOk() (*float64, bool)`

GetFNumberOk returns a tuple with the FNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFNumber

`func (o *SyncAssetExifV1) SetFNumber(v float64)`

SetFNumber sets FNumber field to given value.


### SetFNumberNil

`func (o *SyncAssetExifV1) SetFNumberNil(b bool)`

 SetFNumberNil sets the value for FNumber to be an explicit nil

### UnsetFNumber
`func (o *SyncAssetExifV1) UnsetFNumber()`

UnsetFNumber ensures that no value is present for FNumber, not even an explicit nil
### GetFileSizeInByte

`func (o *SyncAssetExifV1) GetFileSizeInByte() int32`

GetFileSizeInByte returns the FileSizeInByte field if non-nil, zero value otherwise.

### GetFileSizeInByteOk

`func (o *SyncAssetExifV1) GetFileSizeInByteOk() (*int32, bool)`

GetFileSizeInByteOk returns a tuple with the FileSizeInByte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSizeInByte

`func (o *SyncAssetExifV1) SetFileSizeInByte(v int32)`

SetFileSizeInByte sets FileSizeInByte field to given value.


### SetFileSizeInByteNil

`func (o *SyncAssetExifV1) SetFileSizeInByteNil(b bool)`

 SetFileSizeInByteNil sets the value for FileSizeInByte to be an explicit nil

### UnsetFileSizeInByte
`func (o *SyncAssetExifV1) UnsetFileSizeInByte()`

UnsetFileSizeInByte ensures that no value is present for FileSizeInByte, not even an explicit nil
### GetFocalLength

`func (o *SyncAssetExifV1) GetFocalLength() float64`

GetFocalLength returns the FocalLength field if non-nil, zero value otherwise.

### GetFocalLengthOk

`func (o *SyncAssetExifV1) GetFocalLengthOk() (*float64, bool)`

GetFocalLengthOk returns a tuple with the FocalLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFocalLength

`func (o *SyncAssetExifV1) SetFocalLength(v float64)`

SetFocalLength sets FocalLength field to given value.


### SetFocalLengthNil

`func (o *SyncAssetExifV1) SetFocalLengthNil(b bool)`

 SetFocalLengthNil sets the value for FocalLength to be an explicit nil

### UnsetFocalLength
`func (o *SyncAssetExifV1) UnsetFocalLength()`

UnsetFocalLength ensures that no value is present for FocalLength, not even an explicit nil
### GetFps

`func (o *SyncAssetExifV1) GetFps() float64`

GetFps returns the Fps field if non-nil, zero value otherwise.

### GetFpsOk

`func (o *SyncAssetExifV1) GetFpsOk() (*float64, bool)`

GetFpsOk returns a tuple with the Fps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFps

`func (o *SyncAssetExifV1) SetFps(v float64)`

SetFps sets Fps field to given value.


### SetFpsNil

`func (o *SyncAssetExifV1) SetFpsNil(b bool)`

 SetFpsNil sets the value for Fps to be an explicit nil

### UnsetFps
`func (o *SyncAssetExifV1) UnsetFps()`

UnsetFps ensures that no value is present for Fps, not even an explicit nil
### GetIso

`func (o *SyncAssetExifV1) GetIso() int32`

GetIso returns the Iso field if non-nil, zero value otherwise.

### GetIsoOk

`func (o *SyncAssetExifV1) GetIsoOk() (*int32, bool)`

GetIsoOk returns a tuple with the Iso field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIso

`func (o *SyncAssetExifV1) SetIso(v int32)`

SetIso sets Iso field to given value.


### SetIsoNil

`func (o *SyncAssetExifV1) SetIsoNil(b bool)`

 SetIsoNil sets the value for Iso to be an explicit nil

### UnsetIso
`func (o *SyncAssetExifV1) UnsetIso()`

UnsetIso ensures that no value is present for Iso, not even an explicit nil
### GetLatitude

`func (o *SyncAssetExifV1) GetLatitude() float64`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *SyncAssetExifV1) GetLatitudeOk() (*float64, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *SyncAssetExifV1) SetLatitude(v float64)`

SetLatitude sets Latitude field to given value.


### SetLatitudeNil

`func (o *SyncAssetExifV1) SetLatitudeNil(b bool)`

 SetLatitudeNil sets the value for Latitude to be an explicit nil

### UnsetLatitude
`func (o *SyncAssetExifV1) UnsetLatitude()`

UnsetLatitude ensures that no value is present for Latitude, not even an explicit nil
### GetLensModel

`func (o *SyncAssetExifV1) GetLensModel() string`

GetLensModel returns the LensModel field if non-nil, zero value otherwise.

### GetLensModelOk

`func (o *SyncAssetExifV1) GetLensModelOk() (*string, bool)`

GetLensModelOk returns a tuple with the LensModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensModel

`func (o *SyncAssetExifV1) SetLensModel(v string)`

SetLensModel sets LensModel field to given value.


### SetLensModelNil

`func (o *SyncAssetExifV1) SetLensModelNil(b bool)`

 SetLensModelNil sets the value for LensModel to be an explicit nil

### UnsetLensModel
`func (o *SyncAssetExifV1) UnsetLensModel()`

UnsetLensModel ensures that no value is present for LensModel, not even an explicit nil
### GetLongitude

`func (o *SyncAssetExifV1) GetLongitude() float64`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *SyncAssetExifV1) GetLongitudeOk() (*float64, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *SyncAssetExifV1) SetLongitude(v float64)`

SetLongitude sets Longitude field to given value.


### SetLongitudeNil

`func (o *SyncAssetExifV1) SetLongitudeNil(b bool)`

 SetLongitudeNil sets the value for Longitude to be an explicit nil

### UnsetLongitude
`func (o *SyncAssetExifV1) UnsetLongitude()`

UnsetLongitude ensures that no value is present for Longitude, not even an explicit nil
### GetMake

`func (o *SyncAssetExifV1) GetMake() string`

GetMake returns the Make field if non-nil, zero value otherwise.

### GetMakeOk

`func (o *SyncAssetExifV1) GetMakeOk() (*string, bool)`

GetMakeOk returns a tuple with the Make field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMake

`func (o *SyncAssetExifV1) SetMake(v string)`

SetMake sets Make field to given value.


### SetMakeNil

`func (o *SyncAssetExifV1) SetMakeNil(b bool)`

 SetMakeNil sets the value for Make to be an explicit nil

### UnsetMake
`func (o *SyncAssetExifV1) UnsetMake()`

UnsetMake ensures that no value is present for Make, not even an explicit nil
### GetModel

`func (o *SyncAssetExifV1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SyncAssetExifV1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SyncAssetExifV1) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *SyncAssetExifV1) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *SyncAssetExifV1) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetModifyDate

`func (o *SyncAssetExifV1) GetModifyDate() time.Time`

GetModifyDate returns the ModifyDate field if non-nil, zero value otherwise.

### GetModifyDateOk

`func (o *SyncAssetExifV1) GetModifyDateOk() (*time.Time, bool)`

GetModifyDateOk returns a tuple with the ModifyDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifyDate

`func (o *SyncAssetExifV1) SetModifyDate(v time.Time)`

SetModifyDate sets ModifyDate field to given value.


### SetModifyDateNil

`func (o *SyncAssetExifV1) SetModifyDateNil(b bool)`

 SetModifyDateNil sets the value for ModifyDate to be an explicit nil

### UnsetModifyDate
`func (o *SyncAssetExifV1) UnsetModifyDate()`

UnsetModifyDate ensures that no value is present for ModifyDate, not even an explicit nil
### GetOrientation

`func (o *SyncAssetExifV1) GetOrientation() string`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *SyncAssetExifV1) GetOrientationOk() (*string, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *SyncAssetExifV1) SetOrientation(v string)`

SetOrientation sets Orientation field to given value.


### SetOrientationNil

`func (o *SyncAssetExifV1) SetOrientationNil(b bool)`

 SetOrientationNil sets the value for Orientation to be an explicit nil

### UnsetOrientation
`func (o *SyncAssetExifV1) UnsetOrientation()`

UnsetOrientation ensures that no value is present for Orientation, not even an explicit nil
### GetProfileDescription

`func (o *SyncAssetExifV1) GetProfileDescription() string`

GetProfileDescription returns the ProfileDescription field if non-nil, zero value otherwise.

### GetProfileDescriptionOk

`func (o *SyncAssetExifV1) GetProfileDescriptionOk() (*string, bool)`

GetProfileDescriptionOk returns a tuple with the ProfileDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileDescription

`func (o *SyncAssetExifV1) SetProfileDescription(v string)`

SetProfileDescription sets ProfileDescription field to given value.


### SetProfileDescriptionNil

`func (o *SyncAssetExifV1) SetProfileDescriptionNil(b bool)`

 SetProfileDescriptionNil sets the value for ProfileDescription to be an explicit nil

### UnsetProfileDescription
`func (o *SyncAssetExifV1) UnsetProfileDescription()`

UnsetProfileDescription ensures that no value is present for ProfileDescription, not even an explicit nil
### GetProjectionType

`func (o *SyncAssetExifV1) GetProjectionType() string`

GetProjectionType returns the ProjectionType field if non-nil, zero value otherwise.

### GetProjectionTypeOk

`func (o *SyncAssetExifV1) GetProjectionTypeOk() (*string, bool)`

GetProjectionTypeOk returns a tuple with the ProjectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionType

`func (o *SyncAssetExifV1) SetProjectionType(v string)`

SetProjectionType sets ProjectionType field to given value.


### SetProjectionTypeNil

`func (o *SyncAssetExifV1) SetProjectionTypeNil(b bool)`

 SetProjectionTypeNil sets the value for ProjectionType to be an explicit nil

### UnsetProjectionType
`func (o *SyncAssetExifV1) UnsetProjectionType()`

UnsetProjectionType ensures that no value is present for ProjectionType, not even an explicit nil
### GetRating

`func (o *SyncAssetExifV1) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *SyncAssetExifV1) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *SyncAssetExifV1) SetRating(v int32)`

SetRating sets Rating field to given value.


### SetRatingNil

`func (o *SyncAssetExifV1) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *SyncAssetExifV1) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetState

`func (o *SyncAssetExifV1) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SyncAssetExifV1) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SyncAssetExifV1) SetState(v string)`

SetState sets State field to given value.


### SetStateNil

`func (o *SyncAssetExifV1) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *SyncAssetExifV1) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTimeZone

`func (o *SyncAssetExifV1) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *SyncAssetExifV1) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *SyncAssetExifV1) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.


### SetTimeZoneNil

`func (o *SyncAssetExifV1) SetTimeZoneNil(b bool)`

 SetTimeZoneNil sets the value for TimeZone to be an explicit nil

### UnsetTimeZone
`func (o *SyncAssetExifV1) UnsetTimeZone()`

UnsetTimeZone ensures that no value is present for TimeZone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


