# DuplicateDetectionConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether the task is enabled | 
**MaxDistance** | **float64** | Maximum distance threshold for duplicate detection | 

## Methods

### NewDuplicateDetectionConfig

`func NewDuplicateDetectionConfig(enabled bool, maxDistance float64, ) *DuplicateDetectionConfig`

NewDuplicateDetectionConfig instantiates a new DuplicateDetectionConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuplicateDetectionConfigWithDefaults

`func NewDuplicateDetectionConfigWithDefaults() *DuplicateDetectionConfig`

NewDuplicateDetectionConfigWithDefaults instantiates a new DuplicateDetectionConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *DuplicateDetectionConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DuplicateDetectionConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DuplicateDetectionConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMaxDistance

`func (o *DuplicateDetectionConfig) GetMaxDistance() float64`

GetMaxDistance returns the MaxDistance field if non-nil, zero value otherwise.

### GetMaxDistanceOk

`func (o *DuplicateDetectionConfig) GetMaxDistanceOk() (*float64, bool)`

GetMaxDistanceOk returns a tuple with the MaxDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDistance

`func (o *DuplicateDetectionConfig) SetMaxDistance(v float64)`

SetMaxDistance sets MaxDistance field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


