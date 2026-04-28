# SyncAckSetDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Acks** | **[]string** | Acknowledgment IDs (max 1000) | 

## Methods

### NewSyncAckSetDto

`func NewSyncAckSetDto(acks []string, ) *SyncAckSetDto`

NewSyncAckSetDto instantiates a new SyncAckSetDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAckSetDtoWithDefaults

`func NewSyncAckSetDtoWithDefaults() *SyncAckSetDto`

NewSyncAckSetDtoWithDefaults instantiates a new SyncAckSetDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcks

`func (o *SyncAckSetDto) GetAcks() []string`

GetAcks returns the Acks field if non-nil, zero value otherwise.

### GetAcksOk

`func (o *SyncAckSetDto) GetAcksOk() (*[]string, bool)`

GetAcksOk returns a tuple with the Acks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcks

`func (o *SyncAckSetDto) SetAcks(v []string)`

SetAcks sets Acks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


