# 🏢 Día de Oficina — Proyecto 01: Librería "Páginas & Bytes"

¡Bienvenido/a a tu primer día en el equipo de desarrollo! Un nuevo cliente necesita lanzar hoy mismo la presencia digital de su librería independiente antes del cierre de la jornada.

---

## 📋 Ticket #01: Maquetación Web (HTML + CSS)

Construye una landing page atractiva y semántica que incluya como mínimo:

1. **Header:** Nombre de la librería (*"Páginas & Bytes"*) y menú de navegación simple (`Inicio`, `Catálogo`, `Contacto`).
2. **Hero Section:** Un título principal llamativo, una breve descripción de la tienda y un botón de llamada a la acción (*"Ver libros destacados"*).
3. **Sección de Catálogo Destacado:** Al menos **4 tarjetas de libros** maquetadas con **Flexbox** o **CSS Grid**. Cada tarjeta debe mostrar:
   * Título del libro
   * Autor
   * Género / Categoría
   * Precio
4. **Footer:** Datos de contacto ficticios, horarios y derechos de autor.

---

## 🌿 Ticket #02: Flujo de Trabajo en Git (Obligatorio)

Queda **estrictamente prohibido** programar directamente sobre la rama principal. Tu repositorio remoto en GitHub/GitLab debe contar con al menos **3 ramas**:

* **`main`**: Rama de producción (solo recibe código terminado y probado desde `development`).
* **`development`**: Rama de integración donde se unen los avances.
* **`feature/catalogo`** (o `feature/maquetacion`): Rama donde desarrollarás tu HTML y CSS antes de integrarlo a `development`.

---

## 🚀 Ticket #03: Despliegue en Producción (Vercel)

1. Integra los cambios de tu rama `feature` hacia `development`.
2. Cuando compruebes que todo funciona correctamente, haz el merge de `development` hacia `main`.
3. Conecta tu repositorio con **Vercel** y despliega la web tomando como fuente la rama **`main`**.

---

## 🗄️ Ticket Extra #04: Carga Inicial en Base de Datos (MongoDB)

El departamento de inventario ha enviado el primer lote de libros en formato JSON. Debes:

1. Abrir **MongoDB Compass** (o tu clúster en **MongoDB Atlas**).
2. Crear una base de datos llamada `libreria_db`.
3. Crear una colección llamada `libros`.
4. Guardar el siguiente bloque como `catalogo_libros.json` e importarlo en tu colección:

    [
      {
        "isbn": "978-8499082479",
        "titulo": "El nombre del viento",
        "autor": "Patrick Rothfuss",
        "genero": "Fantasía",
        "precio": 21.90,
        "stock": 14,
        "destacado": true
      },
      {
        "isbn": "978-8445000663",
        "titulo": "El Señor de los Anillos: La Comunidad del Anillo",
        "autor": "J.R.R. Tolkien",
        "genero": "Fantasía",
        "precio": 24.50,
        "stock": 8,
        "destacado": true
      },
      {
        "isbn": "978-8466353779",
        "titulo": "Dune",
        "autor": "Frank Herbert",
        "genero": "Ciencia Ficción",
        "precio": 19.95,
        "stock": 20,
        "destacado": true
      },
      {
        "isbn": "978-8497592208",
        "titulo": "Cien años de soledad",
        "autor": "Gabriel García Márquez",
        "genero": "Realismo Mágico",
        "precio": 15.90,
        "stock": 12,
        "destacado": false
      },
      {
        "isbn": "978-8437604947",
        "titulo": "1984",
        "autor": "George Orwell",
        "genero": "Distopía",
        "precio": 12.50,
        "stock": 30,
        "destacado": true
      },
      {
        "isbn": "978-0132350884",
        "titulo": "Clean Code",
        "autor": "Robert C. Martin",
        "genero": "Tecnología",
        "precio": 38.00,
        "stock": 5,
        "destacado": false
      }
    ]

---

## ✅ Checklist para la Entrega Final (Sprint Review)

Al finalizar la sesión, ten listas en tu pantalla estas 3 vistas para mostrar al Tech Lead:
- [ ] Pestaña del repositorio en GitHub/GitLab mostrando las 3 ramas creadas.
- [ ] Pestaña con la URL pública de **Vercel** funcionando.
- [ ] Ventana de **MongoDB** mostrando los 6 libros dentro de `libreria_db.libros`.