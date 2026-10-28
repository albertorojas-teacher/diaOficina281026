# 🍬 Día de Oficina — Proyecto 02: Dulcería "SugarByte"

¡Bienvenido/a al equipo! Nuestro cliente de hoy es una tienda de golosinas artesanales y snacks importados que necesita tener lista su página web de presentación antes de su inauguración este fin de semana.

---

## 📋 Ticket #01: Maquetación Web (HTML + CSS)

Diseña una landing page colorida y atractiva que incluya como mínimo:

1. **Header:** Nombre de la tienda (*"SugarByte"*) y barra de navegación (`Inicio`, `Gomitas`, `Chocolates`, `Packs Regalo`).
2. **Hero Section:** Eslogan principal (*"Tu dosis diaria de azúcar"*), subtítulo descriptivo y botón de llamada a la acción (*"Armar mi caja de dulces"*).
3. **Sección de Más Vendidos:** Mínimo **4 tarjetas de productos** alineadas con **Flexbox** o **CSS Grid**. Cada tarjeta debe mostrar:
   * Nombre del dulce
   * Categoría y peso en gramos
   * Precio
   * Una etiqueta visual o *badge* (ej. *"Ácido"*, *"Vegano"*, *"Importado"*)
4. **Footer:** Dirección del local, horarios de atención, redes sociales y copyright.

---

## 🌿 Ticket #02: Flujo de Trabajo en Git (Obligatorio)

Queda **estrictamente prohibido** programar directamente sobre la rama principal. Tu repositorio remoto en GitHub/GitLab debe reflejar al menos **3 ramas**:

* **`main`**: Rama de producción (código final verificado).
* **`development`**: Rama de integración y pruebas.
* **`feature/escaparate-dulces`** (o `feature/estilos-pastel`): Rama de trabajo donde programarás la maquetación.

---

## 🚀 Ticket #03: Despliegue en Producción (Vercel)

1. Fusiona los avances de tu rama `feature` en `development`.
2. Revisa que el diseño no tenga errores y realiza el merge de `development` hacia `main`.
3. Vincula tu repositorio con **Vercel** para publicar la web desde la rama **`main`**.

---

## 🗄️ Ticket Extra #04: Inventario en Base de Datos (MongoDB)

El encargado de almacén nos ha compartido el stock inicial en formato JSON. Debes:

1. Abrir **MongoDB Compass** (o tu clúster en **MongoDB Atlas**).
2. Crear una base de datos llamada `dulceria_db`.
3. Crear una colección llamada `golosinas`.
4. Guardar el siguiente bloque como `inventario_dulces.json` e importarlo en la colección:

    [
      {
        "sku": "DUL-001",
        "nombre": "Ositos de Goma Hiperácidos",
        "categoria": "Gomitas",
        "peso_gramos": 250,
        "precio": 4.50,
        "es_vegano": true,
        "sin_gluten": true,
        "stock": 45
      },
      {
        "sku": "DUL-002",
        "nombre": "Tableta Chocolate Ruby con Pistacho",
        "categoria": "Chocolates",
        "peso_gramos": 150,
        "precio": 6.90,
        "es_vegano": false,
        "sin_gluten": true,
        "stock": 20
      },
      {
        "sku": "DUL-003",
        "nombre": "Caja Sorpresa Snacks Japoneses",
        "categoria": "Importados",
        "peso_gramos": 500,
        "precio": 18.00,
        "es_vegano": false,
        "sin_gluten": false,
        "stock": 12
      },
      {
        "sku": "DUL-004",
        "nombre": "Nubes de Algodón Sabor Frambuesa",
        "categoria": "Espumas",
        "peso_gramos": 200,
        "precio": 3.80,
        "es_vegano": false,
        "sin_gluten": true,
        "stock": 30
      },
      {
        "sku": "DUL-005",
        "nombre": "Regaliz Negro Artesanal",
        "categoria": "Clásicos",
        "peso_gramos": 180,
        "precio": 3.20,
        "es_vegano": true,
        "sin_gluten": false,
        "stock": 25
      },
      {
        "sku": "DUL-006",
        "nombre": "Mix Caramelo Picante Mexicano",
        "categoria": "Importados",
        "peso_gramos": 300,
        "precio": 7.50,
        "es_vegano": true,
        "sin_gluten": true,
        "stock": 15
      }
    ]

---

## ✅ Checklist para la Entrega Final (Sprint Review)

Al finalizar la sesión, ten listas en tu pantalla estas 3 vistas para mostrar al Tech Lead:
- [ ] Pestaña del repositorio en GitHub/GitLab mostrando las 3 ramas creadas.
- [ ] Pestaña con la URL pública de **Vercel** funcionando.
- [ ] Ventana de **MongoDB** mostrando los 6 productos dentro de `dulceria_db.golosinas`.