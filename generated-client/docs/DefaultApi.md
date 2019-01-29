# DefaultApi

All URIs are relative to *http://petstore.swagger.io/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**petsGet**](DefaultApi.md#petsGet) | **GET** /pets | 

<a name="petsGet"></a>
# **petsGet**
> List&lt;Pet&gt; petsGet()



Returns all pets from the system that the user has access to

### Example
```java
// Import classes:
//import com.bricerising.swaggercodgen.example.java.ApiException;
//import com.bricerising.swaggercodgen.example.java.api.DefaultApi;


DefaultApi apiInstance = new DefaultApi();
try {
    List<Pet> result = apiInstance.petsGet();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling DefaultApi#petsGet");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List&lt;Pet&gt;**](Pet.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

