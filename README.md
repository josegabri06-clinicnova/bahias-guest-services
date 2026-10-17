# Huatulcostays

Sitio web oficial de hospedaje, condominios vacacionales y villa privada en Huatulco, Oaxaca (`huatulcostays.com`).

Este proyecto está **100% desacoplado** del sistema hotelero interno para servir como entidad formal, limpia y verificable ante Meta Business / WhatsApp Business API y Google Hotel Ads con paridad estricta de tarifas.

## Estructura de Archivos
- `index.html`: Landing page principal ejecutiva con llamadas a la acción directas hacia WhatsApp (`+52 958 122 11 11`).
- `privacidad.html`: Política de Privacidad conforme a la LFPDPPP y estándares de Meta con titularidad oficial de Rolando Diaz Ceballos Corral.
- `terminos.html`: Términos y Condiciones del Servicio.
- `styles.css`: Sistema de diseño moderno, responsive y ultraligero.
- `images/`: Galería de fotografías optimizadas sin sellos de agua ni publicidad ajena.
- `vercel.json`: Reglas de enrutamiento limpio y cabeceras de seguridad para Vercel.

## Despliegue en Vercel
1. Conectado al repositorio `josegabri06-clinicnova/bahias-guest-services`.
2. En Vercel: Framework Preset **Other** (HTML estático).
3. Dominio asignado: `huatulcostays.com` (o subdominio asignado).
