# PeopleUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**People** | [**[]PeopleUpdateItem**](PeopleUpdateItem.md) | People to update | 

## Methods

### NewPeopleUpdateDto

`func NewPeopleUpdateDto(people []PeopleUpdateItem, ) *PeopleUpdateDto`

NewPeopleUpdateDto instantiates a new PeopleUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeopleUpdateDtoWithDefaults

`func NewPeopleUpdateDtoWithDefaults() *PeopleUpdateDto`

NewPeopleUpdateDtoWithDefaults instantiates a new PeopleUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeople

`func (o *PeopleUpdateDto) GetPeople() []PeopleUpdateItem`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *PeopleUpdateDto) GetPeopleOk() (*[]PeopleUpdateItem, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *PeopleUpdateDto) SetPeople(v []PeopleUpdateItem)`

SetPeople sets People field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


