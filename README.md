# Api-Libro
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
![1x](https://github.com/adelavargas/Api-Libro/assets/49427124/1ac5217b-d036-4e4d-8389-bb99f3b119ea)
![2x](https://github.com/adelavargas/Api-Libro/assets/49427124/f86cbc21-97be-41af-a2d5-0f0014fe6210)
![3x](https://github.com/adelavargas/Api-Libro/assets/49427124/f9821c7f-3ee5-4f9d-8f96-652c6d8d3b99)
![4x](https://github.com/adelavargas/Api-Libro/assets/49427124/b02948fd-d59e-4b5d-8ba4-38c4c68314d0)
![5x](https://github.com/adelavargas/Api-Libro/assets/49427124/20c2ee6d-41ef-4de7-a57f-5e54b87d346c)
![6x](https://github.com/adelavargas/Api-Libro/assets/49427124/fbd6efac-e612-4c34-9e93-93229a01d9c3)
