# Proyecto Java Back-End - Talento Tech

_Autor: Jorge Coll_

---

## Descripción

Este proyecto es una aplicación de gestión de pedidos y artículos desarrollada en Java de Talento Tech. Permite crear, consultar, modificar y eliminar pedidos y artículos, utilizando buenas prácticas de programación orientada a objetos.

---

## Estructura de Carpetas

- **src/**: Código fuente del proyecto (paquetes `pedido` y `articulo`)
- **lib/**: Dependencias externas (si las hubiera)
- **bin/**: Archivos compilados generados automáticamente

---

## Funcionalidades Principales

- **Gestión de Artículos**
  - Crear, consultar, listar y modificar artículos
- **Gestión de Pedidos**
  - Crear, consultar, actualizar y eliminar pedidos
  - Asociar artículos a pedidos

---

## Tecnologías Utilizadas

- Java 8+
- Colecciones (`ArrayList`)
- Programación orientada a objetos (POO)
- Interfaz de consola (`Scanner`)

---

## Ejecución

1. Clona el repositorio o descarga el código fuente.
2. Abre el proyecto en Visual Studio Code o tu IDE favorito.
3. Compila el proyecto:
   ```sh
   javac -d bin -cp src src/App.java