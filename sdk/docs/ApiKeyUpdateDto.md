# ApiKeyUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | API key name | [optional] 
**Permissions** | Pointer to [**[]Permission**](Permission.md) | List of permissions | [optional] 

## Methods

### NewApiKeyUpdateDto

`func NewApiKeyUpdateDto() *ApiKeyUpdateDto`

NewApiKeyUpdateDto instantiates a new ApiKeyUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyUpdateDtoWithDefaults

`func NewApiKeyUpdateDtoWithDefaults() *ApiKeyUpdateDto`

NewApiKeyUpdateDtoWithDefaults instantiates a new ApiKeyUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ApiKeyUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiKeyUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiKeyUpdateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ApiKeyUpdateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPermissions

`func (o *ApiKeyUpdateDto) GetPermissions() []Permission`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *ApiKeyUpdateDto) GetPermissionsOk() (*[]Permission, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *ApiKeyUpdateDto) SetPermissions(v []Permission)`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *ApiKeyUpdateDto) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


