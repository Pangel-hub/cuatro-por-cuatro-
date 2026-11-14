# Plan de pruebas

| ID | Entrada | Resultado/condición esperada | Estado |
|---|---|---|---|
| T01 | A, H=24, D=4, ciclo=16 | 1 lote terminado a 24 min; 8 min manuales | Referencia manual del equipo pendiente |
| T02 | A, H=23, D=4, ciclo=16 | No iniciar; 0 piezas | Referencia manual del equipo pendiente |
| T03 | A, H=30, D=8, ciclo=16 | 2 lotes; último acabado 28 min; 16 min manuales | Referencia manual del equipo pendiente |
| T04 | H=0 | 0 piezas terminadas | Ejecutar al validar |
| T05 | H=121 | Rechazar entrada | Implementado |
| T06 | Demanda=6 | Rechazar entrada | Implementado |
| T07 | Ciclo=11 o 21 | Rechazar entrada | Implementado |
| T08 | H=1, demanda=40 | Reportar demanda no cumplida | Implementado |
| T09 | Cronograma | Ningún solapamiento manual | Verificación interna del simulador |

Las pruebas técnicas de interfaz deben repetirse en Chrome/Brave Android y en otro dispositivo. Registrar dispositivo, navegador, fecha, incidencias y resultado real.
