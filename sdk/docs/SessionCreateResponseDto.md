# SessionCreateResponseDto

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
**Token** | **string** | Session token | 
**UpdatedAt** | **string** | Last update date | 

## Methods

### NewSessionCreateResponseDto

`func NewSessionCreateResponseDto(appVersion NullableString, createdAt string, current bool, deviceOS string, deviceType string, id string, isPendingSyncReset bool, token string, updatedAt string, ) *SessionCreateResponseDto`

NewSessionCreateResponseDto instantiates a new SessionCreateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionCreateResponseDtoWithDefaults

`func NewSessionCreateResponseDtoWithDefaults() *SessionCreateResponseDto`

NewSessionCreateResponseDtoWithDefaults instantiates a new SessionCreateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppVersion

`func (o *SessionCreateResponseDto) GetAppVersion() string`

GetAppVersion returns the AppVersion field if non-nil, zero value otherwise.

### GetAppVersionOk

`func (o *SessionCreateResponseDto) GetAppVersionOk() (*string, bool)`

GetAppVersionOk returns a tuple with the AppVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppVersion

`func (o *SessionCreateResponseDto) SetAppVersion(v string)`

SetAppVersion sets AppVersion field to given value.


### SetAppVersionNil

`func (o *SessionCreateResponseDto) SetAppVersionNil(b bool)`

 SetAppVersionNil sets the value for AppVersion to be an explicit nil

### UnsetAppVersion
`func (o *SessionCreateResponseDto) UnsetAppVersion()`

UnsetAppVersion ensures that no value is present for AppVersion, not even an explicit nil
### GetCreatedAt

`func (o *SessionCreateResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SessionCreateResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SessionCreateResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrent

`func (o *SessionCreateResponseDto) GetCurrent() bool`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *SessionCreateResponseDto) GetCurrentOk() (*bool, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *SessionCreateResponseDto) SetCurrent(v bool)`

SetCurrent sets Current field to given value.


### GetDeviceOS

`func (o *SessionCreateResponseDto) GetDeviceOS() string`

GetDeviceOS returns the DeviceOS field if non-nil, zero value otherwise.

### GetDeviceOSOk

`func (o *SessionCreateResponseDto) GetDeviceOSOk() (*string, bool)`

GetDeviceOSOk returns a tuple with the DeviceOS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceOS

`func (o *SessionCreateResponseDto) SetDeviceOS(v string)`

SetDeviceOS sets DeviceOS field to given value.


### GetDeviceType

`func (o *SessionCreateResponseDto) GetDeviceType() string`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *SessionCreateResponseDto) GetDeviceTypeOk() (*string, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *SessionCreateResponseDto) SetDeviceType(v string)`

SetDeviceType sets DeviceType field to given value.


### GetExpiresAt

`func (o *SessionCreateResponseDto) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *SessionCreateResponseDto) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *SessionCreateResponseDto) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *SessionCreateResponseDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetId

`func (o *SessionCreateResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SessionCreateResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SessionCreateResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsPendingSyncReset

`func (o *SessionCreateResponseDto) GetIsPendingSyncReset() bool`

GetIsPendingSyncReset returns the IsPendingSyncReset field if non-nil, zero value otherwise.

### GetIsPendingSyncResetOk

`func (o *SessionCreateResponseDto) GetIsPendingSyncResetOk() (*bool, bool)`

GetIsPendingSyncResetOk returns a tuple with the IsPendingSyncReset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPendingSyncReset

`func (o *SessionCreateResponseDto) SetIsPendingSyncReset(v bool)`

SetIsPendingSyncReset sets IsPendingSyncReset field to given value.


### GetToken

`func (o *SessionCreateResponseDto) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *SessionCreateResponseDto) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *SessionCreateResponseDto) SetToken(v string)`

SetToken sets Token field to given value.


### GetUpdatedAt

`func (o *SessionCreateResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SessionCreateResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SessionCreateResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


