# SystemConfigOAuthDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowInsecureRequests** | **bool** | Allow insecure requests | 
**AutoLaunch** | **bool** | Auto launch | 
**AutoRegister** | **bool** | Auto register | 
**ButtonText** | **string** | Button text | 
**ClientId** | **string** | Client ID | 
**ClientSecret** | **string** | Client secret | 
**DefaultStorageQuota** | **NullableInt32** | Default storage quota | 
**Enabled** | **bool** | Enabled | 
**EndSessionEndpoint** | **string** | End session endpoint | 
**IssuerUrl** | **string** | Issuer URL | 
**MobileOverrideEnabled** | **bool** | Mobile override enabled | 
**MobileRedirectUri** | **string** | Mobile redirect URI (set to empty string to disable) | 
**ProfileSigningAlgorithm** | **string** | Profile signing algorithm | 
**Prompt** | **string** | OAuth prompt parameter (e.g. select_account, login, consent) | 
**RoleClaim** | **string** | Role claim | 
**Scope** | **string** | Scope | 
**SigningAlgorithm** | **string** | Signing algorithm | 
**StorageLabelClaim** | **string** | Storage label claim | 
**StorageQuotaClaim** | **string** | Storage quota claim | 
**Timeout** | **int32** | Timeout | 
**TokenEndpointAuthMethod** | [**OAuthTokenEndpointAuthMethod**](OAuthTokenEndpointAuthMethod.md) |  | 

## Methods

### NewSystemConfigOAuthDto

`func NewSystemConfigOAuthDto(allowInsecureRequests bool, autoLaunch bool, autoRegister bool, buttonText string, clientId string, clientSecret string, defaultStorageQuota NullableInt32, enabled bool, endSessionEndpoint string, issuerUrl string, mobileOverrideEnabled bool, mobileRedirectUri string, profileSigningAlgorithm string, prompt string, roleClaim string, scope string, signingAlgorithm string, storageLabelClaim string, storageQuotaClaim string, timeout int32, tokenEndpointAuthMethod OAuthTokenEndpointAuthMethod, ) *SystemConfigOAuthDto`

NewSystemConfigOAuthDto instantiates a new SystemConfigOAuthDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigOAuthDtoWithDefaults

`func NewSystemConfigOAuthDtoWithDefaults() *SystemConfigOAuthDto`

NewSystemConfigOAuthDtoWithDefaults instantiates a new SystemConfigOAuthDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowInsecureRequests

`func (o *SystemConfigOAuthDto) GetAllowInsecureRequests() bool`

GetAllowInsecureRequests returns the AllowInsecureRequests field if non-nil, zero value otherwise.

### GetAllowInsecureRequestsOk

`func (o *SystemConfigOAuthDto) GetAllowInsecureRequestsOk() (*bool, bool)`

GetAllowInsecureRequestsOk returns a tuple with the AllowInsecureRequests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowInsecureRequests

`func (o *SystemConfigOAuthDto) SetAllowInsecureRequests(v bool)`

SetAllowInsecureRequests sets AllowInsecureRequests field to given value.


### GetAutoLaunch

`func (o *SystemConfigOAuthDto) GetAutoLaunch() bool`

GetAutoLaunch returns the AutoLaunch field if non-nil, zero value otherwise.

### GetAutoLaunchOk

`func (o *SystemConfigOAuthDto) GetAutoLaunchOk() (*bool, bool)`

GetAutoLaunchOk returns a tuple with the AutoLaunch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoLaunch

`func (o *SystemConfigOAuthDto) SetAutoLaunch(v bool)`

SetAutoLaunch sets AutoLaunch field to given value.


### GetAutoRegister

`func (o *SystemConfigOAuthDto) GetAutoRegister() bool`

GetAutoRegister returns the AutoRegister field if non-nil, zero value otherwise.

### GetAutoRegisterOk

`func (o *SystemConfigOAuthDto) GetAutoRegisterOk() (*bool, bool)`

GetAutoRegisterOk returns a tuple with the AutoRegister field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRegister

`func (o *SystemConfigOAuthDto) SetAutoRegister(v bool)`

SetAutoRegister sets AutoRegister field to given value.


### GetButtonText

`func (o *SystemConfigOAuthDto) GetButtonText() string`

GetButtonText returns the ButtonText field if non-nil, zero value otherwise.

### GetButtonTextOk

`func (o *SystemConfigOAuthDto) GetButtonTextOk() (*string, bool)`

