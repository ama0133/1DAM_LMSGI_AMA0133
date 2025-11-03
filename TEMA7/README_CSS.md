# 🎨 Tema 7: Hojas de Estilo (CSS)
**Lenguajes de marcas y sistemas de gestión de información**

---

## 1. Introducción y contextualización práctica

Las **hojas de estilo (CSS)** permiten definir la apariencia y el diseño visual de un documento HTML.  
Separan el contenido de la presentación, facilitando el mantenimiento y la reutilización del código.

**Objetivos del tema:**
- Conocer las características de CSS.  
- Aprender su sintaxis.  
- Diferenciar los tipos de selectores.  
- Comprender el concepto de herencia.  

---

## 2. Introducción a CSS

**CSS (Cascading Style Sheets)** es el lenguaje que controla la apariencia visual de los documentos HTML.  
Permite mantener separado el contenido de su diseño, logrando compatibilidad entre distintos dispositivos.

### 🔹 Historia de CSS
Ha evolucionado a lo largo del tiempo en versiones (CSS1, CSS2.1, CSS3) mejorando la compatibilidad y las propiedades.

### 🔹 CSS y los navegadores
Los navegadores pueden interpretar CSS de forma diferente.  
Chrome, Firefox, Safari y Opera son los más compatibles con CSS3.

---

## 3. Características de CSS

Antes se usaban atributos dentro de las etiquetas HTML (`<font>`, `color`, etc.), pero esta práctica está obsoleta.  
CSS permite mantener un diseño centralizado en hojas externas.

### 3.1. Formas de incluir CSS en HTML

1. **En línea:** dentro del elemento HTML.  
2. **Interno:** dentro de `<style>` en el `<head>`.  
3. **Externo:** en un archivo `.css` enlazado con `<link>`.

```html
<link rel="stylesheet" type="text/css" href="estilos.css">
```

### 3.2. Sintaxis de CSS

```css
selector {
  propiedad: valor;
}
```

Ejemplo:
```css
p {
  color: blue;
  font-size: 16px;
}
```

### 3.3. Comentarios

```css
/* Esto es un comentario en CSS */
```

---

## 4. Selectores

Los **selectores** indican qué elementos HTML serán afectados por las reglas CSS.

| Tipo de selector | Descripción | Ejemplo |
|------------------|--------------|----------|
| Universal | Aplica a todos los elementos | `* { color: blue; }` |
| Etiqueta | Aplica a todas las etiquetas de un tipo | `p { text-align:center; }` |
| Clase | Se usa con `class` y punto (`.`) | `.miclase { border: 1px solid red; }` |
| Identificador | Se usa con `id` y almohadilla (`#`) | `#miid { background-color: cyan; }` |
| Descendiente | Elementos dentro de otros | `ul li { color: gray; }` |
| Agrupación | Mismo estilo para varios selectores | `h1, h2 { border: 3px solid green; }` |
| Hijo directo | Solo hijos inmediatos | `p > a { color: yellow; }` |
| Adyacente | Elemento hermano siguiente | `p + div { border: 2px solid blue; }` |
| Atributo | Basado en un atributo | `p[lang="es"] { background:red; }` |

---

## 5. Herencia y Colisiones

Los estilos **se heredan** de los elementos padre a los hijos.  
El **estilo más específico o más reciente** prevalece sobre los demás.

Ejemplo:
```css
div { color: blue; }
p { color: red; } /* Este se aplica porque es más específico */
```

---

## 6. Unidades de medida

### 🔸 Absolutas
| Unidad | Descripción | Equivalencia |
|--------|--------------|---------------|
| in | Pulgadas | 1in = 2.54 cm |
| cm | Centímetros | 1 cm = 10 mm |
| mm | Milímetros | — |
| px | Píxeles | 1px = 1/96 in |
| pt | Puntos | 1pt = 1/72 in |
| pc | Picas | 1pc = 12pt |

### 🔸 Relativas
| Unidad | Descripción |
|--------|--------------|
| em | Tamaño relativo al contenedor padre |
| rem | Tamaño relativo a la fuente raíz |
| % | Relativo al elemento padre |
| vw | 1% del ancho de la ventana |
| vh | 1% del alto de la ventana |

Ejemplo:
```css
div { font-size: 12px; }
p { font-size: 1.5em; } /* 1.5 veces el tamaño del div */
```

---

## 7. Colores

Formas de definir colores:

| Método | Ejemplo | Descripción |
|---------|----------|-------------|
| Nombre | `color: red;` | Usa nombres predefinidos (140 disponibles) |
| RGB | `color: rgb(255,0,0);` | Rojo puro |
| Hexadecimal | `color: #FF0000;` | Equivalente a rojo en RGB |

Herramientas útiles:
- 🎨 [Adobe Color](https://color.adobe.com/es/create/color-wheel)
- 🧩 [W3Schools CSS Colors](https://www.w3schools.com/cssref/css_colors.asp)

---

## 10. Resumen del tema

- CSS separa contenido y diseño.  
- Permite aplicar estilos mediante **selectores**.  
- La **herencia** y **especificidad** determinan qué reglas se aplican.  
- Las **unidades de medida** y **colores** definen el tamaño y apariencia.  
- Se practica la aplicación de CSS mediante casos prácticos.


