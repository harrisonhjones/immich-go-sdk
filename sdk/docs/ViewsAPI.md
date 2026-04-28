# \ViewsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAssetsByOriginalPath**](ViewsAPI.md#GetAssetsByOriginalPath) | **Get** /view/folder | Retrieve assets by original path
[**GetUniqueOriginalPaths**](ViewsAPI.md#GetUniqueOriginalPaths) | **Get** /view/folder/unique-paths | Retrieve unique paths



## GetAssetsByOriginalPath

> []AssetResponseDto GetAssetsByOriginalPath(ctx).Path(path).Execute()

Retrieve assets by original path



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
	path := "path_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ViewsAPI.GetAssetsByOriginalPath(context.Background()).Path(path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViewsAPI.GetAssetsByOriginalPath``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetsByOriginalPath`: []AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `ViewsAPI.GetAssetsByOriginalPath`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetsByOriginalPathRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **path** | **string** |  | 

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


## GetUniqueOriginalPaths

> []string GetUniqueOriginalPaths(ctx).Execute()

Retrieve unique paths



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
	resp, r, err := apiClient.ViewsAPI.GetUniqueOriginalPaths(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViewsAPI.GetUniqueOriginalPaths``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUniqueOriginalPaths`: []string
	fmt.Fprintf(os.Stdout, "Response from `ViewsAPI.GetUniqueOriginalPaths`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUniqueOriginalPathsRequest struct via the builder pattern


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

