# Sistema Despertar · Especificación v0.3

Fuente visual y jugable: `prototipo/sistema-despertar-v0.3.html`.

## 1. Las dos obligaciones
Solo estas dos misiones tienen penalización. Todo lo demás es bonificación.

### Ritual de Activación · diario · 5 min
| Paso | Duración | Contenido | Stat |
|---|---|---|---|
| Autocuidado | 1 min | Agua, medicación si está indicada, cara lavada | VIT |
| Captura | 1 min | Vaciar la cabeza en la bandeja de pendientes | INT |
| Radar | 1 min | Revisar eventos y compromisos de hoy y mañana | INT |
| Siguiente paso | 2 min | Elegir opción A o B y darle una hora | INT |

Plazo por defecto antes de las 11:00, ajustable. A las 11:00 hay un solo aviso y el plazo final pasa a las 20:00.

### Planificación semanal · 30 min
| Bloque | Duración | Contenido |
|---|---|---|
| Mirar atrás | 5 min | Qué se cumplió, qué se atascó y por qué |
| Vaciar la bandeja | 8 min | Cada pendiente se borra, se agenda, se delega o va a un objetivo |
| Radar semanal | 5 min | Eventos, compromisos, pagos y vencimientos de los próximos 14 días |
| Tres objetivos | 7 min | Ordenarlos 1, 2 y 3 y partirlos en pasos de 25 min o menos |
| Bloquear horas | 5 min | Poner en el calendario cuándo se trabaja cada objetivo |

Día por defecto domingo, ajustable. Desbloquea el motor del siguiente paso de la semana.
Incluye un chequeo de ánimo opcional de una pregunta.

## 2. Motor del siguiente paso
- Fuente: los 3 objetivos semanales y los portales abiertos, cada uno con pasos ordenados.
- Muestra solo 2 tarjetas: **A** = primer paso pendiente del objetivo de prioridad 1. **B** = primer paso del objetivo de prioridad 2.
- A da +30 XP. B da +20 XP y no penaliza.
- Un compromiso del radar que vence en menos de 72 h sube a prioridad 1 y el Sistema avisa el cambio.
- Al completar un paso aparece el siguiente del mismo objetivo.
- Un paso pospuesto 3 veces obliga a partirlo en uno más pequeño.

## 3. Radar de compromisos
- Aviso el día anterior y aviso de **hora de salida** (trayecto + margen), no solo la hora del evento.
- Cuenta regresiva en vencimientos.
- Pendiente de decidir: integración con Google Calendar o ingreso manual en v1.

## 3b. Registro de ánimo · 2 toques · opcional
Decidido el 2026-11-24.
- **Toque 1:** ánimo en escala de 5: 1 Muy mal · 2 Mal · 3 Regular · 4 Bien · 5 Muy bien.
- **Toque 2:** confirmar etiquetas y guardar. Las misiones hechas ese día vienen marcadas solas (ritual, movimiento, foco, calma, sueño). Extras opcionales: dormí mal, estrés, ansiedad, irritable, olvidé la medicación.
- No forma parte del mínimo y no tiene penalización.
- Aparece al cerrar el día con un solo aviso. Se puede registrar en cualquier momento; varios registros en un día se promedian.
- **Recompensa:** +5 XP por registrar, igual para cualquier valor. Nunca se premia un ánimo alto.
- **Estadísticas:** desde 14 registros, ánimo promedio en días con y sin cada hábito. Se muestra como asociación, no como causa, y solo si hay al menos 5 días en cada grupo. Calendario anual por colores.
- **Alerta suave:** ánimo 1 durante 3 días seguidos pausa las penalizaciones, muestra recursos de ayuda y sugiere contactar al tratante. No avisa a nadie salvo autorización previa. La pregunta de autodaño sigue en el chequeo semanal.

## 3c. Almacenamiento de datos
Decidido el 2026-11-24: **en el teléfono por defecto, con sincronización opcional.**
- Base de datos local cifrada. Funciona sin conexión y sin cuenta.
- La sincronización exige consentimiento explícito, separado por propósito y revocable:

| Permiso | Qué se envía | Para qué |
|---|---|---|
| Ninguno (por defecto) | Nada sale del teléfono | Uso personal |
| Respaldo personal | Copia cifrada de todos los datos | Recuperar al cambiar de teléfono |
| Compartir con mi coach | Resumen semanal de ritual, planificación y ánimo | Seguimiento en el taller |
| Aportar a la medición del taller | Datos anónimos y agregados | Medir resultados del curso |

- Siempre disponible: exportar todo a un archivo y borrar todo, en el teléfono y en el servidor.
- Los datos de ánimo nunca van a herramientas de analítica ni de publicidad.
- Legal: datos de salud son sensibles. Confirmar vigencia y requisitos de la Ley 21.719 (hipótesis: rige desde diciembre de 2026).

## 4. Reglas de Barkley → mecánicas
Lista citada de memoria de *Taking Charge of Adult ADHD*. Verificar con el libro.
| # | Regla | Mecánica |
|---|---|---|
| 1 | Detén la acción | "Pausa del Cazador": 3 respiraciones antes de abrir correo o redes |
| 2 | Mira el pasado y luego el futuro | "Mirar atrás" semanal y revisión sin culpa de la penalización |
| 3 | Dilo en voz alta | Escribir o dictar en una frase qué se hará y cuándo |
| 4 | Externaliza la información clave | Bandeja de captura, radar, widget en pantalla de inicio |
| 5 | Siente el futuro / externaliza el tiempo | Hora de salida, temporizador visual, cuentas regresivas |
| 6 | Divídelo y haz que importe | Pasos de 25 min o menos, XP por paso, Tienda del Sistema |
| 7 | Haz los problemas externos y físicos | Portales como mapa de pisos con el jefe marcado |
| 8 | Ten sentido del humor | Tono del Sistema, escudos, Modo Recuperación, título "El que regresó" |

Principio general: intervenir en el punto de ejecución.

## 5. Stats
| Stat | Pilar | Sube con |
|---|---|---|
| FUE Fuerza | Actividad física | Movimiento, pausas activas |
| VIT Vitalidad | Sueño y autocuidado | Autocuidado del ritual, cierre del día |
| INT Foco | Estructura y trabajo profundo | Captura, siguiente paso, foco, planificación |
| SEN Calma | Manejo del estrés | Pausa del Cazador, respiración, mindfulness |
| VÍN Vínculo | Conexión social | Mensaje, llamada, trabajo acompañado |

## 6. Misiones de bonificación (opcionales)
Niveles: Mínimo 10 XP · Estándar 25 XP · Élite 50 XP.
| Misión | Stat | Mínimo | Estándar | Élite |
|---|---|---|---|---|
| Mover el cuerpo | FUE | 10 sentadillas o 2 min caminata | 20 min caminata rápida | 30 min ejercicio moderado a vigoroso |
| Bloque de foco | INT | 10 min en el siguiente paso | 2 × 25 min | 90 min |
| Calmar el sistema | SEN | 1 min respiración lenta | 5 min guiada | 15 min mindfulness o yoga |
| Cerrar el día | VIT | Celular fuera de la cama | Acostarse a la hora meta ±30 min | Rutina completa y 7 a 9 h de sueño |
| Conectar | VÍN | Un mensaje | Conversación de 10 min | Sesión de trabajo acompañado |

Misión de emergencia: al azar, máximo 1 al día, 2 min, opcional, sin penalización.
Día de recuperación: 1 por semana, el ritual se reduce a autocuidado y radar.

## 7. Recompensas
| Evento | Recompensa |
|---|---|
| Cada paso del ritual | +5 XP |
| Ritual completo | +30 XP, 10 cristales, 1 Caja de recompensa |
| Siguiente paso hecho | A: +30 XP · B: +20 XP |
| Registrar el ánimo | +5 XP, igual para cualquier valor |
| Planificación semanal | +150 XP, 40 cristales, 1 escudo |
| Racha de ritual | ×1,10 a los 3 días · ×1,25 a los 7 · ×1,50 a los 14 (tope) |
| Cada 7 días de racha | 1 escudo, máximo 2 |
| Subir de nivel | 3 puntos libres y 25 cristales |
| Volver tras 3+ días fallados | Título "El que regresó" y +50 XP |