GetButtonTextOk returns a tuple with the ButtonText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtonText

`func (o *SystemConfigOAuthDto) SetButtonText(v string)`

SetButtonText sets ButtonText field to given value.


### GetClientId

`func (o *SystemConfigOAuthDto) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *SystemConfigOAuthDto) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *SystemConfigOAuthDto) SetClientId(v string)`

SetClientId sets ClientId field to given value.


### GetClientSecret

`func (o *SystemConfigOAuthDto) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *SystemConfigOAuthDto) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *SystemConfigOAuthDto) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.


### GetDefaultStorageQuota

`func (o *SystemConfigOAuthDto) GetDefaultStorageQuota() int32`

GetDefaultStorageQuota returns the DefaultStorageQuota field if non-nil, zero value otherwise.

### GetDefaultStorageQuotaOk

`func (o *SystemConfigOAuthDto) GetDefaultStorageQuotaOk() (*int32, bool)`

GetDefaultStorageQuotaOk returns a tuple with the DefaultStorageQuota field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultStorageQuota

`func (o *SystemConfigOAuthDto) SetDefaultStorageQuota(v int32)`

SetDefaultStorageQuota sets DefaultStorageQuota field to given value.


### SetDefaultStorageQuotaNil

`func (o *SystemConfigOAuthDto) SetDefaultStorageQuotaNil(b bool)`

 SetDefaultStorageQuotaNil sets the value for DefaultStorageQuota to be an explicit nil

### UnsetDefaultStorageQuota
`func (o *SystemConfigOAuthDto) UnsetDefaultStorageQuota()`

UnsetDefaultStorageQuota ensures that no value is present for DefaultStorageQuota, not even an explicit nil
### GetEnabled

`func (o *SystemConfigOAuthDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigOAuthDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigOAuthDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetEndSessionEndpoint

`func (o *SystemConfigOAuthDto) GetEndSessionEndpoint() string`

GetEndSessionEndpoint returns the EndSessionEndpoint field if non-nil, zero value otherwise.

### GetEndSessionEndpointOk

`func (o *SystemConfigOAuthDto) GetEndSessionEndpointOk() (*string, bool)`

GetEndSessionEndpointOk returns a tuple with the EndSessionEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndSessionEndpoint

`func (o *SystemConfigOAuthDto) SetEndSessionEndpoint(v string)`

SetEndSessionEndpoint sets EndSessionEndpoint field to given value.


### GetIssuerUrl

`func (o *SystemConfigOAuthDto) GetIssuerUrl() string`

GetIssuerUrl returns the IssuerUrl field if non-nil, zero value otherwise.

### GetIssuerUrlOk

`func (o *SystemConfigOAuthDto) GetIssuerUrlOk() (*string, bool)`

GetIssuerUrlOk returns a tuple with the IssuerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerUrl

`func (o *SystemConfigOAuthDto) SetIssuerUrl(v string)`

SetIssuerUrl sets IssuerUrl field to given value.


### GetMobileOverrideEnabled

`func (o *SystemConfigOAuthDto) GetMobileOverrideEnabled() bool`

GetMobileOverrideEnabled returns the MobileOverrideEnabled field if non-nil, zero value otherwise.

### GetMobileOverrideEnabledOk

`func (o *SystemConfigOAuthDto) GetMobileOverrideEnabledOk() (*bool, bool)`

GetMobileOverrideEnabledOk returns a tuple with the MobileOverrideEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileOverrideEnabled

`func (o *SystemConfigOAuthDto) SetMobileOverrideEnabled(v bool)`

SetMobileOverrideEnabled sets MobileOverrideEnabled field to given value.


### GetMobileRedirectUri

`func (o *SystemConfigOAuthDto) GetMobileRedirectUri() string`

GetMobileRedirectUri returns the MobileRedirectUri field if non-nil, zero value otherwise.

### GetMobileRedirectUriOk

`func (o *SystemConfigOAuthDto) GetMobileRedirectUriOk() (*string, bool)`

GetMobileRedirectUriOk returns a tuple with the MobileRedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileRedirectUri

`func (o *SystemConfigOAuthDto) SetMobileRedirectUri(v string)`

SetMobileRedirectUri sets MobileRedirectUri field to given value.


### GetProfileSigningAlgorithm

`func (o *SystemConfigOAuthDto) GetProfileSigningAlgorithm() string`

GetProfileSigningAlgorithm returns the ProfileSigningAlgorithm field if non-nil, zero value otherwise.

### GetProfileSigningAlgorithmOk

`func (o *SystemConfigOAuthDto) GetProfileSigningAlgorithmOk() (*string, bool)`

GetProfileSigningAlgorithmOk returns a tuple with the ProfileSigningAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileSigningAlgorithm

`func (o *SystemConfigOAuthDto) SetProfileSigningAlgorithm(v string)`

SetProfileSigningAlgorithm sets ProfileSigningAlgorithm field to given value.


### GetPrompt

`func (o *SystemConfigOAuthDto) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *SystemConfigOAuthDto) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *SystemConfigOAuthDto) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetRoleClaim

`func (o *SystemConfigOAuthDto) GetRoleClaim() string`

GetRoleClaim returns the RoleClaim field if non-nil, zero value otherwise.

### GetRoleClaimOk

`func (o *SystemConfigOAuthDto) GetRoleClaimOk() (*string, bool)`

GetRoleClaimOk returns a tuple with the RoleClaim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleClaim

`func (o *SystemConfigOAuthDto) SetRoleClaim(v string)`

SetRoleClaim sets RoleClaim field to given value.


### GetScope

`func (o *SystemConfigOAuthDto) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *SystemConfigOAuthDto) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *SystemConfigOAuthDto) SetScope(v string)`

SetScope sets Scope field to given value.


### GetSigningAlgorithm

`func (o *SystemConfigOAuthDto) GetSigningAlgorithm() string`

GetSigningAlgorithm returns the SigningAlgorithm field if non-nil, zero value otherwise.

### GetSigningAlgorithmOk

`func (o *SystemConfigOAuthDto) GetSigningAlgorithmOk() (*string, bool)`

GetSigningAlgorithmOk returns a tuple with the SigningAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSigningAlgorithm

`func (o *SystemConfigOAuthDto) SetSigningAlgorithm(v string)`

SetSigningAlgorithm sets SigningAlgorithm field to given value.


### GetStorageLabelClaim

`func (o *SystemConfigOAuthDto) GetStorageLabelClaim() string`

GetStorageLabelClaim returns the StorageLabelClaim field if non-nil, zero value otherwise.

### GetStorageLabelClaimOk

`func (o *SystemConfigOAuthDto) GetStorageLabelClaimOk() (*string, bool)`

GetStorageLabelClaimOk returns a tuple with the StorageLabelClaim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageLabelClaim

`func (o *SystemConfigOAuthDto) SetStorageLabelClaim(v string)`

SetStorageLabelClaim sets StorageLabelClaim field to given value.


### GetStorageQuotaClaim

`func (o *SystemConfigOAuthDto) GetStorageQuotaClaim() string`

GetStorageQuotaClaim returns the StorageQuotaClaim field if non-nil, zero value otherwise.

### GetStorageQuotaClaimOk

`func (o *SystemConfigOAuthDto) GetStorageQuotaClaimOk() (*string, bool)`

GetStorageQuotaClaimOk returns a tuple with the StorageQuotaClaim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageQuotaClaim

`func (o *SystemConfigOAuthDto) SetStorageQuotaClaim(v string)`

SetStorageQuotaClaim sets StorageQuotaClaim field to given value.


### GetTimeout

`func (o *SystemConfigOAuthDto) GetTimeout() int32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *SystemConfigOAuthDto) GetTimeoutOk() (*int32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *SystemConfigOAuthDto) SetTimeout(v int32)`

SetTimeout sets Timeout field to given value.


### GetTokenEndpointAuthMethod

`func (o *SystemConfigOAuthDto) GetTokenEndpointAuthMethod() OAuthTokenEndpointAuthMethod`

GetTokenEndpointAuthMethod returns the TokenEndpointAuthMethod field if non-nil, zero value otherwise.

### GetTokenEndpointAuthMethodOk

`func (o *SystemConfigOAuthDto) GetTokenEndpointAuthMethodOk() (*OAuthTokenEndpointAuthMethod, bool)`

GetTokenEndpointAuthMethodOk returns a tuple with the TokenEndpointAuthMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenEndpointAuthMethod

`func (o *SystemConfigOAuthDto) SetTokenEndpointAuthMethod(v OAuthTokenEndpointAuthMethod)`

SetTokenEndpointAuthMethod sets TokenEndpointAuthMethod field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


