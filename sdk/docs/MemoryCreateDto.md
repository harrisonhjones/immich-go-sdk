# MemoryCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetIds** | Pointer to **[]string** | Asset IDs to associate with memory | [optional] 
**Data** | [**OnThisDayDto**](OnThisDayDto.md) |  | 
**HideAt** | Pointer to **time.Time** | Date when memory should be hidden | [optional] 
**IsSaved** | Pointer to **bool** | Is memory saved | [optional] 
**MemoryAt** | **time.Time** | Memory date | 
**SeenAt** | Pointer to **time.Time** | Date when memory was seen | [optional] 
**ShowAt** | Pointer to **time.Time** | Date when memory should be shown | [optional] 
**Type** | [**MemoryType**](MemoryType.md) |  | 

## Methods

### NewMemoryCreateDto

`func NewMemoryCreateDto(data OnThisDayDto, memoryAt time.Time, type_ MemoryType, ) *MemoryCreateDto`

NewMemoryCreateDto instantiates a new MemoryCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMemoryCreateDtoWithDefaults

`func NewMemoryCreateDtoWithDefaults() *MemoryCreateDto`

NewMemoryCreateDtoWithDefaults instantiates a new MemoryCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetIds

`func (o *MemoryCreateDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *MemoryCreateDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *MemoryCreateDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.

### HasAssetIds

`func (o *MemoryCreateDto) HasAssetIds() bool`

HasAssetIds returns a boolean if a field has been set.

### GetData

`func (o *MemoryCreateDto) GetData() OnThisDayDto`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MemoryCreateDto) GetDataOk() (*OnThisDayDto, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MemoryCreateDto) SetData(v OnThisDayDto)`

SetData sets Data field to given value.


### GetHideAt

`func (o *MemoryCreateDto) GetHideAt() time.Time`

GetHideAt returns the HideAt field if non-nil, zero value otherwise.

### GetHideAtOk

`func (o *MemoryCreateDto) GetHideAtOk() (*time.Time, bool)`

GetHideAtOk returns a tuple with the HideAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideAt

`func (o *MemoryCreateDto) SetHideAt(v time.Time)`

SetHideAt sets HideAt field to given value.

### HasHideAt

`func (o *MemoryCreateDto) HasHideAt() bool`

HasHideAt returns a boolean if a field has been set.

### GetIsSaved

`func (o *MemoryCreateDto) GetIsSaved() bool`

GetIsSaved returns the IsSaved field if non-nil, zero value otherwise.

### GetIsSavedOk

`func (o *MemoryCreateDto) GetIsSavedOk() (*bool, bool)`

GetIsSavedOk returns a tuple with the IsSaved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSaved

`func (o *MemoryCreateDto) SetIsSaved(v bool)`

SetIsSaved sets IsSaved field to given value.

### HasIsSaved

`func (o *MemoryCreateDto) HasIsSaved() bool`

HasIsSaved returns a boolean if a field has been set.

### GetMemoryAt

`func (o *MemoryCreateDto) GetMemoryAt() time.Time`

GetMemoryAt returns the MemoryAt field if non-nil, zero value otherwise.

### GetMemoryAtOk

`func (o *MemoryCreateDto) GetMemoryAtOk() (*time.Time, bool)`

GetMemoryAtOk returns a tuple with the MemoryAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAt

`func (o *MemoryCreateDto) SetMemoryAt(v time.Time)`

SetMemoryAt sets MemoryAt field to given value.


### GetSeenAt

`func (o *MemoryCreateDto) GetSeenAt() time.Time`

GetSeenAt returns the SeenAt field if non-nil, zero value otherwise.

### GetSeenAtOk

`func (o *MemoryCreateDto) GetSeenAtOk() (*time.Time, bool)`

GetSeenAtOk returns a tuple with the SeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeenAt

`func (o *MemoryCreateDto) SetSeenAt(v time.Time)`

SetSeenAt sets SeenAt field to given value.

### HasSeenAt

`func (o *MemoryCreateDto) HasSeenAt() bool`

HasSeenAt returns a boolean if a field has been set.

### GetShowAt

`func (o *MemoryCreateDto) GetShowAt() time.Time`

GetShowAt returns the ShowAt field if non-nil, zero value otherwise.

### GetShowAtOk

`func (o *MemoryCreateDto) GetShowAtOk() (*time.Time, bool)`

GetShowAtOk returns a tuple with the ShowAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowAt

`func (o *MemoryCreateDto) SetShowAt(v time.Time)`

SetShowAt sets ShowAt field to given value.

### HasShowAt

`func (o *MemoryCreateDto) HasShowAt() bool`

HasShowAt returns a boolean if a field has been set.

### GetType

`func (o *MemoryCreateDto) GetType() MemoryType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MemoryCreateDto) GetTypeOk() (*MemoryType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MemoryCreateDto) SetType(v MemoryType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


