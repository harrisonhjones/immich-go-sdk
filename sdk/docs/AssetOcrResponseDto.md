# AssetOcrResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** |  | 
**BoxScore** | **float64** | Confidence score for text detection box | 
**Id** | **string** |  | 
**Text** | **string** | Recognized text | 
**TextScore** | **float64** | Confidence score for text recognition | 
**X1** | **float64** | Normalized x coordinate of box corner 1 (0-1) | 
**X2** | **float64** | Normalized x coordinate of box corner 2 (0-1) | 
**X3** | **float64** | Normalized x coordinate of box corner 3 (0-1) | 
**X4** | **float64** | Normalized x coordinate of box corner 4 (0-1) | 
**Y1** | **float64** | Normalized y coordinate of box corner 1 (0-1) | 
**Y2** | **float64** | Normalized y coordinate of box corner 2 (0-1) | 
**Y3** | **float64** | Normalized y coordinate of box corner 3 (0-1) | 
**Y4** | **float64** | Normalized y coordinate of box corner 4 (0-1) | 

## Methods

### NewAssetOcrResponseDto

`func NewAssetOcrResponseDto(assetId string, boxScore float64, id string, text string, textScore float64, x1 float64, x2 float64, x3 float64, x4 float64, y1 float64, y2 float64, y3 float64, y4 float64, ) *AssetOcrResponseDto`

NewAssetOcrResponseDto instantiates a new AssetOcrResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetOcrResponseDtoWithDefaults

`func NewAssetOcrResponseDtoWithDefaults() *AssetOcrResponseDto`

NewAssetOcrResponseDtoWithDefaults instantiates a new AssetOcrResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetOcrResponseDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetOcrResponseDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetOcrResponseDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetBoxScore

`func (o *AssetOcrResponseDto) GetBoxScore() float64`

GetBoxScore returns the BoxScore field if non-nil, zero value otherwise.

### GetBoxScoreOk

`func (o *AssetOcrResponseDto) GetBoxScoreOk() (*float64, bool)`

GetBoxScoreOk returns a tuple with the BoxScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoxScore

`func (o *AssetOcrResponseDto) SetBoxScore(v float64)`

SetBoxScore sets BoxScore field to given value.


### GetId

`func (o *AssetOcrResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetOcrResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetOcrResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetText

`func (o *AssetOcrResponseDto) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *AssetOcrResponseDto) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *AssetOcrResponseDto) SetText(v string)`

SetText sets Text field to given value.


### GetTextScore

`func (o *AssetOcrResponseDto) GetTextScore() float64`

GetTextScore returns the TextScore field if non-nil, zero value otherwise.

### GetTextScoreOk

`func (o *AssetOcrResponseDto) GetTextScoreOk() (*float64, bool)`

GetTextScoreOk returns a tuple with the TextScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextScore

`func (o *AssetOcrResponseDto) SetTextScore(v float64)`

SetTextScore sets TextScore field to given value.


### GetX1

`func (o *AssetOcrResponseDto) GetX1() float64`

GetX1 returns the X1 field if non-nil, zero value otherwise.

### GetX1Ok

`func (o *AssetOcrResponseDto) GetX1Ok() (*float64, bool)`

GetX1Ok returns a tuple with the X1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX1

`func (o *AssetOcrResponseDto) SetX1(v float64)`

SetX1 sets X1 field to given value.


### GetX2

`func (o *AssetOcrResponseDto) GetX2() float64`

GetX2 returns the X2 field if non-nil, zero value otherwise.

### GetX2Ok

`func (o *AssetOcrResponseDto) GetX2Ok() (*float64, bool)`

GetX2Ok returns a tuple with the X2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX2

`func (o *AssetOcrResponseDto) SetX2(v float64)`

SetX2 sets X2 field to given value.


### GetX3

`func (o *AssetOcrResponseDto) GetX3() float64`

GetX3 returns the X3 field if non-nil, zero value otherwise.

### GetX3Ok

`func (o *AssetOcrResponseDto) GetX3Ok() (*float64, bool)`

GetX3Ok returns a tuple with the X3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX3

`func (o *AssetOcrResponseDto) SetX3(v float64)`

SetX3 sets X3 field to given value.


### GetX4

`func (o *AssetOcrResponseDto) GetX4() float64`

GetX4 returns the X4 field if non-nil, zero value otherwise.

### GetX4Ok

`func (o *AssetOcrResponseDto) GetX4Ok() (*float64, bool)`

GetX4Ok returns a tuple with the X4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX4

`func (o *AssetOcrResponseDto) SetX4(v float64)`

SetX4 sets X4 field to given value.


### GetY1

`func (o *AssetOcrResponseDto) GetY1() float64`

GetY1 returns the Y1 field if non-nil, zero value otherwise.

### GetY1Ok

`func (o *AssetOcrResponseDto) GetY1Ok() (*float64, bool)`

GetY1Ok returns a tuple with the Y1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY1

`func (o *AssetOcrResponseDto) SetY1(v float64)`

SetY1 sets Y1 field to given value.


### GetY2

`func (o *AssetOcrResponseDto) GetY2() float64`

GetY2 returns the Y2 field if non-nil, zero value otherwise.

### GetY2Ok

`func (o *AssetOcrResponseDto) GetY2Ok() (*float64, bool)`

GetY2Ok returns a tuple with the Y2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY2

`func (o *AssetOcrResponseDto) SetY2(v float64)`

SetY2 sets Y2 field to given value.


### GetY3

`func (o *AssetOcrResponseDto) GetY3() float64`

GetY3 returns the Y3 field if non-nil, zero value otherwise.

### GetY3Ok

`func (o *AssetOcrResponseDto) GetY3Ok() (*float64, bool)`

GetY3Ok returns a tuple with the Y3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY3

`func (o *AssetOcrResponseDto) SetY3(v float64)`

SetY3 sets Y3 field to given value.


### GetY4

`func (o *AssetOcrResponseDto) GetY4() float64`

GetY4 returns the Y4 field if non-nil, zero value otherwise.

### GetY4Ok

`func (o *AssetOcrResponseDto) GetY4Ok() (*float64, bool)`

GetY4Ok returns a tuple with the Y4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY4

`func (o *AssetOcrResponseDto) SetY4(v float64)`

SetY4 sets Y4 field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


