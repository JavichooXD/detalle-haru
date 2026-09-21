# 🌻 Galaxia Dorada · Detalle Especial para Haru

Una experiencia inmersiva interactiva en 3D construida con Three.js, Canvas y Web Audio API, diseñada especialmente para **Haru** con motivo de las flores amarillas y la amistad eterna.

---

## ✨ Características Especiales

- **Constelación 3D "HARU"**: Conectada por rayos de luz dorada que titilan suavemente en la bóveda celestial e interactúan al hacer clic.
- **Pétalos y Cometas 3D**: Pétalos de girasol y flores amarillas flotando suavemente en el espacio junto a estrellas fugaces periódicas.
- **Tarjeta Glassmorphism 3D con Pestañas**:
  - 💌 **Carta**: Mensaje poético personalizado con firma de Javier.
  - 🌸 **Jardín de Haru**: 4 flores simbólicas interactivas con sus significados.
  - ✨ **Tu Deseo**: Botón interactivo para liberar una estrella de deseo al centro de la galaxia con fuegos artificiales de partículas.
- **Sintetizador Web Audio API**: Campanillas celestiales y notas relajantes al interactuar con estrellas, flores y deseos, en perfecta armonía con la música de fondo.
- **Rendimiento de 60 FPS sin Lag**: Optimización profunda para GPU móvil y desktop, clamping de DPR y renderizado ligero sin fugas de memoria.
- **Música de fondo**: Reproduce `music.mp3` con control de volumen, silenciador y ondas visualizadoras en tiempo real.

---

## 🚀 Despliegue en Vercel (Paso a Paso)

Este proyecto está 100% optimizado para Vercel como sitio estático de alta velocidad con caché optimizada para audio mediante `vercel.json`.

### Opción 1: Conectar a GitHub y Vercel (Recomendada)

1. **Crear repositorio en GitHub**:
   - Ve a [github.com/new](https://github.com/new) y crea un nuevo repositorio llamado `detalle-haru`.
2. **Subir los cambios locales**:
   Abre una terminal en esta carpeta y ejecuta:
   ```bash
   git remote add origin https://github.com/TU_USUARIO/detalle-haru.git
   git add .
   git commit -m "feat: galaxia dorada especial para Haru"
   git push -u origin main
   ```
3. **Desplegar en Vercel**:
   - Entra a [vercel.com](https://vercel.com) e inicia sesión con GitHub.
   - Haz clic en **"Add New..."** > **"Project"**.
   - Selecciona el repositorio `detalle-haru` e importa con la configuración por defecto (Framework Preset: *Other*).
   - ¡Haz clic en **Deploy** y tu enlace estará listo en segundos!

### Opción 2: Usar Vercel CLI

Si tienes instalado Vercel CLI:
```bash
npx vercel
```
Y para producción:
```bash
npx vercel --prod
```

---

## 💻 Ejecución Local

Para probar localmente, puedes abrir directamente `index.html` en tu navegador favorito o iniciar un servidor local:
```bash
# Con Python
python -m http.server 3000

# O con npx serve
npx -y serve .
```
Luego abre `http://localhost:3000` en tu navegador.

---
Hecho con mucho cariño para Haru 💛🌻
