# SearchFacetCountResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | Number of assets with this facet value | 
**Value** | **string** | Facet value | 

## Methods

### NewSearchFacetCountResponseDto

`func NewSearchFacetCountResponseDto(count int32, value string, ) *SearchFacetCountResponseDto`

NewSearchFacetCountResponseDto instantiates a new SearchFacetCountResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchFacetCountResponseDtoWithDefaults

`func NewSearchFacetCountResponseDtoWithDefaults() *SearchFacetCountResponseDto`

NewSearchFacetCountResponseDtoWithDefaults instantiates a new SearchFacetCountResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *SearchFacetCountResponseDto) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *SearchFacetCountResponseDto) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *SearchFacetCountResponseDto) SetCount(v int32)`

SetCount sets Count field to given value.


### GetValue

`func (o *SearchFacetCountResponseDto) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SearchFacetCountResponseDto) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SearchFacetCountResponseDto) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


