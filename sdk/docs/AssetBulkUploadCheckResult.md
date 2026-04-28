# AssetBulkUploadCheckResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**AssetUploadAction**](AssetUploadAction.md) |  | 
**AssetId** | Pointer to **string** | Existing asset ID if duplicate | [optional] 
**Id** | **string** | Asset ID | 
**IsTrashed** | Pointer to **bool** | Whether existing asset is trashed | [optional] 
**Reason** | Pointer to [**AssetRejectReason**](AssetRejectReason.md) |  | [optional] 

## Methods

### NewAssetBulkUploadCheckResult

`func NewAssetBulkUploadCheckResult(action AssetUploadAction, id string, ) *AssetBulkUploadCheckResult`

NewAssetBulkUploadCheckResult instantiates a new AssetBulkUploadCheckResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetBulkUploadCheckResultWithDefaults

`func NewAssetBulkUploadCheckResultWithDefaults() *AssetBulkUploadCheckResult`

NewAssetBulkUploadCheckResultWithDefaults instantiates a new AssetBulkUploadCheckResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AssetBulkUploadCheckResult) GetAction() AssetUploadAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AssetBulkUploadCheckResult) GetActionOk() (*AssetUploadAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AssetBulkUploadCheckResult) SetAction(v AssetUploadAction)`

SetAction sets Action field to given value.


### GetAssetId

`func (o *AssetBulkUploadCheckResult) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetBulkUploadCheckResult) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetBulkUploadCheckResult) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *AssetBulkUploadCheckResult) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetId

`func (o *AssetBulkUploadCheckResult) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetBulkUploadCheckResult) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetBulkUploadCheckResult) SetId(v string)`

SetId sets Id field to given value.


### GetIsTrashed

`func (o *AssetBulkUploadCheckResult) GetIsTrashed() bool`

GetIsTrashed returns the IsTrashed field if non-nil, zero value otherwise.

### GetIsTrashedOk

`func (o *AssetBulkUploadCheckResult) GetIsTrashedOk() (*bool, bool)`

GetIsTrashedOk returns a tuple with the IsTrashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTrashed

`func (o *AssetBulkUploadCheckResult) SetIsTrashed(v bool)`

SetIsTrashed sets IsTrashed field to given value.

### HasIsTrashed

`func (o *AssetBulkUploadCheckResult) HasIsTrashed() bool`

HasIsTrashed returns a boolean if a field has been set.

### GetReason

`func (o *AssetBulkUploadCheckResult) GetReason() AssetRejectReason`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AssetBulkUploadCheckResult) GetReasonOk() (*AssetRejectReason, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AssetBulkUploadCheckResult) SetReason(v AssetRejectReason)`

SetReason sets Reason field to given value.

### HasReason

`func (o *AssetBulkUploadCheckResult) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


