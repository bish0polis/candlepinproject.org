---
title: REST API
---
# Swagger API
Candlepin exposes Swagger file as a documentation of the service. When using deployed candlepin the swagger file can be accessed at:

```
https://HOST:8443/candlepin/swagger.json

```
An interactive user interface that allows running Candlepin methods can be accessed at:

```
https://HOST:8443/candlepin/docs/
```

If you do not want to serve Swagger, you can turn it off with the following configuration property:

```
candlepin.swagger.enabled=false
```

We also host the Swagger file and the UI statically on this site: 

| Version | Swagger file | Interactive documentation |
|-
| 2.1.25 |  [swagger.json]({{ site.url }}/swagger/candlepin/swagger-2.1.25.json){:target="_blank"}  | [Swagger UI]({{ site.url }}/swagger/?url=candlepin/swagger-2.1.25.json){:target="_blank"} |
| 2.3.10 |  [swagger.json]({{ site.url }}/swagger/candlepin/swagger-2.3.10.json){:target="_blank"}  | [Swagger UI]({{ site.url }}/swagger/?url=candlepin/swagger-2.3.10.json){:target="_blank"} |
| 2.4.8 |  [swagger.json]({{ site.url }}/swagger/candlepin/swagger-2.4.8.json){:target="_blank"}  | [Swagger UI]({{ site.url }}/swagger/?url=candlepin/swagger-2.4.8.json){:target="_blank"} |
| 2.5.7 |  [swagger.json]({{ site.url }}/swagger/candlepin/swagger-2.5.7.json){:target="_blank"}  | [Swagger UI]({{ site.url }}/swagger/?url=candlepin/swagger-2.5.7.json){:target="_blank"} |
|=
