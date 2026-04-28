# NotificationUpdateAllDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ids** | **[]string** | Notification IDs to update | 
**ReadAt** | Pointer to **NullableTime** | Date when notifications were read | [optional] 

## Methods

### NewNotificationUpdateAllDto

`func NewNotificationUpdateAllDto(ids []string, ) *NotificationUpdateAllDto`

NewNotificationUpdateAllDto instantiates a new NotificationUpdateAllDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationUpdateAllDtoWithDefaults

`func NewNotificationUpdateAllDtoWithDefaults() *NotificationUpdateAllDto`

NewNotificationUpdateAllDtoWithDefaults instantiates a new NotificationUpdateAllDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIds

`func (o *NotificationUpdateAllDto) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *NotificationUpdateAllDto) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *NotificationUpdateAllDto) SetIds(v []string)`

SetIds sets Ids field to given value.


### GetReadAt

`func (o *NotificationUpdateAllDto) GetReadAt() time.Time`

GetReadAt returns the ReadAt field if non-nil, zero value otherwise.

### GetReadAtOk

`func (o *NotificationUpdateAllDto) GetReadAtOk() (*time.Time, bool)`

GetReadAtOk returns a tuple with the ReadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadAt

`func (o *NotificationUpdateAllDto) SetReadAt(v time.Time)`

SetReadAt sets ReadAt field to given value.

### HasReadAt

`func (o *NotificationUpdateAllDto) HasReadAt() bool`

HasReadAt returns a boolean if a field has been set.

### SetReadAtNil

`func (o *NotificationUpdateAllDto) SetReadAtNil(b bool)`

 SetReadAtNil sets the value for ReadAt to be an explicit nil

### UnsetReadAt
`func (o *NotificationUpdateAllDto) UnsetReadAt()`

UnsetReadAt ensures that no value is present for ReadAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


