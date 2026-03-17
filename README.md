# 🌾 Reparto INTEGRAL Puerto Sano

App mobile para planilla de reparto de mercadería. Funciona offline, se instala como app nativa en Android e iPhone.

---

## 📲 Cómo instalar en el celular

Una vez publicada en GitHub Pages, cada chofer entra a la URL y la instala:

**Android (Chrome):**
1. Abrí la URL en Chrome
2. Tocá el menú (⋮) → "Agregar a pantalla de inicio"
3. Listo — queda como app con ícono

**iPhone (Safari):**
1. Abrí la URL en Safari
2. Tocá compartir (□↑) → "Agregar a pantalla de inicio"
3. Listo — queda como app con ícono

---

## 🚀 Cómo subir a GitHub Pages (paso a paso)

### Paso 1 — Crear cuenta en GitHub
Entrá a [github.com](https://github.com) y creá una cuenta gratis si no tenés.

### Paso 2 — Crear repositorio nuevo
1. Hacé clic en **"New"** (botón verde)
2. Nombre del repositorio: `reparto-integral`
3. Marcá **"Public"**
4. Hacé clic en **"Create repository"**

### Paso 3 — Subir los archivos
1. En el repositorio vacío, hacé clic en **"uploading an existing file"**
2. Arrastrá o seleccioná todos estos archivos:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - carpeta `icons/` con `icon-192.png` e `icon-512.png`
3. Hacé clic en **"Commit changes"**

### Paso 4 — Activar GitHub Pages
1. En el repositorio, andá a **Settings** (arriba a la derecha)
2. En el menú izquierdo, hacé clic en **Pages**
3. En "Branch", seleccioná **main** → carpeta **/ (root)**
4. Hacé clic en **Save**
5. Esperá 1-2 minutos

### Paso 5 — Tu URL lista
La app va a estar en:
```
https://TU_USUARIO.github.io/reparto-integral/
```

Compartí esa URL con todos los choferes. Cada uno la instala en su celular y tiene su propio datos guardados localmente.

---

## ✅ Funciones

- Planilla de reparto diaria con Nº cliente, referencia, importe y pago
- Estados automáticos: Cobrado / Parcial / Debe / Con vuelto
- Métricas en tiempo real: pedidos, facturado, cobrado, debe, vuelto
- Autoguardado en el dispositivo (los datos no se borran al cerrar)
- Envío por WhatsApp con resumen formateado
- Exportar CSV compatible con Excel
- Funciona 100% offline
- Cada chofer tiene sus propios datos independientes

---

## 🔄 Actualizar la app

Si necesitás hacer cambios, simplemente reemplazá el `index.html` en GitHub y los celulares se actualizan solos la próxima vez que tengan internet.
