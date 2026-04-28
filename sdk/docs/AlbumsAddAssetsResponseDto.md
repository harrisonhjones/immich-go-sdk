# AlbumsAddAssetsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to [**BulkIdErrorReason**](BulkIdErrorReason.md) |  | [optional] 
**Success** | **bool** | Operation success | 

## Methods

### NewAlbumsAddAssetsResponseDto

`func NewAlbumsAddAssetsResponseDto(success bool, ) *AlbumsAddAssetsResponseDto`

NewAlbumsAddAssetsResponseDto instantiates a new AlbumsAddAssetsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlbumsAddAssetsResponseDtoWithDefaults

`func NewAlbumsAddAssetsResponseDtoWithDefaults() *AlbumsAddAssetsResponseDto`

NewAlbumsAddAssetsResponseDtoWithDefaults instantiates a new AlbumsAddAssetsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *AlbumsAddAssetsResponseDto) GetError() BulkIdErrorReason`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AlbumsAddAssetsResponseDto) GetErrorOk() (*BulkIdErrorReason, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AlbumsAddAssetsResponseDto) SetError(v BulkIdErrorReason)`

SetError sets Error field to given value.

### HasError

`func (o *AlbumsAddAssetsResponseDto) HasError() bool`

HasError returns a boolean if a field has been set.

### GetSuccess

`func (o *AlbumsAddAssetsResponseDto) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AlbumsAddAssetsResponseDto) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AlbumsAddAssetsResponseDto) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


