# SyncPersonV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | **NullableTime** | Birth date | 
**Color** | **NullableString** | Color | 
**CreatedAt** | **time.Time** | Created at | 
**FaceAssetId** | **NullableString** | Face asset ID | 
**Id** | **string** | Person ID | 
**IsFavorite** | **bool** | Is favorite | 
**IsHidden** | **bool** | Is hidden | 
**Name** | **string** | Person name | 
**OwnerId** | **string** | Owner ID | 
**UpdatedAt** | **time.Time** | Updated at | 

## Methods

### NewSyncPersonV1

`func NewSyncPersonV1(birthDate NullableTime, color NullableString, createdAt time.Time, faceAssetId NullableString, id string, isFavorite bool, isHidden bool, name string, ownerId string, updatedAt time.Time, ) *SyncPersonV1`

NewSyncPersonV1 instantiates a new SyncPersonV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncPersonV1WithDefaults

`func NewSyncPersonV1WithDefaults() *SyncPersonV1`

NewSyncPersonV1WithDefaults instantiates a new SyncPersonV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *SyncPersonV1) GetBirthDate() time.Time`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *SyncPersonV1) GetBirthDateOk() (*time.Time, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *SyncPersonV1) SetBirthDate(v time.Time)`

SetBirthDate sets BirthDate field to given value.


### SetBirthDateNil

`func (o *SyncPersonV1) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *SyncPersonV1) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *SyncPersonV1) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *SyncPersonV1) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *SyncPersonV1) SetColor(v string)`

SetColor sets Color field to given value.


### SetColorNil

`func (o *SyncPersonV1) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *SyncPersonV1) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetCreatedAt

`func (o *SyncPersonV1) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SyncPersonV1) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SyncPersonV1) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetFaceAssetId

`func (o *SyncPersonV1) GetFaceAssetId() string`

GetFaceAssetId returns the FaceAssetId field if non-nil, zero value otherwise.

### GetFaceAssetIdOk

`func (o *SyncPersonV1) GetFaceAssetIdOk() (*string, bool)`

GetFaceAssetIdOk returns a tuple with the FaceAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFaceAssetId

`func (o *SyncPersonV1) SetFaceAssetId(v string)`

SetFaceAssetId sets FaceAssetId field to given value.


### SetFaceAssetIdNil

`func (o *SyncPersonV1) SetFaceAssetIdNil(b bool)`

 SetFaceAssetIdNil sets the value for FaceAssetId to be an explicit nil

### UnsetFaceAssetId
`func (o *SyncPersonV1) UnsetFaceAssetId()`

UnsetFaceAssetId ensures that no value is present for FaceAssetId, not even an explicit nil
### GetId

`func (o *SyncPersonV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncPersonV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncPersonV1) SetId(v string)`

SetId sets Id field to given value.


### GetIsFavorite

`func (o *SyncPersonV1) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *SyncPersonV1) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *SyncPersonV1) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.


### GetIsHidden

`func (o *SyncPersonV1) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *SyncPersonV1) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *SyncPersonV1) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.


### GetName

`func (o *SyncPersonV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SyncPersonV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SyncPersonV1) SetName(v string)`

SetName sets Name field to given value.


### GetOwnerId

`func (o *SyncPersonV1) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *SyncPersonV1) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *SyncPersonV1) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetUpdatedAt

`func (o *SyncPersonV1) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SyncPersonV1) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SyncPersonV1) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


