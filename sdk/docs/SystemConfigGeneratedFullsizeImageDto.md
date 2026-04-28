# SystemConfigGeneratedFullsizeImageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Enabled | 
**Format** | [**ImageFormat**](ImageFormat.md) |  | 
**Progressive** | Pointer to **bool** | Progressive | [optional] 
**Quality** | **int32** | Quality | 

## Methods

### NewSystemConfigGeneratedFullsizeImageDto

`func NewSystemConfigGeneratedFullsizeImageDto(enabled bool, format ImageFormat, quality int32, ) *SystemConfigGeneratedFullsizeImageDto`

NewSystemConfigGeneratedFullsizeImageDto instantiates a new SystemConfigGeneratedFullsizeImageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigGeneratedFullsizeImageDtoWithDefaults

`func NewSystemConfigGeneratedFullsizeImageDtoWithDefaults() *SystemConfigGeneratedFullsizeImageDto`

NewSystemConfigGeneratedFullsizeImageDtoWithDefaults instantiates a new SystemConfigGeneratedFullsizeImageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *SystemConfigGeneratedFullsizeImageDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigGeneratedFullsizeImageDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigGeneratedFullsizeImageDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetFormat

`func (o *SystemConfigGeneratedFullsizeImageDto) GetFormat() ImageFormat`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *SystemConfigGeneratedFullsizeImageDto) GetFormatOk() (*ImageFormat, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *SystemConfigGeneratedFullsizeImageDto) SetFormat(v ImageFormat)`

SetFormat sets Format field to given value.


### GetProgressive

`func (o *SystemConfigGeneratedFullsizeImageDto) GetProgressive() bool`

GetProgressive returns the Progressive field if non-nil, zero value otherwise.

### GetProgressiveOk

`func (o *SystemConfigGeneratedFullsizeImageDto) GetProgressiveOk() (*bool, bool)`

GetProgressiveOk returns a tuple with the Progressive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressive

`func (o *SystemConfigGeneratedFullsizeImageDto) SetProgressive(v bool)`

SetProgressive sets Progressive field to given value.

### HasProgressive

`func (o *SystemConfigGeneratedFullsizeImageDto) HasProgressive() bool`

HasProgressive returns a boolean if a field has been set.

### GetQuality

`func (o *SystemConfigGeneratedFullsizeImageDto) GetQuality() int32`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *SystemConfigGeneratedFullsizeImageDto) GetQualityOk() (*int32, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *SystemConfigGeneratedFullsizeImageDto) SetQuality(v int32)`

SetQuality sets Quality field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


