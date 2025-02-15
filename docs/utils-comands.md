
## **Comandos Básicos**
| Comando                     | Descripción                                                 |
|-----------------------------|-------------------------------------------------------------|
| `dotnet new list`        | Lista las plantillas disponibles para crear proyectos      |
| `dotnet new sln -n MiSolucion` | Crea una nueva solución de proyectos                      |
| `dotnet new console -n MiApp` | Crea un nuevo proyecto de consola                           |
| `dotnet new webapi -n MiApi`  | Crea una nueva API RESTful                                 |
| `dotnet build`               | Compila el proyecto actual                                 |
| `dotnet run`                 | Ejecuta el proyecto actual                                 |
| `dotnet clean`               | Limpia los archivos de compilación                         |
| `dotnet restore`             | Restaura las dependencias del proyecto                     |
| `dotnet test`                | Ejecuta las pruebas del proyecto                           |
| `dotnet publish -c Release`  | Publica el proyecto listo para producción                  |
| `dotnet --version`           | Muestra la versión de .NET instalada                       |

---

## **Creación de Proyectos**
| Comando                           | Descripción                                              |
|-----------------------------------|----------------------------------------------------------|
| `dotnet new mvc -n MiWebApp`      | Crea un proyecto web con MVC                             |
| `dotnet new classlib -n MiLib`    | Crea una nueva biblioteca de clases                      |
| `dotnet new blazorserver -n BlazorApp` | Crea una app Blazor Server                             |
| `dotnet new worker -n MiWorker`   | Crea un servicio de trabajo en segundo plano             |
| `dotnet new xunit -n MiTests`     | Crea un proyecto de pruebas con xUnit                    |

---

## **Administración de Paquetes (NuGet)**
| Comando                                   | Descripción                                            |
|-------------------------------------------|--------------------------------------------------------|
| `dotnet add package <paquete>`            | Agrega un paquete NuGet al proyecto actual             |
| `dotnet remove package <paquete>`         | Elimina un paquete NuGet del proyecto actual           |
| `dotnet list package`                     | Lista los paquetes instalados en el proyecto actual    |
| `dotnet restore`                          | Restaura todos los paquetes necesarios                 |

---

## **Migración y Mantenimiento**
| Comando                                   | Descripción                                            |
|-------------------------------------------|--------------------------------------------------------|
| `dotnet ef migrations add <Nombre>`       | Agrega una nueva migración (Entity Framework Core)     |
| `dotnet ef database update`               | Aplica migraciones a la base de datos                 |
| `dotnet ef database drop`                 | Elimina la base de datos actual                       |

---

## **Publicación y Despliegue**
| Comando                                              | Descripción                                          |
|------------------------------------------------------|------------------------------------------------------|
| `dotnet publish -c Release -o ./publicado`           | Publica la aplicación para producción                |
| `dotnet publish -r linux-x64`                        | Publica para una arquitectura específica             |
| `dotnet publish -r win10-x64 --self-contained`       | Publica una app independiente (no necesita .NET)    |

---

## **Información del Sistema**
| Comando                     | Descripción                                                 |
|-----------------------------|-------------------------------------------------------------|
| `dotnet --info`             | Muestra información detallada del entorno de .NET           |
| `dotnet list <proyecto> reference` | Lista las referencias del proyecto                 |
