# Auditoría TI — Tijuana Centro

Aplicación web para el plan de auditorías de activo fijo TI en la plaza Tijuana Centro.

## 🚀 Despliegue en GitHub Pages

1. Crea un repositorio en GitHub (puede ser privado o público)
2. Sube el archivo `index.html` a la rama `main`
3. Ve a **Settings → Pages**
4. En *Source*, selecciona `Deploy from a branch` → `main` → `/ (root)`
5. Espera ~2 minutos y visita la URL generada (ej. `https://tuusuario.github.io/repositorio`)

## 🔑 Configurar Google Maps API (opcional pero recomendado)

Para tiempos de traslado en tiempo real con tráfico:

1. Ve a [console.cloud.google.com](https://console.cloud.google.com)
2. Crea un proyecto o selecciona uno existente
3. Habilita **Maps JavaScript API** y **Distance Matrix API**
4. Crea una clave de API y restringe al dominio de tu GitHub Pages
5. Ingresa la clave en la app al iniciar o via el botón **API**

Sin clave, la app usa tiempos estimados basados en distancia (25 km/h urbano).

## 👤 Acceso Administrador

Las credenciales de acceso al panel admin están protegidas mediante hash SHA-256.
Nunca se almacena la contraseña en texto plano en el código fuente.

## 🛠 Características

- ✅ 248 tiendas de la plaza Tijuana Centro
- ✅ 5 ingenieros con zonas geográficas optimizadas
- ✅ 10 días consecutivos (6–15 marzo 2026, incl. fines de semana)
- ✅ ~5 tiendas por ingeniero por día (carga equilibrada)
- ✅ Tiempos en tiempo real vía Google Maps Distance Matrix API
- ✅ Rutas diarias optimizadas con liga directa a Google Maps
- ✅ Panel admin con edición de nombres de ingenieros
- ✅ Diseño responsivo (móvil y escritorio)
- ✅ Credenciales admin protegidas con SHA-256

