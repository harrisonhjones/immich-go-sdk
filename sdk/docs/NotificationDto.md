# NotificationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | Creation date | 
**Data** | Pointer to **map[string]interface{}** | Additional notification data | [optional] 
**Description** | Pointer to **string** | Notification description | [optional] 
**Id** | **string** | Notification ID | 
**Level** | [**NotificationLevel**](NotificationLevel.md) |  | 
**ReadAt** | Pointer to **time.Time** | Date when notification was read | [optional] 
**Title** | **string** | Notification title | 
**Type** | [**NotificationType**](NotificationType.md) |  | 

## Methods

### NewNotificationDto

`func NewNotificationDto(createdAt time.Time, id string, level NotificationLevel, title string, type_ NotificationType, ) *NotificationDto`

NewNotificationDto instantiates a new NotificationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationDtoWithDefaults

`func NewNotificationDtoWithDefaults() *NotificationDto`

NewNotificationDtoWithDefaults instantiates a new NotificationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *NotificationDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *NotificationDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *NotificationDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetData

`func (o *NotificationDto) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *NotificationDto) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *NotificationDto) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *NotificationDto) HasData() bool`

HasData returns a boolean if a field has been set.

### GetDescription

`func (o *NotificationDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *NotificationDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *NotificationDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *NotificationDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *NotificationDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NotificationDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NotificationDto) SetId(v string)`

SetId sets Id field to given value.


### GetLevel

`func (o *NotificationDto) GetLevel() NotificationLevel`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *NotificationDto) GetLevelOk() (*NotificationLevel, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *NotificationDto) SetLevel(v NotificationLevel)`

SetLevel sets Level field to given value.


### GetReadAt

`func (o *NotificationDto) GetReadAt() time.Time`

GetReadAt returns the ReadAt field if non-nil, zero value otherwise.

### GetReadAtOk

`func (o *NotificationDto) GetReadAtOk() (*time.Time, bool)`

GetReadAtOk returns a tuple with the ReadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadAt

`func (o *NotificationDto) SetReadAt(v time.Time)`

SetReadAt sets ReadAt field to given value.

### HasReadAt

`func (o *NotificationDto) HasReadAt() bool`

HasReadAt returns a boolean if a field has been set.

### GetTitle

`func (o *NotificationDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *NotificationDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *NotificationDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetType

`func (o *NotificationDto) GetType() NotificationType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NotificationDto) GetTypeOk() (*NotificationType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NotificationDto) SetType(v NotificationType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


