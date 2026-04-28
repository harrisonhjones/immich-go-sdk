# UserLicense

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivatedAt** | **time.Time** | Activation date | 
**ActivationKey** | **string** | Activation key | 
**LicenseKey** | **string** | License key (format: /^IM(SV|CL)(-[\\dA-Za-z]{4}){8}$/) | 

## Methods

### NewUserLicense

`func NewUserLicense(activatedAt time.Time, activationKey string, licenseKey string, ) *UserLicense`

NewUserLicense instantiates a new UserLicense object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserLicenseWithDefaults

`func NewUserLicenseWithDefaults() *UserLicense`

NewUserLicenseWithDefaults instantiates a new UserLicense object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivatedAt

`func (o *UserLicense) GetActivatedAt() time.Time`

GetActivatedAt returns the ActivatedAt field if non-nil, zero value otherwise.

### GetActivatedAtOk

`func (o *UserLicense) GetActivatedAtOk() (*time.Time, bool)`

GetActivatedAtOk returns a tuple with the ActivatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivatedAt

`func (o *UserLicense) SetActivatedAt(v time.Time)`

SetActivatedAt sets ActivatedAt field to given value.


### GetActivationKey

`func (o *UserLicense) GetActivationKey() string`

GetActivationKey returns the ActivationKey field if non-nil, zero value otherwise.

### GetActivationKeyOk

`func (o *UserLicense) GetActivationKeyOk() (*string, bool)`

GetActivationKeyOk returns a tuple with the ActivationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivationKey

`func (o *UserLicense) SetActivationKey(v string)`

SetActivationKey sets ActivationKey field to given value.


### GetLicenseKey

`func (o *UserLicense) GetLicenseKey() string`

GetLicenseKey returns the LicenseKey field if non-nil, zero value otherwise.

### GetLicenseKeyOk

`func (o *UserLicense) GetLicenseKeyOk() (*string, bool)`

GetLicenseKeyOk returns a tuple with the LicenseKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseKey

`func (o *UserLicense) SetLicenseKey(v string)`

SetLicenseKey sets LicenseKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


