# JobCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | [**ManualJobName**](ManualJobName.md) |  | 

## Methods

### NewJobCreateDto

`func NewJobCreateDto(name ManualJobName, ) *JobCreateDto`

NewJobCreateDto instantiates a new JobCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobCreateDtoWithDefaults

`func NewJobCreateDtoWithDefaults() *JobCreateDto`

NewJobCreateDtoWithDefaults instantiates a new JobCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *JobCreateDto) GetName() ManualJobName`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *JobCreateDto) GetNameOk() (*ManualJobName, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *JobCreateDto) SetName(v ManualJobName)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


