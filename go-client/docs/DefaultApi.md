# \DefaultApi

All URIs are relative to *https://api.pbxdom.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CallsGet**](DefaultApi.md#CallsGet) | **Get** /Calls | 
[**FeaturesChartsGet**](DefaultApi.md#FeaturesChartsGet) | **Get** /Features/charts | 
[**FeaturesReportsGet**](DefaultApi.md#FeaturesReportsGet) | **Get** /Features/reports | 
[**FeaturesWidgetGet**](DefaultApi.md#FeaturesWidgetGet) | **Get** /Features/widget | 


# **CallsGet**
> []InlineResponse200 CallsGet($rptType, $rptId, $start, $limit, $sortBy, $sortType, $fromDate, $toDate, $duration, $phone, $phone1, $co, $ext, $pbxId, $callSource, $callType, $direction, $callerName, $did, $dnis, $acc, $ring, $cost, $group)



Gets `Calls` info. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rptType** | **float64**| Report type. (0 report, 1 widget, 2 chart). | 
 **rptId** | **float64**| Report id. | 
 **start** | **float32**| Start offset. | [optional] 
 **limit** | **float32**| Number of results to return. Max 10K. | [optional] 
 **sortBy** | **string**| Sort column. | [optional] 
 **sortType** | **string**| Sort mode asc/desc. | [optional] 
 **fromDate** | **string**| Start date time. | [optional] 
 **toDate** | **string**| End date time. | [optional] 
 **duration** | **float32**| Duration range. | [optional] 
 **phone** | **string**| List of caller phone. | [optional] 
 **phone1** | **string**| List of dialled phones. | [optional] 
 **co** | **string**| List of trunk/co. | [optional] 
 **ext** | **string**| list of extensions. | [optional] 
 **pbxId** | **float32**| list of PBX Ids. | [optional] 
 **callSource** | **float32**| list of callsource. | [optional] 
 **callType** | **float32**| list of call type signatures.(5 Unanswered Calls, 7 Transfered Calls, 8 Forwarded Calls) | [optional] 
 **direction** | **float32**| list of direction.(0 incoming, 1 outgoing, 2 internal) | [optional] 
 **callerName** | **string**| list of caller name. | [optional] 
 **did** | **string**| list of did. | [optional] 
 **dnis** | **string**| list of dnis. | [optional] 
 **acc** | **string**| list of account code. | [optional] 
 **ring** | **float32**| Ring range.Seconds unit. | [optional] 
 **cost** | **float32**| Cost range. | [optional] 
 **group** | **float32**| Department/Group id. | [optional] 

### Return type

[**[]InlineResponse200**](inline_response_200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FeaturesChartsGet**
> []InlineResponse200 FeaturesChartsGet()



Gets `Charts` list. 


### Parameters
This endpoint does not need any parameter.

### Return type

[**[]InlineResponse200**](inline_response_200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FeaturesReportsGet**
> []InlineResponse200 FeaturesReportsGet()



Gets `Reports` list. 


### Parameters
This endpoint does not need any parameter.

### Return type

[**[]InlineResponse200**](inline_response_200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **FeaturesWidgetGet**
> []InlineResponse200 FeaturesWidgetGet()



Gets `Widgets` list. 


### Parameters
This endpoint does not need any parameter.

### Return type

[**[]InlineResponse200**](inline_response_200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

