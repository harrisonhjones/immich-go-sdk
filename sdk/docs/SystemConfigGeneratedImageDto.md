# SystemConfigGeneratedImageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | [**ImageFormat**](ImageFormat.md) |  | 
**Progressive** | Pointer to **bool** | Progressive | [optional] 
**Quality** | **int32** | Quality | 
**Size** | **int32** | Size | 

## Methods

### NewSystemConfigGeneratedImageDto

`func NewSystemConfigGeneratedImageDto(format ImageFormat, quality int32, size int32, ) *SystemConfigGeneratedImageDto`

NewSystemConfigGeneratedImageDto instantiates a new SystemConfigGeneratedImageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigGeneratedImageDtoWithDefaults

`func NewSystemConfigGeneratedImageDtoWithDefaults() *SystemConfigGeneratedImageDto`

NewSystemConfigGeneratedImageDtoWithDefaults instantiates a new SystemConfigGeneratedImageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *SystemConfigGeneratedImageDto) GetFormat() ImageFormat`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *SystemConfigGeneratedImageDto) GetFormatOk() (*ImageFormat, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *SystemConfigGeneratedImageDto) SetFormat(v ImageFormat)`

SetFormat sets Format field to given value.


### GetProgressive

`func (o *SystemConfigGeneratedImageDto) GetProgressive() bool`

GetProgressive returns the Progressive field if non-nil, zero value otherwise.

### GetProgressiveOk

`func (o *SystemConfigGeneratedImageDto) GetProgressiveOk() (*bool, bool)`

GetProgressiveOk returns a tuple with the Progressive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressive

`func (o *SystemConfigGeneratedImageDto) SetProgressive(v bool)`

SetProgressive sets Progressive field to given value.

### HasProgressive

`func (o *SystemConfigGeneratedImageDto) HasProgressive() bool`

HasProgressive returns a boolean if a field has been set.

### GetQuality

`func (o *SystemConfigGeneratedImageDto) GetQuality() int32`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *SystemConfigGeneratedImageDto) GetQualityOk() (*int32, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *SystemConfigGeneratedImageDto) SetQuality(v int32)`

SetQuality sets Quality field to given value.


### GetSize

`func (o *SystemConfigGeneratedImageDto) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *SystemConfigGeneratedImageDto) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *SystemConfigGeneratedImageDto) SetSize(v int32)`

SetSize sets Size field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


