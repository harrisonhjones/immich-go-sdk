# BulkIdResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to [**BulkIdErrorReason**](BulkIdErrorReason.md) |  | [optional] 
**ErrorMessage** | Pointer to **string** |  | [optional] 
**Id** | **string** | ID | 
**Success** | **bool** | Whether operation succeeded | 

## Methods

### NewBulkIdResponseDto

`func NewBulkIdResponseDto(id string, success bool, ) *BulkIdResponseDto`

NewBulkIdResponseDto instantiates a new BulkIdResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkIdResponseDtoWithDefaults

`func NewBulkIdResponseDtoWithDefaults() *BulkIdResponseDto`

NewBulkIdResponseDtoWithDefaults instantiates a new BulkIdResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *BulkIdResponseDto) GetError() BulkIdErrorReason`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BulkIdResponseDto) GetErrorOk() (*BulkIdErrorReason, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BulkIdResponseDto) SetError(v BulkIdErrorReason)`

SetError sets Error field to given value.

### HasError

`func (o *BulkIdResponseDto) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorMessage

`func (o *BulkIdResponseDto) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *BulkIdResponseDto) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *BulkIdResponseDto) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *BulkIdResponseDto) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetId

`func (o *BulkIdResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BulkIdResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BulkIdResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetSuccess

`func (o *BulkIdResponseDto) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *BulkIdResponseDto) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *BulkIdResponseDto) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


