# ⚙ BF Productos y Servicios — Sitio Web

Sitio web oficial del taller metalúrgico BF Productos y Servicios.  
Desarrollado para publicar en **GitHub Pages** — sin costos, sin servidor, sin mantenimiento técnico.

---

## 📁 Estructura de archivos

```
bf-index.html     ← Página principal (inicio, novedades, contacto, mapa)
bf-productos.html ← Galería de trabajos (Carrocerías, Estructuras, Equipamiento, Otros)
bf-admin.html     ← Panel de administración (protegido con contraseña)
README.md         ← Este archivo
```

---

## 🚀 Cómo publicar en GitHub Pages

1. Crear cuenta en [github.com](https://github.com) (gratis)
2. Crear un repositorio nuevo llamado `bf-web` (o el nombre que prefieras)
3. Subir los 3 archivos `.html` al repositorio
4. Ir a **Settings → Pages → Source → Deploy from branch → main**
5. La página queda disponible en: `https://TU-USUARIO.github.io/bf-web/bf-index.html`

> Para que `bf-index.html` sea la página de inicio por defecto, renombrarlo a `index.html` antes de subir.

---

## 🔐 Panel de administración

**Cómo acceder:**
- Directo: abrir `bf-admin.html` en el navegador
- Oculto: desde cualquier página, hacer **triple clic** en la esquina inferior derecha del footer

**Contraseña por defecto:** `bf2026`  
⚠️ **Importante:** Cambiar la contraseña en la primera sesión desde la pestaña *Configuración* del panel admin.

**Desde el panel podés:**
- ✍️ Publicar, ver y eliminar novedades (con título, fecha, texto e imagen)
- 🖼️ Subir, renombrar y borrar fotos en cada categoría de la galería
- 🔒 Cambiar la contraseña de acceso

---

## 📌 Datos a actualizar

Antes de publicar, revisar en `bf-index.html`:

| Campo | Ubicación | Valor actual |
|---|---|---|
| Email | Sección contacto | `bfproductosyservicios@gmail.com` |
| WhatsApp | Links en toda la página | `https://w.app/zwassv` |
| Google Maps embed | Sección contacto | URL del iframe |
| Link Google Maps | Debajo del mapa | `https://share.google/cF3YX1ZZ8mhxVCasz` |
| Dirección física | Tarjeta ubicación | Completar dirección exacta |

---

## 💡 Uso diario

**Para publicar una novedad:**
1. Ir a `bf-admin.html` → ingresar contraseña
2. Pestaña "Novedades" → completar título, fecha, texto y foto opcional
3. Hacer clic en "Publicar novedad"
4. Aparece automáticamente en la página principal

**Para agregar fotos a la galería:**
1. Ir a `bf-admin.html` → ingresar contraseña
2. Pestaña "Galería" → elegir categoría
3. Hacer clic en el tile "Agregar foto"
4. Las fotos quedan guardadas y visibles para todos

---

## 🛠️ Tecnologías

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks, sin dependencias)
- Google Fonts (Oswald + Open Sans)
- Almacenamiento persistente vía `window.storage` (Claude.ai)
- Compatible con todos los navegadores modernos

---

*Sitio desarrollado con Claude — Anthropic*
