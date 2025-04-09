# Modelos 3D 📦

Este directorio contiene modelos 3D creados utilizando **Blockbench**. Los modelos están diseñados con texturas de alta calidad y optimizados para su uso en proyectos que requieran un estilo voxel.

---

## Detalles de los Modelos

- **Estilo:** Voxel con PixelArt.
- **Herramienta de creación:** Blockbench → https://www.blockbench.net/
- **Resolución base de texturas:** 32x32 píxeles (PixelArt).
- **Formato de exportación:** `.obj` 
❗PUEDE SER CAMBIADO❗ No Exportar de momento solo el guradado de modelos.

---

## 🎨 Directrices para la Creación de Modelos 3D

### 🛠 Herramienta de Modelado
- Todos los modelos deben ser creados usando **Blockbench**.
- El modelo final debe exportarse en formato **`.obj`**.

### 📐 Resolución y Estilo de Textura
- **Resolución base:** `32px x 32px`. (que en realidad es 128 x 128 píxeles)->
    esto pasa lo de 128px para meter todas las texturas de un modelo en un solo atlas.
    ejemplo:
    ![Texture Example](https://raw.githubusercontent.com/AgustinBeniteez/ProyectoDaw/refs/heads/main/Modelos%203D/vending%20machine/texture_machine.png)
    Si te das cuenta hay varias partes de la maquina en una misma textura.
    pero puedes usar mas de una sola textura para partes transparentes, cosas mas detalladas, etc...
---
- **Estilo:** PixelArt (NO REALISTA).
- Todas las texturas deben ser **dibujadas a mano** en estilo **PixelArt**.
- No se permite usar texturas realistas ni resoluciones que rompan la estética 
(ejemplo 900px , o 1920px x 1080px).

### ✏️ Detalles y Excepciones
- Para elementos pequeños como **números, letras u otros detalles**, se permite usar un área mayor en el atlas (máximo `64px x 64px`).
- Esto mejora la legibilidad sin romper el estilo visual del juego.
- **No se permite usar texturas de resoluciones excesivas** (ej. 900px).

### 🧾 Formato de Nombre de Texturas
Texture_NombreDelObjeto_NombreEspecial
#### 🔤 Ejemplos:
Texture_Consola_PantallaNumeros Texture_Puerta_Dañada Texture_Caja_Metalica

- `Texture_`: prefijo obligatorio.
- `NombreDelObjeto`: objeto principal.
- `NombreEspecial`: variante o propósito específico.

---

## 🧱 Buenas Prácticas
- Se usaran Texturas de **resolución de 128px**.
- No usar SuperResoluciones de texturas como 1920px x 1080px,etc... (no se permiten).
- Usa una **paleta de colores coherente**.
- No dejes píxeles sueltos ni colores fuera del estilo general.
- Mantén un bajo número de polígonos.
- Prioriza la simplicidad y claridad visual.

---

## Guardado de modelos 3D

### 📂 Estructura de Carpetas
- los modelos deben estar en la carpeta `Modelos 3D`.
- Creando una carpeta para cada modelo (con su nombre).
- Dentro de la carpeta del modelo, guardar:
    - El Archivo para poder hacer modificaciones `.bbmodel` [Guardado Normal del proyecto en Blockbench].
    - Todas las texturas en formato `.png`.
    - Archivo Exportado `.obj` [Exportado del proyecto en Blockbench].
    


---

## Créditos

- **Modelador 3D:** AgustinBenitez 
- **Modelador 3D:** Ferrer  
- **Modelador 3D:** Marcos Jimenes  


**INFO:** Todos los modelos y texturas han sido creados exclusivamente para este proyecto.

