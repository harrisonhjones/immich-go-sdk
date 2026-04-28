# MaintenanceStatusResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | [**MaintenanceAction**](MaintenanceAction.md) |  | 
**Active** | **bool** |  | 
**Error** | Pointer to **string** |  | [optional] 
**Progress** | Pointer to **float32** |  | [optional] 
**Task** | Pointer to **string** |  | [optional] 

## Methods

### NewMaintenanceStatusResponseDto

`func NewMaintenanceStatusResponseDto(action MaintenanceAction, active bool, ) *MaintenanceStatusResponseDto`

NewMaintenanceStatusResponseDto instantiates a new MaintenanceStatusResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMaintenanceStatusResponseDtoWithDefaults

`func NewMaintenanceStatusResponseDtoWithDefaults() *MaintenanceStatusResponseDto`

NewMaintenanceStatusResponseDtoWithDefaults instantiates a new MaintenanceStatusResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *MaintenanceStatusResponseDto) GetAction() MaintenanceAction`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *MaintenanceStatusResponseDto) GetActionOk() (*MaintenanceAction, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *MaintenanceStatusResponseDto) SetAction(v MaintenanceAction)`

SetAction sets Action field to given value.


### GetActive

`func (o *MaintenanceStatusResponseDto) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *MaintenanceStatusResponseDto) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *MaintenanceStatusResponseDto) SetActive(v bool)`

SetActive sets Active field to given value.


### GetError

`func (o *MaintenanceStatusResponseDto) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MaintenanceStatusResponseDto) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MaintenanceStatusResponseDto) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *MaintenanceStatusResponseDto) HasError() bool`

HasError returns a boolean if a field has been set.

### GetProgress

`func (o *MaintenanceStatusResponseDto) GetProgress() float32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *MaintenanceStatusResponseDto) GetProgressOk() (*float32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *MaintenanceStatusResponseDto) SetProgress(v float32)`

SetProgress sets Progress field to given value.

### HasProgress

`func (o *MaintenanceStatusResponseDto) HasProgress() bool`

HasProgress returns a boolean if a field has been set.

### GetTask

`func (o *MaintenanceStatusResponseDto) GetTask() string`

GetTask returns the Task field if non-nil, zero value otherwise.

### GetTaskOk

`func (o *MaintenanceStatusResponseDto) GetTaskOk() (*string, bool)`

GetTaskOk returns a tuple with the Task field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTask

`func (o *MaintenanceStatusResponseDto) SetTask(v string)`

SetTask sets Task field to given value.

### HasTask

`func (o *MaintenanceStatusResponseDto) HasTask() bool`

HasTask returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


