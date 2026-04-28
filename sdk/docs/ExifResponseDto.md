# ExifResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | Pointer to **NullableString** | City name | [optional] 
**Country** | Pointer to **NullableString** | Country name | [optional] 
**DateTimeOriginal** | Pointer to **NullableTime** | Original date/time | [optional] 
**Description** | Pointer to **NullableString** | Image description | [optional] 
**ExifImageHeight** | Pointer to **NullableFloat32** | Image height in pixels | [optional] 
**ExifImageWidth** | Pointer to **NullableFloat32** | Image width in pixels | [optional] 
**ExposureTime** | Pointer to **NullableString** | Exposure time | [optional] 
**FNumber** | Pointer to **NullableFloat32** | F-number (aperture) | [optional] 
**FileSizeInByte** | Pointer to **NullableInt32** | File size in bytes | [optional] 
**FocalLength** | Pointer to **NullableFloat32** | Focal length in mm | [optional] 
**Iso** | Pointer to **NullableFloat32** | ISO sensitivity | [optional] 
**Latitude** | Pointer to **NullableFloat32** | GPS latitude | [optional] 
**LensModel** | Pointer to **NullableString** | Lens model | [optional] 
**Longitude** | Pointer to **NullableFloat32** | GPS longitude | [optional] 
**Make** | Pointer to **NullableString** | Camera make | [optional] 
**Model** | Pointer to **NullableString** | Camera model | [optional] 
**ModifyDate** | Pointer to **NullableTime** | Modification date/time | [optional] 
**Orientation** | Pointer to **NullableString** | Image orientation | [optional] 
**ProjectionType** | Pointer to **NullableString** | Projection type | [optional] 
**Rating** | Pointer to **NullableFloat32** | Rating | [optional] 
**State** | Pointer to **NullableString** | State/province name | [optional] 
**TimeZone** | Pointer to **NullableString** | Time zone | [optional] 

## Methods

### NewExifResponseDto

`func NewExifResponseDto() *ExifResponseDto`

NewExifResponseDto instantiates a new ExifResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExifResponseDtoWithDefaults

`func NewExifResponseDtoWithDefaults() *ExifResponseDto`

NewExifResponseDtoWithDefaults instantiates a new ExifResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *ExifResponseDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ExifResponseDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ExifResponseDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ExifResponseDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *ExifResponseDto) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *ExifResponseDto) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *ExifResponseDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ExifResponseDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ExifResponseDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ExifResponseDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ExifResponseDto) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ExifResponseDto) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDateTimeOriginal

`func (o *ExifResponseDto) GetDateTimeOriginal() time.Time`

GetDateTimeOriginal returns the DateTimeOriginal field if non-nil, zero value otherwise.

### GetDateTimeOriginalOk

`func (o *ExifResponseDto) GetDateTimeOriginalOk() (*time.Time, bool)`

GetDateTimeOriginalOk returns a tuple with the DateTimeOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTimeOriginal

`func (o *ExifResponseDto) SetDateTimeOriginal(v time.Time)`

SetDateTimeOriginal sets DateTimeOriginal field to given value.

### HasDateTimeOriginal

`func (o *ExifResponseDto) HasDateTimeOriginal() bool`

HasDateTimeOriginal returns a boolean if a field has been set.

### SetDateTimeOriginalNil

`func (o *ExifResponseDto) SetDateTimeOriginalNil(b bool)`

 SetDateTimeOriginalNil sets the value for DateTimeOriginal to be an explicit nil

### UnsetDateTimeOriginal
`func (o *ExifResponseDto) UnsetDateTimeOriginal()`

UnsetDateTimeOriginal ensures that no value is present for DateTimeOriginal, not even an explicit nil
### GetDescription

