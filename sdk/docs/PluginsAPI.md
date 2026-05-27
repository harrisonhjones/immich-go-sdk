# \PluginsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPlugin**](PluginsAPI.md#GetPlugin) | **Get** /plugins/{id} | Retrieve a plugin
[**SearchPluginMethods**](PluginsAPI.md#SearchPluginMethods) | **Get** /plugins/methods | Retrieve plugin methods
[**SearchPluginTemplates**](PluginsAPI.md#SearchPluginTemplates) | **Get** /plugins/templates | Retrieve workflow templates
[**SearchPlugins**](PluginsAPI.md#SearchPlugins) | **Get** /plugins | List all plugins



## GetPlugin

> PluginResponseDto GetPlugin(ctx, id).Execute()

Retrieve a plugin



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
	resp, r, err := apiClient.PluginsAPI.GetPlugin(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.GetPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlugin`: PluginResponseDto
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.GetPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PluginResponseDto**](PluginResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPluginMethods

> []PluginMethodResponseDto SearchPluginMethods(ctx).Description(description).Enabled(enabled).Id(id).Name(name).PluginName(pluginName).PluginVersion(pluginVersion).Title(title).Trigger(trigger).Type_(type_).Execute()

Retrieve plugin methods



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
	description := "description_example" // string |  (optional)
	enabled := true // bool | Whether the plugin method is enabled (optional)
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Plugin method ID (optional)
	name := "name_example" // string |  (optional)
	pluginName := "pluginName_example" // string | Plugin name (optional)
	pluginVersion := "pluginVersion_example" // string | Plugin version (optional)
	title := "title_example" // string |  (optional)
	trigger := openapiclient.WorkflowTrigger("AssetCreate") // WorkflowTrigger | Workflow trigger (optional)
	type_ := openapiclient.WorkflowType("AssetV1") // WorkflowType | Workflow types (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.SearchPluginMethods(context.Background()).Description(description).Enabled(enabled).Id(id).Name(name).PluginName(pluginName).PluginVersion(pluginVersion).Title(title).Trigger(trigger).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.SearchPluginMethods``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPluginMethods`: []PluginMethodResponseDto
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.SearchPluginMethods`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPluginMethodsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **string** |  | 
 **enabled** | **bool** | Whether the plugin method is enabled | 
 **id** | **string** | Plugin method ID | 
 **name** | **string** |  | 
 **pluginName** | **string** | Plugin name | 
 **pluginVersion** | **string** | Plugin version | 
 **title** | **string** |  | 
 **trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) | Workflow trigger | 
 **type_** | [**WorkflowType**](WorkflowType.md) | Workflow types | 

### Return type

[**[]PluginMethodResponseDto**](PluginMethodResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPluginTemplates

> []PluginTemplateResponseDto SearchPluginTemplates(ctx).Execute()

Retrieve workflow templates



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
	resp, r, err := apiClient.PluginsAPI.SearchPluginTemplates(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.SearchPluginTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPluginTemplates`: []PluginTemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.SearchPluginTemplates`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSearchPluginTemplatesRequest struct via the builder pattern


### Return type

[**[]PluginTemplateResponseDto**](PluginTemplateResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchPlugins

> []PluginResponseDto SearchPlugins(ctx).Description(description).Enabled(enabled).Id(id).Name(name).Title(title).Version(version).Execute()

List all plugins



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
	description := "description_example" // string |  (optional)
	enabled := true // bool | Whether the plugin is enabled (optional)
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Plugin ID (optional)
	name := "name_example" // string |  (optional)
	title := "title_example" // string |  (optional)
	version := "version_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.SearchPlugins(context.Background()).Description(description).Enabled(enabled).Id(id).Name(name).Title(title).Version(version).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.SearchPlugins``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPlugins`: []PluginResponseDto
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.SearchPlugins`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPluginsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **description** | **string** |  | 
 **enabled** | **bool** | Whether the plugin is enabled | 
 **id** | **string** | Plugin ID | 
 **name** | **string** |  | 
 **title** | **string** |  | 
 **version** | **string** |  | 

### Return type

[**[]PluginResponseDto**](PluginResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

