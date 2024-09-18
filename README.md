# ft_printf Project (English)

## Introduction

The ft_printf project consists of implementing a simplified version of the `printf` function from the C standard library. 
The `printf` function in C is used to format and print text to the console or other output devices. It allows for control over the printing of different data types, such as characters, strings, integers, and pointers, using format specifiers.

## Project Guide

To better understand how to approach this project, it is recommended to review the following guides:

- [Guide on the printf function in C](https://www.it.uc3m.es/pbasanta/asng/course_notes/input_output_printf_es.html)
- [ft_printf Guide in C](https://42-cursus.gitbook.io/guide/rank-01/ft_printf)

## Created Files

The `ft_printf` project includes the following files:

- **ft_printf.c**: Contains the main implementation of the `ft_printf` function, which handles formatted output.
- **ft_printf.h**: Header file that declares the function prototypes and defines data structures necessary for `ft_printf`.
- **identifier_cs.c**: Implementation of format specifiers for characters and strings (`%c`, `%s`).
- **identifier_x.c**: Implementation of format specifiers for hexadecimal numbers (`%x`, `%X`, `%p`).
- **identifier_num.c**: Implementation of format specifiers for integers (`%d`, `%i`, `%u`).

## File Explanation

- The **ft_printf.c** file contains the main logic of the `ft_printf` function, coordinating the handling of variable arguments and calling specific format identifier functions as needed.
- The **identifier_cs.c**, **identifier_x.c**, and **identifier_num.c** files separate the logic for handling each type of format specifier (`%c`, `%s`, `%x`, `%d`, `%i`, `%u`). This separation helps modularize the code and makes it easier to maintain.

This project provides an opportunity to become familiar with advanced concepts like string handling, variable arguments, and format manipulation in the context of C.

---


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
