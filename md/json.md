---
hide:
  -footer
---
# JSON
## ¿Que es un JSON?
JSON es un formato que almacena información estructurada y se utiliza principalmente para transferir datos entre un servidor y un cliente.

Hay dos elementos centrales en un objeto JSON: claves (Keys) y valores (Values).


* Las Keys deben ser cadenas de caracteres (strings). Como su nombre en español lo indica, estas contienen una secuencia de caracteres rodeados de comillas.
* Los Values son un tipo de datos JSON válido. Puede tener la forma de un arreglo (array), objeto, cadena (string), booleano, número o nulo.

## Ejemplos
### Ejemplo 1
```
{
  "libro": [
    {
      "id": "01",
      "lenguaje": "Java",
      "Edición":"Tercera",
      "Autor": "Herbert Schildt"
    }
    {
      "id": "02",
      "lenguaje": "C++",
      "Edición":"Primera",
      "Autor": "E. balagurusamy"
    }
  ]
}
```
### Ejemplo 2
```
{
  "Nombre":"Pepito Pérez",
  "DNI":"12345678A",
  "Edad":22,
  "Asignaturas":{
    "Obligatorias":{
      "Sistemas operativos",
      "Compiladores",
      "Bases de datos"
    },
    "Optativas":{
      "Bades de Datos NoSQL",
      "Minería de datos",
      "Programación Lógica"
    },
    "LibreElección":{
      "Ajedrez",
      "Música Clásica"
    }
  }
}
```