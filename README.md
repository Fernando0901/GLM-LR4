# Guía interactiva — CNC LowRider v4 🛠️

Página web autocontenida (`index.html`) para planificar y construir tu propia **LowRider v4** de V1 Engineering: componentes, paso a paso, herramientas, piezas impresas en 3D, cómo ajustar los modelos, calculadora oficial de medidas, visor 3D paramétrico y la evaluación técnica de la tabla de torsión diseñada por IA del video de trailcurrentopensource.

## Cómo usarla

Abre `index.html` en cualquier navegador moderno (doble clic). Solo necesita conexión a internet para el visor 3D (three.js por CDN) y los videos incrustados; todo lo demás funciona offline.

## Qué incluye

| Sección | Contenido |
|---|---|
| Resumen | Configuración de la máquina, costos, capacidades |
| Visor 3D | Esquema paramétrico que se redimensiona con tus medidas (rotar/zoom) |
| Calculadora | Réplica exacta de la oficial de V1E (mm/pulgadas) con lista de corte |
| Diagrama | Vista superior SVG sincronizada con la calculadora |
| Tabla de torsión | Evaluación completa del diseño del video + parámetros CAM |
| Materiales | BOM completo: rieles, partes especiales, tornillería, partes planas |
| Piezas 3D | Tabla de ~35 piezas impresas con rellenos y avisos de slicing |
| Ajustar modelos | Strut generator, placas XZ, plugin FreeCAD + skills de IA |
| Paso a paso | 8 fases del ensamble oficial con tips críticos |
| Electrónica | Jackpot/SKR Pro, firmware, aspiración con tierra |
| Calibración | Pasos/mm, cuadrado por diagonales, nivel Z |
| Seguridad | Estática, router, toolpaths |

## Verificación

Las fórmulas de la calculadora provienen del [código fuente público](https://github.com/V1EngineeringInc/V1EngineeringInc-Docs) de V1 Engineering y fueron cotejadas número por número contra la [calculadora oficial](https://docs.v1e.com/lowrider/calculator/) (mm y pulgadas). El visor 3D es un esquema didáctico simplificado, **no** CAD oficial.

## Fuentes

- [Documentación oficial LowRider v4](https://docs.v1e.com/lowrider/) — V1 Engineering
- [Video: "I Built the LowRider V4 DIY CNC With the help of AI Agents"](https://www.youtube.com/watch?v=10SrEGDkLX0) — trailcurrentopensource
- [TorsionTable.zip (release con modelo FreeCAD + CAM)](https://github.com/trailcurrentoss/YouTubeCodeSamples/releases/tag/torsion-table-release)
- [Utilities-Logo FreeCAD Plugin](https://github.com/trailcurrentoss/Utilities-LogoFreeCADPlugin) · [TrailCurrentClaudeSkills](https://github.com/trailcurrentoss/TrailCurrentClaudeSkills) · [trailcurrent.com](https://trailcurrent.com/)

## Aviso

El diseño LowRider CNC v4 pertenece a **V1 Engineering Inc.** (archivos bajo [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). Esta guía es una recopilación no oficial con fines educativos: verifica siempre contra la documentación oficial antes de cortar o imprimir. Construcción bajo tu propio riesgo.
