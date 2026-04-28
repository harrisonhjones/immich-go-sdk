# \AssetsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckBulkUpload**](AssetsAPI.md#CheckBulkUpload) | **Post** /assets/bulk-upload-check | Check bulk upload
[**CopyAsset**](AssetsAPI.md#CopyAsset) | **Put** /assets/copy | Copy asset
[**DeleteAssetMetadata**](AssetsAPI.md#DeleteAssetMetadata) | **Delete** /assets/{id}/metadata/{key} | Delete asset metadata by key
[**DeleteAssets**](AssetsAPI.md#DeleteAssets) | **Delete** /assets | Delete assets
[**DeleteBulkAssetMetadata**](AssetsAPI.md#DeleteBulkAssetMetadata) | **Delete** /assets/metadata | Delete asset metadata
[**DownloadAsset**](AssetsAPI.md#DownloadAsset) | **Get** /assets/{id}/original | Download original asset
[**EditAsset**](AssetsAPI.md#EditAsset) | **Put** /assets/{id}/edits | Apply edits to an existing asset
[**GetAssetEdits**](AssetsAPI.md#GetAssetEdits) | **Get** /assets/{id}/edits | Retrieve edits for an existing asset
[**GetAssetInfo**](AssetsAPI.md#GetAssetInfo) | **Get** /assets/{id} | Retrieve an asset
[**GetAssetMetadata**](AssetsAPI.md#GetAssetMetadata) | **Get** /assets/{id}/metadata | Get asset metadata
[**GetAssetMetadataByKey**](AssetsAPI.md#GetAssetMetadataByKey) | **Get** /assets/{id}/metadata/{key} | Retrieve asset metadata by key
[**GetAssetOcr**](AssetsAPI.md#GetAssetOcr) | **Get** /assets/{id}/ocr | Retrieve asset OCR data
[**GetAssetStatistics**](AssetsAPI.md#GetAssetStatistics) | **Get** /assets/statistics | Get asset statistics
[**PlayAssetVideo**](AssetsAPI.md#PlayAssetVideo) | **Get** /assets/{id}/video/playback | Play asset video
[**RemoveAssetEdits**](AssetsAPI.md#RemoveAssetEdits) | **Delete** /assets/{id}/edits | Remove edits from an existing asset
[**RunAssetJobs**](AssetsAPI.md#RunAssetJobs) | **Post** /assets/jobs | Run an asset job
[**UpdateAsset**](AssetsAPI.md#UpdateAsset) | **Put** /assets/{id} | Update an asset
[**UpdateAssetMetadata**](AssetsAPI.md#UpdateAssetMetadata) | **Put** /assets/{id}/metadata | Update asset metadata
[**UpdateAssets**](AssetsAPI.md#UpdateAssets) | **Put** /assets | Update assets
[**UpdateBulkAssetMetadata**](AssetsAPI.md#UpdateBulkAssetMetadata) | **Put** /assets/metadata | Upsert asset metadata
[**UploadAsset**](AssetsAPI.md#UploadAsset) | **Post** /assets | Upload asset
[**ViewAsset**](AssetsAPI.md#ViewAsset) | **Get** /assets/{id}/thumbnail | View asset thumbnail



## CheckBulkUpload

> AssetBulkUploadCheckResponseDto CheckBulkUpload(ctx).AssetBulkUploadCheckDto(assetBulkUploadCheckDto).Execute()

Check bulk upload



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
	assetBulkUploadCheckDto := *openapiclient.NewAssetBulkUploadCheckDto([]openapiclient.AssetBulkUploadCheckItem{*openapiclient.NewAssetBulkUploadCheckItem("Checksum_example", "Id_example")}) // AssetBulkUploadCheckDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.CheckBulkUpload(context.Background()).AssetBulkUploadCheckDto(assetBulkUploadCheckDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.CheckBulkUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckBulkUpload`: AssetBulkUploadCheckResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.CheckBulkUpload`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckBulkUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetBulkUploadCheckDto** | [**AssetBulkUploadCheckDto**](AssetBulkUploadCheckDto.md) |  | 

### Return type

[**AssetBulkUploadCheckResponseDto**](AssetBulkUploadCheckResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CopyAsset

> CopyAsset(ctx).AssetCopyDto(assetCopyDto).Execute()

Copy asset



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
	assetCopyDto := *openapiclient.NewAssetCopyDto("SourceId_example", "TargetId_example") // AssetCopyDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.CopyAsset(context.Background()).AssetCopyDto(assetCopyDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.CopyAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCopyAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetCopyDto** | [**AssetCopyDto**](AssetCopyDto.md) |  | 

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


## DeleteAssetMetadata

> DeleteAssetMetadata(ctx, id, key).Execute()

Delete asset metadata by key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Asset ID
	key := "key_example" // string | Metadata key

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.DeleteAssetMetadata(context.Background(), id, key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.DeleteAssetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Asset ID | 
**key** | **string** | Metadata key | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAssetMetadataRequest struct via the builder pattern


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


## DeleteAssets

> DeleteAssets(ctx).AssetBulkDeleteDto(assetBulkDeleteDto).Execute()

Delete assets



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
	assetBulkDeleteDto := *openapiclient.NewAssetBulkDeleteDto([]string{"Ids_example"}) // AssetBulkDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.DeleteAssets(context.Background()).AssetBulkDeleteDto(assetBulkDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.DeleteAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetBulkDeleteDto** | [**AssetBulkDeleteDto**](AssetBulkDeleteDto.md) |  | 

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


## DeleteBulkAssetMetadata

> DeleteBulkAssetMetadata(ctx).AssetMetadataBulkDeleteDto(assetMetadataBulkDeleteDto).Execute()

Delete asset metadata



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
	assetMetadataBulkDeleteDto := *openapiclient.NewAssetMetadataBulkDeleteDto([]openapiclient.AssetMetadataBulkDeleteItemDto{*openapiclient.NewAssetMetadataBulkDeleteItemDto("AssetId_example", "Key_example")}) // AssetMetadataBulkDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.DeleteBulkAssetMetadata(context.Background()).AssetMetadataBulkDeleteDto(assetMetadataBulkDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.DeleteBulkAssetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBulkAssetMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetMetadataBulkDeleteDto** | [**AssetMetadataBulkDeleteDto**](AssetMetadataBulkDeleteDto.md) |  | 

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


## DownloadAsset

> *os.File DownloadAsset(ctx, id).Edited(edited).Key(key).Slug(slug).Execute()

Download original asset



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
	edited := true // bool | Return edited asset if available (optional) (default to false)
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.DownloadAsset(context.Background(), id).Edited(edited).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.DownloadAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadAsset`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.DownloadAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **edited** | **bool** | Return edited asset if available | [default to false]
 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditAsset

> AssetEditsResponseDto EditAsset(ctx, id).AssetEditsCreateDto(assetEditsCreateDto).Execute()

Apply edits to an existing asset



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
	assetEditsCreateDto := *openapiclient.NewAssetEditsCreateDto([]openapiclient.AssetEditActionItemDto{*openapiclient.NewAssetEditActionItemDto(openapiclient.AssetEditAction("crop"), *openapiclient.NewAssetEditActionItemDtoParameters(float32(123), float32(123), float32(123), float32(123), float32(123), openapiclient.MirrorAxis("horizontal")))}) // AssetEditsCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.EditAsset(context.Background(), id).AssetEditsCreateDto(assetEditsCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.EditAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditAsset`: AssetEditsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.EditAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetEditsCreateDto** | [**AssetEditsCreateDto**](AssetEditsCreateDto.md) |  | 

### Return type

[**AssetEditsResponseDto**](AssetEditsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetEdits

> AssetEditsResponseDto GetAssetEdits(ctx, id).Execute()

Retrieve edits for an existing asset



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
	resp, r, err := apiClient.AssetsAPI.GetAssetEdits(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetEdits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetEdits`: AssetEditsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetEdits`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetEditsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AssetEditsResponseDto**](AssetEditsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetInfo

> AssetResponseDto GetAssetInfo(ctx, id).Key(key).Slug(slug).Execute()

Retrieve an asset



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
	resp, r, err := apiClient.AssetsAPI.GetAssetInfo(context.Background(), id).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetInfo`: AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[**AssetResponseDto**](AssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetMetadata

> []AssetMetadataResponseDto GetAssetMetadata(ctx, id).Execute()

Get asset metadata



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
	resp, r, err := apiClient.AssetsAPI.GetAssetMetadata(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetMetadata`: []AssetMetadataResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetMetadata`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AssetMetadataResponseDto**](AssetMetadataResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetMetadataByKey

> AssetMetadataResponseDto GetAssetMetadataByKey(ctx, id, key).Execute()

Retrieve asset metadata by key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Asset ID
	key := "key_example" // string | Metadata key

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.GetAssetMetadataByKey(context.Background(), id, key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetMetadataByKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetMetadataByKey`: AssetMetadataResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetMetadataByKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Asset ID | 
**key** | **string** | Metadata key | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetMetadataByKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AssetMetadataResponseDto**](AssetMetadataResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetOcr

> []AssetOcrResponseDto GetAssetOcr(ctx, id).Execute()

Retrieve asset OCR data



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
	resp, r, err := apiClient.AssetsAPI.GetAssetOcr(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetOcr``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetOcr`: []AssetOcrResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetOcr`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetOcrRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AssetOcrResponseDto**](AssetOcrResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetStatistics

> AssetStatsResponseDto GetAssetStatistics(ctx).IsFavorite(isFavorite).IsTrashed(isTrashed).Visibility(visibility).Execute()

Get asset statistics



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
	isFavorite := true // bool | Filter by favorite status (optional)
	isTrashed := true // bool | Filter by trash status (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.GetAssetStatistics(context.Background()).IsFavorite(isFavorite).IsTrashed(isTrashed).Visibility(visibility).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.GetAssetStatistics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetStatistics`: AssetStatsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.GetAssetStatistics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetStatisticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **isFavorite** | **bool** | Filter by favorite status | 
 **isTrashed** | **bool** | Filter by trash status | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 

### Return type

[**AssetStatsResponseDto**](AssetStatsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlayAssetVideo

> *os.File PlayAssetVideo(ctx, id).Key(key).Slug(slug).Execute()

Play asset video



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
	resp, r, err := apiClient.AssetsAPI.PlayAssetVideo(context.Background(), id).Key(key).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.PlayAssetVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlayAssetVideo`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.PlayAssetVideo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPlayAssetVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **key** | **string** |  | 
 **slug** | **string** |  | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveAssetEdits

> RemoveAssetEdits(ctx, id).Execute()

Remove edits from an existing asset



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
	r, err := apiClient.AssetsAPI.RemoveAssetEdits(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.RemoveAssetEdits``: %v\n", err)
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

Other parameters are passed through a pointer to a apiRemoveAssetEditsRequest struct via the builder pattern


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


## RunAssetJobs

> RunAssetJobs(ctx).AssetJobsDto(assetJobsDto).Execute()

Run an asset job



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
	assetJobsDto := *openapiclient.NewAssetJobsDto([]string{"AssetIds_example"}, openapiclient.AssetJobName("refresh-faces")) // AssetJobsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.RunAssetJobs(context.Background()).AssetJobsDto(assetJobsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.RunAssetJobs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRunAssetJobsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetJobsDto** | [**AssetJobsDto**](AssetJobsDto.md) |  | 

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


## UpdateAsset

> AssetResponseDto UpdateAsset(ctx, id).UpdateAssetDto(updateAssetDto).Execute()

Update an asset



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
	updateAssetDto := *openapiclient.NewUpdateAssetDto() // UpdateAssetDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.UpdateAsset(context.Background(), id).UpdateAssetDto(updateAssetDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.UpdateAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAsset`: AssetResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.UpdateAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAssetDto** | [**UpdateAssetDto**](UpdateAssetDto.md) |  | 

### Return type

[**AssetResponseDto**](AssetResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAssetMetadata

> []AssetMetadataResponseDto UpdateAssetMetadata(ctx, id).AssetMetadataUpsertDto(assetMetadataUpsertDto).Execute()

Update asset metadata



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
	assetMetadataUpsertDto := *openapiclient.NewAssetMetadataUpsertDto([]openapiclient.AssetMetadataUpsertItemDto{*openapiclient.NewAssetMetadataUpsertItemDto("Key_example", map[string]interface{}{"key": interface{}(123)})}) // AssetMetadataUpsertDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.UpdateAssetMetadata(context.Background(), id).AssetMetadataUpsertDto(assetMetadataUpsertDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.UpdateAssetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAssetMetadata`: []AssetMetadataResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.UpdateAssetMetadata`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAssetMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetMetadataUpsertDto** | [**AssetMetadataUpsertDto**](AssetMetadataUpsertDto.md) |  | 

### Return type

[**[]AssetMetadataResponseDto**](AssetMetadataResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAssets

> UpdateAssets(ctx).AssetBulkUpdateDto(assetBulkUpdateDto).Execute()

Update assets



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
	assetBulkUpdateDto := *openapiclient.NewAssetBulkUpdateDto([]string{"Ids_example"}) // AssetBulkUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AssetsAPI.UpdateAssets(context.Background()).AssetBulkUpdateDto(assetBulkUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.UpdateAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetBulkUpdateDto** | [**AssetBulkUpdateDto**](AssetBulkUpdateDto.md) |  | 

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


## UpdateBulkAssetMetadata

> []AssetMetadataBulkResponseDto UpdateBulkAssetMetadata(ctx).AssetMetadataBulkUpsertDto(assetMetadataBulkUpsertDto).Execute()

Upsert asset metadata



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
	assetMetadataBulkUpsertDto := *openapiclient.NewAssetMetadataBulkUpsertDto([]openapiclient.AssetMetadataBulkUpsertItemDto{*openapiclient.NewAssetMetadataBulkUpsertItemDto("AssetId_example", "Key_example", map[string]interface{}{"key": interface{}(123)})}) // AssetMetadataBulkUpsertDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.UpdateBulkAssetMetadata(context.Background()).AssetMetadataBulkUpsertDto(assetMetadataBulkUpsertDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.UpdateBulkAssetMetadata``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateBulkAssetMetadata`: []AssetMetadataBulkResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.UpdateBulkAssetMetadata`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateBulkAssetMetadataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetMetadataBulkUpsertDto** | [**AssetMetadataBulkUpsertDto**](AssetMetadataBulkUpsertDto.md) |  | 

### Return type

[**[]AssetMetadataBulkResponseDto**](AssetMetadataBulkResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadAsset

> AssetMediaResponseDto UploadAsset(ctx).AssetData(assetData).FileCreatedAt(fileCreatedAt).FileModifiedAt(fileModifiedAt).Key(key).Slug(slug).XImmichChecksum(xImmichChecksum).Duration(duration).Filename(filename).IsFavorite(isFavorite).LivePhotoVideoId(livePhotoVideoId).Metadata(metadata).SidecarData(sidecarData).Visibility(visibility).Execute()

Upload asset



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
	assetData := os.NewFile(1234, "some_file") // *os.File | Asset file data
	fileCreatedAt := time.Now() // time.Time | File creation date
	fileModifiedAt := time.Now() // time.Time | File modification date
	key := "key_example" // string |  (optional)
	slug := "slug_example" // string |  (optional)
	xImmichChecksum := "xImmichChecksum_example" // string | sha1 checksum that can be used for duplicate detection before the file is uploaded (optional)
	duration := "duration_example" // string | Duration (for videos) (optional)
	filename := "filename_example" // string | Filename (optional)
	isFavorite := true // bool | Mark as favorite (optional)
	livePhotoVideoId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Live photo video ID (optional)
	metadata := []openapiclient.AssetMetadataUpsertItemDto{*openapiclient.NewAssetMetadataUpsertItemDto("Key_example", map[string]interface{}{"key": interface{}(123)})} // []AssetMetadataUpsertItemDto | Asset metadata items (optional)
	sidecarData := os.NewFile(1234, "some_file") // *os.File | Sidecar file data (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.UploadAsset(context.Background()).AssetData(assetData).FileCreatedAt(fileCreatedAt).FileModifiedAt(fileModifiedAt).Key(key).Slug(slug).XImmichChecksum(xImmichChecksum).Duration(duration).Filename(filename).IsFavorite(isFavorite).LivePhotoVideoId(livePhotoVideoId).Metadata(metadata).SidecarData(sidecarData).Visibility(visibility).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.UploadAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadAsset`: AssetMediaResponseDto
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.UploadAsset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetData** | ***os.File** | Asset file data | 
 **fileCreatedAt** | **time.Time** | File creation date | 
 **fileModifiedAt** | **time.Time** | File modification date | 
 **key** | **string** |  | 
 **slug** | **string** |  | 
 **xImmichChecksum** | **string** | sha1 checksum that can be used for duplicate detection before the file is uploaded | 
 **duration** | **string** | Duration (for videos) | 
 **filename** | **string** | Filename | 
 **isFavorite** | **bool** | Mark as favorite | 
 **livePhotoVideoId** | **string** | Live photo video ID | 
 **metadata** | [**[]AssetMetadataUpsertItemDto**](AssetMetadataUpsertItemDto.md) | Asset metadata items | 
 **sidecarData** | ***os.File** | Sidecar file data | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 

### Return type

[**AssetMediaResponseDto**](AssetMediaResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ViewAsset

> *os.File ViewAsset(ctx, id).Edited(edited).Key(key).Size(size).Slug(slug).Execute()

View asset thumbnail



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
	edited := true // bool | Return edited asset if available (optional) (default to false)
	key := "key_example" // string |  (optional)
	size := openapiclient.AssetMediaSize("original") // AssetMediaSize |  (optional)
	slug := "slug_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsAPI.ViewAsset(context.Background(), id).Edited(edited).Key(key).Size(size).Slug(slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsAPI.ViewAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViewAsset`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AssetsAPI.ViewAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiViewAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **edited** | **bool** | Return edited asset if available | [default to false]
 **key** | **string** |  | 
 **size** | [**AssetMediaSize**](AssetMediaSize.md) |  | 
 **slug** | **string** |  | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

