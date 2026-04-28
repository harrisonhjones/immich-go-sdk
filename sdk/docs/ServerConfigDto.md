# ServerConfigDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalDomain** | **string** | External domain URL | 
**IsInitialized** | **bool** | Whether the server has been initialized | 
**IsOnboarded** | **bool** | Whether the admin has completed onboarding | 
**LoginPageMessage** | **string** | Login page message | 
**MaintenanceMode** | **bool** | Whether maintenance mode is active | 
**MapDarkStyleUrl** | **string** | Map dark style URL | 
**MapLightStyleUrl** | **string** | Map light style URL | 
**OauthButtonText** | **string** | OAuth button text | 
**PublicUsers** | **bool** | Whether public user registration is enabled | 
**TrashDays** | **int32** | Number of days before trashed assets are permanently deleted | 
**UserDeleteDelay** | **int32** | Delay in days before deleted users are permanently removed | 

## Methods

### NewServerConfigDto

`func NewServerConfigDto(externalDomain string, isInitialized bool, isOnboarded bool, loginPageMessage string, maintenanceMode bool, mapDarkStyleUrl string, mapLightStyleUrl string, oauthButtonText string, publicUsers bool, trashDays int32, userDeleteDelay int32, ) *ServerConfigDto`

NewServerConfigDto instantiates a new ServerConfigDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerConfigDtoWithDefaults

`func NewServerConfigDtoWithDefaults() *ServerConfigDto`

NewServerConfigDtoWithDefaults instantiates a new ServerConfigDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalDomain

`func (o *ServerConfigDto) GetExternalDomain() string`

GetExternalDomain returns the ExternalDomain field if non-nil, zero value otherwise.

### GetExternalDomainOk

`func (o *ServerConfigDto) GetExternalDomainOk() (*string, bool)`

GetExternalDomainOk returns a tuple with the ExternalDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDomain

`func (o *ServerConfigDto) SetExternalDomain(v string)`

SetExternalDomain sets ExternalDomain field to given value.


### GetIsInitialized

`func (o *ServerConfigDto) GetIsInitialized() bool`

GetIsInitialized returns the IsInitialized field if non-nil, zero value otherwise.

### GetIsInitializedOk

`func (o *ServerConfigDto) GetIsInitializedOk() (*bool, bool)`

GetIsInitializedOk returns a tuple with the IsInitialized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsInitialized

`func (o *ServerConfigDto) SetIsInitialized(v bool)`

SetIsInitialized sets IsInitialized field to given value.


### GetIsOnboarded

`func (o *ServerConfigDto) GetIsOnboarded() bool`

GetIsOnboarded returns the IsOnboarded field if non-nil, zero value otherwise.

### GetIsOnboardedOk

`func (o *ServerConfigDto) GetIsOnboardedOk() (*bool, bool)`

GetIsOnboardedOk returns a tuple with the IsOnboarded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOnboarded

`func (o *ServerConfigDto) SetIsOnboarded(v bool)`

SetIsOnboarded sets IsOnboarded field to given value.


### GetLoginPageMessage

`func (o *ServerConfigDto) GetLoginPageMessage() string`

GetLoginPageMessage returns the LoginPageMessage field if non-nil, zero value otherwise.

### GetLoginPageMessageOk

`func (o *ServerConfigDto) GetLoginPageMessageOk() (*string, bool)`

GetLoginPageMessageOk returns a tuple with the LoginPageMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginPageMessage

`func (o *ServerConfigDto) SetLoginPageMessage(v string)`

SetLoginPageMessage sets LoginPageMessage field to given value.


### GetMaintenanceMode

`func (o *ServerConfigDto) GetMaintenanceMode() bool`

GetMaintenanceMode returns the MaintenanceMode field if non-nil, zero value otherwise.

### GetMaintenanceModeOk

`func (o *ServerConfigDto) GetMaintenanceModeOk() (*bool, bool)`

GetMaintenanceModeOk returns a tuple with the MaintenanceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenanceMode

`func (o *ServerConfigDto) SetMaintenanceMode(v bool)`

SetMaintenanceMode sets MaintenanceMode field to given value.


### GetMapDarkStyleUrl

`func (o *ServerConfigDto) GetMapDarkStyleUrl() string`

GetMapDarkStyleUrl returns the MapDarkStyleUrl field if non-nil, zero value otherwise.

### GetMapDarkStyleUrlOk

`func (o *ServerConfigDto) GetMapDarkStyleUrlOk() (*string, bool)`

GetMapDarkStyleUrlOk returns a tuple with the MapDarkStyleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapDarkStyleUrl

`func (o *ServerConfigDto) SetMapDarkStyleUrl(v string)`

SetMapDarkStyleUrl sets MapDarkStyleUrl field to given value.


### GetMapLightStyleUrl

`func (o *ServerConfigDto) GetMapLightStyleUrl() string`

GetMapLightStyleUrl returns the MapLightStyleUrl field if non-nil, zero value otherwise.

### GetMapLightStyleUrlOk

`func (o *ServerConfigDto) GetMapLightStyleUrlOk() (*string, bool)`

GetMapLightStyleUrlOk returns a tuple with the MapLightStyleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMapLightStyleUrl

`func (o *ServerConfigDto) SetMapLightStyleUrl(v string)`

SetMapLightStyleUrl sets MapLightStyleUrl field to given value.


### GetOauthButtonText

`func (o *ServerConfigDto) GetOauthButtonText() string`

GetOauthButtonText returns the OauthButtonText field if non-nil, zero value otherwise.

### GetOauthButtonTextOk

`func (o *ServerConfigDto) GetOauthButtonTextOk() (*string, bool)`

GetOauthButtonTextOk returns a tuple with the OauthButtonText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthButtonText

`func (o *ServerConfigDto) SetOauthButtonText(v string)`

SetOauthButtonText sets OauthButtonText field to given value.


### GetPublicUsers

`func (o *ServerConfigDto) GetPublicUsers() bool`

GetPublicUsers returns the PublicUsers field if non-nil, zero value otherwise.

### GetPublicUsersOk

`func (o *ServerConfigDto) GetPublicUsersOk() (*bool, bool)`

GetPublicUsersOk returns a tuple with the PublicUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicUsers

`func (o *ServerConfigDto) SetPublicUsers(v bool)`

SetPublicUsers sets PublicUsers field to given value.


### GetTrashDays

`func (o *ServerConfigDto) GetTrashDays() int32`

GetTrashDays returns the TrashDays field if non-nil, zero value otherwise.

### GetTrashDaysOk

`func (o *ServerConfigDto) GetTrashDaysOk() (*int32, bool)`

GetTrashDaysOk returns a tuple with the TrashDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashDays

`func (o *ServerConfigDto) SetTrashDays(v int32)`

SetTrashDays sets TrashDays field to given value.


### GetUserDeleteDelay

`func (o *ServerConfigDto) GetUserDeleteDelay() int32`

GetUserDeleteDelay returns the UserDeleteDelay field if non-nil, zero value otherwise.

### GetUserDeleteDelayOk

`func (o *ServerConfigDto) GetUserDeleteDelayOk() (*int32, bool)`

GetUserDeleteDelayOk returns a tuple with the UserDeleteDelay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserDeleteDelay

`func (o *ServerConfigDto) SetUserDeleteDelay(v int32)`

SetUserDeleteDelay sets UserDeleteDelay field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


