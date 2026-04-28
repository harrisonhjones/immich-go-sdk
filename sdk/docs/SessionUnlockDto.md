# SessionUnlockDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Password** | Pointer to **string** | User password (required if PIN code is not provided) | [optional] 
**PinCode** | Pointer to **string** | New PIN code (4-6 digits) | [optional] 

## Methods

### NewSessionUnlockDto

`func NewSessionUnlockDto() *SessionUnlockDto`

NewSessionUnlockDto instantiates a new SessionUnlockDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionUnlockDtoWithDefaults

`func NewSessionUnlockDtoWithDefaults() *SessionUnlockDto`

NewSessionUnlockDtoWithDefaults instantiates a new SessionUnlockDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPassword

`func (o *SessionUnlockDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *SessionUnlockDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *SessionUnlockDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *SessionUnlockDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPinCode

`func (o *SessionUnlockDto) GetPinCode() string`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *SessionUnlockDto) GetPinCodeOk() (*string, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *SessionUnlockDto) SetPinCode(v string)`

SetPinCode sets PinCode field to given value.

### HasPinCode

`func (o *SessionUnlockDto) HasPinCode() bool`

HasPinCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


