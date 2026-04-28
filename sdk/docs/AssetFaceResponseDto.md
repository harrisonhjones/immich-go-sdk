# AssetFaceResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BoundingBoxX1** | **int32** | Bounding box X1 coordinate | 
**BoundingBoxX2** | **int32** | Bounding box X2 coordinate | 
**BoundingBoxY1** | **int32** | Bounding box Y1 coordinate | 
**BoundingBoxY2** | **int32** | Bounding box Y2 coordinate | 
**Id** | **string** | Face ID | 
**ImageHeight** | **int32** | Image height in pixels | 
**ImageWidth** | **int32** | Image width in pixels | 
**Person** | [**NullablePersonResponseDto**](PersonResponseDto.md) |  | 
**SourceType** | Pointer to [**SourceType**](SourceType.md) |  | [optional] 

## Methods

### NewAssetFaceResponseDto

`func NewAssetFaceResponseDto(boundingBoxX1 int32, boundingBoxX2 int32, boundingBoxY1 int32, boundingBoxY2 int32, id string, imageHeight int32, imageWidth int32, person NullablePersonResponseDto, ) *AssetFaceResponseDto`

NewAssetFaceResponseDto instantiates a new AssetFaceResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetFaceResponseDtoWithDefaults

`func NewAssetFaceResponseDtoWithDefaults() *AssetFaceResponseDto`

NewAssetFaceResponseDtoWithDefaults instantiates a new AssetFaceResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBoundingBoxX1

`func (o *AssetFaceResponseDto) GetBoundingBoxX1() int32`

GetBoundingBoxX1 returns the BoundingBoxX1 field if non-nil, zero value otherwise.

### GetBoundingBoxX1Ok

`func (o *AssetFaceResponseDto) GetBoundingBoxX1Ok() (*int32, bool)`

GetBoundingBoxX1Ok returns a tuple with the BoundingBoxX1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX1

`func (o *AssetFaceResponseDto) SetBoundingBoxX1(v int32)`

SetBoundingBoxX1 sets BoundingBoxX1 field to given value.


### GetBoundingBoxX2

`func (o *AssetFaceResponseDto) GetBoundingBoxX2() int32`

GetBoundingBoxX2 returns the BoundingBoxX2 field if non-nil, zero value otherwise.

### GetBoundingBoxX2Ok

`func (o *AssetFaceResponseDto) GetBoundingBoxX2Ok() (*int32, bool)`

GetBoundingBoxX2Ok returns a tuple with the BoundingBoxX2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX2

`func (o *AssetFaceResponseDto) SetBoundingBoxX2(v int32)`

SetBoundingBoxX2 sets BoundingBoxX2 field to given value.


### GetBoundingBoxY1

`func (o *AssetFaceResponseDto) GetBoundingBoxY1() int32`

GetBoundingBoxY1 returns the BoundingBoxY1 field if non-nil, zero value otherwise.

### GetBoundingBoxY1Ok

`func (o *AssetFaceResponseDto) GetBoundingBoxY1Ok() (*int32, bool)`

GetBoundingBoxY1Ok returns a tuple with the BoundingBoxY1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY1

`func (o *AssetFaceResponseDto) SetBoundingBoxY1(v int32)`

SetBoundingBoxY1 sets BoundingBoxY1 field to given value.


### GetBoundingBoxY2

`func (o *AssetFaceResponseDto) GetBoundingBoxY2() int32`

GetBoundingBoxY2 returns the BoundingBoxY2 field if non-nil, zero value otherwise.

### GetBoundingBoxY2Ok

`func (o *AssetFaceResponseDto) GetBoundingBoxY2Ok() (*int32, bool)`

GetBoundingBoxY2Ok returns a tuple with the BoundingBoxY2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY2

`func (o *AssetFaceResponseDto) SetBoundingBoxY2(v int32)`

SetBoundingBoxY2 sets BoundingBoxY2 field to given value.


### GetId

`func (o *AssetFaceResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetFaceResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetFaceResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetImageHeight

`func (o *AssetFaceResponseDto) GetImageHeight() int32`

GetImageHeight returns the ImageHeight field if non-nil, zero value otherwise.

### GetImageHeightOk

`func (o *AssetFaceResponseDto) GetImageHeightOk() (*int32, bool)`

GetImageHeightOk returns a tuple with the ImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageHeight

`func (o *AssetFaceResponseDto) SetImageHeight(v int32)`

SetImageHeight sets ImageHeight field to given value.


### GetImageWidth

`func (o *AssetFaceResponseDto) GetImageWidth() int32`

GetImageWidth returns the ImageWidth field if non-nil, zero value otherwise.

### GetImageWidthOk

`func (o *AssetFaceResponseDto) GetImageWidthOk() (*int32, bool)`

GetImageWidthOk returns a tuple with the ImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageWidth

`func (o *AssetFaceResponseDto) SetImageWidth(v int32)`

SetImageWidth sets ImageWidth field to given value.


### GetPerson

`func (o *AssetFaceResponseDto) GetPerson() PersonResponseDto`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *AssetFaceResponseDto) GetPersonOk() (*PersonResponseDto, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *AssetFaceResponseDto) SetPerson(v PersonResponseDto)`

SetPerson sets Person field to given value.


### SetPersonNil

`func (o *AssetFaceResponseDto) SetPersonNil(b bool)`

 SetPersonNil sets the value for Person to be an explicit nil

### UnsetPerson
`func (o *AssetFaceResponseDto) UnsetPerson()`

UnsetPerson ensures that no value is present for Person, not even an explicit nil
### GetSourceType

`func (o *AssetFaceResponseDto) GetSourceType() SourceType`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *AssetFaceResponseDto) GetSourceTypeOk() (*SourceType, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *AssetFaceResponseDto) SetSourceType(v SourceType)`

SetSourceType sets SourceType field to given value.

### HasSourceType

`func (o *AssetFaceResponseDto) HasSourceType() bool`

HasSourceType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


