# Lenguajes de Marcas y Sistemas de Gestión de Información - Tema 5

## 🧩 Tablas y Formularios en HTML

Este tema aborda dos elementos esenciales del lenguaje HTML: **tablas** y **formularios**, que permiten estructurar información y recoger datos del usuario respectivamente.

---

## 1️⃣ Introducción
En este tema aprenderás a:
- Crear tablas en HTML para organizar información en filas y columnas.
- Usar formularios para interactuar con el usuario.
- Aplicar atributos y etiquetas específicas para controlar su comportamiento.

---

## 2️⃣ Tablas en HTML

### Estructura básica:
```html
<table>
  <caption>Título de la tabla</caption>
  <thead>
    <tr><th>Cabecera</th></tr>
  </thead>
  <tbody>
    <tr><td>Contenido</td></tr>
  </tbody>
  <tfoot>
    <tr><td>Pie</td></tr>
  </tfoot>
</table>
```

### Elementos importantes:
- `<thead>`, `<tbody>`, `<tfoot>` → agrupan filas.
- `<tr>` → define una fila.
- `<th>` → define una celda de cabecera.
- `<td>` → define una celda de datos.

### Otras etiquetas:
- `<col>` y `<colgroup>` → agrupan columnas para aplicar estilos específicos.

### Atributos clave:
- `colspan` → une celdas horizontalmente.  
- `rowspan` → une celdas verticalmente.

📎 Recurso: [Ejemplos en W3Schools](https://www.w3schools.com/tags/tag_col.asp)

---

## 3️⃣ Formularios en HTML

### Estructura básica:
```html
<form action="proceso.php" method="post">
  <!-- Controles del formulario -->
</form>
```

### Atributos principales:
- `action` → destino de los datos.
- `method` → tipo de envío (`get` o `post`).

#### Métodos:
- **GET:** los datos aparecen en la URL (no seguros).
- **POST:** los datos viajan ocultos (uso recomendado).

📎 Recurso: [Audio sobre lenguajes cliente/servidor](https://bit.ly/3enxKm9)

---

## 4️⃣ Atributos comunes en controles

| Atributo | Descripción |
|-----------|--------------|
| `type` | Tipo de control (text, password, submit...) |
| `name` | Identificador único |
| `value` | Valor inicial |
| `required` | Campo obligatorio |
| `size`, `maxlength`, `minlength` | Tamaños y límites |
| `autofocus` | Control con foco inicial |
| `disabled`, `readonly` | Desactivar o solo lectura |
| `tabindex` | Orden de tabulación |

---

## 5️⃣ Controles del formulario

### 🔘 Botones
| Tipo | Etiqueta | Función | Atributo |
|------|------------|----------|-----------|
| Botón general | `<input>` | Ejecuta scripts | `type="button"` |
| Envío | `<input>` | Envía datos | `type="submit"` |
| Borrado | `<input>` | Limpia el formulario | `type="reset"` |

📎 Recurso: [Vídeo uso de botones](https://bit.ly/3fE4Kqt)

---

### 📝 Cajas de texto
| Tipo | Etiqueta | Descripción |
|------|-----------|-------------|
| Texto | `<input type="text">` | Entrada alfanumérica |
| Contraseña | `<input type="password">` | Entrada oculta |
| Área de texto | `<textarea>` | Texto multilínea |

---

### ☑️ Casillas de verificación
```html
<input type="checkbox" name="opcion1" checked>
```
Permiten seleccionar varias opciones.  
Atributos: `checked`, `value`.

---

### 🔘 Botones de radio
```html
<input type="radio" name="grupo" value="1" checked>
```
Seleccionan **una única opción** entre varias.  
Atributos: `name`, `value`, `checked`.

---

### 📜 Listas desplegables
```html
<select name="cursos" size="1">
  <option value="html" selected>HTML</option>
  <option value="css">CSS</option>
</select>
```
Atributos: `size`, `value`, `selected`.

📎 Recurso: [Vídeo uso de listas desplegables](https://bit.ly/2USfPMx)

---


## 6️⃣ Resumen
- Las **tablas** organizan la información mediante filas y columnas.
- Los **formularios** permiten enviar datos al servidor (por `get` o `post`).
- Se han visto los **controles más comunes**: botones, cajas, checkboxes, radio, select.
- Se incluye el uso de **agrupaciones** con `fieldset` y `legend`.

---

## 🔗 Webgrafía
- [W3Schools - HTML](https://www.w3schools.com/)
- [MDN Web Docs](https://developer.mozilla.org/es/docs/Web)
- [W3C](https://www.w3.org/)
- [HTML Living Standard](https://html.spec.whatwg.org/)


