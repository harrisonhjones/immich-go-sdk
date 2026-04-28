# \DownloadAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DownloadArchive**](DownloadAPI.md#DownloadArchive) | **Post** /download/archive | Download asset archive
[**GetDownloadInfo**](DownloadAPI.md#GetDownloadInfo) | **Post** /download/info | Retrieve download information



## DownloadArchive

> *os.File DownloadArchive(ctx).DownloadArchiveDto(downloadArchiveDto).Key(key).Slug(slug).Execute()

Download asset archive



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
	downloadArchiveDto := *openapiclient.NewDownloadArchiveDto([]string{"AssetIds_example"}) // DownloadArchiveDto | 
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DownloadAPI.DownloadArchive(context.Background()).DownloadArchiveDto(downloadArchiveDto).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DownloadAPI.DownloadArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadArchive`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `DownloadAPI.DownloadArchive`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDownloadArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **downloadArchiveDto** | [**DownloadArchiveDto**](DownloadArchiveDto.md) |  | 
 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDownloadInfo

> DownloadResponseDto GetDownloadInfo(ctx).DownloadInfoDto(downloadInfoDto).Key(key).Slug(slug).Execute()

Retrieve download information



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
	downloadInfoDto := *openapiclient.NewDownloadInfoDto() // DownloadInfoDto | 
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DownloadAPI.GetDownloadInfo(context.Background()).DownloadInfoDto(downloadInfoDto).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DownloadAPI.GetDownloadInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDownloadInfo`: DownloadResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DownloadAPI.GetDownloadInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDownloadInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **downloadInfoDto** | [**DownloadInfoDto**](DownloadInfoDto.md) |  | 
 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[**DownloadResponseDto**](DownloadResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

