# \SharedLinksAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddSharedLinkAssets**](SharedLinksAPI.md#AddSharedLinkAssets) | **Put** /shared-links/{id}/assets | Add assets to a shared link
[**CreateSharedLink**](SharedLinksAPI.md#CreateSharedLink) | **Post** /shared-links | Create a shared link
[**GetAllSharedLinks**](SharedLinksAPI.md#GetAllSharedLinks) | **Get** /shared-links | Retrieve all shared links
[**GetMySharedLink**](SharedLinksAPI.md#GetMySharedLink) | **Get** /shared-links/me | Retrieve current shared link
[**GetSharedLinkById**](SharedLinksAPI.md#GetSharedLinkById) | **Get** /shared-links/{id} | Retrieve a shared link
[**RemoveSharedLink**](SharedLinksAPI.md#RemoveSharedLink) | **Delete** /shared-links/{id} | Delete a shared link
[**RemoveSharedLinkAssets**](SharedLinksAPI.md#RemoveSharedLinkAssets) | **Delete** /shared-links/{id}/assets | Remove assets from a shared link
[**SharedLinkLogin**](SharedLinksAPI.md#SharedLinkLogin) | **Post** /shared-links/login | Shared link login
[**UpdateSharedLink**](SharedLinksAPI.md#UpdateSharedLink) | **Patch** /shared-links/{id} | Update a shared link



## AddSharedLinkAssets

> []AssetIdsResponseDto AddSharedLinkAssets(ctx, id).AssetIdsDto(assetIdsDto).Execute()

Add assets to a shared link



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
	assetIdsDto := *openapiclient.NewAssetIdsDto([]string{"AssetIds_example"}) // AssetIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.AddSharedLinkAssets(context.Background(), id).AssetIdsDto(assetIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.AddSharedLinkAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddSharedLinkAssets`: []AssetIdsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.AddSharedLinkAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddSharedLinkAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetIdsDto** | [**AssetIdsDto**](AssetIdsDto.md) |  | 

### Return type

[**[]AssetIdsResponseDto**](AssetIdsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateSharedLink

> SharedLinkResponseDto CreateSharedLink(ctx).SharedLinkCreateDto(sharedLinkCreateDto).Execute()

Create a shared link



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
	sharedLinkCreateDto := *openapiclient.NewSharedLinkCreateDto(openapiclient.SharedLinkType("ALBUM")) // SharedLinkCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.CreateSharedLink(context.Background()).SharedLinkCreateDto(sharedLinkCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.CreateSharedLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateSharedLink`: SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.CreateSharedLink`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSharedLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sharedLinkCreateDto** | [**SharedLinkCreateDto**](SharedLinkCreateDto.md) |  | 

### Return type

[**SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllSharedLinks

> []SharedLinkResponseDto GetAllSharedLinks(ctx).AlbumId(albumId).Id(id).Execute()

Retrieve all shared links



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
	albumId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by album ID (optional)
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter by shared link ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.GetAllSharedLinks(context.Background()).AlbumId(albumId).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.GetAllSharedLinks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllSharedLinks`: []SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.GetAllSharedLinks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllSharedLinksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **albumId** | **string** | Filter by album ID | 
 **id** | **string** | Filter by shared link ID | 

### Return type

[**[]SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMySharedLink

> SharedLinkResponseDto GetMySharedLink(ctx).Key(key).Slug(slug).Execute()

Retrieve current shared link



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
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.GetMySharedLink(context.Background()).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.GetMySharedLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMySharedLink`: SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.GetMySharedLink`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMySharedLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[**SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSharedLinkById

> SharedLinkResponseDto GetSharedLinkById(ctx, id).Execute()

Retrieve a shared link



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
	resp, r, err := apiClient.SharedLinksAPI.GetSharedLinkById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.GetSharedLinkById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSharedLinkById`: SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.GetSharedLinkById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSharedLinkByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveSharedLink

> RemoveSharedLink(ctx, id).Execute()

Delete a shared link



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
	r, err := apiClient.SharedLinksAPI.RemoveSharedLink(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.RemoveSharedLink``: %v\n", err)
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

Other parameters are passed through a pointer to a apiRemoveSharedLinkRequest struct via the builder pattern


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


## RemoveSharedLinkAssets

> []AssetIdsResponseDto RemoveSharedLinkAssets(ctx, id).AssetIdsDto(assetIdsDto).Execute()

Remove assets from a shared link



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
	assetIdsDto := *openapiclient.NewAssetIdsDto([]string{"AssetIds_example"}) // AssetIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.RemoveSharedLinkAssets(context.Background(), id).AssetIdsDto(assetIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.RemoveSharedLinkAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveSharedLinkAssets`: []AssetIdsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.RemoveSharedLinkAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveSharedLinkAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetIdsDto** | [**AssetIdsDto**](AssetIdsDto.md) |  | 

### Return type

[**[]AssetIdsResponseDto**](AssetIdsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SharedLinkLogin

> SharedLinkResponseDto SharedLinkLogin(ctx).SharedLinkLoginDto(sharedLinkLoginDto).Key(key).Slug(slug).Execute()

Shared link login



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
	sharedLinkLoginDto := *openapiclient.NewSharedLinkLoginDto("password") // SharedLinkLoginDto | 
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.SharedLinkLogin(context.Background()).SharedLinkLoginDto(sharedLinkLoginDto).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.SharedLinkLogin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SharedLinkLogin`: SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.SharedLinkLogin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSharedLinkLoginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sharedLinkLoginDto** | [**SharedLinkLoginDto**](SharedLinkLoginDto.md) |  | 
 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[**SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSharedLink

> SharedLinkResponseDto UpdateSharedLink(ctx, id).SharedLinkEditDto(sharedLinkEditDto).Execute()

Update a shared link



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
	sharedLinkEditDto := *openapiclient.NewSharedLinkEditDto() // SharedLinkEditDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SharedLinksAPI.UpdateSharedLink(context.Background(), id).SharedLinkEditDto(sharedLinkEditDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SharedLinksAPI.UpdateSharedLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateSharedLink`: SharedLinkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SharedLinksAPI.UpdateSharedLink`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSharedLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sharedLinkEditDto** | [**SharedLinkEditDto**](SharedLinkEditDto.md) |  | 

### Return type

[**SharedLinkResponseDto**](SharedLinkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

