# Lenguajes de Marcas y Sistemas de Gestión de Información - Tema 4

## 🧩 Identificación de Etiquetas y Atributos en HTML

Este tema aborda las etiquetas y atributos fundamentales del lenguaje HTML, que permiten estructurar y presentar contenido en la web de manera efectiva.

---

## 1️⃣ Introducción
En este tema aprenderás a:
- Conocer las principales etiquetas utilizadas en el cuerpo de un documento HTML.
- Trabajar con enlaces para crear relaciones entre documentos.
- Crear listas para organizar información de manera jerárquica.
- Incluir contenido incrustado como imágenes y documentos HTML.

---

## 2️⃣ Etiquetas de Texto

### Estructura básica:
```html
<p>Este es un párrafo de texto.</p>
<strong>Texto importante</strong>
<em>Texto en cursiva</em>
<a href="https://example.com">Este es un enlace</a>
```

### Elementos importantes:
- `<br>` → Salto de línea.
- `<span>` → Texto sin significado semántico.
- `<strong>` → Texto importante (se muestra en negrita).
- `<em>` → Énfasis (se muestra en cursiva).

### Otras etiquetas:
- `<sub>` y `<sup>` → Subíndice y superíndice, respectivamente.
- `<mark>` → Resalta texto.

📎 Recurso: [Ejemplos en W3Schools](https://www.w3schools.com/tags/default.asp)

---

## 3️⃣ Enlaces en HTML

### Estructura básica:
```html
<a href="https://www.ejemplo.com" target="_blank">Visitar Ejemplo</a>
```

### Atributos clave:
- `href` → Define el destino del enlace.
- `target` → Especifica cómo abrir el enlace (`_blank`, `_self`, etc.).

---

## 4️⃣ Listas en HTML

### Tipos de listas:
- **Ordenadas** (`<ol>`)
- **No ordenadas** (`<ul>`)
- **De definición** (`<dl>`)

### Estructura básica:
```html
<ul>
  <li>Elemento de lista 1</li>
  <li>Elemento de lista 2</li>
</ul>
```

### Elementos importantes:
- `<li>` → Define un elemento dentro de la lista.

---

## 5️⃣ Contenido Incrustado

### Imágenes:
```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

### Documentos HTML incrustados:
```html
<iframe src="https://www.ejemplo.com" width="600" height="400"></iframe>
```

### Atributos clave:
- `src` → Ruta del recurso externo.
- `alt` → Texto alternativo para imágenes.

📎 Recurso: [Uso de iframe](https://www.w3schools.com/html/html_iframe.asp)

---

## 6️⃣ Casos Prácticos

### 🧠 Caso práctico 1: “Plantilla de trabajadores”
Crear una plantilla HTML que incluya:
- Formato de texto con etiquetas como `<strong>` y `<em>`.
- Listas para organizar información.
- Un enlace a la página de la empresa que se abra en una nueva pestaña.
- Una imagen representativa.

---

### 🧩 Caso práctico 2: “Última versión plantilla trabajadores”
Incluir en la plantilla:
- Un enlace en la imagen que abra la web de la empresa en la misma pestaña.
- Un menú con enlaces a secciones como "Datos personales" y "Estudios".
- Un iframe que muestre la ubicación de la empresa.

---

## 7️⃣ Resumen
- Se han estudiado las **etiquetas de texto** más comunes y su uso.
- Se ha aprendido a crear **enlaces** y **listas** en HTML.
- Se ha explorado cómo incluir **contenido incrustado** como imágenes y documentos.
- Se han propuesto **casos prácticos** para aplicar lo aprendido.

---

## 🔗 Webgrafía
- [W3Schools - HTML](https://www.w3schools.com/)
- [MDN Web Docs](https://developer.mozilla.org/es/docs/Web)
- [W3C](https://www.w3.org/)
- [HTML Living Standard](https://html.spec.whatwg.org/)
