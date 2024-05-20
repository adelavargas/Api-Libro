## Pruebas de la API

A continuación se detallan las pruebas realizadas a los diferentes endpoints de la API utilizando Postman.

### 1. Obtener todos los libros

- **Método**: GET
- **URL**: `http://localhost:8080/libros`
- **Resultado**: Se recibió una lista de todos los libros existentes en la base de datos.

### 2. Obtener un libro por ID

- **Método**: GET
- **URL**: `http://localhost:8080/libros/{id_libro}`
- **ID Libro**: 1
- **Resultado**: Se recibió la información del libro con ID 1.

### 3. Crear un nuevo libro

- **Método**: POST
- **URL**: `http://localhost:8080/libros`
- **Cuerpo de la Solicitud**:
  ```json
  {
      "id": 3,
      "titulo": "Nuevo Libro",
      "autor": "Nuevo Autor",
      "editorial": "Nueva Editorial",
      "anioPublicacion": 2024
  }
![2x](https://github.com/adelavargas/Api-Libro/assets/49427124/539a416c-e4d8-4f44-afac-5f99dbf2c1a4)
![3x](https://github.com/adelavargas/Api-Libro/assets/49427124/a2642212-8410-4731-ad97-8c8e988d821a)
![4x](https://github.com/adelavargas/Api-Libro/assets/49427124/50ccf817-3db0-4b99-ba85-6b17abf1086c)
![5x](https://github.com/adelavargas/Api-Libro/assets/49427124/322fb0aa-9a29-4072-9524-6ceefa7df736)
![6x](https://github.com/adelavargas/Api-Libro/assets/49427124/1295404b-bc86-467d-97ab-ced441e5b71d)
![1x](https://github.com/adelavargas/Api-Libro/assets/49427124/b54084d6-8b2b-48e5-9f69-ffb0b4c8f929)
