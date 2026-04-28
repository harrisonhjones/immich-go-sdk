# PinCodeChangeDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NewPinCode** | **string** | New PIN code (4-6 digits) | 
**Password** | Pointer to **string** | User password (required if PIN code is not provided) | [optional] 
**PinCode** | Pointer to **string** | New PIN code (4-6 digits) | [optional] 

## Methods

### NewPinCodeChangeDto

`func NewPinCodeChangeDto(newPinCode string, ) *PinCodeChangeDto`

NewPinCodeChangeDto instantiates a new PinCodeChangeDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPinCodeChangeDtoWithDefaults

`func NewPinCodeChangeDtoWithDefaults() *PinCodeChangeDto`

NewPinCodeChangeDtoWithDefaults instantiates a new PinCodeChangeDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNewPinCode

`func (o *PinCodeChangeDto) GetNewPinCode() string`

GetNewPinCode returns the NewPinCode field if non-nil, zero value otherwise.

### GetNewPinCodeOk

`func (o *PinCodeChangeDto) GetNewPinCodeOk() (*string, bool)`

GetNewPinCodeOk returns a tuple with the NewPinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPinCode

`func (o *PinCodeChangeDto) SetNewPinCode(v string)`

SetNewPinCode sets NewPinCode field to given value.


### GetPassword

`func (o *PinCodeChangeDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *PinCodeChangeDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *PinCodeChangeDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *PinCodeChangeDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPinCode

`func (o *PinCodeChangeDto) GetPinCode() string`

GetPinCode returns the PinCode field if non-nil, zero value otherwise.

### GetPinCodeOk

`func (o *PinCodeChangeDto) GetPinCodeOk() (*string, bool)`

GetPinCodeOk returns a tuple with the PinCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinCode

`func (o *PinCodeChangeDto) SetPinCode(v string)`

SetPinCode sets PinCode field to given value.

### HasPinCode

`func (o *PinCodeChangeDto) HasPinCode() bool`

HasPinCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


