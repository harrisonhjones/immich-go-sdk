# SyncStreamDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reset** | Pointer to **bool** | Reset sync state | [optional] 
**Types** | [**[]SyncRequestType**](SyncRequestType.md) | Sync request types | 

## Methods

### NewSyncStreamDto

`func NewSyncStreamDto(types []SyncRequestType, ) *SyncStreamDto`

NewSyncStreamDto instantiates a new SyncStreamDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncStreamDtoWithDefaults

`func NewSyncStreamDtoWithDefaults() *SyncStreamDto`

NewSyncStreamDtoWithDefaults instantiates a new SyncStreamDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReset

`func (o *SyncStreamDto) GetReset() bool`

GetReset returns the Reset field if non-nil, zero value otherwise.

### GetResetOk

`func (o *SyncStreamDto) GetResetOk() (*bool, bool)`

GetResetOk returns a tuple with the Reset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReset

`func (o *SyncStreamDto) SetReset(v bool)`

SetReset sets Reset field to given value.

### HasReset

`func (o *SyncStreamDto) HasReset() bool`

HasReset returns a boolean if a field has been set.

### GetTypes

`func (o *SyncStreamDto) GetTypes() []SyncRequestType`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *SyncStreamDto) GetTypesOk() (*[]SyncRequestType, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *SyncStreamDto) SetTypes(v []SyncRequestType)`

SetTypes sets Types field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


