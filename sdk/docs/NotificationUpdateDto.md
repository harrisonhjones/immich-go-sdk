# NotificationUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReadAt** | Pointer to **NullableTime** | Date when notification was read | [optional] 

## Methods

### NewNotificationUpdateDto

`func NewNotificationUpdateDto() *NotificationUpdateDto`

NewNotificationUpdateDto instantiates a new NotificationUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationUpdateDtoWithDefaults

`func NewNotificationUpdateDtoWithDefaults() *NotificationUpdateDto`

NewNotificationUpdateDtoWithDefaults instantiates a new NotificationUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReadAt

`func (o *NotificationUpdateDto) GetReadAt() time.Time`

GetReadAt returns the ReadAt field if non-nil, zero value otherwise.

### GetReadAtOk

`func (o *NotificationUpdateDto) GetReadAtOk() (*time.Time, bool)`

GetReadAtOk returns a tuple with the ReadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadAt

`func (o *NotificationUpdateDto) SetReadAt(v time.Time)`

SetReadAt sets ReadAt field to given value.

### HasReadAt

`func (o *NotificationUpdateDto) HasReadAt() bool`

HasReadAt returns a boolean if a field has been set.

### SetReadAtNil

`func (o *NotificationUpdateDto) SetReadAtNil(b bool)`

 SetReadAtNil sets the value for ReadAt to be an explicit nil

### UnsetReadAt
`func (o *NotificationUpdateDto) UnsetReadAt()`

UnsetReadAt ensures that no value is present for ReadAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


