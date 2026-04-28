# SessionResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppVersion** | **NullableString** | App version | 
**CreatedAt** | **string** | Creation date | 
**Current** | **bool** | Is current session | 
**DeviceOS** | **string** | Device OS | 
**DeviceType** | **string** | Device type | 
**ExpiresAt** | Pointer to **string** | Expiration date | [optional] 
**Id** | **string** | Session ID | 
**IsPendingSyncReset** | **bool** | Is pending sync reset | 
**UpdatedAt** | **string** | Last update date | 

## Methods

### NewSessionResponseDto

`func NewSessionResponseDto(appVersion NullableString, createdAt string, current bool, deviceOS string, deviceType string, id string, isPendingSyncReset bool, updatedAt string, ) *SessionResponseDto`

NewSessionResponseDto instantiates a new SessionResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionResponseDtoWithDefaults

`func NewSessionResponseDtoWithDefaults() *SessionResponseDto`

NewSessionResponseDtoWithDefaults instantiates a new SessionResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppVersion

`func (o *SessionResponseDto) GetAppVersion() string`

GetAppVersion returns the AppVersion field if non-nil, zero value otherwise.

### GetAppVersionOk

`func (o *SessionResponseDto) GetAppVersionOk() (*string, bool)`

GetAppVersionOk returns a tuple with the AppVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppVersion

`func (o *SessionResponseDto) SetAppVersion(v string)`

SetAppVersion sets AppVersion field to given value.


### SetAppVersionNil

`func (o *SessionResponseDto) SetAppVersionNil(b bool)`

 SetAppVersionNil sets the value for AppVersion to be an explicit nil

### UnsetAppVersion
`func (o *SessionResponseDto) UnsetAppVersion()`

UnsetAppVersion ensures that no value is present for AppVersion, not even an explicit nil
### GetCreatedAt

`func (o *SessionResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SessionResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SessionResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrent

`func (o *SessionResponseDto) GetCurrent() bool`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *SessionResponseDto) GetCurrentOk() (*bool, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *SessionResponseDto) SetCurrent(v bool)`

SetCurrent sets Current field to given value.


### GetDeviceOS

`func (o *SessionResponseDto) GetDeviceOS() string`

GetDeviceOS returns the DeviceOS field if non-nil, zero value otherwise.

### GetDeviceOSOk

`func (o *SessionResponseDto) GetDeviceOSOk() (*string, bool)`

GetDeviceOSOk returns a tuple with the DeviceOS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceOS

`func (o *SessionResponseDto) SetDeviceOS(v string)`

SetDeviceOS sets DeviceOS field to given value.


### GetDeviceType

`func (o *SessionResponseDto) GetDeviceType() string`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *SessionResponseDto) GetDeviceTypeOk() (*string, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *SessionResponseDto) SetDeviceType(v string)`

SetDeviceType sets DeviceType field to given value.


### GetExpiresAt

`func (o *SessionResponseDto) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SessionResponseDto) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SessionResponseDto) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *SessionResponseDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetId

`func (o *SessionResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SessionResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SessionResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsPendingSyncReset

`func (o *SessionResponseDto) GetIsPendingSyncReset() bool`

GetIsPendingSyncReset returns the IsPendingSyncReset field if non-nil, zero value otherwise.

### GetIsPendingSyncResetOk

`func (o *SessionResponseDto) GetIsPendingSyncResetOk() (*bool, bool)`

GetIsPendingSyncResetOk returns a tuple with the IsPendingSyncReset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPendingSyncReset

`func (o *SessionResponseDto) SetIsPendingSyncReset(v bool)`

SetIsPendingSyncReset sets IsPendingSyncReset field to given value.


### GetUpdatedAt

`func (o *SessionResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SessionResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SessionResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


