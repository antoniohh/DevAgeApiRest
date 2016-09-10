# DevAge Api RESTful
## Versión 1.0.0.0.
## Servicio Web RESTful para app android DevAge basado en Php, MySql y Json.

### Novedades versión 1.0.0.0.

> Versión final de la Api.

> Operaciones soportadas on POST: 'signup', 'login', 'listado', 'add' y 'saludo'.

> Conexión con MySql on PDO.

### Implementaciones.

> Intercambio de información con el formato de comunicación Json para compartir recursos.

> Conexión a base de datos MySql con PDO previniendo la inyección de sentencias.

### Descripción.

La comunicación la realizamos enviando los datos en formato Json:

```
{
	"operacion":"saludo"
}
```

Recibiendo la salida también en Json:

```
{
  "resultado":{
    "estado":"Correcto",
    "mensaje":"API REST on POST Saludando."
  }
}
```

### Fundamentos.

DevAge Api es un servicio web RESTful para app android DevAge, proyecto final del
curso de perfeccionamiento de Android, impartido en la Escuela de Ingenierías
Industriales de la Universidad de Extremadura. Esta api forma parte de este
proyecto, junto con la aplicación java para móviles android DevAge. EL lenguaje
en el que se ha escrito la api es Php, la base de datos MySql y el formato de
intercambio de información, los datos de la aplicación, es Json.

El verbo utilizado en las peticiones a la API REST es POST. Mediante este verbo
identificamos las operaciones y obtenemos la salida de datos correspondiente.
Aunque el verbo GET también está implementado, no reliaza función.
Para ejecutarlo es necesario dar permisos de ejecución.

### Mas Información.

> [blog.antoniohorrillo.com] (http://blog.antoniohorrillo.com/node/16)

### Licencia.

**GNU GENERAL PUBLIC LICENSE** Version 3, 29 June 2007. Ver el archivo LICENSE.

DevAge Api RESTful.
