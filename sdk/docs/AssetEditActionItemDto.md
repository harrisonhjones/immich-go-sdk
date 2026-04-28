# AssetEditActionItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**AssetEditAction**](AssetEditAction.md) |  | 
**Parameters** | [**AssetEditActionItemDtoParameters**](AssetEditActionItemDtoParameters.md) |  | 

## Methods

### NewAssetEditActionItemDto

`func NewAssetEditActionItemDto(action AssetEditAction, parameters AssetEditActionItemDtoParameters, ) *AssetEditActionItemDto`

NewAssetEditActionItemDto instantiates a new AssetEditActionItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEditActionItemDtoWithDefaults

`func NewAssetEditActionItemDtoWithDefaults() *AssetEditActionItemDto`

NewAssetEditActionItemDtoWithDefaults instantiates a new AssetEditActionItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AssetEditActionItemDto) GetAction() AssetEditAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AssetEditActionItemDto) GetActionOk() (*AssetEditAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AssetEditActionItemDto) SetAction(v AssetEditAction)`

SetAction sets Action field to given value.


### GetParameters

`func (o *AssetEditActionItemDto) GetParameters() AssetEditActionItemDtoParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *AssetEditActionItemDto) GetParametersOk() (*AssetEditActionItemDtoParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *AssetEditActionItemDto) SetParameters(v AssetEditActionItemDtoParameters)`

SetParameters sets Parameters field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