`func (o *ExifResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ExifResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ExifResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ExifResponseDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ExifResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ExifResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExifImageHeight

`func (o *ExifResponseDto) GetExifImageHeight() float32`

GetExifImageHeight returns the ExifImageHeight field if non-nil, zero value otherwise.

### GetExifImageHeightOk

`func (o *ExifResponseDto) GetExifImageHeightOk() (*float32, bool)`

GetExifImageHeightOk returns a tuple with the ExifImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExifImageHeight

`func (o *ExifResponseDto) SetExifImageHeight(v float32)`

SetExifImageHeight sets ExifImageHeight field to given value.

### HasExifImageHeight

`func (o *ExifResponseDto) HasExifImageHeight() bool`

HasExifImageHeight returns a boolean if a field has been set.

### SetExifImageHeightNil

`func (o *ExifResponseDto) SetExifImageHeightNil(b bool)`

 SetExifImageHeightNil sets the value for ExifImageHeight to be an explicit nil

### UnsetExifImageHeight
`func (o *ExifResponseDto) UnsetExifImageHeight()`

UnsetExifImageHeight ensures that no value is present for ExifImageHeight, not even an explicit nil
### GetExifImageWidth

`func (o *ExifResponseDto) GetExifImageWidth() float32`

GetExifImageWidth returns the ExifImageWidth field if non-nil, zero value otherwise.

### GetExifImageWidthOk

`func (o *ExifResponseDto) GetExifImageWidthOk() (*float32, bool)`

GetExifImageWidthOk returns a tuple with the ExifImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExifImageWidth

`func (o *ExifResponseDto) SetExifImageWidth(v float32)`

SetExifImageWidth sets ExifImageWidth field to given value.

### HasExifImageWidth

`func (o *ExifResponseDto) HasExifImageWidth() bool`

HasExifImageWidth returns a boolean if a field has been set.

### SetExifImageWidthNil

`func (o *ExifResponseDto) SetExifImageWidthNil(b bool)`

 SetExifImageWidthNil sets the value for ExifImageWidth to be an explicit nil

### UnsetExifImageWidth
`func (o *ExifResponseDto) UnsetExifImageWidth()`

UnsetExifImageWidth ensures that no value is present for ExifImageWidth, not even an explicit nil
### GetExposureTime

`func (o *ExifResponseDto) GetExposureTime() string`

GetExposureTime returns the ExposureTime field if non-nil, zero value otherwise.

### GetExposureTimeOk

`func (o *ExifResponseDto) GetExposureTimeOk() (*string, bool)`

GetExposureTimeOk returns a tuple with the ExposureTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExposureTime

`func (o *ExifResponseDto) SetExposureTime(v string)`

SetExposureTime sets ExposureTime field to given value.

### HasExposureTime

`func (o *ExifResponseDto) HasExposureTime() bool`

HasExposureTime returns a boolean if a field has been set.

### SetExposureTimeNil

`func (o *ExifResponseDto) SetExposureTimeNil(b bool)`

 SetExposureTimeNil sets the value for ExposureTime to be an explicit nil

### UnsetExposureTime
`func (o *ExifResponseDto) UnsetExposureTime()`

UnsetExposureTime ensures that no value is present for ExposureTime, not even an explicit nil
### GetFNumber

`func (o *ExifResponseDto) GetFNumber() float32`

GetFNumber returns the FNumber field if non-nil, zero value otherwise.

### GetFNumberOk

`func (o *ExifResponseDto) GetFNumberOk() (*float32, bool)`

GetFNumberOk returns a tuple with the FNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFNumber

`func (o *ExifResponseDto) SetFNumber(v float32)`

SetFNumber sets FNumber field to given value.

### HasFNumber

`func (o *ExifResponseDto) HasFNumber() bool`

HasFNumber returns a boolean if a field has been set.

### SetFNumberNil

`func (o *ExifResponseDto) SetFNumberNil(b bool)`

 SetFNumberNil sets the value for FNumber to be an explicit nil

### UnsetFNumber
`func (o *ExifResponseDto) UnsetFNumber()`

UnsetFNumber ensures that no value is present for FNumber, not even an explicit nil
### GetFileSizeInByte

`func (o *ExifResponseDto) GetFileSizeInByte() int32`

GetFileSizeInByte returns the FileSizeInByte field if non-nil, zero value otherwise.

### GetFileSizeInByteOk

`func (o *ExifResponseDto) GetFileSizeInByteOk() (*int32, bool)`

GetFileSizeInByteOk returns a tuple with the FileSizeInByte field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSizeInByte

`func (o *ExifResponseDto) SetFileSizeInByte(v int32)`

SetFileSizeInByte sets FileSizeInByte field to given value.

### HasFileSizeInByte

`func (o *ExifResponseDto) HasFileSizeInByte() bool`

HasFileSizeInByte returns a boolean if a field has been set.

### SetFileSizeInByteNil

`func (o *ExifResponseDto) SetFileSizeInByteNil(b bool)`

 SetFileSizeInByteNil sets the value for FileSizeInByte to be an explicit nil

### UnsetFileSizeInByte
`func (o *ExifResponseDto) UnsetFileSizeInByte()`

UnsetFileSizeInByte ensures that no value is present for FileSizeInByte, not even an explicit nil
### GetFocalLength

`func (o *ExifResponseDto) GetFocalLength() float32`

GetFocalLength returns the FocalLength field if non-nil, zero value otherwise.

### GetFocalLengthOk

`func (o *ExifResponseDto) GetFocalLengthOk() (*float32, bool)`

GetFocalLengthOk returns a tuple with the FocalLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFocalLength

`func (o *ExifResponseDto) SetFocalLength(v float32)`

SetFocalLength sets FocalLength field to given value.

### HasFocalLength

`func (o *ExifResponseDto) HasFocalLength() bool`

HasFocalLength returns a boolean if a field has been set.

### SetFocalLengthNil

`func (o *ExifResponseDto) SetFocalLengthNil(b bool)`

 SetFocalLengthNil sets the value for FocalLength to be an explicit nil

### UnsetFocalLength
`func (o *ExifResponseDto) UnsetFocalLength()`

UnsetFocalLength ensures that no value is present for FocalLength, not even an explicit nil
### GetIso

`func (o *ExifResponseDto) GetIso() float32`

GetIso returns the Iso field if non-nil, zero value otherwise.

### GetIsoOk

`func (o *ExifResponseDto) GetIsoOk() (*float32, bool)`

GetIsoOk returns a tuple with the Iso field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIso

`func (o *ExifResponseDto) SetIso(v float32)`

SetIso sets Iso field to given value.

### HasIso

`func (o *ExifResponseDto) HasIso() bool`

HasIso returns a boolean if a field has been set.

### SetIsoNil

`func (o *ExifResponseDto) SetIsoNil(b bool)`

 SetIsoNil sets the value for Iso to be an explicit nil

### UnsetIso
`func (o *ExifResponseDto) UnsetIso()`

UnsetIso ensures that no value is present for Iso, not even an explicit nil
### GetLatitude

`func (o *ExifResponseDto) GetLatitude() float32`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *ExifResponseDto) GetLatitudeOk() (*float32, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *ExifResponseDto) SetLatitude(v float32)`

