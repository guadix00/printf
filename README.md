# Proyecto ft_printf

## Introducción

El proyecto ft_printf consiste en la implementación de una versión simplificada de la función `printf` de la biblioteca estándar de C. La función `printf` en C se utiliza para formatear y imprimir texto en la consola o en otros dispositivos de salida. Permite controlar la impresión de diferentes tipos de datos, como caracteres, cadenas de caracteres, números enteros y punteros, entre otros, utilizando especificadores de formato.

## Guía para el Proyecto

Para comprender mejor cómo abordar este proyecto, se recomienda revisar las siguientes guías:

- [Guía sobre la función printf en C](https://www.it.uc3m.es/pbasanta/asng/course_notes/input_output_printf_es.html)
- [Guía ft_printf en C](https://42-cursus.gitbook.io/guide/rank-01/ft_printf)

## Archivos Creados

El proyecto `ft_printf` incluye los siguientes archivos:

- **ft_printf.c**: Contiene la implementación principal de la función `ft_printf`, que maneja la impresión con formato.
- **ft_printf.h**: Archivo de cabecera que declara los prototipos de funciones y define estructuras de datos necesarias para `ft_printf`.
- **identifier_cs.c**: Implementación de identificadores de formato para caracteres y cadenas de caracteres (`%c`, `%s`).
- **identifier_x.c**: Implementación de identificadores de formato para números hexadecimales (`%x`, `%X`, `%p`).
- **identifier_num.c**: Implementación de identificadores de formato para números enteros (`%d`, `%i`, `%u`,).

## Explicación de Archivos

- El archivo **ft_printf.c** contiene la lógica principal de la función `ft_printf`, coordinando el manejo de argumentos variables y llamando a las funciones específicas de identificación de formato según sea necesario.
- Los archivos **identifier_cs.c**, **identifier_x.c** y **identifier_num.c** separan la implementación de la lógica que maneja cada tipo de identificador de formato (`%c`, `%s`, `%x`, `%d`, `%i`, `%u`). Esta separación ayuda a modularizar el código y facilita su mantenimiento.

Este proyecto permite familiarizarse con conceptos avanzados de manejo de cadenas, argumentos variables y manipulación de formatos en el contexto de C.
