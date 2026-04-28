# MemoryResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assets** | [**[]AssetResponseDto**](AssetResponseDto.md) |  | 
**CreatedAt** | **time.Time** | Creation date | 
**Data** | [**OnThisDayDto**](OnThisDayDto.md) |  | 
**DeletedAt** | Pointer to **time.Time** | Deletion date | [optional] 
**HideAt** | Pointer to **time.Time** | Date when memory should be hidden | [optional] 
**Id** | **string** | Memory ID | 
**IsSaved** | **bool** | Is memory saved | 
**MemoryAt** | **time.Time** | Memory date | 
**OwnerId** | **string** | Owner user ID | 
**SeenAt** | Pointer to **time.Time** | Date when memory was seen | [optional] 
**ShowAt** | Pointer to **time.Time** | Date when memory should be shown | [optional] 
**Type** | [**MemoryType**](MemoryType.md) |  | 
**UpdatedAt** | **time.Time** | Last update date | 

## Methods

### NewMemoryResponseDto

`func NewMemoryResponseDto(assets []AssetResponseDto, createdAt time.Time, data OnThisDayDto, id string, isSaved bool, memoryAt time.Time, ownerId string, type_ MemoryType, updatedAt time.Time, ) *MemoryResponseDto`

NewMemoryResponseDto instantiates a new MemoryResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMemoryResponseDtoWithDefaults

`func NewMemoryResponseDtoWithDefaults() *MemoryResponseDto`

NewMemoryResponseDtoWithDefaults instantiates a new MemoryResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssets

`func (o *MemoryResponseDto) GetAssets() []AssetResponseDto`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *MemoryResponseDto) GetAssetsOk() (*[]AssetResponseDto, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *MemoryResponseDto) SetAssets(v []AssetResponseDto)`

SetAssets sets Assets field to given value.


### GetCreatedAt

`func (o *MemoryResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MemoryResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MemoryResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetData

`func (o *MemoryResponseDto) GetData() OnThisDayDto`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MemoryResponseDto) GetDataOk() (*OnThisDayDto, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MemoryResponseDto) SetData(v OnThisDayDto)`

SetData sets Data field to given value.


### GetDeletedAt

`func (o *MemoryResponseDto) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *MemoryResponseDto) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *MemoryResponseDto) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *MemoryResponseDto) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetHideAt

`func (o *MemoryResponseDto) GetHideAt() time.Time`

GetHideAt returns the HideAt field if non-nil, zero value otherwise.

### GetHideAtOk

`func (o *MemoryResponseDto) GetHideAtOk() (*time.Time, bool)`

GetHideAtOk returns a tuple with the HideAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideAt

`func (o *MemoryResponseDto) SetHideAt(v time.Time)`

SetHideAt sets HideAt field to given value.

### HasHideAt

`func (o *MemoryResponseDto) HasHideAt() bool`

HasHideAt returns a boolean if a field has been set.

### GetId

`func (o *MemoryResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MemoryResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MemoryResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsSaved

`func (o *MemoryResponseDto) GetIsSaved() bool`

GetIsSaved returns the IsSaved field if non-nil, zero value otherwise.

### GetIsSavedOk

`func (o *MemoryResponseDto) GetIsSavedOk() (*bool, bool)`

GetIsSavedOk returns a tuple with the IsSaved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSaved

`func (o *MemoryResponseDto) SetIsSaved(v bool)`

SetIsSaved sets IsSaved field to given value.


### GetMemoryAt

`func (o *MemoryResponseDto) GetMemoryAt() time.Time`

GetMemoryAt returns the MemoryAt field if non-nil, zero value otherwise.

### GetMemoryAtOk

`func (o *MemoryResponseDto) GetMemoryAtOk() (*time.Time, bool)`

GetMemoryAtOk returns a tuple with the MemoryAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAt

`func (o *MemoryResponseDto) SetMemoryAt(v time.Time)`

SetMemoryAt sets MemoryAt field to given value.


### GetOwnerId

`func (o *MemoryResponseDto) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *MemoryResponseDto) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *MemoryResponseDto) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetSeenAt

`func (o *MemoryResponseDto) GetSeenAt() time.Time`

GetSeenAt returns the SeenAt field if non-nil, zero value otherwise.

### GetSeenAtOk

`func (o *MemoryResponseDto) GetSeenAtOk() (*time.Time, bool)`

GetSeenAtOk returns a tuple with the SeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeenAt

`func (o *MemoryResponseDto) SetSeenAt(v time.Time)`

SetSeenAt sets SeenAt field to given value.

### HasSeenAt

`func (o *MemoryResponseDto) HasSeenAt() bool`

HasSeenAt returns a boolean if a field has been set.

### GetShowAt

`func (o *MemoryResponseDto) GetShowAt() time.Time`

GetShowAt returns the ShowAt field if non-nil, zero value otherwise.

### GetShowAtOk

`func (o *MemoryResponseDto) GetShowAtOk() (*time.Time, bool)`

GetShowAtOk returns a tuple with the ShowAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowAt

`func (o *MemoryResponseDto) SetShowAt(v time.Time)`

SetShowAt sets ShowAt field to given value.

### HasShowAt

`func (o *MemoryResponseDto) HasShowAt() bool`

HasShowAt returns a boolean if a field has been set.

### GetType

`func (o *MemoryResponseDto) GetType() MemoryType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MemoryResponseDto) GetTypeOk() (*MemoryType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MemoryResponseDto) SetType(v MemoryType)`

SetType sets Type field to given value.


### GetUpdatedAt

`func (o *MemoryResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *MemoryResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *MemoryResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


