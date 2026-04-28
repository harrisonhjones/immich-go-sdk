# \SearchAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAssetsByCity**](SearchAPI.md#GetAssetsByCity) | **Get** /search/cities | Retrieve assets by city
[**GetExploreData**](SearchAPI.md#GetExploreData) | **Get** /search/explore | Retrieve explore data
[**GetSearchSuggestions**](SearchAPI.md#GetSearchSuggestions) | **Get** /search/suggestions | Retrieve search suggestions
[**SearchAssetStatistics**](SearchAPI.md#SearchAssetStatistics) | **Post** /search/statistics | Search asset statistics
[**SearchAssets**](SearchAPI.md#SearchAssets) | **Post** /search/metadata | Search assets by metadata
[**SearchLargeAssets**](SearchAPI.md#SearchLargeAssets) | **Post** /search/large-assets | Search large assets
[**SearchPerson**](SearchAPI.md#SearchPerson) | **Get** /search/person | Search people
[**SearchPlaces**](SearchAPI.md#SearchPlaces) | **Get** /search/places | Search places
[**SearchRandom**](SearchAPI.md#SearchRandom) | **Post** /search/random | Search random assets
[**SearchSmart**](SearchAPI.md#SearchSmart) | **Post** /search/smart | Smart asset search



## GetAssetsByCity

> []AssetResponseDto GetAssetsByCity(ctx).Execute()

Retrieve assets by city



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.GetAssetsByCity(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.GetAssetsByCity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetsByCity`: []AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.GetAssetsByCity`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetsByCityRequest struct via the builder pattern


### Return type

[**[]AssetResponseDto**](AssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetExploreData

> []SearchExploreResponseDto GetExploreData(ctx).Execute()

Retrieve explore data



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.GetExploreData(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.GetExploreData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetExploreData`: []SearchExploreResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.GetExploreData`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetExploreDataRequest struct via the builder pattern


### Return type

[**[]SearchExploreResponseDto**](SearchExploreResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSearchSuggestions

> []string GetSearchSuggestions(ctx).Type_(type_).Country(country).IncludeNull(includeNull).LensModel(lensModel).Make(make).Model(model).State(state).Execute()

Retrieve search suggestions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	type_ := openapiclient.SearchSuggestionType("country") // SearchSuggestionType | 
	country := "country_example" // string | Filter by country (optional)
	includeNull := true // bool | Include null values in suggestions (optional)
	lensModel := "lensModel_example" // string | Filter by lens model (optional)
	make := "make_example" // string | Filter by camera make (optional)
	model := "model_example" // string | Filter by camera model (optional)
	state := "state_example" // string | Filter by state/province (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.GetSearchSuggestions(context.Background()).Type_(type_).Country(country).IncludeNull(includeNull).LensModel(lensModel).Make(make).Model(model).State(state).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.GetSearchSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSearchSuggestions`: []string
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.GetSearchSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSearchSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | [**SearchSuggestionType**](SearchSuggestionType.md) |  | 
 **country** | **string** | Filter by country | 
 **includeNull** | **bool** | Include null values in suggestions | 
 **lensModel** | **string** | Filter by lens model | 
 **make** | **string** | Filter by camera make | 
 **model** | **string** | Filter by camera model | 
 **state** | **string** | Filter by state/province | 

### Return type

**[]string**

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchAssetStatistics

> SearchStatisticsResponseDto SearchAssetStatistics(ctx).StatisticsSearchDto(statisticsSearchDto).Execute()

Search asset statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	statisticsSearchDto := *openapiclient.NewStatisticsSearchDto() // StatisticsSearchDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchAssetStatistics(context.Background()).StatisticsSearchDto(statisticsSearchDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchAssetStatistics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAssetStatistics`: SearchStatisticsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchAssetStatistics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAssetStatisticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **statisticsSearchDto** | [**StatisticsSearchDto**](StatisticsSearchDto.md) |  | 

### Return type

[**SearchStatisticsResponseDto**](SearchStatisticsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchAssets

> SearchResponseDto SearchAssets(ctx).MetadataSearchDto(metadataSearchDto).Execute()

Search assets by metadata



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	metadataSearchDto := *openapiclient.NewMetadataSearchDto() // MetadataSearchDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchAssets(context.Background()).MetadataSearchDto(metadataSearchDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAssets`: SearchResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **metadataSearchDto** | [**MetadataSearchDto**](MetadataSearchDto.md) |  | 

### Return type

[**SearchResponseDto**](SearchResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchLargeAssets

> []AssetResponseDto SearchLargeAssets(ctx).AlbumIds(albumIds).City(city).Country(country).CreatedAfter(createdAfter).CreatedBefore(createdBefore).IsEncoded(isEncoded).IsFavorite(isFavorite).IsMotion(isMotion).IsNotInAlbum(isNotInAlbum).IsOffline(isOffline).LensModel(lensModel).LibraryId(libraryId).Make(make).MinFileSize(minFileSize).Model(model).Ocr(ocr).PersonIds(personIds).Rating(rating).Size(size).State(state).TagIds(tagIds).TakenAfter(takenAfter).TakenBefore(takenBefore).TrashedAfter(trashedAfter).TrashedBefore(trashedBefore).Type_(type_).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).Visibility(visibility).WithDeleted(withDeleted).WithExif(withExif).Execute()

Search large assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	albumIds := []string{"Inner_example"} // []string | Filter by album IDs (optional)
	city := "city_example" // string | Filter by city name (optional)
	country := "country_example" // string | Filter by country name (optional)
	createdAfter := time.Now() // time.Time | Filter by creation date (after) (optional)
	createdBefore := time.Now() // time.Time | Filter by creation date (before) (optional)
	isEncoded := true // bool | Filter by encoded status (optional)
	isFavorite := true // bool | Filter by favorite status (optional)
	isMotion := true // bool | Filter by motion photo status (optional)
	isNotInAlbum := true // bool | Filter assets not in any album (optional)
	isOffline := true // bool | Filter by offline status (optional)
	lensModel := "lensModel_example" // string | Filter by lens model (optional)
	libraryId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Library ID to filter by (optional)
	make := "make_example" // string | Filter by camera make (optional)
	minFileSize := int32(56) // int32 | Minimum file size in bytes (optional)
	model := "model_example" // string | Filter by camera model (optional)
	ocr := "ocr_example" // string | Filter by OCR text content (optional)
	personIds := []string{"Inner_example"} // []string | Filter by person IDs (optional)
	rating := float32(8.14) // float32 | Filter by rating [1-5], or null for unrated (optional)
	size := float32(8.14) // float32 | Number of results to return (optional)
	state := "state_example" // string | Filter by state/province name (optional)
	tagIds := []string{"Inner_example"} // []string | Filter by tag IDs (optional)
	takenAfter := time.Now() // time.Time | Filter by taken date (after) (optional)
	takenBefore := time.Now() // time.Time | Filter by taken date (before) (optional)
	trashedAfter := time.Now() // time.Time | Filter by trash date (after) (optional)
	trashedBefore := time.Now() // time.Time | Filter by trash date (before) (optional)
	type_ := openapiclient.AssetTypeEnum("IMAGE") // AssetTypeEnum |  (optional)
	updatedAfter := time.Now() // time.Time | Filter by update date (after) (optional)
	updatedBefore := time.Now() // time.Time | Filter by update date (before) (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility |  (optional)
	withDeleted := true // bool | Include deleted assets (optional)
	withExif := true // bool | Include EXIF data in response (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchLargeAssets(context.Background()).AlbumIds(albumIds).City(city).Country(country).CreatedAfter(createdAfter).CreatedBefore(createdBefore).IsEncoded(isEncoded).IsFavorite(isFavorite).IsMotion(isMotion).IsNotInAlbum(isNotInAlbum).IsOffline(isOffline).LensModel(lensModel).LibraryId(libraryId).Make(make).MinFileSize(minFileSize).Model(model).Ocr(ocr).PersonIds(personIds).Rating(rating).Size(size).State(state).TagIds(tagIds).TakenAfter(takenAfter).TakenBefore(takenBefore).TrashedAfter(trashedAfter).TrashedBefore(trashedBefore).Type_(type_).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).Visibility(visibility).WithDeleted(withDeleted).WithExif(withExif).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchLargeAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchLargeAssets`: []AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchLargeAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchLargeAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumIds** | **[]string** | Filter by album IDs | 
 **city** | **string** | Filter by city name | 
 **country** | **string** | Filter by country name | 
 **createdAfter** | **time.Time** | Filter by creation date (after) | 
 **createdBefore** | **time.Time** | Filter by creation date (before) | 
 **isEncoded** | **bool** | Filter by encoded status | 
 **isFavorite** | **bool** | Filter by favorite status | 
 **isMotion** | **bool** | Filter by motion photo status | 
 **isNotInAlbum** | **bool** | Filter assets not in any album | 
 **isOffline** | **bool** | Filter by offline status | 
 **lensModel** | **string** | Filter by lens model | 
 **libraryId** | **string** | Library ID to filter by | 
 **make** | **string** | Filter by camera make | 
 **minFileSize** | **int32** | Minimum file size in bytes | 
 **model** | **string** | Filter by camera model | 
 **ocr** | **string** | Filter by OCR text content | 
 **personIds** | **[]string** | Filter by person IDs | 
 **rating** | **float32** | Filter by rating [1-5], or null for unrated | 
 **size** | **float32** | Number of results to return | 
 **state** | **string** | Filter by state/province name | 
 **tagIds** | **[]string** | Filter by tag IDs | 
 **takenAfter** | **time.Time** | Filter by taken date (after) | 
 **takenBefore** | **time.Time** | Filter by taken date (before) | 
 **trashedAfter** | **time.Time** | Filter by trash date (after) | 
 **trashedBefore** | **time.Time** | Filter by trash date (before) | 
 **type_** | [**AssetTypeEnum**](AssetTypeEnum.md) |  | 
 **updatedAfter** | **time.Time** | Filter by update date (after) | 
 **updatedBefore** | **time.Time** | Filter by update date (before) | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 
 **withDeleted** | **bool** | Include deleted assets | 
 **withExif** | **bool** | Include EXIF data in response | 

### Return type

[**[]AssetResponseDto**](AssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPerson

> []PersonResponseDto SearchPerson(ctx).Name(name).WithHidden(withHidden).Execute()

Search people



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	name := "name_example" // string | Person name to search for
	withHidden := true // bool | Include hidden people (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchPerson(context.Background()).Name(name).WithHidden(withHidden).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchPerson``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPerson`: []PersonResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchPerson`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPersonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Person name to search for | 
 **withHidden** | **bool** | Include hidden people | 

### Return type

[**[]PersonResponseDto**](PersonResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPlaces

> []PlacesResponseDto SearchPlaces(ctx).Name(name).Execute()

Search places



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	name := "name_example" // string | Place name to search for

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchPlaces(context.Background()).Name(name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchPlaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPlaces`: []PlacesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchPlaces`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPlacesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Place name to search for | 

### Return type

[**[]PlacesResponseDto**](PlacesResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchRandom

> []AssetResponseDto SearchRandom(ctx).RandomSearchDto(randomSearchDto).Execute()

Search random assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	randomSearchDto := *openapiclient.NewRandomSearchDto() // RandomSearchDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchRandom(context.Background()).RandomSearchDto(randomSearchDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchRandom``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchRandom`: []AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchRandom`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchRandomRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **randomSearchDto** | [**RandomSearchDto**](RandomSearchDto.md) |  | 

### Return type

[**[]AssetResponseDto**](AssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchSmart

> SearchResponseDto SearchSmart(ctx).SmartSearchDto(smartSearchDto).Execute()

Smart asset search



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	smartSearchDto := *openapiclient.NewSmartSearchDto() // SmartSearchDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SearchAPI.SearchSmart(context.Background()).SmartSearchDto(smartSearchDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SearchAPI.SearchSmart``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchSmart`: SearchResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SearchAPI.SearchSmart`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchSmartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smartSearchDto** | [**SmartSearchDto**](SmartSearchDto.md) |  | 

### Return type

[**SearchResponseDto**](SearchResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

