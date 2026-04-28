# SyncAckDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ack** | **string** | Acknowledgment ID | 
**Type** | [**SyncEntityType**](SyncEntityType.md) |  | 

## Methods

### NewSyncAckDto

`func NewSyncAckDto(ack string, type_ SyncEntityType, ) *SyncAckDto`

NewSyncAckDto instantiates a new SyncAckDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAckDtoWithDefaults

`func NewSyncAckDtoWithDefaults() *SyncAckDto`

NewSyncAckDtoWithDefaults instantiates a new SyncAckDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAck

`func (o *SyncAckDto) GetAck() string`

GetAck returns the Ack field if non-nil, zero value otherwise.

### GetAckOk

`func (o *SyncAckDto) GetAckOk() (*string, bool)`

GetAckOk returns a tuple with the Ack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAck

`func (o *SyncAckDto) SetAck(v string)`

SetAck sets Ack field to given value.


### GetType

`func (o *SyncAckDto) GetType() SyncEntityType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SyncAckDto) GetTypeOk() (*SyncEntityType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SyncAckDto) SetType(v SyncEntityType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


