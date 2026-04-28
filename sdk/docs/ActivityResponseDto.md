# ActivityResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **NullableString** | Asset ID (if activity is for an asset) | 
**Comment** | Pointer to **NullableString** | Comment text (for comment activities) | [optional] 
**CreatedAt** | **time.Time** | Creation date | 
**Id** | **string** | Activity ID | 
**Type** | [**ReactionType**](ReactionType.md) |  | 
**User** | [**UserResponseDto**](UserResponseDto.md) |  | 

## Methods

### NewActivityResponseDto

`func NewActivityResponseDto(assetId NullableString, createdAt time.Time, id string, type_ ReactionType, user UserResponseDto, ) *ActivityResponseDto`

NewActivityResponseDto instantiates a new ActivityResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityResponseDtoWithDefaults

`func NewActivityResponseDtoWithDefaults() *ActivityResponseDto`

NewActivityResponseDtoWithDefaults instantiates a new ActivityResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *ActivityResponseDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *ActivityResponseDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *ActivityResponseDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### SetAssetIdNil

`func (o *ActivityResponseDto) SetAssetIdNil(b bool)`

 SetAssetIdNil sets the value for AssetId to be an explicit nil

### UnsetAssetId
`func (o *ActivityResponseDto) UnsetAssetId()`

UnsetAssetId ensures that no value is present for AssetId, not even an explicit nil
### GetComment

`func (o *ActivityResponseDto) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ActivityResponseDto) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ActivityResponseDto) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ActivityResponseDto) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *ActivityResponseDto) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *ActivityResponseDto) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetCreatedAt

`func (o *ActivityResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ActivityResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ActivityResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *ActivityResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ActivityResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ActivityResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *ActivityResponseDto) GetType() ReactionType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ActivityResponseDto) GetTypeOk() (*ReactionType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ActivityResponseDto) SetType(v ReactionType)`

SetType sets Type field to given value.


### GetUser

`func (o *ActivityResponseDto) GetUser() UserResponseDto`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *ActivityResponseDto) GetUserOk() (*UserResponseDto, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *ActivityResponseDto) SetUser(v UserResponseDto)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


