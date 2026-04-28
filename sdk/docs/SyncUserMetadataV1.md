# SyncUserMetadataV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | [**UserMetadataKey**](UserMetadataKey.md) |  | 
**UserId** | **string** | User ID | 
**Value** | **map[string]interface{}** | User metadata value | 

## Methods

### NewSyncUserMetadataV1

`func NewSyncUserMetadataV1(key UserMetadataKey, userId string, value map[string]interface{}, ) *SyncUserMetadataV1`

NewSyncUserMetadataV1 instantiates a new SyncUserMetadataV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncUserMetadataV1WithDefaults

`func NewSyncUserMetadataV1WithDefaults() *SyncUserMetadataV1`

NewSyncUserMetadataV1WithDefaults instantiates a new SyncUserMetadataV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *SyncUserMetadataV1) GetKey() UserMetadataKey`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *SyncUserMetadataV1) GetKeyOk() (*UserMetadataKey, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *SyncUserMetadataV1) SetKey(v UserMetadataKey)`

SetKey sets Key field to given value.


### GetUserId

`func (o *SyncUserMetadataV1) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SyncUserMetadataV1) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SyncUserMetadataV1) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetValue

`func (o *SyncUserMetadataV1) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SyncUserMetadataV1) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SyncUserMetadataV1) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


