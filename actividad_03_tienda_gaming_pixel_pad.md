# 🎮 Día de Oficina — Proyecto 03: Tienda Gaming "Pixel & Pad"

¡Bienvenido/a al estudio! Nuestro cliente es una tienda especializada en videojuegos, consolas retro y periféricos para PC que necesita publicar su landing page de ofertas antes de terminar el día.

---

## 📋 Ticket #01: Maquetación Web (HTML + CSS)

Desarrolla una landing page con estética moderna (se recomienda *Dark Mode* con colores neón o de alto contraste) que incluya:

1. **Header:** Nombre de la tienda (*"Pixel & Pad"*) y menú de navegación (`Inicio`, `Consolas`, `Videojuegos`, `Periféricos`).
2. **Hero Section:** Título principal (*"Equipa tu Setup al siguiente nivel"*), texto de bienvenida y botón de acción (*"Ver ofertas de la semana"*).
3. **Sección de Productos Destacados:** Al menos **4 tarjetas de productos** organizadas con **Flexbox** o **CSS Grid**. Cada tarjeta debe mostrar:
   * Nombre del producto
   * Plataforma o Categoría
   * Estado (`Nuevo` o `Reacondicionado`)
   * Precio
4. **Footer:** Enlaces a soporte técnico, políticas de garantía y derechos reservados.

---

## 🌿 Ticket #02: Flujo de Trabajo en Git (Obligatorio)

Queda **estrictamente prohibido** programar directamente sobre la rama principal. Tu repositorio remoto en GitHub/GitLab debe contar con al menos **3 ramas**:

* **`main`**: Rama de producción conectada al servidor web.
* **`development`**: Rama de integración donde se validan los cambios.
* **`feature/catalogo-gaming`** (o `feature/dark-theme`): Rama de desarrollo para tu maquetación HTML y CSS.

---

## 🚀 Ticket #03: Despliegue en Producción (Vercel)

1. Une los cambios de tu rama `feature` dentro de `development`.
2. Verifica que la página se visualice correctamente y haz el merge de `development` hacia `main`.
3. Conecta tu repositorio con **Vercel** para desplegar automáticamente la rama **`main`**.

---

## 🗄️ Ticket Extra #04: Base de Datos de Catálogo (MongoDB)

El proveedor de hardware nos ha enviado el listado inicial de stock en formato JSON. Debes:

1. Abrir **MongoDB Compass** (o tu clúster en **MongoDB Atlas**).
2. Crear una base de datos llamada `gaming_db`.
3. Crear una colección llamada `hardware_juegos`.
4. Guardar el siguiente bloque como `catalogo_gaming.json` e importarlo en la colección:

    [
      {
        "codigo": "GM-101",
        "producto": "Teclado Mecánico 75% Switch Red",
        "categoria": "Periféricos",
        "plataforma": "PC / Mac",
        "precio": 89.99,
        "condicion": "Nuevo",
        "stock": 18,
        "envio_gratis": true
      },
      {
        "codigo": "GM-102",
        "producto": "Resident Evil 2 Remake - Edición Coleccionista",
        "categoria": "Videojuegos",
        "plataforma": "Xbox / PS5",
        "precio": 49.90,
        "condicion": "Nuevo",
        "stock": 6,
        "envio_gratis": true
      },
      {
        "codigo": "GM-103",
        "producto": "Mando Pro Inalámbrico Hall Effect",
        "categoria": "Accesorios",
        "plataforma": "Multiplataforma",
        "precio": 55.00,
        "condicion": "Nuevo",
        "stock": 24,
        "envio_gratis": true
      },
      {
        "codigo": "GM-104",
        "producto": "Consola Portátil Retro Emulación IPS",
        "categoria": "Consolas",
        "plataforma": "Retro",
        "precio": 64.50,
        "condicion": "Nuevo",
        "stock": 10,
        "envio_gratis": true
      },
      {
        "codigo": "GM-105",
        "producto": "Ratón Gaming Ultraligero 26000 DPI",
        "categoria": "Periféricos",
        "plataforma": "PC",
        "precio": 59.95,
        "condicion": "Nuevo",
        "stock": 15,
        "envio_gratis": true
      },
      {
        "codigo": "GM-106",
        "producto": "Game Boy Color Edición Transparente",
        "categoria": "Consolas",
        "plataforma": "Retro",
        "precio": 110.00,
        "condicion": "Reacondicionado",
        "stock": 2,
        "envio_gratis": true
      }
    ]

---

## ✅ Checklist para la Entrega Final (Sprint Review)

Al finalizar la sesión, ten listas en tu pantalla estas 3 vistas para mostrar al Tech Lead:
- [ ] Pestaña del repositorio en GitHub/GitLab mostrando las 3 ramas creadas.
- [ ] Pestaña con la URL pública de **Vercel** funcionando.
- [ ] Ventana de **MongoDB** mostrando los 6 artículos dentro de `gaming_db.hardware_juegos`.