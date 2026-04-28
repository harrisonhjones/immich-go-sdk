# OcrConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether the task is enabled | 
**MaxResolution** | **int32** | Maximum resolution for OCR processing | 
**MinDetectionScore** | **float64** | Minimum confidence score for text detection | 
**MinRecognitionScore** | **float64** | Minimum confidence score for text recognition | 
**ModelName** | **string** | Name of the model to use | 

## Methods

### NewOcrConfig

`func NewOcrConfig(enabled bool, maxResolution int32, minDetectionScore float64, minRecognitionScore float64, modelName string, ) *OcrConfig`

NewOcrConfig instantiates a new OcrConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOcrConfigWithDefaults

`func NewOcrConfigWithDefaults() *OcrConfig`

NewOcrConfigWithDefaults instantiates a new OcrConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *OcrConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *OcrConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *OcrConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMaxResolution

`func (o *OcrConfig) GetMaxResolution() int32`

GetMaxResolution returns the MaxResolution field if non-nil, zero value otherwise.

### GetMaxResolutionOk

`func (o *OcrConfig) GetMaxResolutionOk() (*int32, bool)`

GetMaxResolutionOk returns a tuple with the MaxResolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxResolution

`func (o *OcrConfig) SetMaxResolution(v int32)`

SetMaxResolution sets MaxResolution field to given value.


### GetMinDetectionScore

`func (o *OcrConfig) GetMinDetectionScore() float64`

GetMinDetectionScore returns the MinDetectionScore field if non-nil, zero value otherwise.

### GetMinDetectionScoreOk

`func (o *OcrConfig) GetMinDetectionScoreOk() (*float64, bool)`

GetMinDetectionScoreOk returns a tuple with the MinDetectionScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinDetectionScore

`func (o *OcrConfig) SetMinDetectionScore(v float64)`

SetMinDetectionScore sets MinDetectionScore field to given value.


### GetMinRecognitionScore

`func (o *OcrConfig) GetMinRecognitionScore() float64`

GetMinRecognitionScore returns the MinRecognitionScore field if non-nil, zero value otherwise.

### GetMinRecognitionScoreOk

`func (o *OcrConfig) GetMinRecognitionScoreOk() (*float64, bool)`

GetMinRecognitionScoreOk returns a tuple with the MinRecognitionScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRecognitionScore

`func (o *OcrConfig) SetMinRecognitionScore(v float64)`

SetMinRecognitionScore sets MinRecognitionScore field to given value.


### GetModelName

`func (o *OcrConfig) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *OcrConfig) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *OcrConfig) SetModelName(v string)`

SetModelName sets ModelName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


