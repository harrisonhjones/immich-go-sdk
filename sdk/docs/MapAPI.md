# \MapAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMapMarkers**](MapAPI.md#GetMapMarkers) | **Get** /map/markers | Retrieve map markers
[**ReverseGeocode**](MapAPI.md#ReverseGeocode) | **Get** /map/reverse-geocode | Reverse geocode coordinates



## GetMapMarkers

> []MapMarkerResponseDto GetMapMarkers(ctx).FileCreatedAfter(fileCreatedAfter).FileCreatedBefore(fileCreatedBefore).IsArchived(isArchived).IsFavorite(isFavorite).WithPartners(withPartners).WithSharedAlbums(withSharedAlbums).Execute()

Retrieve map markers



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
	fileCreatedAfter := time.Now() // time.Time | Filter assets created after this date (optional)
	fileCreatedBefore := time.Now() // time.Time | Filter assets created before this date (optional)
	isArchived := true // bool | Filter by archived status (optional)
	isFavorite := true // bool | Filter by favorite status (optional)
	withPartners := true // bool | Include partner assets (optional)
	withSharedAlbums := true // bool | Include shared album assets (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MapAPI.GetMapMarkers(context.Background()).FileCreatedAfter(fileCreatedAfter).FileCreatedBefore(fileCreatedBefore).IsArchived(isArchived).IsFavorite(isFavorite).WithPartners(withPartners).WithSharedAlbums(withSharedAlbums).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MapAPI.GetMapMarkers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMapMarkers`: []MapMarkerResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MapAPI.GetMapMarkers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMapMarkersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fileCreatedAfter** | **time.Time** | Filter assets created after this date | 
 **fileCreatedBefore** | **time.Time** | Filter assets created before this date | 
 **isArchived** | **bool** | Filter by archived status | 
 **isFavorite** | **bool** | Filter by favorite status | 
 **withPartners** | **bool** | Include partner assets | 
 **withSharedAlbums** | **bool** | Include shared album assets | 

### Return type

[**[]MapMarkerResponseDto**](MapMarkerResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReverseGeocode

> []MapReverseGeocodeResponseDto ReverseGeocode(ctx).Lat(lat).Lon(lon).Execute()

Reverse geocode coordinates



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
	lat := float64(1.2) // float64 | Latitude (-90 to 90)
	lon := float64(1.2) // float64 | Longitude (-180 to 180)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MapAPI.ReverseGeocode(context.Background()).Lat(lat).Lon(lon).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MapAPI.ReverseGeocode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReverseGeocode`: []MapReverseGeocodeResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MapAPI.ReverseGeocode`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReverseGeocodeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lat** | **float64** | Latitude (-90 to 90) | 
 **lon** | **float64** | Longitude (-180 to 180) | 

### Return type

[**[]MapReverseGeocodeResponseDto**](MapReverseGeocodeResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

