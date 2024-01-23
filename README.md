# SOAP Echo Service

Echo Service.

Example request payload.
```xml
<soap:Envelope xmlns:soap="http://www.w3.org/2003/05/soap-envelope">
   <soap:Header/>
   <soap:Body>
   <echo:echoString xmlns:echo="http://echo.services.core.carbon.wso2.org">
      <in>Hello World</in>
   </echo:echoString>
   </soap:Body>
</soap:Envelope>
```
