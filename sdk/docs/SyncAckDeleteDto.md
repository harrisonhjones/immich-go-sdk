# SyncAckDeleteDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Types** | Pointer to [**[]SyncEntityType**](SyncEntityType.md) | Sync entity types to delete acks for | [optional] 

## Methods

### NewSyncAckDeleteDto

`func NewSyncAckDeleteDto() *SyncAckDeleteDto`

NewSyncAckDeleteDto instantiates a new SyncAckDeleteDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAckDeleteDtoWithDefaults

`func NewSyncAckDeleteDtoWithDefaults() *SyncAckDeleteDto`

NewSyncAckDeleteDtoWithDefaults instantiates a new SyncAckDeleteDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTypes

`func (o *SyncAckDeleteDto) GetTypes() []SyncEntityType`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *SyncAckDeleteDto) GetTypesOk() (*[]SyncEntityType, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *SyncAckDeleteDto) SetTypes(v []SyncEntityType)`

SetTypes sets Types field to given value.

### HasTypes

`func (o *SyncAckDeleteDto) HasTypes() bool`

HasTypes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


