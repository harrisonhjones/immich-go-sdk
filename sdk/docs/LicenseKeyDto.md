# LicenseKeyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivationKey** | **string** | Activation key | 
**LicenseKey** | **string** | License key (format: /^IM(SV|CL)(-[\\dA-Za-z]{4}){8}$/) | 

## Methods

### NewLicenseKeyDto

`func NewLicenseKeyDto(activationKey string, licenseKey string, ) *LicenseKeyDto`

NewLicenseKeyDto instantiates a new LicenseKeyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseKeyDtoWithDefaults

`func NewLicenseKeyDtoWithDefaults() *LicenseKeyDto`

NewLicenseKeyDtoWithDefaults instantiates a new LicenseKeyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivationKey

`func (o *LicenseKeyDto) GetActivationKey() string`

GetActivationKey returns the ActivationKey field if non-nil, zero value otherwise.

### GetActivationKeyOk

`func (o *LicenseKeyDto) GetActivationKeyOk() (*string, bool)`

GetActivationKeyOk returns a tuple with the ActivationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationKey

`func (o *LicenseKeyDto) SetActivationKey(v string)`

SetActivationKey sets ActivationKey field to given value.


### GetLicenseKey

`func (o *LicenseKeyDto) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *LicenseKeyDto) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *LicenseKeyDto) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


