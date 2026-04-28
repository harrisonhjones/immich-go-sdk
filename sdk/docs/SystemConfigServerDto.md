# SystemConfigServerDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalDomain** | **string** | External domain | 
**LoginPageMessage** | **string** | Login page message | 
**PublicUsers** | **bool** | Public users | 

## Methods

### NewSystemConfigServerDto

`func NewSystemConfigServerDto(externalDomain string, loginPageMessage string, publicUsers bool, ) *SystemConfigServerDto`

NewSystemConfigServerDto instantiates a new SystemConfigServerDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigServerDtoWithDefaults

`func NewSystemConfigServerDtoWithDefaults() *SystemConfigServerDto`

NewSystemConfigServerDtoWithDefaults instantiates a new SystemConfigServerDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalDomain

`func (o *SystemConfigServerDto) GetExternalDomain() string`

GetExternalDomain returns the ExternalDomain field if non-nil, zero value otherwise.

### GetExternalDomainOk

`func (o *SystemConfigServerDto) GetExternalDomainOk() (*string, bool)`

GetExternalDomainOk returns a tuple with the ExternalDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalDomain

`func (o *SystemConfigServerDto) SetExternalDomain(v string)`

SetExternalDomain sets ExternalDomain field to given value.


### GetLoginPageMessage

`func (o *SystemConfigServerDto) GetLoginPageMessage() string`

GetLoginPageMessage returns the LoginPageMessage field if non-nil, zero value otherwise.

### GetLoginPageMessageOk

`func (o *SystemConfigServerDto) GetLoginPageMessageOk() (*string, bool)`

GetLoginPageMessageOk returns a tuple with the LoginPageMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginPageMessage

`func (o *SystemConfigServerDto) SetLoginPageMessage(v string)`

SetLoginPageMessage sets LoginPageMessage field to given value.


### GetPublicUsers

`func (o *SystemConfigServerDto) GetPublicUsers() bool`

GetPublicUsers returns the PublicUsers field if non-nil, zero value otherwise.

### GetPublicUsersOk

`func (o *SystemConfigServerDto) GetPublicUsersOk() (*bool, bool)`

GetPublicUsersOk returns a tuple with the PublicUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicUsers

`func (o *SystemConfigServerDto) SetPublicUsers(v bool)`

SetPublicUsers sets PublicUsers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


