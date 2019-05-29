# DefaultApi

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**post**](DefaultApi.md#post) | **POST** /* | 


<a name="post"></a>
# **post**
> post(soAPRequest, soAPAction)



### Example
```java
// Import classes:
//import org.wso2.client.api.ApiException;
//import org.wso2.client.api.complaitsWSO2Soap.DefaultApi;


DefaultApi apiInstance = new DefaultApi();
String soAPRequest = "soAPRequest_example"; // String | SOAP request.
String soAPAction = "soAPAction_example"; // String | SOAPAction header for soap 1.1
try {
    apiInstance.post(soAPRequest, soAPAction);
} catch (ApiException e) {
    System.err.println("Exception when calling DefaultApi#post");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **soAPRequest** | **String**| SOAP request. |
 **soAPAction** | **String**| SOAPAction header for soap 1.1 | [optional]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: text/xml, application/soap+xml
 - **Accept**: text/xml, application/soap+xml

