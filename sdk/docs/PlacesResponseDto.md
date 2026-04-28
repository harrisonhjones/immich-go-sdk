# PlacesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Admin1name** | Pointer to **string** | Administrative level 1 name (state/province) | [optional] 
**Admin2name** | Pointer to **string** | Administrative level 2 name (county/district) | [optional] 
**Latitude** | **float32** | Latitude coordinate | 
**Longitude** | **float32** | Longitude coordinate | 
**Name** | **string** | Place name | 

## Methods

### NewPlacesResponseDto

`func NewPlacesResponseDto(latitude float32, longitude float32, name string, ) *PlacesResponseDto`

NewPlacesResponseDto instantiates a new PlacesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlacesResponseDtoWithDefaults

`func NewPlacesResponseDtoWithDefaults() *PlacesResponseDto`

NewPlacesResponseDtoWithDefaults instantiates a new PlacesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdmin1name

`func (o *PlacesResponseDto) GetAdmin1name() string`

GetAdmin1name returns the Admin1name field if non-nil, zero value otherwise.

### GetAdmin1nameOk

`func (o *PlacesResponseDto) GetAdmin1nameOk() (*string, bool)`

GetAdmin1nameOk returns a tuple with the Admin1name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdmin1name

`func (o *PlacesResponseDto) SetAdmin1name(v string)`

SetAdmin1name sets Admin1name field to given value.

### HasAdmin1name

`func (o *PlacesResponseDto) HasAdmin1name() bool`

HasAdmin1name returns a boolean if a field has been set.

### GetAdmin2name

`func (o *PlacesResponseDto) GetAdmin2name() string`

GetAdmin2name returns the Admin2name field if non-nil, zero value otherwise.

### GetAdmin2nameOk

`func (o *PlacesResponseDto) GetAdmin2nameOk() (*string, bool)`

GetAdmin2nameOk returns a tuple with the Admin2name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdmin2name

`func (o *PlacesResponseDto) SetAdmin2name(v string)`

SetAdmin2name sets Admin2name field to given value.

### HasAdmin2name

`func (o *PlacesResponseDto) HasAdmin2name() bool`

HasAdmin2name returns a boolean if a field has been set.

### GetLatitude

`func (o *PlacesResponseDto) GetLatitude() float32`

GetLatitude returns the Latitude field if non-nil, zero value otherwise.

### GetLatitudeOk

`func (o *PlacesResponseDto) GetLatitudeOk() (*float32, bool)`

GetLatitudeOk returns a tuple with the Latitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatitude

`func (o *PlacesResponseDto) SetLatitude(v float32)`

SetLatitude sets Latitude field to given value.


### GetLongitude

`func (o *PlacesResponseDto) GetLongitude() float32`

GetLongitude returns the Longitude field if non-nil, zero value otherwise.

### GetLongitudeOk

`func (o *PlacesResponseDto) GetLongitudeOk() (*float32, bool)`

GetLongitudeOk returns a tuple with the Longitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongitude

`func (o *PlacesResponseDto) SetLongitude(v float32)`

SetLongitude sets Longitude field to given value.


### GetName

`func (o *PlacesResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PlacesResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PlacesResponseDto) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


