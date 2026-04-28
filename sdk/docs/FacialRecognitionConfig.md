# FacialRecognitionConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether the task is enabled | 
**MaxDistance** | **float64** | Maximum distance threshold for face recognition | 
**MinFaces** | **int32** | Minimum number of faces required for recognition | 
**MinScore** | **float64** | Minimum confidence score for face detection | 
**ModelName** | **string** | Name of the model to use | 

## Methods

### NewFacialRecognitionConfig

`func NewFacialRecognitionConfig(enabled bool, maxDistance float64, minFaces int32, minScore float64, modelName string, ) *FacialRecognitionConfig`

NewFacialRecognitionConfig instantiates a new FacialRecognitionConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFacialRecognitionConfigWithDefaults

`func NewFacialRecognitionConfigWithDefaults() *FacialRecognitionConfig`

NewFacialRecognitionConfigWithDefaults instantiates a new FacialRecognitionConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *FacialRecognitionConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FacialRecognitionConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FacialRecognitionConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMaxDistance

`func (o *FacialRecognitionConfig) GetMaxDistance() float64`

GetMaxDistance returns the MaxDistance field if non-nil, zero value otherwise.

### GetMaxDistanceOk

`func (o *FacialRecognitionConfig) GetMaxDistanceOk() (*float64, bool)`

GetMaxDistanceOk returns a tuple with the MaxDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDistance

`func (o *FacialRecognitionConfig) SetMaxDistance(v float64)`

SetMaxDistance sets MaxDistance field to given value.


### GetMinFaces

`func (o *FacialRecognitionConfig) GetMinFaces() int32`

GetMinFaces returns the MinFaces field if non-nil, zero value otherwise.

### GetMinFacesOk

`func (o *FacialRecognitionConfig) GetMinFacesOk() (*int32, bool)`

GetMinFacesOk returns a tuple with the MinFaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinFaces

`func (o *FacialRecognitionConfig) SetMinFaces(v int32)`

SetMinFaces sets MinFaces field to given value.


### GetMinScore

`func (o *FacialRecognitionConfig) GetMinScore() float64`

GetMinScore returns the MinScore field if non-nil, zero value otherwise.

### GetMinScoreOk

`func (o *FacialRecognitionConfig) GetMinScoreOk() (*float64, bool)`

GetMinScoreOk returns a tuple with the MinScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinScore

`func (o *FacialRecognitionConfig) SetMinScore(v float64)`

SetMinScore sets MinScore field to given value.


### GetModelName

`func (o *FacialRecognitionConfig) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *FacialRecognitionConfig) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *FacialRecognitionConfig) SetModelName(v string)`

SetModelName sets ModelName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


