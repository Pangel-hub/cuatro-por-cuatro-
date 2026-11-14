# Referencias para derivación manual del checkpoint

Estas referencias se incluyen como guía de comprobación; no sustituyen la derivación escrita e independiente del equipo. Antes de solicitar o usar el código como validador, cada equipo debe hacer sus propios diagramas y cálculos a mano, como pide el punto de control del Caso 4 (p. 30).

## Prueba i — A, H=24 min, demanda=4 piezas, ciclo=16 min
- Carga inicial M1 / lote 1: 0–4.
- Impresión M1: 4–20.
- Descarga M1: 20–22.
- Acabado del lote 1: 22–24.
- Lotes iniciados: 1. Lotes terminados: 1. Piezas: 4. Manual ocupado: 4 + 2 + 2 = 8 min. Último acabado: 24 min.

## Prueba ii — A, H=23 min, demanda=4 piezas, ciclo=16 min
- La condición de inicio exige L + ciclo + U + F = 4 + 16 + 2 + 2 = 24 min.
- Como 24 > 23, no se inicia el lote.
- Lotes iniciados: 0. Terminados: 0. Piezas: 0. Manual ocupado: 0 min. Último acabado: no aplica.

## Prueba iii — A, H=30 min, demanda=8 piezas, ciclo=16 min
- Carga inicial M1 / lote 1: 0–4; impresión: 4–20.
- Carga inicial M2 / lote 2: 4–8; impresión: 8–24.
- Visita M1: espera de persona 8–20; descarga lote 1: 20–22. No se recarga porque desde 22 min no cabe 4 + 16 + 2 + 2 dentro de H=30. Acabado lote 1: 22–24.
- Visita M2: impresión ya termina en 24; descarga lote 2: 24–26; no se recarga; acabado lote 2: 26–28.
- Lotes iniciados: 2. Terminados: 2. Piezas: 8. Manual ocupado: cargas 8 + descargas 4 + acabados 4 = 16 min. Último acabado: 28 min.

## Nota
La secuencia anterior aplica literalmente el filtro de inicio y la visita M1–M2. Comparar estos resultados con el anexo patrón que libere el docente. Si hubiera discrepancias, registrar el supuesto o regla que las explica antes de corregir el código.
