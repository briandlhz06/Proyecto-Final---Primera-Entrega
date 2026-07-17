# Enlace Sur - Sistema de gestión comercial

Proyecto desarrollado para organizar el proceso comercial de Enlace Sur. El sistema permite registrar oportunidades, asignar responsables, programar seguimientos y conservar el historial de cada contacto.

## Primera entrega

La entrega incluye:

- Estudio de factibilidad técnica, operativa y económica
- Modelo Entidad Relación
- Esquema jerárquico y modular
- Primeras interfaces gráficas
- Login funcional conectado a MariaDB
- Proyecto completo desarrollado con Blazor Server

## Tecnologías utilizadas

- C#
- .NET 10
- Blazor Server
- MariaDB
- HTML y CSS

## Contenido

```text
EnlaceSur_Proyecto.7z/
  EnlaceSur/
  enlace_sur.sql
  Leeme.txt
  Capturas/
```

La presentación puede abrirse directamente desde `Abrime.html` en el main de este repo. Es autocontenida y no necesita conexión a Internet.

## Ejecución

1. Importar `enlace_sur.sql` en MariaDB.
2. Verificar que MariaDB esté disponible en `127.0.0.1:3306`.
3. Entrar en `EnlaceSur`.
4. Ejecutar:

```bash
dotnet run
```

5. Abrir en el navegador la dirección indicada por la consola.

La conexión local predeterminada utiliza la base `enlace_sur`, el usuario `root` y la contraseña `root`. Estos valores pueden cambiarse mediante las variables `ENLACE_DB_HOST`, `ENLACE_DB_PORT`, `ENLACE_DB_USER`, `ENLACE_DB_PASSWORD` y `ENLACE_DB_NAME`.

## Usuarios de demostración

- `brian / brian123`: administrador
- `lautaro / lautaro123`: generación de leads
- `flor / flor123`: redes sociales

## Funciones principales

- Inicio de sesión y permisos según el tipo de usuario
- Alta, edición, consulta y filtrado de leads
- Asignación de responsables
- Registro de seguimientos
- Agenda de contactos
- Tablero comercial
- Gestión de consultas recibidas desde la web
- Registro y seguimiento de trabajos
- Administración de usuarios

## Autor

Brian De La Hoz  
Proyecto, Diseño e Implementación de Sistemas Computacionales
