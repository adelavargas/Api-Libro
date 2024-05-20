
Proyecto API RESTful de Libros con Spring Boot
Este proyecto consiste en la creación de una API RESTful para gestionar libros utilizando Spring Boot. La API expone endpoints para consultar, crear y obtener información sobre libros.

Tecnologías utilizadas
Spring Boot
Java
Postman
visual sstudio code

------------Estructura del proyecto----------
com.tuuniversidad.models: Contiene la clase Libro que representa la entidad de negocio.
com.tuuniversidad.repository: Contiene la interface LibroRepository que define las operaciones de acceso a datos sobre los libros.
com.tuuniversidad.service: Contiene la clase LibroServiceImpl que implementa la lógica de negocio para la gestión de libros.
com.tuuniversidad.controllers: Contiene la clase LibroController que expone los endpoints RESTful para la API.


Método: GET
URL: http://localhost:8080/libros/1
JSON
{
  "id": 1,
  "titulo": "ien Anos de Soledad",
  "autor": "Gabriel García Márquez",
  "editorial": "Sudamericano",
  "anioPublicacion": 1967
}

![1x](https://github.com/adelavargas/Api-Libro/assets/49427124/b54084d6-8b2b-48e5-9f69-ffb0b4c8f929)
![2x](https://github.com/adelavargas/Api-Libro/assets/49427124/539a416c-e4d8-4f44-afac-5f99dbf2c1a4)
![3x](https://github.com/adelavargas/Api-Libro/assets/49427124/a2642212-8410-4731-ad97-8c8e988d821a)
![4x](https://github.com/adelavargas/Api-Libro/assets/49427124/50ccf817-3db0-4b99-ba85-6b17abf1086c)
![5x](https://github.com/adelavargas/Api-Libro/assets/49427124/322fb0aa-9a29-4072-9524-6ceefa7df736)
![6x](https://github.com/adelavargas/Api-Libro/assets/49427124/1295404b-bc86-467d-97ab-ced441e5b71d)

