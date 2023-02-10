<img align="right" src="https://github.com/ada-school/module-template/blob/main/ada.png">

## Configurando Swagger y la documentación de Api REST

Para iniciar con la configuración de Swagger, importamos la siguiente dependencia

```
implementation 'org.springdoc:springdoc-openapi-ui:1.6.14'
implementation 'org.springdoc:springdoc-openapi-starter-webmvc-ui:2.0.2'
```

Despues de esto actualizamos la versión del siguiente plugin

```
id 'org.springframework.boot' version '2.6.2'
```

En aplication.properties, agregamos las siguientes lines

```
springdoc.swagger-ui.path=/swagger-ui.html
springdoc.api-docs.path=/api-docs
```

Hecho esto, ya podemos revisar la documentación y swagger con los siquientes links:

 * [Swagger](http://localhost:8080/swagger-ui/index.html#/).
 ```
 http://localhost:8080/swagger-ui/index.html#/
 ```
 ![image](https://user-images.githubusercontent.com/90571387/217974304-61153b50-5fb5-403a-8cb0-24b111d62870.png)

 * [Api Docs](http://localhost:8080/api-docs).
 ```
 http://localhost:8080/api-docs
 ```
 ![image](https://user-images.githubusercontent.com/90571387/217974470-95b38abd-9da5-4865-b043-3c015172af52.png)
