# ipdm-oto-2025--Carlos_Rivarola-_ejercicios-1-2
# Ejercicios 1 y 2 - Jetpack Compose Básico

Este repositorio incluye dos ejercicios introductorios a Jetpack Compose para Android. Ambos se desarrollaron como parte de la práctica para familiarizarse con los elementos básicos de interfaz de usuario (UI).

---

## 📌 Ejercicio 1: App de Saludo Personalizado

En esta app se creó una interfaz que muestra un mensaje de saludo, utilizando elementos de texto e imagen que admiten composición con `@Composable`.

### ✅ Características:

- Imagen de fondo con opacidad ajustada.
- Texto personalizado con tamaño grande y centrado.
- Texto secundario alineado a la derecha.
- Uso de `Column`, `Text`, `Image` y modificadores como `padding`, `alignment`, `fontSize`.

### 📷 Captura de pantalla:

![image](https://github.com/user-attachments/assets/53afd84e-eade-44c0-9eb5-ed45cdc5871c)


---

## 📌 Ejercicio 2: Artículo de Compose

Se desarrolló una pantalla de artículo informativo sobre Jetpack Compose, con imagen de encabezado y texto justificado.

### ✅ Características:

- Imagen encabezado que ocupa el ancho completo (`ContentScale.Crop`).
- Título con `fontSize = 24sp` y padding de 16dp.
- Párrafos con alineación justificada (`TextAlign.Justify`) y padding lateral.
- Uso de `stringResource()` para internacionalización de texto.

### 🖼️ Captura de pantalla:

![image](https://github.com/user-attachments/assets/ca7b2340-4aad-4dc3-8339-85fddf6bbc98)


---

## 🧾 Recursos utilizados

### 📷 Imágenes:
- `image002.png` (para el saludo)
- `c8c16974d0aef074.png` (para el artículo)

### 🧵 Strings (`res/values/strings.xml`):

```xml
<string name="hola_carlos_text">HOLA CARLOS</string>
<string name="por_carlos_text">Por Carlos</string>

<string name="title">Jetpack Compose tutorial</string>
<string name="paragraph1">Jetpack Compose is a modern toolkit for building native Android UI...</string>
<string name="paragraph2">In this tutorial, you build a simple UI component with declarative functions...</string>
