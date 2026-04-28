# \TagsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkTagAssets**](TagsAPI.md#BulkTagAssets) | **Put** /tags/assets | Tag assets
[**CreateTag**](TagsAPI.md#CreateTag) | **Post** /tags | Create a tag
[**DeleteTag**](TagsAPI.md#DeleteTag) | **Delete** /tags/{id} | Delete a tag
[**GetAllTags**](TagsAPI.md#GetAllTags) | **Get** /tags | Retrieve tags
[**GetTagById**](TagsAPI.md#GetTagById) | **Get** /tags/{id} | Retrieve a tag
[**TagAssets**](TagsAPI.md#TagAssets) | **Put** /tags/{id}/assets | Tag assets
[**UntagAssets**](TagsAPI.md#UntagAssets) | **Delete** /tags/{id}/assets | Untag assets
[**UpdateTag**](TagsAPI.md#UpdateTag) | **Put** /tags/{id} | Update a tag
[**UpsertTags**](TagsAPI.md#UpsertTags) | **Put** /tags | Upsert tags



## BulkTagAssets

> TagBulkAssetsResponseDto BulkTagAssets(ctx).TagBulkAssetsDto(tagBulkAssetsDto).Execute()

Tag assets



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
	tagBulkAssetsDto := *openapiclient.NewTagBulkAssetsDto([]string{"AssetIds_example"}, []string{"TagIds_example"}) // TagBulkAssetsDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TagsAPI.BulkTagAssets(context.Background()).TagBulkAssetsDto(tagBulkAssetsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.BulkTagAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkTagAssets`: TagBulkAssetsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.BulkTagAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkTagAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tagBulkAssetsDto** | [**TagBulkAssetsDto**](TagBulkAssetsDto.md) |  | 

### Return type

[**TagBulkAssetsResponseDto**](TagBulkAssetsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTag

> TagResponseDto CreateTag(ctx).TagCreateDto(tagCreateDto).Execute()

Create a tag



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
	tagCreateDto := *openapiclient.NewTagCreateDto("Name_example") // TagCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TagsAPI.CreateTag(context.Background()).TagCreateDto(tagCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.CreateTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTag`: TagResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.CreateTag`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tagCreateDto** | [**TagCreateDto**](TagCreateDto.md) |  | 

### Return type

[**TagResponseDto**](TagResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteTag

> DeleteTag(ctx, id).Execute()

Delete a tag



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
	r, err := apiClient.TagsAPI.DeleteTag(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.DeleteTag``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteTagRequest struct via the builder pattern


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


## GetAllTags

> []TagResponseDto GetAllTags(ctx).Execute()

Retrieve tags



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
	resp, r, err := apiClient.TagsAPI.GetAllTags(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.GetAllTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllTags`: []TagResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.GetAllTags`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAllTagsRequest struct via the builder pattern


### Return type

[**[]TagResponseDto**](TagResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTagById

> TagResponseDto GetTagById(ctx, id).Execute()

Retrieve a tag



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
	resp, r, err := apiClient.TagsAPI.GetTagById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.GetTagById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTagById`: TagResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.GetTagById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTagByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TagResponseDto**](TagResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TagAssets

> []BulkIdResponseDto TagAssets(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Tag assets



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
	resp, r, err := apiClient.TagsAPI.TagAssets(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.TagAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TagAssets`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.TagAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTagAssetsRequest struct via the builder pattern


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


## UntagAssets

> []BulkIdResponseDto UntagAssets(ctx, id).BulkIdsDto(bulkIdsDto).Execute()

Untag assets



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
	resp, r, err := apiClient.TagsAPI.UntagAssets(context.Background(), id).BulkIdsDto(bulkIdsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.UntagAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UntagAssets`: []BulkIdResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.UntagAssets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUntagAssetsRequest struct via the builder pattern


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


## UpdateTag

> TagResponseDto UpdateTag(ctx, id).TagUpdateDto(tagUpdateDto).Execute()

Update a tag



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
	tagUpdateDto := *openapiclient.NewTagUpdateDto() // TagUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TagsAPI.UpdateTag(context.Background(), id).TagUpdateDto(tagUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.UpdateTag``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTag`: TagResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.UpdateTag`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTagRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **tagUpdateDto** | [**TagUpdateDto**](TagUpdateDto.md) |  | 

### Return type

[**TagResponseDto**](TagResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertTags

> []TagResponseDto UpsertTags(ctx).TagUpsertDto(tagUpsertDto).Execute()

Upsert tags



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
	tagUpsertDto := *openapiclient.NewTagUpsertDto([]string{"Tags_example"}) // TagUpsertDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TagsAPI.UpsertTags(context.Background()).TagUpsertDto(tagUpsertDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TagsAPI.UpsertTags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertTags`: []TagResponseDto
	fmt.Fprintf(os.Stdout, "Response from `TagsAPI.UpsertTags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpsertTagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tagUpsertDto** | [**TagUpsertDto**](TagUpsertDto.md) |  | 

### Return type

[**[]TagResponseDto**](TagResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

