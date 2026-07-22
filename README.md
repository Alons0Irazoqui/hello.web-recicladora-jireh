# Brief de Proyecto — Recicladora "Jireh"

Landing page corporativa para **Recicladora "Jireh"**. Este documento es el informe de referencia para el desarrollo del sitio: reúne la información del negocio, el branding y los requisitos visuales que debe cumplir el proyecto.

El desarrollo se construye sobre una **plantilla base de HTML ya existente**. Ya se entregó por separado un prompt inicial para adaptar dicha plantilla al negocio; este README complementa ese prompt con la información de marca y los lineamientos visuales obligatorios. **La estructura de secciones de la página ya está definida por la plantilla base y debe respetarse tal cual** — este documento no indica qué secciones incluir ni en qué orden.

---

## 1. Información del negocio

Datos extraídos de los materiales gráficos (flyers) provistos en la carpeta `imagenes/`.

| Campo | Detalle |
|---|---|
| **Nombre** | Recicladora "Jireh" |
| **Eslogan** | Compromiso con el medio ambiente |
| **Rubro** | Compra y reciclaje de equipos de aire acondicionado en desuso o descompuestos |
| **Teléfono / WhatsApp** | 999 646 5382 |

### Servicios / productos que compran
- Minisplit de ventana
- Minisplit de piso
- Minisplit de techo
- Equipos industriales
- Chillers

### Propuesta de valor
- Pago al instante por el equipo.
- Servicio de recolección a domicilio ("vamos por él a donde estés").
- Proceso rápido y seguro.
- Compromiso ambiental: evitan la contaminación, reutilizan materiales y promueven un futuro mejor.
- Contacto principal vía WhatsApp para cotizar.

> No se localizaron datos de dirección física ni horarios de atención en el material disponible, por lo que no se incluyen en este brief.

---

## 2. Branding

Paleta, tipografía e identidad visual definidas a partir del logo y los flyers en `imagenes/`.

### Paleta de colores

| Color | HEX aproximado | Uso |
|---|---|---|
| Azul marino corporativo | `#1B3A66` | Color primario: textos de marca, encabezados, fondos de bloques destacados |
| Azul medio (isotipo) | `#2D6CB5` | Detalle del logo, acentos secundarios, degradados |
| Verde ecológico | `#6CB33F` | Color de acento: CTAs, íconos, elementos que comunican sustentabilidad |
| Blanco | `#FFFFFF` | Fondo principal, espacios en blanco, contraste |

> Estos HEX son una aproximación visual extraída de los flyers. Al construir el sitio, verificar/ajustar los tonos exactos con el logo en alta resolución para asegurar consistencia de marca.

### Tipografía sugerida
- **Encabezados / títulos:** una tipografía sans-serif de trazo grueso y geométrico (ej. Montserrat ExtraBold, Poppins Bold o similar), que replique el estilo condensado y de alto impacto usado en los títulos de los flyers.
- **Cuerpo de texto:** una sans-serif limpia y moderna de buena legibilidad (ej. Inter, Montserrat Regular o similar), coherente con un estilo big tech.

### Identidad visual
La marca combina dos ideas: **sustentabilidad** (verde, hojas, reciclaje) y **confianza/profesionalismo** (azul marino, formas sólidas). El logo es un isotipo ovalado en degradado azul con un ícono de unidad de aire acondicionado y herramienta, acompañado del nombre "RECICLADORA JIREH" y el eslogan "Compromiso con el medio ambiente". La iconografía de apoyo usada en los materiales incluye: manito con dinero, camión de recolección con pin de ubicación, escudo con check, hojas/reciclaje. Estos elementos visuales (no necesariamente los mismos íconos) deben inspirar el lenguaje visual del sitio.

---

## 3. Estilo visual obligatorio

El sitio debe transmitir un estilo:
- **Premium, enterprise y corporativo de marca.**
- **Nivel big tech**: elegante y a la vez minimalista.

Esto aplica sobre toda la interfaz: composición, espaciados, jerarquía tipográfica y tratamiento de imágenes, manteniendo la identidad de marca definida en la sección anterior.

---

## 4. Efectos y animaciones requeridos

El proyecto debe incluir:
- **Animaciones de scroll**: efectos visuales que se activan a medida que el usuario navega la página.
- **Pantalla de carga (preloader)**: spinner de carga junto con el logo del negocio, mostrado antes de que cargue el sitio.
- **Animaciones en el título del hero**: efecto de máquina de escribir, cambio de color en las letras, u otros efectos tipográficos similares.

---

## 5. Instrucciones sobre assets

- El logo disponible en `imagenes/` tiene **fondo**. Antes de usarlo en el sitio, se debe **remover el fondo** para obtener una versión limpia (transparente) del logo.
- Las fotos de equipos y los flyers en `imagenes/` son material de referencia para extraer información e identidad de marca; no están pensadas para usarse como imágenes finales del sitio sin revisión previa de calidad y encuadre.

---

## 6. Nota para el desarrollador

Este proyecto se construye iterando con **Claude Code**. El desarrollador puede (y debe) darle instrucciones a Claude las veces que sea necesario para ajustar diseño, contenido, animaciones y detalles hasta lograr el resultado deseado. No es necesario acertar todo a la primera iteración.

---

## Checklist para el desarrollador

- [ ] Leer este README y el prompt inicial de adaptación de la plantilla.
- [ ] Remover el fondo del logo de `imagenes/` y generar una versión limpia (transparente) para usar en el sitio.
- [ ] Aplicar la paleta de colores de marca (azul marino, azul medio, verde ecológico, blanco) en todo el sitio.
- [ ] Aplicar la tipografía sugerida (encabezados de trazo grueso + cuerpo limpio y moderno).
- [ ] Incorporar la información del negocio (nombre, teléfono/WhatsApp, servicios, propuesta de valor) en la plantilla base, respetando su estructura de secciones.
- [ ] Lograr un estilo visual premium, enterprise y minimalista, nivel big tech.
- [ ] Implementar animaciones de scroll en la página.
- [ ] Implementar pantalla de carga (preloader) con spinner + logo del negocio.
- [ ] Implementar animación del título del hero (máquina de escribir, cambio de color u otro efecto tipográfico).
- [ ] Revisar que las imágenes usadas en el sitio final tengan buena calidad y encuadre.
- [ ] Iterar con Claude Code hasta lograr el resultado deseado.
