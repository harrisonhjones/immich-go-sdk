# SyncMemoryV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | Created at | 
**Data** | **map[string]interface{}** | Data | 
**DeletedAt** | **NullableTime** | Deleted at | 
**HideAt** | **NullableTime** | Hide at | 
**Id** | **string** | Memory ID | 
**IsSaved** | **bool** | Is saved | 
**MemoryAt** | **time.Time** | Memory at | 
**OwnerId** | **string** | Owner ID | 
**SeenAt** | **NullableTime** | Seen at | 
**ShowAt** | **NullableTime** | Show at | 
**Type** | [**MemoryType**](MemoryType.md) |  | 
**UpdatedAt** | **time.Time** | Updated at | 

## Methods

### NewSyncMemoryV1

`func NewSyncMemoryV1(createdAt time.Time, data map[string]interface{}, deletedAt NullableTime, hideAt NullableTime, id string, isSaved bool, memoryAt time.Time, ownerId string, seenAt NullableTime, showAt NullableTime, type_ MemoryType, updatedAt time.Time, ) *SyncMemoryV1`

NewSyncMemoryV1 instantiates a new SyncMemoryV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncMemoryV1WithDefaults

`func NewSyncMemoryV1WithDefaults() *SyncMemoryV1`

NewSyncMemoryV1WithDefaults instantiates a new SyncMemoryV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *SyncMemoryV1) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SyncMemoryV1) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SyncMemoryV1) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetData

`func (o *SyncMemoryV1) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SyncMemoryV1) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SyncMemoryV1) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetDeletedAt

`func (o *SyncMemoryV1) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncMemoryV1) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncMemoryV1) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncMemoryV1) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncMemoryV1) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetHideAt

`func (o *SyncMemoryV1) GetHideAt() time.Time`

GetHideAt returns the HideAt field if non-nil, zero value otherwise.

### GetHideAtOk

`func (o *SyncMemoryV1) GetHideAtOk() (*time.Time, bool)`

GetHideAtOk returns a tuple with the HideAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideAt

`func (o *SyncMemoryV1) SetHideAt(v time.Time)`

SetHideAt sets HideAt field to given value.


### SetHideAtNil

`func (o *SyncMemoryV1) SetHideAtNil(b bool)`

 SetHideAtNil sets the value for HideAt to be an explicit nil

### UnsetHideAt
`func (o *SyncMemoryV1) UnsetHideAt()`

UnsetHideAt ensures that no value is present for HideAt, not even an explicit nil
### GetId

`func (o *SyncMemoryV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncMemoryV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncMemoryV1) SetId(v string)`

SetId sets Id field to given value.


### GetIsSaved

`func (o *SyncMemoryV1) GetIsSaved() bool`

GetIsSaved returns the IsSaved field if non-nil, zero value otherwise.

### GetIsSavedOk

`func (o *SyncMemoryV1) GetIsSavedOk() (*bool, bool)`

GetIsSavedOk returns a tuple with the IsSaved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSaved

`func (o *SyncMemoryV1) SetIsSaved(v bool)`

SetIsSaved sets IsSaved field to given value.


### GetMemoryAt

`func (o *SyncMemoryV1) GetMemoryAt() time.Time`

GetMemoryAt returns the MemoryAt field if non-nil, zero value otherwise.

### GetMemoryAtOk

`func (o *SyncMemoryV1) GetMemoryAtOk() (*time.Time, bool)`

GetMemoryAtOk returns a tuple with the MemoryAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAt

`func (o *SyncMemoryV1) SetMemoryAt(v time.Time)`

SetMemoryAt sets MemoryAt field to given value.


### GetOwnerId

`func (o *SyncMemoryV1) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *SyncMemoryV1) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *SyncMemoryV1) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetSeenAt

`func (o *SyncMemoryV1) GetSeenAt() time.Time`

GetSeenAt returns the SeenAt field if non-nil, zero value otherwise.

### GetSeenAtOk

`func (o *SyncMemoryV1) GetSeenAtOk() (*time.Time, bool)`

GetSeenAtOk returns a tuple with the SeenAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeenAt

`func (o *SyncMemoryV1) SetSeenAt(v time.Time)`

SetSeenAt sets SeenAt field to given value.


### SetSeenAtNil

`func (o *SyncMemoryV1) SetSeenAtNil(b bool)`

 SetSeenAtNil sets the value for SeenAt to be an explicit nil

### UnsetSeenAt
`func (o *SyncMemoryV1) UnsetSeenAt()`

UnsetSeenAt ensures that no value is present for SeenAt, not even an explicit nil
### GetShowAt

`func (o *SyncMemoryV1) GetShowAt() time.Time`

GetShowAt returns the ShowAt field if non-nil, zero value otherwise.

### GetShowAtOk

`func (o *SyncMemoryV1) GetShowAtOk() (*time.Time, bool)`

GetShowAtOk returns a tuple with the ShowAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowAt

`func (o *SyncMemoryV1) SetShowAt(v time.Time)`

SetShowAt sets ShowAt field to given value.


### SetShowAtNil

`func (o *SyncMemoryV1) SetShowAtNil(b bool)`

 SetShowAtNil sets the value for ShowAt to be an explicit nil

### UnsetShowAt
`func (o *SyncMemoryV1) UnsetShowAt()`

UnsetShowAt ensures that no value is present for ShowAt, not even an explicit nil
### GetType

`func (o *SyncMemoryV1) GetType() MemoryType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SyncMemoryV1) GetTypeOk() (*MemoryType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SyncMemoryV1) SetType(v MemoryType)`

SetType sets Type field to given value.


### GetUpdatedAt

`func (o *SyncMemoryV1) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SyncMemoryV1) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SyncMemoryV1) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


