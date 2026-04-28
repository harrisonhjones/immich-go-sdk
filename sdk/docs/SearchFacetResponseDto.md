# SearchFacetResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Counts** | [**[]SearchFacetCountResponseDto**](SearchFacetCountResponseDto.md) |  | 
**FieldName** | **string** | Facet field name | 

## Methods

### NewSearchFacetResponseDto

`func NewSearchFacetResponseDto(counts []SearchFacetCountResponseDto, fieldName string, ) *SearchFacetResponseDto`

NewSearchFacetResponseDto instantiates a new SearchFacetResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchFacetResponseDtoWithDefaults

`func NewSearchFacetResponseDtoWithDefaults() *SearchFacetResponseDto`

NewSearchFacetResponseDtoWithDefaults instantiates a new SearchFacetResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCounts

`func (o *SearchFacetResponseDto) GetCounts() []SearchFacetCountResponseDto`

GetCounts returns the Counts field if non-nil, zero value otherwise.

### GetCountsOk

`func (o *SearchFacetResponseDto) GetCountsOk() (*[]SearchFacetCountResponseDto, bool)`

GetCountsOk returns a tuple with the Counts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounts

`func (o *SearchFacetResponseDto) SetCounts(v []SearchFacetCountResponseDto)`

SetCounts sets Counts field to given value.


### GetFieldName

`func (o *SearchFacetResponseDto) GetFieldName() string`

GetFieldName returns the FieldName field if non-nil, zero value otherwise.

### GetFieldNameOk

`func (o *SearchFacetResponseDto) GetFieldNameOk() (*string, bool)`

GetFieldNameOk returns a tuple with the FieldName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldName

`func (o *SearchFacetResponseDto) SetFieldName(v string)`

SetFieldName sets FieldName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


