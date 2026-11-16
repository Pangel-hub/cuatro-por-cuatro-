# Caso 4 — Capa a Capa — Parte 2

Aplicación web didáctica para la Parte 2 del Caso 4. Incluye muestreo, ergonomía, biomecánica, propuesta conceptual de rediseño y simulador de producción A/B/C.

## Interfaz adaptable\nLa interfaz se adapta automáticamente a teléfono, tableta y escritorio mediante CSS responsive. En dispositivos estrechos, las tablas y el Gantt conservan desplazamiento horizontal localizado para mantener legibilidad.\n\n## Ejecutar
Abre `index.html` en un navegador moderno. No requiere instalación, API, base de datos ni credenciales. Para publicar en GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Datos de entrada
- Muestreo: 104 trabajo manual, 84 espera de impresión, 12 búsqueda; total 200.
- Ergonomía: P1 (96 cm, 38 cm), P2 (101, 42), P3 (106, 46), P4 (111, 50).
- Criterio didáctico de superficie: 2–8 cm bajo el codo; mesa fija 100 cm, ajustable 92–108 cm; bandejas 52 y 35 cm.
- Biomecánica: M = m × 9.81 × d; objeto hipotético de 1 kg y distancias 0.40 / 0.20 m.
- Producción: A (2 máquinas, L4, U2, F2, inversión 0), B (2 máquinas, L2, U2, F2, inversión 360), C (3 máquinas, L4, U2, F2, inversión 1200); lote de 4, ciclo automático 16 min.

## Modelo de despacho
Carga inicial M1, M2, M3 en orden; visitas cíclicas M1–M2–M3; espera si la siguiente impresora no ha concluido; descarga, recarga si cabe y acabado inmediato del lote descargado después de la eventual recarga. La persona no realiza tareas manuales simultáneas. Un lote solo cuenta cuando queda descargado y acabado dentro de H. Se descuenta la demanda al iniciar lote. El filtro de inicio es una condición de factibilidad básica, no garantiza optimalidad general.

## Economía
20 sesiones, 12 u. m. por pieza adicional frente a A, menos inversión. No se monetiza el tiempo libre de la persona porque el supuesto de caso fija el tiempo de personal.

## Validación académica
Las pruebas i (H=24, D=4), ii (H=23, D=4) y iii (H=30, D=8), alternativa A y ciclo 16 min, se deben derivar manualmente antes de compararlas con la aplicación. Consultar `documentacion/referencias_checkpoint.md`. La herramienta no presenta sus propias salidas como evidencia manual.

## Límites
Datos sintéticos. Cuatro perfiles antropométricos no permiten inferir percentiles poblacionales. El momento de fuerza es un ejemplo matemático, no un límite clínico o normativo. El muestreo describe actividad y no prueba causalidad. Los efectos del rediseño son hipótesis pendientes de medición.

## Equipo
Completar los nombres reales y registrar quién modeló, quién verificó manualmente, quién programó y quién revisó críticamente. No atribuir tareas que no se hayan realizado.