SetLatitude sets Latitude field to given value.

### HasLatitude

`func (o *ExifResponseDto) HasLatitude() bool`

HasLatitude returns a boolean if a field has been set.

### SetLatitudeNil

`func (o *ExifResponseDto) SetLatitudeNil(b bool)`

 SetLatitudeNil sets the value for Latitude to be an explicit nil

### UnsetLatitude
`func (o *ExifResponseDto) UnsetLatitude()`

UnsetLatitude ensures that no value is present for Latitude, not even an explicit nil
### GetLensModel

`func (o *ExifResponseDto) GetLensModel() string`

GetLensModel returns the LensModel field if non-nil, zero value otherwise.

### GetLensModelOk

`func (o *ExifResponseDto) GetLensModelOk() (*string, bool)`

GetLensModelOk returns a tuple with the LensModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensModel

`func (o *ExifResponseDto) SetLensModel(v string)`

SetLensModel sets LensModel field to given value.

### HasLensModel

`func (o *ExifResponseDto) HasLensModel() bool`

HasLensModel returns a boolean if a field has been set.

### SetLensModelNil

`func (o *ExifResponseDto) SetLensModelNil(b bool)`

 SetLensModelNil sets the value for LensModel to be an explicit nil

### UnsetLensModel
`func (o *ExifResponseDto) UnsetLensModel()`

UnsetLensModel ensures that no value is present for LensModel, not even an explicit nil
### GetLongitude

