# MemoryUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsSaved** | Pointer to **bool** | Is memory saved | [optional] 
**MemoryAt** | Pointer to **time.Time** | Memory date | [optional] 
**SeenAt** | Pointer to **time.Time** | Date when memory was seen | [optional] 

## Methods

### NewMemoryUpdateDto

`func NewMemoryUpdateDto() *MemoryUpdateDto`

NewMemoryUpdateDto instantiates a new MemoryUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMemoryUpdateDtoWithDefaults

`func NewMemoryUpdateDtoWithDefaults() *MemoryUpdateDto`

NewMemoryUpdateDtoWithDefaults instantiates a new MemoryUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsSaved

`func (o *MemoryUpdateDto) GetIsSaved() bool`

GetIsSaved returns the IsSaved field if non-nil, zero value otherwise.

### GetIsSavedOk

`func (o *MemoryUpdateDto) GetIsSavedOk() (*bool, bool)`

GetIsSavedOk returns a tuple with the IsSaved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSaved

`func (o *MemoryUpdateDto) SetIsSaved(v bool)`

SetIsSaved sets IsSaved field to given value.

### HasIsSaved

`func (o *MemoryUpdateDto) HasIsSaved() bool`

HasIsSaved returns a boolean if a field has been set.

### GetMemoryAt

`func (o *MemoryUpdateDto) GetMemoryAt() time.Time`

GetMemoryAt returns the MemoryAt field if non-nil, zero value otherwise.

### GetMemoryAtOk

`func (o *MemoryUpdateDto) GetMemoryAtOk() (*time.Time, bool)`

GetMemoryAtOk returns a tuple with the MemoryAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAt

`func (o *MemoryUpdateDto) SetMemoryAt(v time.Time)`

SetMemoryAt sets MemoryAt field to given value.

### HasMemoryAt

`func (o *MemoryUpdateDto) HasMemoryAt() bool`

HasMemoryAt returns a boolean if a field has been set.

### GetSeenAt

`func (o *MemoryUpdateDto) GetSeenAt() time.Time`

GetSeenAt returns the SeenAt field if non-nil, zero value otherwise.

### GetSeenAtOk

`func (o *MemoryUpdateDto) GetSeenAtOk() (*time.Time, bool)`

GetSeenAtOk returns a tuple with the SeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeenAt

`func (o *MemoryUpdateDto) SetSeenAt(v time.Time)`

SetSeenAt sets SeenAt field to given value.

### HasSeenAt

`func (o *MemoryUpdateDto) HasSeenAt() bool`

HasSeenAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


