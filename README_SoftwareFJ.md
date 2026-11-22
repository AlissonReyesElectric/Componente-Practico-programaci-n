# 🐾 Software FJ -- Business Manager

## Descripción del proyecto

Software FJ -- Business Manager es una aplicación de escritorio
desarrollada en Python que permite gestionar información de clientes,
servicios y reservas mediante una interfaz gráfica.

Este proyecto se realiza como parte del componente práctico del curso
**Programación (213023)** de la Universidad Nacional Abierta y a
Distancia (UNAD), con el propósito de aplicar conceptos de programación
orientada a objetos, validación de datos y manejo de excepciones.

## Objetivo

Desarrollar una aplicación que facilite la organización y administración
de clientes, servicios y reservas, incorporando validaciones que ayuden
a prevenir errores durante el uso del sistema.

## Funcionalidades

-   **Gestión de clientes:** registro y consulta de clientes.
-   **Validación de datos:** comprobación de campos requeridos y formato
    de correo electrónico.
-   **Control de registros duplicados:** prevención de clientes o
    servicios repetidos según las validaciones implementadas.
-   **Gestión de servicios:** registro y consulta de servicios, con
    información como categoría, descripción, precio y cantidad o
    capacidad.
-   **Gestión de reservas:** creación, consulta y actualización del
    estado de reservas.
-   **Validación de reservas:** revisión de datos ingresados, fechas y
    posibles conflictos de programación.
-   **Manejo de excepciones:** mensajes de alerta para informar al
    usuario sobre errores o datos inválidos.
-   **Interfaz gráfica:** navegación por los diferentes módulos mediante
    una interfaz construida con CustomTkinter.

## Tecnologías utilizadas

-   **Python 3.13**
-   **CustomTkinter** -- interfaz gráfica de escritorio.
-   **Tkinter messagebox** -- mensajes de alerta y notificación.
-   **Expresiones regulares (re)** -- validación de formatos de datos.
-   **datetime** -- manejo y validación de fechas y horas.
-   **GitHub** -- almacenamiento y control del código fuente.

## Organización del sistema

El sistema cuenta con módulos principales para:

1.  **Dashboard:** vista general de la aplicación.
2.  **Clientes:** registro y consulta de información.
3.  **Servicios:** administración del catálogo de servicios.
4.  **Reservas:** creación y seguimiento de reservas.
5.  **Historial:** visualización de eventos realizados durante la
    ejecución.

## Manejo de excepciones y validaciones

La aplicación incorpora controles para manejar situaciones como campos
vacíos, datos con formatos incorrectos, registros duplicados y
conflictos en las reservas. También utiliza una excepción personalizada
denominada `DatosInvalidosError` para representar situaciones de datos o
acciones no válidas.

Estas validaciones permiten mostrar mensajes comprensibles al usuario y
evitar interrupciones inesperadas durante el funcionamiento del
programa.

## Almacenamiento de información

Los datos se almacenan temporalmente en listas internas de Python. Por
esta razón, la información registrada se mantiene mientras la aplicación
está en ejecución; al cerrar el programa, los datos no se conservan. El
proyecto no utiliza una base de datos.

## Requisitos

-   Python 3.13 instalado.
-   La biblioteca CustomTkinter.

Instalación de CustomTkinter desde la terminal:

``` bash
pip install customtkinter
```

## Ejecución

1.  Descargue o clone este repositorio.
2.  Abra el archivo Python del proyecto en Visual Studio Code u otro
    editor compatible.
3.  Verifique que Python y CustomTkinter estén instalados.
4.  Ejecute el archivo principal desde la terminal:

``` bash
python problemasfase4_3.py
```

> Si el archivo tiene un nombre diferente en su equipo, utilice el
> nombre real del archivo Python al ejecutar el comando.

## Autor

**Alisson Charloth Reyes Ballesteros**\
Universidad Nacional Abierta y a Distancia -- UNAD\
Curso: Programación (213023)

## Repositorio

Código fuente del componente práctico:

https://github.com/AlissonReyesElectric/Componente-Practico-programaci-n

------------------------------------------------------------------------

*Proyecto académico desarrollado para aplicar conceptos de programación
orientada a objetos, validación de datos y manejo de excepciones en
Python.*