`func (o *ExifResponseDto) GetLongitude() float32`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *ExifResponseDto) GetLongitudeOk() (*float32, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *ExifResponseDto) SetLongitude(v float32)`

SetLongitude sets Longitude field to given value.

### HasLongitude

`func (o *ExifResponseDto) HasLongitude() bool`

HasLongitude returns a boolean if a field has been set.

### SetLongitudeNil

`func (o *ExifResponseDto) SetLongitudeNil(b bool)`

 SetLongitudeNil sets the value for Longitude to be an explicit nil

### UnsetLongitude
`func (o *ExifResponseDto) UnsetLongitude()`

UnsetLongitude ensures that no value is present for Longitude, not even an explicit nil
### GetMake

`func (o *ExifResponseDto) GetMake() string`

GetMake returns the Make field if non-nil, zero value otherwise.

### GetMakeOk

`func (o *ExifResponseDto) GetMakeOk() (*string, bool)`

GetMakeOk returns a tuple with the Make field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMake

`func (o *ExifResponseDto) SetMake(v string)`

SetMake sets Make field to given value.

### HasMake

`func (o *ExifResponseDto) HasMake() bool`

HasMake returns a boolean if a field has been set.

### SetMakeNil

`func (o *ExifResponseDto) SetMakeNil(b bool)`

 SetMakeNil sets the value for Make to be an explicit nil

### UnsetMake
`func (o *ExifResponseDto) UnsetMake()`

UnsetMake ensures that no value is present for Make, not even an explicit nil
### GetModel

`func (o *ExifResponseDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ExifResponseDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ExifResponseDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *ExifResponseDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *ExifResponseDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *ExifResponseDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetModifyDate

`func (o *ExifResponseDto) GetModifyDate() time.Time`

GetModifyDate returns the ModifyDate field if non-nil, zero value otherwise.

### GetModifyDateOk

`func (o *ExifResponseDto) GetModifyDateOk() (*time.Time, bool)`

GetModifyDateOk returns a tuple with the ModifyDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifyDate

`func (o *ExifResponseDto) SetModifyDate(v time.Time)`

SetModifyDate sets ModifyDate field to given value.

### HasModifyDate

`func (o *ExifResponseDto) HasModifyDate() bool`

HasModifyDate returns a boolean if a field has been set.

### SetModifyDateNil

`func (o *ExifResponseDto) SetModifyDateNil(b bool)`

 SetModifyDateNil sets the value for ModifyDate to be an explicit nil

### UnsetModifyDate
`func (o *ExifResponseDto) UnsetModifyDate()`

UnsetModifyDate ensures that no value is present for ModifyDate, not even an explicit nil
### GetOrientation

`func (o *ExifResponseDto) GetOrientation() string`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *ExifResponseDto) GetOrientationOk() (*string, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *ExifResponseDto) SetOrientation(v string)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *ExifResponseDto) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### SetOrientationNil

`func (o *ExifResponseDto) SetOrientationNil(b bool)`

 SetOrientationNil sets the value for Orientation to be an explicit nil

### UnsetOrientation
`func (o *ExifResponseDto) UnsetOrientation()`

UnsetOrientation ensures that no value is present for Orientation, not even an explicit nil
### GetProjectionType

`func (o *ExifResponseDto) GetProjectionType() string`

GetProjectionType returns the ProjectionType field if non-nil, zero value otherwise.

### GetProjectionTypeOk

`func (o *ExifResponseDto) GetProjectionTypeOk() (*string, bool)`

GetProjectionTypeOk returns a tuple with the ProjectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectionType

`func (o *ExifResponseDto) SetProjectionType(v string)`

SetProjectionType sets ProjectionType field to given value.

### HasProjectionType

`func (o *ExifResponseDto) HasProjectionType() bool`

HasProjectionType returns a boolean if a field has been set.

### SetProjectionTypeNil

`func (o *ExifResponseDto) SetProjectionTypeNil(b bool)`

 SetProjectionTypeNil sets the value for ProjectionType to be an explicit nil

### UnsetProjectionType
`func (o *ExifResponseDto) UnsetProjectionType()`

UnsetProjectionType ensures that no value is present for ProjectionType, not even an explicit nil
### GetRating

`func (o *ExifResponseDto) GetRating() float32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *ExifResponseDto) GetRatingOk() (*float32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *ExifResponseDto) SetRating(v float32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *ExifResponseDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *ExifResponseDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *ExifResponseDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetState

`func (o *ExifResponseDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ExifResponseDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ExifResponseDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ExifResponseDto) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *ExifResponseDto) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ExifResponseDto) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTimeZone

`func (o *ExifResponseDto) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *ExifResponseDto) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *ExifResponseDto) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.

### HasTimeZone

`func (o *ExifResponseDto) HasTimeZone() bool`

HasTimeZone returns a boolean if a field has been set.

### SetTimeZoneNil

`func (o *ExifResponseDto) SetTimeZoneNil(b bool)`

 SetTimeZoneNil sets the value for TimeZone to be an explicit nil

### UnsetTimeZone
`func (o *ExifResponseDto) UnsetTimeZone()`

UnsetTimeZone ensures that no value is present for TimeZone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


