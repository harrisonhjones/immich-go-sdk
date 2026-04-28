# SystemConfigMachineLearningDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvailabilityChecks** | [**MachineLearningAvailabilityChecksDto**](MachineLearningAvailabilityChecksDto.md) |  | 
**Clip** | [**CLIPConfig**](CLIPConfig.md) |  | 
**DuplicateDetection** | [**DuplicateDetectionConfig**](DuplicateDetectionConfig.md) |  | 
**Enabled** | **bool** | Enabled | 
**FacialRecognition** | [**FacialRecognitionConfig**](FacialRecognitionConfig.md) |  | 
**Ocr** | [**OcrConfig**](OcrConfig.md) |  | 
**Urls** | **[]string** | ML service URLs | 

## Methods

### NewSystemConfigMachineLearningDto

`func NewSystemConfigMachineLearningDto(availabilityChecks MachineLearningAvailabilityChecksDto, clip CLIPConfig, duplicateDetection DuplicateDetectionConfig, enabled bool, facialRecognition FacialRecognitionConfig, ocr OcrConfig, urls []string, ) *SystemConfigMachineLearningDto`

NewSystemConfigMachineLearningDto instantiates a new SystemConfigMachineLearningDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigMachineLearningDtoWithDefaults

`func NewSystemConfigMachineLearningDtoWithDefaults() *SystemConfigMachineLearningDto`

NewSystemConfigMachineLearningDtoWithDefaults instantiates a new SystemConfigMachineLearningDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailabilityChecks

`func (o *SystemConfigMachineLearningDto) GetAvailabilityChecks() MachineLearningAvailabilityChecksDto`

GetAvailabilityChecks returns the AvailabilityChecks field if non-nil, zero value otherwise.

### GetAvailabilityChecksOk

`func (o *SystemConfigMachineLearningDto) GetAvailabilityChecksOk() (*MachineLearningAvailabilityChecksDto, bool)`

GetAvailabilityChecksOk returns a tuple with the AvailabilityChecks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailabilityChecks

`func (o *SystemConfigMachineLearningDto) SetAvailabilityChecks(v MachineLearningAvailabilityChecksDto)`

SetAvailabilityChecks sets AvailabilityChecks field to given value.


### GetClip

`func (o *SystemConfigMachineLearningDto) GetClip() CLIPConfig`

GetClip returns the Clip field if non-nil, zero value otherwise.

### GetClipOk

`func (o *SystemConfigMachineLearningDto) GetClipOk() (*CLIPConfig, bool)`

GetClipOk returns a tuple with the Clip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClip

`func (o *SystemConfigMachineLearningDto) SetClip(v CLIPConfig)`

SetClip sets Clip field to given value.


### GetDuplicateDetection

`func (o *SystemConfigMachineLearningDto) GetDuplicateDetection() DuplicateDetectionConfig`

GetDuplicateDetection returns the DuplicateDetection field if non-nil, zero value otherwise.

### GetDuplicateDetectionOk

`func (o *SystemConfigMachineLearningDto) GetDuplicateDetectionOk() (*DuplicateDetectionConfig, bool)`

GetDuplicateDetectionOk returns a tuple with the DuplicateDetection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateDetection

`func (o *SystemConfigMachineLearningDto) SetDuplicateDetection(v DuplicateDetectionConfig)`

SetDuplicateDetection sets DuplicateDetection field to given value.


### GetEnabled

`func (o *SystemConfigMachineLearningDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SystemConfigMachineLearningDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SystemConfigMachineLearningDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetFacialRecognition

`func (o *SystemConfigMachineLearningDto) GetFacialRecognition() FacialRecognitionConfig`

GetFacialRecognition returns the FacialRecognition field if non-nil, zero value otherwise.

### GetFacialRecognitionOk

`func (o *SystemConfigMachineLearningDto) GetFacialRecognitionOk() (*FacialRecognitionConfig, bool)`

GetFacialRecognitionOk returns a tuple with the FacialRecognition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacialRecognition

`func (o *SystemConfigMachineLearningDto) SetFacialRecognition(v FacialRecognitionConfig)`

SetFacialRecognition sets FacialRecognition field to given value.


### GetOcr

`func (o *SystemConfigMachineLearningDto) GetOcr() OcrConfig`

GetOcr returns the Ocr field if non-nil, zero value otherwise.

### GetOcrOk

`func (o *SystemConfigMachineLearningDto) GetOcrOk() (*OcrConfig, bool)`

GetOcrOk returns a tuple with the Ocr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcr

`func (o *SystemConfigMachineLearningDto) SetOcr(v OcrConfig)`

SetOcr sets Ocr field to given value.


### GetUrls

`func (o *SystemConfigMachineLearningDto) GetUrls() []string`

GetUrls returns the Urls field if non-nil, zero value otherwise.

### GetUrlsOk

`func (o *SystemConfigMachineLearningDto) GetUrlsOk() (*[]string, bool)`

GetUrlsOk returns a tuple with the Urls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrls

`func (o *SystemConfigMachineLearningDto) SetUrls(v []string)`

SetUrls sets Urls field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


