# SyncAssetEditV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**AssetEditAction**](AssetEditAction.md) |  | 
**AssetId** | **string** | Asset ID | 
**Id** | **string** | Edit ID | 
**Parameters** | **map[string]interface{}** | Edit parameters | 
**Sequence** | **int32** | Edit sequence | 

## Methods

### NewSyncAssetEditV1

`func NewSyncAssetEditV1(action AssetEditAction, assetId string, id string, parameters map[string]interface{}, sequence int32, ) *SyncAssetEditV1`

NewSyncAssetEditV1 instantiates a new SyncAssetEditV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetEditV1WithDefaults

`func NewSyncAssetEditV1WithDefaults() *SyncAssetEditV1`

NewSyncAssetEditV1WithDefaults instantiates a new SyncAssetEditV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *SyncAssetEditV1) GetAction() AssetEditAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *SyncAssetEditV1) GetActionOk() (*AssetEditAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *SyncAssetEditV1) SetAction(v AssetEditAction)`

SetAction sets Action field to given value.


### GetAssetId

`func (o *SyncAssetEditV1) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *SyncAssetEditV1) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *SyncAssetEditV1) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetId

`func (o *SyncAssetEditV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAssetEditV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAssetEditV1) SetId(v string)`

SetId sets Id field to given value.


### GetParameters

`func (o *SyncAssetEditV1) GetParameters() map[string]interface{}`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *SyncAssetEditV1) GetParametersOk() (*map[string]interface{}, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *SyncAssetEditV1) SetParameters(v map[string]interface{})`

SetParameters sets Parameters field to given value.


### GetSequence

`func (o *SyncAssetEditV1) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *SyncAssetEditV1) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *SyncAssetEditV1) SetSequence(v int32)`

SetSequence sets Sequence field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


