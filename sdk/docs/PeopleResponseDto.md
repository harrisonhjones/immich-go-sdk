# PeopleResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasNextPage** | Pointer to **bool** | Whether there are more pages | [optional] 
**Hidden** | **int32** | Number of hidden people | 
**People** | [**[]PersonResponseDto**](PersonResponseDto.md) |  | 
**Total** | **int32** | Total number of people | 

## Methods

### NewPeopleResponseDto

`func NewPeopleResponseDto(hidden int32, people []PersonResponseDto, total int32, ) *PeopleResponseDto`

NewPeopleResponseDto instantiates a new PeopleResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeopleResponseDtoWithDefaults

`func NewPeopleResponseDtoWithDefaults() *PeopleResponseDto`

NewPeopleResponseDtoWithDefaults instantiates a new PeopleResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasNextPage

`func (o *PeopleResponseDto) GetHasNextPage() bool`

GetHasNextPage returns the HasNextPage field if non-nil, zero value otherwise.

### GetHasNextPageOk

`func (o *PeopleResponseDto) GetHasNextPageOk() (*bool, bool)`

GetHasNextPageOk returns a tuple with the HasNextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNextPage

`func (o *PeopleResponseDto) SetHasNextPage(v bool)`

SetHasNextPage sets HasNextPage field to given value.

### HasHasNextPage

`func (o *PeopleResponseDto) HasHasNextPage() bool`

HasHasNextPage returns a boolean if a field has been set.

### GetHidden

`func (o *PeopleResponseDto) GetHidden() int32`

GetHidden returns the Hidden field if non-nil, zero value otherwise.

### GetHiddenOk

`func (o *PeopleResponseDto) GetHiddenOk() (*int32, bool)`

GetHiddenOk returns a tuple with the Hidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHidden

`func (o *PeopleResponseDto) SetHidden(v int32)`

SetHidden sets Hidden field to given value.


### GetPeople

`func (o *PeopleResponseDto) GetPeople() []PersonResponseDto`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *PeopleResponseDto) GetPeopleOk() (*[]PersonResponseDto, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *PeopleResponseDto) SetPeople(v []PersonResponseDto)`

SetPeople sets People field to given value.


### GetTotal

`func (o *PeopleResponseDto) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PeopleResponseDto) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PeopleResponseDto) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


