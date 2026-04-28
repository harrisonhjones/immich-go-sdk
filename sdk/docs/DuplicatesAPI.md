# \DuplicatesAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteDuplicate**](DuplicatesAPI.md#DeleteDuplicate) | **Delete** /duplicates/{id} | Delete a duplicate
[**DeleteDuplicates**](DuplicatesAPI.md#DeleteDuplicates) | **Delete** /duplicates | Delete duplicates
[**GetAssetDuplicates**](DuplicatesAPI.md#GetAssetDuplicates) | **Get** /duplicates | Retrieve duplicates
[**ResolveDuplicates**](DuplicatesAPI.md#ResolveDuplicates) | **Post** /duplicates/resolve | Resolve duplicate groups



## DeleteDuplicate

> DeleteDuplicate(ctx, id).Execute()

Delete a duplicate



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
	r, err := apiClient.DuplicatesAPI.DeleteDuplicate(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DuplicatesAPI.DeleteDuplicate``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteDuplicateRequest struct via the builder pattern


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


## DeleteDuplicates

> DeleteDuplicates(ctx).BulkIdsDto(bulkIdsDto).Execute()

Delete duplicates



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
	r, err := apiClient.DuplicatesAPI.DeleteDuplicates(context.Background()).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DuplicatesAPI.DeleteDuplicates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDuplicatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkIdsDto** | [**BulkIdsDto**](BulkIdsDto.md) |  | 

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


## GetAssetDuplicates

> []DuplicateResponseDto GetAssetDuplicates(ctx).Execute()

Retrieve duplicates



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
	resp, r, err := apiClient.DuplicatesAPI.GetAssetDuplicates(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DuplicatesAPI.GetAssetDuplicates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetDuplicates`: []DuplicateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DuplicatesAPI.GetAssetDuplicates`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetDuplicatesRequest struct via the builder pattern


### Return type

[**[]DuplicateResponseDto**](DuplicateResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveDuplicates

> []BulkIdResponseDto ResolveDuplicates(ctx).DuplicateResolveDto(duplicateResolveDto).Execute()

Resolve duplicate groups



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
	duplicateResolveDto := *openapiclient.NewDuplicateResolveDto([]openapiclient.DuplicateResolveGroupDto{*openapiclient.NewDuplicateResolveGroupDto("DuplicateId_example", []string{"KeepAssetIds_example"}, []string{"TrashAssetIds_example"})}) // DuplicateResolveDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DuplicatesAPI.ResolveDuplicates(context.Background()).DuplicateResolveDto(duplicateResolveDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DuplicatesAPI.ResolveDuplicates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveDuplicates`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DuplicatesAPI.ResolveDuplicates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiResolveDuplicatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **duplicateResolveDto** | [**DuplicateResolveDto**](DuplicateResolveDto.md) |  | 

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

