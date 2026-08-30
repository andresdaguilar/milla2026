# Plan Milla 6:00 — Andrés

Web del plan de entrenamiento para la **Milla Urbana New Balance**, Buenos Aires, sábado **21/11/2026**.

## Qué es esto

- **`plan.json`** — la fuente de datos. Es la exportación completa de `Plan Milla 6-00 - dia por dia.xlsx`:
  18 semanas, 126 días, todos los campos de la planilla (plan + registro de lo hecho),
  más una guía de ejecución (`guia`) generada para cada sesión.
- **`index.html`** — la web. Un solo archivo, sin dependencias, con el JSON embebido.
  Funciona abriéndolo directo desde el disco o publicado en GitHub Pages.

## Las dos vistas

| Tab | Qué muestra |
|---|---|
| **Hoy** | La sesión del día: objetivo, pasos de ejecución, ritmos de referencia, criterio de sesión bien hecha, avisos, gimnasio y nota del plan. Debajo, el resto de la semana y la tabla de referencias medidas + cuenta regresiva de los tests. |
| **Plan completo** | Las 18 semanas plegables, con los 126 días. Cada día se abre y muestra todos los campos de la planilla más la guía de ejecución. La semana en curso se abre sola; el día de hoy queda resaltado. |

## Regenerar

`plan.json` e `index.html` se generan desde el `.xlsx`. Si cambia la planilla, hay que regenerarlos:
la planilla sigue siendo la fuente de verdad, esto es una vista.

## Referencias medidas (no estimadas)

- FC máxima real: **198 ppm** (test 23/07)
- Umbral: **FC 166-174 · 6:50/km**
- Trote fácil: **7:30-8:00/km**, techo FC 160-163
- Piso de velocidad: **8:00-8:15/km**
- 400 m máximo: **1:50** (replicado 23/07 y 15/08)
- 200 m: **46.6-50.5 s** (27/08)
- Milla actual **8:56** · milla histórica **7:20**
