# \MemoriesAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddMemoryAssets**](MemoriesAPI.md#AddMemoryAssets) | **Put** /memories/{id}/assets | Add assets to a memory
[**CreateMemory**](MemoriesAPI.md#CreateMemory) | **Post** /memories | Create a memory
[**DeleteMemory**](MemoriesAPI.md#DeleteMemory) | **Delete** /memories/{id} | Delete a memory
[**GetMemory**](MemoriesAPI.md#GetMemory) | **Get** /memories/{id} | Retrieve a memory
[**MemoriesStatistics**](MemoriesAPI.md#MemoriesStatistics) | **Get** /memories/statistics | Retrieve memories statistics
[**RemoveMemoryAssets**](MemoriesAPI.md#RemoveMemoryAssets) | **Delete** /memories/{id}/assets | Remove assets from a memory
[**SearchMemories**](MemoriesAPI.md#SearchMemories) | **Get** /memories | Retrieve memories
[**UpdateMemory**](MemoriesAPI.md#UpdateMemory) | **Put** /memories/{id} | Update a memory



## AddMemoryAssets

> []BulkIdResponseDto AddMemoryAssets(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Add assets to a memory



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
	bulkIdsDto := *openapiclient.NewBulkIdsDto([]string{"Ids_example"}) // BulkIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.AddMemoryAssets(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.AddMemoryAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddMemoryAssets`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.AddMemoryAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddMemoryAssetsRequest struct via the builder pattern


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


## CreateMemory

> MemoryResponseDto CreateMemory(ctx).MemoryCreateDto(memoryCreateDto).Execute()

Create a memory



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	memoryCreateDto := *openapiclient.NewMemoryCreateDto(*openapiclient.NewOnThisDayDto(int32(123)), time.Now(), openapiclient.MemoryType("on_this_day")) // MemoryCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.CreateMemory(context.Background()).MemoryCreateDto(memoryCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.CreateMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMemory`: MemoryResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.CreateMemory`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMemoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **memoryCreateDto** | [**MemoryCreateDto**](MemoryCreateDto.md) |  | 

### Return type

[**MemoryResponseDto**](MemoryResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMemory

> DeleteMemory(ctx, id).Execute()

Delete a memory



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
	r, err := apiClient.MemoriesAPI.DeleteMemory(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.DeleteMemory``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteMemoryRequest struct via the builder pattern


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


## GetMemory

> MemoryResponseDto GetMemory(ctx, id).Execute()

Retrieve a memory



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
	resp, r, err := apiClient.MemoriesAPI.GetMemory(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.GetMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMemory`: MemoryResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.GetMemory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMemoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MemoryResponseDto**](MemoryResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MemoriesStatistics

> MemoryStatisticsResponseDto MemoriesStatistics(ctx).For_(for_).IsSaved(isSaved).IsTrashed(isTrashed).Order(order).Size(size).Type_(type_).Execute()

Retrieve memories statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	for_ := time.Now() // time.Time | Filter by date (optional)
	isSaved := true // bool | Filter by saved status (optional)
	isTrashed := true // bool | Include trashed memories (optional)
	order := openapiclient.MemorySearchOrder("asc") // MemorySearchOrder |  (optional)
	size := int32(56) // int32 | Number of memories to return (optional)
	type_ := openapiclient.MemoryType("on_this_day") // MemoryType |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.MemoriesStatistics(context.Background()).For_(for_).IsSaved(isSaved).IsTrashed(isTrashed).Order(order).Size(size).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.MemoriesStatistics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MemoriesStatistics`: MemoryStatisticsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.MemoriesStatistics`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMemoriesStatisticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **for_** | **time.Time** | Filter by date | 
 **isSaved** | **bool** | Filter by saved status | 
 **isTrashed** | **bool** | Include trashed memories | 
 **order** | [**MemorySearchOrder**](MemorySearchOrder.md) |  | 
 **size** | **int32** | Number of memories to return | 
 **type_** | [**MemoryType**](MemoryType.md) |  | 

### Return type

[**MemoryStatisticsResponseDto**](MemoryStatisticsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveMemoryAssets

> []BulkIdResponseDto RemoveMemoryAssets(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Remove assets from a memory



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
	bulkIdsDto := *openapiclient.NewBulkIdsDto([]string{"Ids_example"}) // BulkIdsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.RemoveMemoryAssets(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.RemoveMemoryAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveMemoryAssets`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.RemoveMemoryAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveMemoryAssetsRequest struct via the builder pattern


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


## SearchMemories

> []MemoryResponseDto SearchMemories(ctx).For_(for_).IsSaved(isSaved).IsTrashed(isTrashed).Order(order).Size(size).Type_(type_).Execute()

Retrieve memories



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	for_ := time.Now() // time.Time | Filter by date (optional)
	isSaved := true // bool | Filter by saved status (optional)
	isTrashed := true // bool | Include trashed memories (optional)
	order := openapiclient.MemorySearchOrder("asc") // MemorySearchOrder |  (optional)
	size := int32(56) // int32 | Number of memories to return (optional)
	type_ := openapiclient.MemoryType("on_this_day") // MemoryType |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.SearchMemories(context.Background()).For_(for_).IsSaved(isSaved).IsTrashed(isTrashed).Order(order).Size(size).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.SearchMemories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchMemories`: []MemoryResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.SearchMemories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchMemoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **for_** | **time.Time** | Filter by date | 
 **isSaved** | **bool** | Filter by saved status | 
 **isTrashed** | **bool** | Include trashed memories | 
 **order** | [**MemorySearchOrder**](MemorySearchOrder.md) |  | 
 **size** | **int32** | Number of memories to return | 
 **type_** | [**MemoryType**](MemoryType.md) |  | 

### Return type

[**[]MemoryResponseDto**](MemoryResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMemory

> MemoryResponseDto UpdateMemory(ctx, id).MemoryUpdateDto(memoryUpdateDto).Execute()

Update a memory



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
	memoryUpdateDto := *openapiclient.NewMemoryUpdateDto() // MemoryUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.UpdateMemory(context.Background(), id).MemoryUpdateDto(memoryUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.UpdateMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMemory`: MemoryResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.UpdateMemory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMemoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **memoryUpdateDto** | [**MemoryUpdateDto**](MemoryUpdateDto.md) |  | 

### Return type

[**MemoryResponseDto**](MemoryResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

