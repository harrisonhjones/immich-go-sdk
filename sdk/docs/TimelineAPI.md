# \TimelineAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTimeBucket**](TimelineAPI.md#GetTimeBucket) | **Get** /timeline/bucket | Get time bucket
[**GetTimeBuckets**](TimelineAPI.md#GetTimeBuckets) | **Get** /timeline/buckets | Get time buckets



## GetTimeBucket

> TimeBucketAssetResponseDto GetTimeBucket(ctx).TimeBucket(timeBucket).AlbumId(albumId).Bbox(bbox).IsFavorite(isFavorite).IsTrashed(isTrashed).Key(key).Order(order).PersonId(personId).Slug(slug).TagId(tagId).UserId(userId).Visibility(visibility).WithCoordinates(withCoordinates).WithPartners(withPartners).WithStacked(withStacked).Execute()

Get time bucket



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
	timeBucket := "2024-01-01" // string | Time bucket identifier in YYYY-MM-DD format
	albumId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets belonging to a specific album (optional)
	bbox := "11.075683,49.416711,11.117589,49.454875" // string | Bounding box coordinates as west,south,east,north (WGS84) (optional)
	isFavorite := true // bool | Filter by favorite status (true for favorites only, false for non-favorites only) (optional)
	isTrashed := true // bool | Filter by trash status (true for trashed assets only, false for non-trashed only) (optional)
	key := "key_example" // string |  (optional)
	order := openapiclient.AssetOrder("asc") // AssetOrder | Sort order for assets within time buckets (ASC for oldest first, DESC for newest first) (optional)
	personId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets containing a specific person (face recognition) (optional)
	slug := "slug_example" // string |  (optional)
	tagId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets with a specific tag (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets by specific user ID (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility | Filter by asset visibility status (ARCHIVE, TIMELINE, HIDDEN, LOCKED) (optional)
	withCoordinates := true // bool | Include location data in the response (optional)
	withPartners := true // bool | Include assets shared by partners (optional)
	withStacked := true // bool | Include stacked assets in the response. When true, only primary assets from stacks are returned. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimelineAPI.GetTimeBucket(context.Background()).TimeBucket(timeBucket).AlbumId(albumId).Bbox(bbox).IsFavorite(isFavorite).IsTrashed(isTrashed).Key(key).Order(order).PersonId(personId).Slug(slug).TagId(tagId).UserId(userId).Visibility(visibility).WithCoordinates(withCoordinates).WithPartners(withPartners).WithStacked(withStacked).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimelineAPI.GetTimeBucket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTimeBucket`: TimeBucketAssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TimelineAPI.GetTimeBucket`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTimeBucketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **timeBucket** | **string** | Time bucket identifier in YYYY-MM-DD format | 
 **albumId** | **string** | Filter assets belonging to a specific album | 
 **bbox** | **string** | Bounding box coordinates as west,south,east,north (WGS84) | 
 **isFavorite** | **bool** | Filter by favorite status (true for favorites only, false for non-favorites only) | 
 **isTrashed** | **bool** | Filter by trash status (true for trashed assets only, false for non-trashed only) | 
 **key** | **string** |  | 
 **order** | [**AssetOrder**](AssetOrder.md) | Sort order for assets within time buckets (ASC for oldest first, DESC for newest first) | 
 **personId** | **string** | Filter assets containing a specific person (face recognition) | 
 **slug** | **string** |  | 
 **tagId** | **string** | Filter assets with a specific tag | 
 **userId** | **string** | Filter assets by specific user ID | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) | Filter by asset visibility status (ARCHIVE, TIMELINE, HIDDEN, LOCKED) | 
 **withCoordinates** | **bool** | Include location data in the response | 
 **withPartners** | **bool** | Include assets shared by partners | 
 **withStacked** | **bool** | Include stacked assets in the response. When true, only primary assets from stacks are returned. | 

### Return type

[**TimeBucketAssetResponseDto**](TimeBucketAssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTimeBuckets

> []TimeBucketsResponseDto GetTimeBuckets(ctx).AlbumId(albumId).Bbox(bbox).IsFavorite(isFavorite).IsTrashed(isTrashed).Key(key).Order(order).PersonId(personId).Slug(slug).TagId(tagId).UserId(userId).Visibility(visibility).WithCoordinates(withCoordinates).WithPartners(withPartners).WithStacked(withStacked).Execute()

Get time buckets



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
	albumId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets belonging to a specific album (optional)
	bbox := "11.075683,49.416711,11.117589,49.454875" // string | Bounding box coordinates as west,south,east,north (WGS84) (optional)
	isFavorite := true // bool | Filter by favorite status (true for favorites only, false for non-favorites only) (optional)
	isTrashed := true // bool | Filter by trash status (true for trashed assets only, false for non-trashed only) (optional)
	key := "key_example" // string |  (optional)
	order := openapiclient.AssetOrder("asc") // AssetOrder | Sort order for assets within time buckets (ASC for oldest first, DESC for newest first) (optional)
	personId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets containing a specific person (face recognition) (optional)
	slug := "slug_example" // string |  (optional)
	tagId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets with a specific tag (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter assets by specific user ID (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility | Filter by asset visibility status (ARCHIVE, TIMELINE, HIDDEN, LOCKED) (optional)
	withCoordinates := true // bool | Include location data in the response (optional)
	withPartners := true // bool | Include assets shared by partners (optional)
	withStacked := true // bool | Include stacked assets in the response. When true, only primary assets from stacks are returned. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TimelineAPI.GetTimeBuckets(context.Background()).AlbumId(albumId).Bbox(bbox).IsFavorite(isFavorite).IsTrashed(isTrashed).Key(key).Order(order).PersonId(personId).Slug(slug).TagId(tagId).UserId(userId).Visibility(visibility).WithCoordinates(withCoordinates).WithPartners(withPartners).WithStacked(withStacked).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TimelineAPI.GetTimeBuckets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTimeBuckets`: []TimeBucketsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TimelineAPI.GetTimeBuckets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTimeBucketsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumId** | **string** | Filter assets belonging to a specific album | 
 **bbox** | **string** | Bounding box coordinates as west,south,east,north (WGS84) | 
 **isFavorite** | **bool** | Filter by favorite status (true for favorites only, false for non-favorites only) | 
 **isTrashed** | **bool** | Filter by trash status (true for trashed assets only, false for non-trashed only) | 
 **key** | **string** |  | 
 **order** | [**AssetOrder**](AssetOrder.md) | Sort order for assets within time buckets (ASC for oldest first, DESC for newest first) | 
 **personId** | **string** | Filter assets containing a specific person (face recognition) | 
 **slug** | **string** |  | 
 **tagId** | **string** | Filter assets with a specific tag | 
 **userId** | **string** | Filter assets by specific user ID | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) | Filter by asset visibility status (ARCHIVE, TIMELINE, HIDDEN, LOCKED) | 
 **withCoordinates** | **bool** | Include location data in the response | 
 **withPartners** | **bool** | Include assets shared by partners | 
 **withStacked** | **bool** | Include stacked assets in the response. When true, only primary assets from stacks are returned. | 

### Return type

[**[]TimeBucketsResponseDto**](TimeBucketsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

