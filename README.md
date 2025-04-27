# TestingReadmeProyect 🛠️
Esto es un proyecto creado con fines completamente educativos.

## Tabla de contenidos 📋
- [Demostración](#demostración)
- [Requisitos](#requisitos)
- [Características](#características)
- [Instalación](#instalación)

<br>

## Demostración 🎥

![Image](https://i.postimg.cc/kGrx3zLR/Image-Example.png)

<br>

## Requisitos ✅

- NET 9 SDK Installed
- PostgreSQL 14

<br>

## Caracteristicas ✨

- ASP.NET Core 9.0
- Entity Framework
- PostreSQL 14

<br>

## Ejecución o instalación 🚀

1. Establecer la configuración de tu cadena de conexión correctamente en `appsettings.json.`

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=TuBaseDeDatos;User Id=tu_usuario;Password=tu_contraseña;"
  }
}

```
2. Correr las migraciones, para generar la base de datos

```
dotnet ef migrations add Inicial
dotnet ef database update
```
3. Finalizadas las migraciones, correr el proyecto.

```
dotnet run
```










