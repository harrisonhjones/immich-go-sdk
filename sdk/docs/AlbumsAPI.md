# \AlbumsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddAssetsToAlbum**](AlbumsAPI.md#AddAssetsToAlbum) | **Put** /albums/{id}/assets | Add assets to an album
[**AddAssetsToAlbums**](AlbumsAPI.md#AddAssetsToAlbums) | **Put** /albums/assets | Add assets to albums
[**AddUsersToAlbum**](AlbumsAPI.md#AddUsersToAlbum) | **Put** /albums/{id}/users | Share album with users
[**CreateAlbum**](AlbumsAPI.md#CreateAlbum) | **Post** /albums | Create an album
[**DeleteAlbum**](AlbumsAPI.md#DeleteAlbum) | **Delete** /albums/{id} | Delete an album
[**GetAlbumInfo**](AlbumsAPI.md#GetAlbumInfo) | **Get** /albums/{id} | Retrieve an album
[**GetAlbumMapMarkers**](AlbumsAPI.md#GetAlbumMapMarkers) | **Get** /albums/{id}/map-markers | Retrieve album map markers
[**GetAlbumStatistics**](AlbumsAPI.md#GetAlbumStatistics) | **Get** /albums/statistics | Retrieve album statistics
[**GetAllAlbums**](AlbumsAPI.md#GetAllAlbums) | **Get** /albums | List all albums
[**RemoveAssetFromAlbum**](AlbumsAPI.md#RemoveAssetFromAlbum) | **Delete** /albums/{id}/assets | Remove assets from an album
[**RemoveUserFromAlbum**](AlbumsAPI.md#RemoveUserFromAlbum) | **Delete** /albums/{id}/user/{userId} | Remove user from album
[**UpdateAlbumInfo**](AlbumsAPI.md#UpdateAlbumInfo) | **Patch** /albums/{id} | Update an album
[**UpdateAlbumUser**](AlbumsAPI.md#UpdateAlbumUser) | **Put** /albums/{id}/user/{userId} | Update user role



## AddAssetsToAlbum

> []BulkIdResponseDto AddAssetsToAlbum(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Add assets to an album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	bulkIdsDto := *openapiclient.NewBulkIdsDto([]string{"Ids_example"}) // BulkIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.AddAssetsToAlbum(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.AddAssetsToAlbum``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddAssetsToAlbum`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.AddAssetsToAlbum`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddAssetsToAlbumRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bulkIdsDto** | [**BulkIdsDto**](BulkIdsDto.md) |  | 

### Return type

[**[]BulkIdResponseDto**](BulkIdResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddAssetsToAlbums

> AlbumsAddAssetsResponseDto AddAssetsToAlbums(ctx).AlbumsAddAssetsDto(albumsAddAssetsDto).Execute()

Add assets to albums



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
	albumsAddAssetsDto := *openapiclient.NewAlbumsAddAssetsDto([]string{"AlbumIds_example"}, []string{"AssetIds_example"}) // AlbumsAddAssetsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.AddAssetsToAlbums(context.Background()).AlbumsAddAssetsDto(albumsAddAssetsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.AddAssetsToAlbums``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddAssetsToAlbums`: AlbumsAddAssetsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.AddAssetsToAlbums`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddAssetsToAlbumsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumsAddAssetsDto** | [**AlbumsAddAssetsDto**](AlbumsAddAssetsDto.md) |  | 

### Return type

[**AlbumsAddAssetsResponseDto**](AlbumsAddAssetsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddUsersToAlbum

> AlbumResponseDto AddUsersToAlbum(ctx, id).AddUsersDto(addUsersDto).Execute()

Share album with users



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	addUsersDto := *openapiclient.NewAddUsersDto([]openapiclient.AlbumUserAddDto{*openapiclient.NewAlbumUserAddDto("UserId_example")}) // AddUsersDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.AddUsersToAlbum(context.Background(), id).AddUsersDto(addUsersDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.AddUsersToAlbum``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddUsersToAlbum`: AlbumResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.AddUsersToAlbum`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddUsersToAlbumRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addUsersDto** | [**AddUsersDto**](AddUsersDto.md) |  | 

### Return type

[**AlbumResponseDto**](AlbumResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAlbum

> AlbumResponseDto CreateAlbum(ctx).CreateAlbumDto(createAlbumDto).Execute()

Create an album



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
	createAlbumDto := *openapiclient.NewCreateAlbumDto("AlbumName_example") // CreateAlbumDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.CreateAlbum(context.Background()).CreateAlbumDto(createAlbumDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.CreateAlbum``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAlbum`: AlbumResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.CreateAlbum`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAlbumRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAlbumDto** | [**CreateAlbumDto**](CreateAlbumDto.md) |  | 

### Return type

[**AlbumResponseDto**](AlbumResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAlbum

> DeleteAlbum(ctx, id).Execute()

Delete an album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AlbumsAPI.DeleteAlbum(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.DeleteAlbum``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAlbumRequest struct via the builder pattern


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


## GetAlbumInfo

> AlbumResponseDto GetAlbumInfo(ctx, id).Key(key).Slug(slug).Execute()

Retrieve an album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.GetAlbumInfo(context.Background(), id).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.GetAlbumInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlbumInfo`: AlbumResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.GetAlbumInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAlbumInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[**AlbumResponseDto**](AlbumResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAlbumMapMarkers

> []MapMarkerResponseDto GetAlbumMapMarkers(ctx, id).Key(key).Slug(slug).Execute()

Retrieve album map markers



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.GetAlbumMapMarkers(context.Background(), id).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.GetAlbumMapMarkers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlbumMapMarkers`: []MapMarkerResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.GetAlbumMapMarkers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAlbumMapMarkersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **key** | **string** |  | 
 **slug** | **string** |  | 

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


## GetAlbumStatistics

> AlbumStatisticsResponseDto GetAlbumStatistics(ctx).Execute()

Retrieve album statistics



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
	resp, r, err := apiClient.AlbumsAPI.GetAlbumStatistics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.GetAlbumStatistics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlbumStatistics`: AlbumStatisticsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.GetAlbumStatistics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAlbumStatisticsRequest struct via the builder pattern


### Return type

[**AlbumStatisticsResponseDto**](AlbumStatisticsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllAlbums

> []AlbumResponseDto GetAllAlbums(ctx).AssetId(assetId).Shared(shared).Execute()

List all albums



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
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter albums containing this asset ID (ignores shared parameter) (optional)
	shared := true // bool | Filter by shared status: true = only shared, false = not shared, undefined = all owned albums (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.GetAllAlbums(context.Background()).AssetId(assetId).Shared(shared).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.GetAllAlbums``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllAlbums`: []AlbumResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.GetAllAlbums`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllAlbumsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetId** | **string** | Filter albums containing this asset ID (ignores shared parameter) | 
 **shared** | **bool** | Filter by shared status: true &#x3D; only shared, false &#x3D; not shared, undefined &#x3D; all owned albums | 

### Return type

[**[]AlbumResponseDto**](AlbumResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveAssetFromAlbum

> []BulkIdResponseDto RemoveAssetFromAlbum(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Remove assets from an album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	bulkIdsDto := *openapiclient.NewBulkIdsDto([]string{"Ids_example"}) // BulkIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.RemoveAssetFromAlbum(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.RemoveAssetFromAlbum``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveAssetFromAlbum`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.RemoveAssetFromAlbum`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveAssetFromAlbumRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **bulkIdsDto** | [**BulkIdsDto**](BulkIdsDto.md) |  | 

### Return type

[**[]BulkIdResponseDto**](BulkIdResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveUserFromAlbum

> RemoveUserFromAlbum(ctx, id, userId).Execute()

Remove user from album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userId := "userId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AlbumsAPI.RemoveUserFromAlbum(context.Background(), id, userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.RemoveUserFromAlbum``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveUserFromAlbumRequest struct via the builder pattern


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


## UpdateAlbumInfo

> AlbumResponseDto UpdateAlbumInfo(ctx, id).UpdateAlbumDto(updateAlbumDto).Execute()

Update an album



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	updateAlbumDto := *openapiclient.NewUpdateAlbumDto() // UpdateAlbumDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlbumsAPI.UpdateAlbumInfo(context.Background(), id).UpdateAlbumDto(updateAlbumDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.UpdateAlbumInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAlbumInfo`: AlbumResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AlbumsAPI.UpdateAlbumInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAlbumInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAlbumDto** | [**UpdateAlbumDto**](UpdateAlbumDto.md) |  | 

### Return type

[**AlbumResponseDto**](AlbumResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAlbumUser

> UpdateAlbumUser(ctx, id, userId).UpdateAlbumUserDto(updateAlbumUserDto).Execute()

Update user role



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userId := "userId_example" // string | 
	updateAlbumUserDto := *openapiclient.NewUpdateAlbumUserDto(openapiclient.AlbumUserRole("editor")) // UpdateAlbumUserDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AlbumsAPI.UpdateAlbumUser(context.Background(), id, userId).UpdateAlbumUserDto(updateAlbumUserDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlbumsAPI.UpdateAlbumUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**userId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAlbumUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateAlbumUserDto** | [**UpdateAlbumUserDto**](UpdateAlbumUserDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

