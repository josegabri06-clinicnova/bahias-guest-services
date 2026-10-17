# Bahías Guest Services

Sitio web corporativo independiente de hospitalidad, concierge y atención al huésped en Bahías de Huatulco, Oaxaca.

Este proyecto está **100% desacoplado** del sistema hotelero interno para servir como entidad formal, limpia y verificable ante Meta Business / WhatsApp Business API.

## Estructura de Archivos
- `index.html`: Landing page principal ejecutiva con llamadas a la acción directas hacia WhatsApp (`+52 958 122 11 11`).
- `privacidad.html`: Política de Privacidad conforme a la LFPDPPP y estándares de Meta.
- `terminos.html`: Términos y Condiciones del Servicio.
- `styles.css`: Sistema de diseño moderno, responsive y ultraligero.
- `vercel.json`: Reglas de enrutamiento limpio y cabeceras de seguridad para Vercel.

## Despliegue en Vercel
1. Puedes crear un nuevo repositorio en GitHub (ej: `bahias-guest-services`) y subir esta carpeta.
2. En Vercel: Click en **"Add New... -> Project"** y seleccionar el repositorio `bahias-guest-services`.
3. Framework Preset: **Other** (HTML estático).
4. Conectar el dominio personalizado (ej: `bahiasguestservices.com`).
