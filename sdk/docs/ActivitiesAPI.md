# \ActivitiesAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateActivity**](ActivitiesAPI.md#CreateActivity) | **Post** /activities | Create an activity
[**DeleteActivity**](ActivitiesAPI.md#DeleteActivity) | **Delete** /activities/{id} | Delete an activity
[**GetActivities**](ActivitiesAPI.md#GetActivities) | **Get** /activities | List all activities
[**GetActivityStatistics**](ActivitiesAPI.md#GetActivityStatistics) | **Get** /activities/statistics | Retrieve activity statistics



## CreateActivity

> ActivityResponseDto CreateActivity(ctx).ActivityCreateDto(activityCreateDto).Execute()

Create an activity



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	activityCreateDto := *openapiclient.NewActivityCreateDto("AlbumId_example", openapiclient.ReactionType("comment")) // ActivityCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivitiesAPI.CreateActivity(context.Background()).ActivityCreateDto(activityCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivitiesAPI.CreateActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateActivity`: ActivityResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ActivitiesAPI.CreateActivity`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **activityCreateDto** | [**ActivityCreateDto**](ActivityCreateDto.md) |  | 

### Return type

[**ActivityResponseDto**](ActivityResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteActivity

> DeleteActivity(ctx, id).Execute()

Delete an activity



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ActivitiesAPI.DeleteActivity(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivitiesAPI.DeleteActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetActivities

> []ActivityResponseDto GetActivities(ctx).AlbumId(albumId).AssetId(assetId).Level(level).Type_(type_).UserId(userId).Execute()

List all activities



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	albumId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Album ID
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Asset ID (if activity is for an asset) (optional)
	level := openapiclient.ReactionLevel("album") // ReactionLevel |  (optional)
	type_ := openapiclient.ReactionType("comment") // ReactionType |  (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by user ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivitiesAPI.GetActivities(context.Background()).AlbumId(albumId).AssetId(assetId).Level(level).Type_(type_).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivitiesAPI.GetActivities``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetActivities`: []ActivityResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ActivitiesAPI.GetActivities`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetActivitiesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumId** | **string** | Album ID | 
 **assetId** | **string** | Asset ID (if activity is for an asset) | 
 **level** | [**ReactionLevel**](ReactionLevel.md) |  | 
 **type_** | [**ReactionType**](ReactionType.md) |  | 
 **userId** | **string** | Filter by user ID | 

### Return type

[**[]ActivityResponseDto**](ActivityResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetActivityStatistics

> ActivityStatisticsResponseDto GetActivityStatistics(ctx).AlbumId(albumId).AssetId(assetId).Execute()

Retrieve activity statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	albumId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Album ID
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Asset ID (if activity is for an asset) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivitiesAPI.GetActivityStatistics(context.Background()).AlbumId(albumId).AssetId(assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivitiesAPI.GetActivityStatistics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetActivityStatistics`: ActivityStatisticsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ActivitiesAPI.GetActivityStatistics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetActivityStatisticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumId** | **string** | Album ID | 
 **assetId** | **string** | Asset ID (if activity is for an asset) | 

### Return type

[**ActivityStatisticsResponseDto**](ActivityStatisticsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

