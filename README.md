# Ondas sin cable · Blog sobre WiMAX (IEEE 802.16)

Sitio web de una sola página para la materia **Redes de Computadoras I** (INCOS El Alto).
Está escrito con **HTML, CSS y JavaScript puros**: no necesita compilación, ni frameworks, ni servidor. Todo el sitio (estilos, scripts, diagramas SVG y datos) vive en `index.html`.

## Qué incluye

- **Portada** con ilustración SVG animada, cinta de datos y foto real de una estación base.
- **WiMAX en seis números** con contadores y gráficos de despliegues.
- **Historia interactiva** año por año (1998–2020) con navegación por teclado.
- **Personajes** en tarjetas que se voltean.
- **Cómo funciona**: arquitectura, OFDM/OFDMA, QoS, seguridad y bandas por país.
- **Visualizador de tráfico (OFDMA/QoS)**: reparto de subportadoras según la clase de servicio (UGS, ertPS, rtPS, nrtPS, BE).
- **Anatomía de una red WiMAX**: diagrama con puntos interactivos (antenas, radio, backhaul, CPE, LOS/NLOS, red del operador).
- **Simulador de cobertura** con modulación adaptativa y señal.
- **Mapa esquemático de despliegues** (13 ciudades y países).
- **Galería de fotos** con visor ampliado, modo carrusel y pase automático.
- **WiMAX en Bolivia** (Entel, AXS, 3,5 GHz) y **empresas** con filtros y búsqueda.
- **Por qué perdió frente a LTE**, comparador WiMAX vs Wi-Fi/LTE/5G y línea de vida 2001–2026.
- **Glosario** de siglas y **referencias bibliográficas en APA (7.ª ed.)**.

## Extras de la interfaz

- Tema claro y oscuro con preferencia guardada.
- Buscador rápido de la página: `Ctrl + K` o `/`.
- Atajos: `T` cambia el tema, `?` muestra la ayuda y `←`/`→` recorren la línea de tiempo.
- Navegación lateral con seguimiento del scroll, botón de volver arriba con anillo de progreso y estilos de impresión/PDF.
- Accesible: foco visible, etiquetas ARIA, textos alternativos y respeto por `prefers-reduced-motion`.

## Cómo verlo

**En línea:** https://zeref6588-crypto.github.io/wimax/
Publicado con GitHub Pages desde la rama `main` (carpeta raíz).

**En tu computadora:**

```bash
# Abrir directamente en el navegador
index.html
```

Sin JavaScript el texto, las fotos y las referencias se leen igual; solo se desactivan las partes interactivas.
Necesita internet para las tipografías de Google Fonts y las fotos de Wikimedia Commons.

## Actualizar el sitio publicado

GitHub Pages reconstruye el sitio en unos segundos después de cada `push` a `main`:

```bash
git add .
git commit -m "Descripción del cambio"
git push
```

Si alguna vez necesitas revisar la configuración: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

## Créditos de las fotografías

Las fotos son de Wikimedia Commons y se usan bajo su licencia. Se acreditan también en cada ficha dentro de la sección «WiMAX en fotos».

| Fotografía | Autor | Licencia |
| --- | --- | --- |
| WiMAX 2.1 base station by UQ Communications | Yoh-Plus | CC BY 4.0 |
| Wimax base LTU1 | Stalinas | CC BY-SA 3.0 |
| Fixed Wireless Access Antenna Alvarion Hokkaido Japan | Fastlamb | CC BY-SA 4.0 |
| Alvarion CPE | Vitaliy Neret | CC BY 3.0 |
| Banglalion wimax indoor modem and wifi router hotspot | Zamanological | CC BY-SA 3.0 |
| 2008 WiMAX Expo Taipei ASUS Eee PC 901 with WUSB25E2V2 | Rico Shen | CC BY-SA 4.0 |
| WiMAX equipment | Groupe Aménagement Numérique des Territoires | CC BY 2.0 |
| HTC Evo 4G | Christian Lo | CC BY 2.0 |
| Enforta BS | Vitaliy Neret | CC BY-SA 3.0 |

Los diagramas, gráficos e ilustraciones SVG son originales del proyecto.
Las citas y referencias bibliográficas (formato APA 7) están en la sección **Referencias** de la página.

## Autoría

Trabajo académico de **Juan Daniel Mamani Coro** — Sistemas Informáticos, INCOS El Alto.
Contenido elaborado para la materia **Redes de Computadoras I**, gestión 2026.
