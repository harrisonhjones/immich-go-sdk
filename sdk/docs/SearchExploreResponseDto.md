# SearchExploreResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldName** | **string** | Explore field name | 
**Items** | [**[]SearchExploreItem**](SearchExploreItem.md) |  | 

## Methods

### NewSearchExploreResponseDto

`func NewSearchExploreResponseDto(fieldName string, items []SearchExploreItem, ) *SearchExploreResponseDto`

NewSearchExploreResponseDto instantiates a new SearchExploreResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchExploreResponseDtoWithDefaults

`func NewSearchExploreResponseDtoWithDefaults() *SearchExploreResponseDto`

NewSearchExploreResponseDtoWithDefaults instantiates a new SearchExploreResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldName

`func (o *SearchExploreResponseDto) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *SearchExploreResponseDto) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *SearchExploreResponseDto) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.


### GetItems

`func (o *SearchExploreResponseDto) GetItems() []SearchExploreItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SearchExploreResponseDto) GetItemsOk() (*[]SearchExploreItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SearchExploreResponseDto) SetItems(v []SearchExploreItem)`

SetItems sets Items field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


