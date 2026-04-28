# SyncStackV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | Created at | 
**Id** | **string** | Stack ID | 
**OwnerId** | **string** | Owner ID | 
**PrimaryAssetId** | **string** | Primary asset ID | 
**UpdatedAt** | **time.Time** | Updated at | 

## Methods

### NewSyncStackV1

`func NewSyncStackV1(createdAt time.Time, id string, ownerId string, primaryAssetId string, updatedAt time.Time, ) *SyncStackV1`

NewSyncStackV1 instantiates a new SyncStackV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncStackV1WithDefaults

`func NewSyncStackV1WithDefaults() *SyncStackV1`

NewSyncStackV1WithDefaults instantiates a new SyncStackV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *SyncStackV1) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SyncStackV1) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SyncStackV1) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *SyncStackV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncStackV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncStackV1) SetId(v string)`

SetId sets Id field to given value.


### GetOwnerId

`func (o *SyncStackV1) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *SyncStackV1) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *SyncStackV1) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetPrimaryAssetId

`func (o *SyncStackV1) GetPrimaryAssetId() string`

GetPrimaryAssetId returns the PrimaryAssetId field if non-nil, zero value otherwise.

### GetPrimaryAssetIdOk

`func (o *SyncStackV1) GetPrimaryAssetIdOk() (*string, bool)`

GetPrimaryAssetIdOk returns a tuple with the PrimaryAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryAssetId

`func (o *SyncStackV1) SetPrimaryAssetId(v string)`

SetPrimaryAssetId sets PrimaryAssetId field to given value.


### GetUpdatedAt

`func (o *SyncStackV1) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SyncStackV1) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SyncStackV1) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