- Curva: XP del nivel n al n+1 = 100 + 20 × (n − 1).
- Caja de recompensa: contenido variable sin valor monetario (dato científico, frase del curso, tema visual, título, cristales, escudo con baja probabilidad).
- Tienda del Sistema: la persona define recompensas reales y su precio en cristales (principio de Premack).

## 8. Penalización
Nunca se pierden niveles, stats, cristales ni compras. Sin mensajes de culpa. Sin notificaciones después de la hora de cierre.

### Ritual no cumplido
| Cuándo | Efecto |
|---|---|
| 1 día | Se gasta un escudo si hay. Si no: ritual de 8 min al día siguiente (5 + 3 de revisión sin culpa), estado Fatiga con XP ×0,5 hasta completarlo, racha a cero |
| 2 días seguidos | Recalibración obligatoria: mover plazo o cambiar la señal si-entonces, eligiendo entre 3 opciones |
| 3+ días | Modo Recuperación: penalizaciones suspendidas, ritual de 60 s (agua + radar) |

### Planificación semanal no cumplida
| Cuándo | Efecto |
|---|---|
| Lunes sin plan | Portal semanal cerrado: motor usa objetivos viejos, Tienda bloqueada. Rescate de 15 min disponible hasta el miércoles |
| Miércoles sin plan | XP ×0,5 hasta el domingo. Próxima planificación con plantilla prellenada |
| 2 semanas sin plan | Se suspende la penalización semanal. Se ofrece planificación grupal del taller o guiada por voz de 15 min |

### Freno clínico
Ánimo muy bajo o ideas de autodaño: pausa total de penalizaciones y recursos de ayuda en Chile
(Salud Responde 600 360 7777, línea de prevención del suicidio *4141, **verificar antes de lanzar**).
La app no reemplaza tratamiento.

## 9. Progresión
| Rango | Nivel | Examen |
|---|---|---|
| E | 1–9 | Inicio |
| D | 10–19 | Ritual 5/7 días y 1 planificación |
| C | 20–34 | Ritual 5/7 durante 2 semanas y ambas planificaciones |
| B | 35–49 | Ritual 21/30 y 4 planificaciones |
| A | 50–69 | Ritual 45/60, 8 planificaciones y 3 portales cerrados |
| S | 70+ | Rango A sostenido 90 días |

- **Portales**: proyecto temido partido en pisos de 10 a 25 min, con el jefe marcado. Alimentan el motor del siguiente paso.
- **Llave de mazmorra instantánea**: sesión de foco cronometrada, sola o acompañada.
- **Cambio de clase**: cada módulo del curso desbloquea una clase con misión especial y título.

## 10. Voz del Sistema
Frases cortas, segunda persona, tono frío y épico, nunca sarcástico. Habla del plan, nunca de la persona.
- "El Ritual de Activación ha llegado. 5 minutos. Primer paso: un vaso de agua."
- "Opción A: escribir 3 títulos del informe, 10 minutos. Opción B: reunir las boletas, 5 minutos. Elige."
- "Reunión a las 15:00. Debes salir a las 14:35."
- "La Planificación semanal está disponible. 30 minutos. Sin ella, el portal de la semana no se abre."
- "Ayer el ritual no se cumplió. Hoy dura 8 minutos. Tu progreso está intacto."

## 11. Evidencia
Verificadas en PubMed:
- Luman M, Oosterlaan J, Sergeant JA. Clin Psychol Rev 2005. https://doi.org/10.1016/j.cpr.2004.11.001 (niños; extrapolar a adultos es hipótesis)
- Singh B, et al. Br J Sports Med 2025. https://doi.org/10.1136/bjsports-2024-108589
- Zhu F, et al. Front Public Health 2023. https://doi.org/10.3389/fpubh.2023.1133727
- Sun W, et al. Psychiatry Res 2022. https://doi.org/10.1016/j.psychres.2022.114509

Por confirmar:
- Barkley RA. Taking Charge of Adult ADHD. Guilford Press.
- Lally P, et al. Eur J Soc Psychol 2010 (no indexado en PubMed).
- Gollwitzer PM, Sheeran P. Adv Exp Soc Psychol 2006.

Sin evidencia directa: no hay ensayos de gamificación tipo RPG en adultos con TDAH.
