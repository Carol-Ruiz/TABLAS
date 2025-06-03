
# TABLAS

- En este proyecto realizaado se presentara una serie de 10 tablas realizadas en HTML usando diferentes metodos, con un estilo realizado mediante un archivo CSS.
---

## `tablas.html` — Explicación línea por línea

## Estructura General

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tablas</title>
  <link rel="stylesheet" href="./_css/style.css">
</head>
```
- Define el tipo de documento como HTML5.
- El documento está escrito en español.
- Se especifica la codificación UTF-8 y se adapta a dispositivos móviles.
- Se enlaza la hoja de estilos `style.css`.

## Cuerpo del documento `<body>`

```html
<body>
  <header>
    <h1>Tablas en HTML</h1>
  </header>
```
- Título principal con estilo personalizado.

## Formulario de navegación

```html
<div class="navigation-form">
    <form action="" method="get">
        <label for="section">Ir a la tabla:</label>
        <select id="section" name="section" onchange="location = this.value;">
            <option value="">Seleccione la tabla</option>
            <option value="#tabla1">Tabla 1</option>
            ...
        </select>
    </form>
</div>
```
- Menú desplegable que permite saltar a las diferentes secciones del documento.

## Secciones de tablas

```html
<main>
  <section id="tabla1">
    <h2>Tabla 1</h2>
    <table>
      ...
    </table>
  </section>
</main>
```
- Se crean 10 secciones (`tabla1` a `tabla10`) con distintos tipos de tablas para mostrar información relacionada con artistas y discos.

## Pie de página

```html
<footer>&copy 2025</footer>
```
- Pie de página con año.

---

## Explicación  `style.css`

## Estilo general

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  margin: 0;
  padding: 0;
}
```
- Fuente y fondo base para el sitio web.

### Cabecera

```css
header {
  background-color: #d45dec;
  color: #141313;
  padding: 15px;
  text-align: center;
}
```
- Cabecera centrada con fondo púrpura.

### Navegación

```css
.navigation-form form {
  display: inline-block;
  background-color: #d5b7db;
  padding: 15px;
  border-radius: 5px;
}
```
- Formulario de navegación estilizado con bordes redondeados.

### Tablas generales

```css
table {
  width: 80%;
  margin: 20px 0;
  border-collapse: collapse;
}
th, td {
  padding: 10px;
  text-align: left;
  border: 1px solid #181616;
}
th {
  background-color: #85a7da;
}
```
- Estructura base de todas las tablas.

---

## 🎨 Estilos por Tabla

- **#tabla1**: Hover amarillo.
- **#tabla2**: Encabezado rosado, borde punteado y subrayado al pasar el mouse.
- **#tabla3**: Fondo celeste y hover turquesa.
- **#tabla4**: Filas alternas y hover morado.
- **#tabla5**: Columna derecha alineada, hover verde.
- **#tabla6**: Tablas anidadas con decoraciones y hover con subrayado.
- **#tabla7**: Borde azul, hover fucsia.
- **#tabla8**: Borde punteado morado, hover rojo.
- **#tabla9**: Hover gris y subrayado, fondo rosado.
- **#tabla10**: Bordes gruesos y hover verde esmeralda.

### Pie de página

```css
footer {
  background-color: #d45dec;
  color: #0f0e0e;
  padding: 15px;
  text-align: center;
}
```
- Estilo visual para el pie de página.

---

