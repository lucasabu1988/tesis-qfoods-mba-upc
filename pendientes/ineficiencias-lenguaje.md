# Análisis de Ineficiencias de Lenguaje — Tesis QFoods

**Fecha:** 2026-04-05  
**Versión analizada:** v11 maestra consolidada  
**Diagnóstico global:** ~23.7% del texto es redundante o prescindible (~2,800 palabras)

---

## Resumen Ejecutivo

| Zona de la tesis | % ineficiencia | Palabras recuperables |
|---|---|---|
| Cap I — Marco Teórico | ~26% | ~1,370 |
| Resumen + Abstract | ~25% | ~105 |
| Cap VIII — Conclusiones/Recomendaciones | ~20% | ~240 |
| Cap II — Contexto | ~21% | ~210 |
| Cap III — Metodología | ~21% | ~200 |
| **Total** | **~24%** | **~2,800 palabras** |

---

## Tipo 1 — Repetición directa entre secciones

Misma información aparece textualmente en múltiples lugares:

| Contenido repetido | 1ª aparición | Repeticiones innecesarias |
|---|---|---|
| Los 6 marcos teóricos + autores fundacionales | Resumen | Tabla 1.4 + intro de 1.4.1 a 1.4.7 (×7 veces) |
| EVA pasó de -S/274k a +S/25,838 | Resumen | 1.1, 1.4.4, Cap VII, Conclusión 3 |
| GA +92.5% YoY sin crecimiento proporcional | 1.1 Planteamiento | 1.4.2 Agencia + Conclusión 1 + H1b |
| Altman Z" rango 5.71–7.82 zona segura | Resumen | 1.4.7, Cap VII, Conclusión 3 (4 menciones) |
| Sánchez-Almeyda et al. (2025) 147 empresas Colombia | 1.4.7 | Recomendación 11 (paráfrasis casi idéntica) |
| Briano-Turrent y Poletti-Hughes (2017) | 1.1 párrafo 3 | **Párrafo siguiente en 1.1 repite el mismo estudio** |
| Chambi-Condori et al. (2025): 80% EVA negativo | 1.4.1 | Recomendación 12 y Conclusión 5 |
| Liquidez corriente 1.29→1.79 / Endeudamiento 0.59→0.29 | Resumen | Conclusión 3 (copia casi literal) |

---

## Tipo 2 — Escritura de más (frases sin carga informativa)

- **"La presente tesis diseña, implementa y valida empíricamente…"** — "empíricamente" es redundante si ya se dice "valida"; "la presente tesis" es formulismo evitable.
- **"Este mecanismo compensatorio es exactamente lo que el SROD busca institucionalizar en Q Foods."** — el párrafo anterior ya lo decía implícitamente.
- **"Este hallazgo contextualiza la posición de Q Foods…"** / **"Este patrón es consistente con lo observado en Q Foods…"** — frases-puente repetidas ~8–10 veces en el Cap. I. Reemplazar por una sola transición al inicio de cada subsección.
- En las recomendaciones: **"La lógica económica es directa:"** / **"La lógica de negocio es virtuosa:"** — introducciones ornamentales prescindibles.

---

## Tipo 3 — Sección más ineficiente: 1.4.8 Crítica al CAPM (~41% redundante)

- El argumento central (CAPM sobreestima el costo de capital para MYPEs) está bien planteado en los primeros 3 párrafos.
- Los siguientes 6 párrafos citan a Ang, Fuenzalida, Pereiro, Bonilla y Moscoso repitiendo la **misma conclusión** con distintas geografías.
- El párrafo de cierre llega después de haber agotado el argumento.

**Acción recomendada:** Condensar los 6 párrafos de evidencia adicional en una tabla de 5 filas (Estudio / País / Hallazgo). Reducir sección de ~1,100 a ~650 palabras. Esta sección sola representa el **16% de todo el texto redundante** de la tesis.

---

## Tipo 4 — Objetivos e Hipótesis duplican el Resumen

- Sección 1.3 y 1.6 repiten en formato lista lo que el Resumen ya sintetizó en prosa.
- Frases de transición en cada objetivo son más largas de lo necesario.
- **Acción:** recortar ~50 palabras en frases introductorias de cada ítem.

---

## Tipo 5 — Conclusiones que parafrasean resultados ya presentados

- **Conclusión 3** es casi copia literal del Resumen ejecutivo (mismos números, mismo orden).
- Las conclusiones deben *interpretar* resultados, no repetirlos.
- **Acción:** reescribir Conclusión 3 enfocándola en implicancias, no en reporte de cifras. Recortable en ~35%.

---

## Ranking de secciones por % de ineficiencia

| % inefic. | Palabras recuperables | Sección |
|---|---|---|
| 41% | 450 | Cap I — 1.4.8 Crítica al CAPM en MYPEs |
| 30% | 210 | Cap I — 1.4.1 Pecking Order |
| 29% | 140 | Cap I — 1.2 Justificación académica |
| 28% | 180 | Cap I — 1.4.2 Teoría de Agencia |
| 26% | 180 | Cap I — 1.4.4 VBM / EVA |
| 25% | 140 | Cap I — 1.4.7 Altman Z-Score |
| 25% | 55  | Resumen (ES) |
| 25% | 50  | Abstract (EN) |
| 24% | 130 | Cap I — 1.1 Planteamiento del Problema |
| 21% | 200 | Cap III — Metodología y Diseño SROD |
| 20% | 120 | Cap VIII — Conclusiones |
| 17% | 120 | Cap VIII — Recomendaciones |

---

## Acciones prioritarias (orden por impacto)

1. [ ] Condensar sección 1.4.8 (CAPM) en tabla de evidencias → ahorra ~450 palabras
2. [ ] Eliminar frases-puente repetidas en Cap I ("Este hallazgo contextualiza…") → ~120 palabras
3. [ ] Reescribir Conclusión 3 para que interprete en vez de repetir el Resumen → ~100 palabras
4. [ ] Unificar las 4 menciones del Altman Z" rango 5.71–7.82 en una sola referencia cruzada → ~60 palabras
5. [ ] Eliminar doble mención de Briano-Turrent (2017) en 1.1 → ~80 palabras
6. [ ] Acortar frases introductorias en Objetivos (1.3) e Hipótesis (1.6) → ~50 palabras
