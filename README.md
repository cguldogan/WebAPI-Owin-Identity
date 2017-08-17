# WebAPI-Owin-Identity
Token Based Authentication using ASP.NET Web API 2, Owin, and Identity

This project is created according to this following post 
(http://bitoftech.net/2014/06/01/token-based-authentication-asp-net-web-api-2-owin-asp-net-identity/)

You need to change connection string parameter in web config file according to your environment settings.

```xml
<connectionStrings>
    <add name="AuthContext" connectionString="Data Source=.\SQLEXPRESS;Initial Catalog=APIAuth;Integrated Security=SSPI;"   providerName="System.Data.SqlClient" />
</connectionStrings>
```
