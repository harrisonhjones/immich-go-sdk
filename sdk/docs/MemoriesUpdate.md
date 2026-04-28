# MemoriesUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Duration** | Pointer to **int32** | Memory duration in seconds | [optional] 
**Enabled** | Pointer to **bool** | Whether memories are enabled | [optional] 

## Methods

### NewMemoriesUpdate

`func NewMemoriesUpdate() *MemoriesUpdate`

NewMemoriesUpdate instantiates a new MemoriesUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMemoriesUpdateWithDefaults

`func NewMemoriesUpdateWithDefaults() *MemoriesUpdate`

NewMemoriesUpdateWithDefaults instantiates a new MemoriesUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuration

`func (o *MemoriesUpdate) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *MemoriesUpdate) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *MemoriesUpdate) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *MemoriesUpdate) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### GetEnabled

`func (o *MemoriesUpdate) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *MemoriesUpdate) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *MemoriesUpdate) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *MemoriesUpdate) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


