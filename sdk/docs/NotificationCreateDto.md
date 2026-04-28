# NotificationCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **map[string]interface{}** | Additional notification data | [optional] 
**Description** | Pointer to **NullableString** | Notification description | [optional] 
**Level** | Pointer to [**NotificationLevel**](NotificationLevel.md) |  | [optional] 
**ReadAt** | Pointer to **NullableTime** | Date when notification was read | [optional] 
**Title** | **string** | Notification title | 
**Type** | Pointer to [**NotificationType**](NotificationType.md) |  | [optional] 
**UserId** | **string** | User ID to send notification to | 

## Methods

### NewNotificationCreateDto

`func NewNotificationCreateDto(title string, userId string, ) *NotificationCreateDto`

NewNotificationCreateDto instantiates a new NotificationCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationCreateDtoWithDefaults

`func NewNotificationCreateDtoWithDefaults() *NotificationCreateDto`

NewNotificationCreateDtoWithDefaults instantiates a new NotificationCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *NotificationCreateDto) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *NotificationCreateDto) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *NotificationCreateDto) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *NotificationCreateDto) HasData() bool`

HasData returns a boolean if a field has been set.

### GetDescription

`func (o *NotificationCreateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *NotificationCreateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *NotificationCreateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *NotificationCreateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *NotificationCreateDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *NotificationCreateDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetLevel

`func (o *NotificationCreateDto) GetLevel() NotificationLevel`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *NotificationCreateDto) GetLevelOk() (*NotificationLevel, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *NotificationCreateDto) SetLevel(v NotificationLevel)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *NotificationCreateDto) HasLevel() bool`

HasLevel returns a boolean if a field has been set.

### GetReadAt

`func (o *NotificationCreateDto) GetReadAt() time.Time`

GetReadAt returns the ReadAt field if non-nil, zero value otherwise.

### GetReadAtOk

`func (o *NotificationCreateDto) GetReadAtOk() (*time.Time, bool)`

GetReadAtOk returns a tuple with the ReadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadAt

`func (o *NotificationCreateDto) SetReadAt(v time.Time)`

SetReadAt sets ReadAt field to given value.

### HasReadAt

`func (o *NotificationCreateDto) HasReadAt() bool`

HasReadAt returns a boolean if a field has been set.

### SetReadAtNil

`func (o *NotificationCreateDto) SetReadAtNil(b bool)`

 SetReadAtNil sets the value for ReadAt to be an explicit nil

### UnsetReadAt
`func (o *NotificationCreateDto) UnsetReadAt()`

UnsetReadAt ensures that no value is present for ReadAt, not even an explicit nil
### GetTitle

`func (o *NotificationCreateDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *NotificationCreateDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *NotificationCreateDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetType

`func (o *NotificationCreateDto) GetType() NotificationType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NotificationCreateDto) GetTypeOk() (*NotificationType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NotificationCreateDto) SetType(v NotificationType)`

SetType sets Type field to given value.

### HasType

`func (o *NotificationCreateDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUserId

`func (o *NotificationCreateDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *NotificationCreateDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *NotificationCreateDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


