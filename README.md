# ITPro Storefront A (Template Demo)
**Catálogo visual + WhatsApp** (sin carrito, sin panel administrable)

## Objetivo
Este repositorio es una **plantilla base reutilizable** para entregar rápidamente un sitio tipo catálogo/tienda ligera para negocios de **ropa y accesorios** (gorras, relojes, zapatos, etc.), con un look **premium** y un flujo de venta directo por **WhatsApp**.

La idea no es desarrollar desde cero para cada cliente, sino **personalizar** (branding, contenido, productos, categorías y CTAs) sobre una base ya lista.

---

## Alcance (Qué incluye)
### Páginas / secciones (MVP)
- **Home** (hero + secciones modulares)
- **Categorías / Colecciones** (listado visual)
- **Detalle de producto** (galería, descripción, precio)
- **CTA a WhatsApp** (por producto y global)
- **Contacto** (WhatsApp + formulario simple / links)
- Footer con links, redes, info de negocio

### Flujo de venta
- El cliente **explora productos** y da clic en **“Pedir por WhatsApp”**
- El mensaje de WhatsApp puede incluir (según config):
  - Nombre del producto
  - Variante/talla/color (si aplica)
  - Precio
  - Link del producto

### Personalización por cliente (sin romper la plantilla)
- Logo, paleta de colores, tipografías
- Imágenes (hero, banners, productos)
- Textos (copy), secciones habilitadas/orden
- Categorías/colecciones y productos
- Links a WhatsApp, redes sociales, ubicación, etc.

---

## Fuera de alcance (Qué NO incluye)
Para evitar “scope creep”, **no incluye**:
- ❌ Carrito
- ❌ Checkout
- ❌ Pagos en línea
- ❌ Panel administrable / CMS para que el cliente edite
- ❌ Cuentas de usuario / login
- ❌ Órdenes registradas en sistema
- ❌ Integraciones complejas (envíos automáticos, inventario real, ERP/CRM, etc.)

> Cualquier cosa fuera de alcance se considera **add-on** o **siguiente fase**.

---

## Principios de la plantilla
- **Reutilizable**: misma base para múltiples clientes.
- **Premium y neutra**: estética limpia, modular y fácil de “rebrandear”.
- **Rápida de adaptar**: cambios típicos se hacen por configuración/archivos de contenido.
- **Alcance controlado**: A = catálogo + WhatsApp. Nada más.

---

## Estado del proyecto
- **Estatus:** WIP (en construcción)
- **Meta MVP:** demo funcional navegable con data mock y CTA WhatsApp.

---

## Cómo usar este repo
### Como plantilla
1. Marcar este repo como **Template Repository** en GitHub.
2. Crear un nuevo repo desde esta plantilla para un cliente o demo.
3. Personalizar branding + contenido + productos.

### Ejecución local / Deploy
> **TBD** (definiremos stack, scripts y proceso de deployment cuando arranquemos la implementación).

---

## Definición de “MVP listo”
Se considera listo cuando:
- El sitio es navegable (Home → Categorías → Producto).
- Todos los CTAs a WhatsApp funcionan.
- Hay data mock suficiente para demo (mín. 10–20 productos).
- Responsive correcto (mobile-first).
- Textos y placeholders coherentes (sin “lorem ipsum” en demo final).

---

## Roadmap (alto nivel)
- [ ] Estructura base del sitio (layout + navegación)
- [ ] Home modular (secciones configurables)
- [ ] Catálogo + filtros básicos (si aplica)
- [ ] Página de producto + CTA WhatsApp
- [ ] Config de branding (theme) y contenido
- [ ] Deploy demo (link público) — TBD
