# AssetEditActionItemResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**AssetEditAction**](AssetEditAction.md) |  | 
**Id** | **string** | Asset edit ID | 
**Parameters** | [**AssetEditActionItemDtoParameters**](AssetEditActionItemDtoParameters.md) |  | 

## Methods

### NewAssetEditActionItemResponseDto

`func NewAssetEditActionItemResponseDto(action AssetEditAction, id string, parameters AssetEditActionItemDtoParameters, ) *AssetEditActionItemResponseDto`

NewAssetEditActionItemResponseDto instantiates a new AssetEditActionItemResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEditActionItemResponseDtoWithDefaults

`func NewAssetEditActionItemResponseDtoWithDefaults() *AssetEditActionItemResponseDto`

NewAssetEditActionItemResponseDtoWithDefaults instantiates a new AssetEditActionItemResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AssetEditActionItemResponseDto) GetAction() AssetEditAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AssetEditActionItemResponseDto) GetActionOk() (*AssetEditAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AssetEditActionItemResponseDto) SetAction(v AssetEditAction)`

SetAction sets Action field to given value.


### GetId

`func (o *AssetEditActionItemResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetEditActionItemResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetEditActionItemResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetParameters

`func (o *AssetEditActionItemResponseDto) GetParameters() AssetEditActionItemDtoParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *AssetEditActionItemResponseDto) GetParametersOk() (*AssetEditActionItemDtoParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *AssetEditActionItemResponseDto) SetParameters(v AssetEditActionItemDtoParameters)`

SetParameters sets Parameters field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


