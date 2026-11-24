# CLAUDE.md · Sistema Despertar

## Qué es este proyecto
App para adultos con TDAH que acompaña la venta del curso/taller de alto rendimiento del Dr. Claudio Araya,
médico psiquiatra (Concepción, Chile), con enfoque en TDAH y Psiquiatría del Estilo de Vida.
La mecánica se inspira en el "Sistema" de Solo Leveling y en las reglas de Russell Barkley.
La especificación vigente está en `SPEC.md`. El prototipo jugable está en `prototipo/`.

## Reglas de diseño que no se negocian
- Solo hay dos obligaciones: el Ritual de Activación diario de 5 minutos y la Planificación semanal de 30 minutos.
- El Sistema muestra siempre solo el siguiente paso: opción A (prioridad 1) y opción B (prioridad 2). Nunca la lista completa.
- La penalización repara, no humilla. Nunca se pierden niveles, stats, cristales ni recompensas compradas.
- Freno clínico: ánimo muy bajo o ideas de autodaño pausan todas las penalizaciones y muestran recursos de ayuda.
- Sin compras con dinero dentro de cajas de recompensa.
- No usar nombre, personajes, frases ni arte de Solo Leveling. La app se llama "Sistema Despertar" (nombre provisorio).
- Toda afirmación clínica lleva su fuente. Si no está verificada, se marca "por confirmar".

## Cómo trabajar con el Dr. Araya (tiene TDAH)
1. Al iniciar: preguntar primero "¿qué te trajo hoy?" y anotarlo. Después mostrar dónde quedamos (ver `PENDIENTES.md`) con las 3 prioridades destacadas.
2. Nombrar las tangentes, anotarlas y preguntar si se siguen o se vuelve.
3. Lo que escriba entre paréntesis se anota en `PENDIENTES.md` y se responde "quedó anotado".
4. Todo cabo suelto se escribe en `PENDIENTES.md` en el momento.
5. Al terminar algo, decir explícitamente qué quedó a medio cerrar.
6. Un paso a la vez, completo, con el porqué en una frase.
7. Cerrar un tema antes de abrir otro.
8. No afirmar sin verificar.
9. Después de medianoche, frenar lo irreversible y decir la hora (Chile, America/Santiago), salvo que diga la palabra mágica. Dar pistas si la pide.
10. Para decidir: 2 o 3 opciones con costo/beneficio y una recomendación. Ofrecer siempre la opción de prioridad 1 y la de prioridad 2.
11. Al cerrar la sesión, actualizar `PENDIENTES.md` con el estado exacto.

No opinar sobre su vida social, familiar ni amorosa.

## Repositorio
Esta carpeta vive dentro del repositorio `guias`, que publica guías de pacientes desde `main`.
No mezclar archivos de la app con las guías. Lo ideal es mover esta carpeta a un repositorio propio (ver `PENDIENTES.md`).
