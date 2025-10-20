# 📘 Tema 5: Tablas y Formularios  
**Lenguajes de marcas y sistemas de gestión de información (LMSGI)**  

---

## 🧭 Introducción
En este tema se estudian **las tablas y los formularios en HTML**, dos elementos esenciales para estructurar e interactuar con la información en una página web:

- **Tablas** → Organizan contenido en filas y columnas.  
- **Formularios** → Permiten recoger datos del usuario y enviarlos a un servidor para su procesamiento.

---

## 🧩 Tablas en HTML

### 🔹 Estructura básica
```html
<table>
  <caption>Título de la tabla</caption>
  <thead>
    <tr>
      <th>Cabecera 1</th>
      <th>Cabecera 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dato 1</td>
      <td>Dato 2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Pie de tabla</td>
    </tr>
  </tfoot>
</table>
```

### 🔹 Etiquetas útiles
- `<col>` y `<colgroup>` → Agrupan columnas (útil para aplicar estilos).  
- `<thead>`, `<tbody>`, `<tfoot>` → Organizan filas por secciones.  

### 🔹 Atributos importantes
| Atributo | Función |
|-----------|----------|
| `colspan` | Une celdas horizontalmente. |
| `rowspan` | Une celdas verticalmente. |

---

## 🧠 Formularios en HTML

### 🔹 Estructura básica
```html
<form action="proceso.php" method="post">
  <!-- Controles del formulario -->
</form>
```

**Atributos principales:**
- `action` → Página o script que procesará los datos.  
- `method` → 
  - `get`: los datos se ven en la URL (no usar para información sensible).  
  - `post`: los datos se envían ocultos.  

---

## 🧱 Atributos comunes de controles
| Atributo | Descripción |
|-----------|--------------|
| `type` | Tipo de control (`text`, `password`, `submit`...). |
| `name` | Nombre identificador del control. |
| `value` | Valor por defecto. |
| `required` | Campo obligatorio. |
| `maxlength` / `minlength` | Límite de caracteres. |
| `disabled` | Desactiva el control. |
| `readonly` | Solo lectura. |
| `autofocus` | Enfoca el control al cargar. |
| `tabindex` | Orden de tabulación. |

---

## 🧰 Tipos de controles

### 🔸 Botones
```html
<input type="button" value="Hola Mundo">
<input type="submit" value="Enviar">
<input type="reset" value="Borrar">
```

### 🔸 Cajas de texto
```html
<input type="text" name="usuario" placeholder="Introduce tu nombre">
<input type="password" name="clave" placeholder="Contraseña">
<textarea name="mensaje" rows="4" cols="30"></textarea>
```

### 🔸 Casillas y botones de opción
```html
<!-- Casillas -->
<input type="checkbox" name="curso" value="HTML" checked> HTML
<input type="checkbox" name="curso" value="CSS"> CSS

<!-- Botones radio -->
<input type="radio" name="turno" value="mañana" checked> Mañana
<input type="radio" name="turno" value="tarde"> Tarde
```
