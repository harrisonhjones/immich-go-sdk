# \TrashAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EmptyTrash**](TrashAPI.md#EmptyTrash) | **Post** /trash/empty | Empty trash
[**RestoreAssets**](TrashAPI.md#RestoreAssets) | **Post** /trash/restore/assets | Restore assets
[**RestoreTrash**](TrashAPI.md#RestoreTrash) | **Post** /trash/restore | Restore trash



## EmptyTrash

> TrashResponseDto EmptyTrash(ctx).Execute()

Empty trash



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrashAPI.EmptyTrash(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrashAPI.EmptyTrash``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmptyTrash`: TrashResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TrashAPI.EmptyTrash`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiEmptyTrashRequest struct via the builder pattern


### Return type

[**TrashResponseDto**](TrashResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreAssets

> TrashResponseDto RestoreAssets(ctx).BulkIdsDto(bulkIdsDto).Execute()

Restore assets



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
	bulkIdsDto := *openapiclient.NewBulkIdsDto([]string{"Ids_example"}) // BulkIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrashAPI.RestoreAssets(context.Background()).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrashAPI.RestoreAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreAssets`: TrashResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TrashAPI.RestoreAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRestoreAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkIdsDto** | [**BulkIdsDto**](BulkIdsDto.md) |  | 

### Return type

[**TrashResponseDto**](TrashResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreTrash

> TrashResponseDto RestoreTrash(ctx).Execute()

Restore trash



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrashAPI.RestoreTrash(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrashAPI.RestoreTrash``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreTrash`: TrashResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TrashAPI.RestoreTrash`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRestoreTrashRequest struct via the builder pattern


### Return type

[**TrashResponseDto**](TrashResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

