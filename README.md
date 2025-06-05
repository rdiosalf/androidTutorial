# Aprendiendo Desarrollo Android con Kotlin

Este repositorio sigue un [tutorial de YouTube](https://www.youtube.com/watch?v=vJapzH_46a8&ab_channel=Programaci%C3%B3nbyAristiDevs) del canal **Programación by AristiDevs** para aprender a crear aplicaciones Android utilizando **Kotlin**.

## Estructura del Proyecto

### 📁 `exercises`
- Primeros ejercicios y contacto con la sintaxis de Kotlin.

### 📁 `firstApp`
- Aplicación de tipo **Hola Mundo**.
- Incluye un `EditText` para introducir un nombre.
- Utiliza `Intent` para navegar a otra vista y mostrar un saludo personalizado.

### 📁 `imccalculator`
- Aplicación para calcular el **Índice de Masa Corporal (IMC)**.

### 📁 `todoapp`
- Aplicación para generar tareas, organizadas por categorías.

### 📁 `menu`
- `Activity` genérica que actúa como **menú principal**.
- Permite acceder a las diferentes aplicaciones de ejemplo: `firstApp`, `IMC`, `todoApp`.

## Conceptos Aprendidos

- ✅ Uso de **vistas XML** clásicas: `res/layout/*.xml`.
- ✅ Uso de `res/values/strings.xml` para:
  - Soporte multi-idioma.
  - Evitar hardcoding mediante refactorización de cadenas.
- ✅ Uso de `res/values/themes.xml` para:
  - Definir atributos comunes y evitar duplicaciones.
- ✅ Uso de `res/values/colors.xml` para gestionar paleta de colores.
- ✅ Uso de `res/drawable/` para imágenes, íconos, y recursos no incluidos por defecto en Android.
- ✅ Navegación entre vistas (intent), paso de datos de una vista a otra (putExtra)
- ✅ Uso de diálogos, RecyclerView (adapter holder) y renderización  
- ✅ Archivo `AndroidManifest.xml`:
  - Registra las distintas `Activity` utilizadas en la aplicación.
