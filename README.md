# 🔁 La Brecha Invisible — herramientas del libro

App web con las herramientas del libro *La Brecha Invisible*, de **Leonardo Pineda Lombana**,
para conectar la ciberseguridad con el lenguaje del negocio.

Funciona en computador, tablet y celular desde el navegador, se puede instalar como app y funciona sin internet.
Lo que cada persona escribe se guarda solo en su dispositivo (no hay cuentas ni servidor).

## Herramientas

| Cap. | Herramienta | Qué hace la app |
|---|---|---|
| 1 | El Traductor Bidireccional | Traduce una frase técnica al negocio y al revés, con detector de jerga. |
| 2 | Los 3 filtros antes de bloquear | Calcula las horas que cuesta una restricción y da un veredicto. |
| 3 | La Plantilla Financiera de una Página | Hace las cuentas y arma la página de 4 cuadrantes para el CFO (imprimible). |
| 4 | Las 3 Preguntas del CEO | Revisa si el proyecto está listo: sin jerga y con métricas de negocio. |
| 5 | La conversación del "Sí, y…" | Guion en 4 pasos y acta de responsabilidad compartida. |
| 6 | El Validador de Frameworks | Tres preguntas y veredicto antes de firmar. |
| 7 | Las 5 preguntas iniciales | Arma el brief del proyecto empezando por el dolor. |
| 8 | La Regla de las Tres Frases | Cuenta palabras y oraciones y compara el antes y el después. |
| 10 | Guía de Bolsillo del Traductor Ejecutivo | Fórmula de tres frases para CEO, CFO, comité, equipo técnico o incidente. |

Además: detector de jerga en la portada, biblioteca para guardar, copiar e imprimir documentos, y copia de seguridad en JSON.

## Publicarla
1. En GitHub: **Settings → Pages → Source: GitHub Actions** (una sola vez).
2. Cada cambio en `main` publica la app en `https://<tu-usuario>.github.io/brecha/`.
3. Para instalarla: en iPhone/iPad (Safari) *Compartir → Añadir a pantalla de inicio*; en Chrome, el ícono de instalar en la barra de direcciones.

## Desarrollo
HTML + CSS + JS sin dependencias. Para probar localmente:

```bash
python3 -m http.server 8000
```

y abre http://localhost:8000.
