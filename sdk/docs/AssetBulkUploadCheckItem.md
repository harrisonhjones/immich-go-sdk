# AssetBulkUploadCheckItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checksum** | **string** | Base64 or hex encoded SHA1 hash | 
**Id** | **string** | Asset ID | 

## Methods

### NewAssetBulkUploadCheckItem

`func NewAssetBulkUploadCheckItem(checksum string, id string, ) *AssetBulkUploadCheckItem`

NewAssetBulkUploadCheckItem instantiates a new AssetBulkUploadCheckItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetBulkUploadCheckItemWithDefaults

`func NewAssetBulkUploadCheckItemWithDefaults() *AssetBulkUploadCheckItem`

NewAssetBulkUploadCheckItemWithDefaults instantiates a new AssetBulkUploadCheckItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecksum

`func (o *AssetBulkUploadCheckItem) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *AssetBulkUploadCheckItem) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *AssetBulkUploadCheckItem) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.


### GetId

`func (o *AssetBulkUploadCheckItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetBulkUploadCheckItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetBulkUploadCheckItem) SetId(v string)`

SetId sets Id field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


