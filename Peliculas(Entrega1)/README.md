Trabajo Práctico 1 / Programación Web

Realizado por **Matias Muller**

# Dominio de la aplicación

El dominio elegido es una **Lista de peliculas favoritas**
Cada pelicula cuenta con los siguientes atributos:

-   `id` → identificador único
-   `title` → título de la tarea
-   `description` → descripción de la tarea
-   `completed` → estado de la tarea (pendiente o completada)

# Estructura

    Peliculas/
     ├── index.html           # Esqueleto de la pagina
     ├── main.go              # Servidor principal
     └── static/
         └── estilos.css      # Estilos

# Requisitos previos

- [Go](https://go.dev/) 1.22 o superior   


# Ejecución

1) Clonar este repositorio o descargar los archivos.

2) Ejecutar el servidor en Go:

   - En consola:
     cd Peliculas(Entrega 1)
     go run main.go

3) Abrir en el navegador: [http://localhost:8080](http://localhost:8080) - Página de presentación
