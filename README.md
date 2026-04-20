# RepMedic — Landing Page

Landing page para **RepMedic**, proveedor de equipo médico, redes e infraestructura y software RIS/PACS en México.

## Estructura

```
repmedic/
├── repmedic-landing.html   # Sitio completo (single-file)
├── favicon.png             # Ícono (fallback; el HTML usa SVG inline)
└── README.md
```

## Tecnología

- HTML + CSS + JS vanilla — sin frameworks, sin dependencias de build
- Fuentes: [Inter](https://fonts.google.com/specimen/Inter) + [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) vía Google Fonts
- Formulario de contacto: [Web3Forms](https://web3forms.com/) (envío sin backend)

## Secciones

| Sección | Descripción |
|---|---|
| Hero | Presentación principal con mock del sistema MED IQ — Detalle de estudios |
| Servicios | Venta de equipo, mantenimiento, redes, ERP y software MED IQ |
| MED IQ | Pantalla de consultas médicas y características del software RIS/PACS |
| Proceso | 5 pasos desde diagnóstico hasta soporte continuo |
| Nosotros | Diferenciadores frente a otros proveedores |
| Contacto | Formulario Web3Forms + WhatsApp directo |

## Configurar el formulario

1. Obtén tu Access Key en [app.web3forms.com](https://app.web3forms.com/)
2. En `repmedic-landing.html` reemplaza el valor del campo oculto:

```html
<input type="hidden" name="access_key" value="TU_ACCESS_KEY_AQUI">
```

Los correos llegarán a la dirección registrada en Web3Forms.

## Despliegue

El sitio es un único archivo HTML — se puede servir desde cualquier hosting estático (GitHub Pages, Netlify, Vercel, etc.) sin configuración adicional.

```bash
# Ejemplo con GitHub Pages: sube el repo y activa Pages apuntando a la raíz
```

## Contacto

- **RepMedic** · Pachuca, Hidalgo, México
- Tel: 771 150 8547 / 771 446 4323
- repmedic@outlook.es · [repmedic.com.mx](https://www.repmedic.com.mx)
- Software MED IQ desarrollado por [Persist Software Group](https://persist.lat/site)
