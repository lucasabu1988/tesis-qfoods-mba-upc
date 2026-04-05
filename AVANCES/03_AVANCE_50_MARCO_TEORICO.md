# AVANCE 50% — MARCO TEÓRICO Y TRABAJO DE CAMPO INICIADO
## Tesis MBA UPC — Etapa 3: Seminario de Investigación III

---

**Título:**  
Diseño, Validación e Implementación de un Sistema de Ratios Orientado a la Decisión (SROD) en Q Foods

**Autor:** Lucas Abugattas  
**Programa:** MBA — UPC  
**Fecha:** Abril 2026  
**Estado:** Avance 50% — Marco teórico completo + Recolección de datos iniciada

---

## SECCIÓN I: MARCO TEÓRICO COMPLETO

### Capítulo 1: Análisis Financiero en PYMEs

#### 1.1 La brecha analítica en las PYMEs peruanas

Las PYMEs representan más del 96% del tejido empresarial peruano y generan aproximadamente el 85% del empleo privado en el país (PRODUCE, 2023). Sin embargo, la gran mayoría opera sin sistemas formales de análisis financiero, tomando decisiones basadas en flujo de caja inmediato antes que en diagnósticos integrales de su posición financiera.

Esta brecha tiene tres dimensiones: (1) **metodológica**, dado que los sistemas de ratios estándar están calibrados para empresas cotizadas con estructuras de capital más complejas; (2) **informacional**, ya que muchas PYMEs no mantienen contabilidad en formato NIIF ni producen estados financieros auditados; y (3) **operativa**, porque los gerentes-propietarios de PYMEs raramente tienen formación financiera avanzada.

#### 1.2 Dimensiones del análisis de ratios financieros

El análisis de ratios financieros se organiza en cuatro dimensiones clásicas:

**Liquidez:** Mide la capacidad de la empresa para cumplir con sus obligaciones de corto plazo sin comprometer la continuidad operativa.
- *Razón corriente* = Activo corriente / Pasivo corriente
- *Prueba ácida* = (Activo corriente − Inventarios) / Pasivo corriente
- *Razón de caja* = Efectivo / Pasivo corriente

**Solvencia y endeudamiento:** Evalúa la solidez de la estructura de capital y la capacidad de servicio de deuda.
- *Razón de deuda* = Pasivo total / Activo total
- *Deuda/Patrimonio* = Pasivo total / Patrimonio
- *Cobertura de intereses* = EBIT / Gastos financieros

**Rentabilidad:** Mide la eficiencia en la generación de utilidades relativa a ventas, activos o patrimonio.
- *ROA* = Utilidad neta / Activo total
- *ROE* = Utilidad neta / Patrimonio
- *Margen bruto, operativo y neto*

**Eficiencia operativa:** Evalúa la velocidad de rotación de los activos operativos clave.
- *Rotación de inventarios* = Costo de ventas / Inventario promedio
- *Días de cobro* = (Cuentas por cobrar / Ventas) × 365
- *Ciclo de conversión de efectivo* = Días inventario + Días cobro − Días pago

---

### Capítulo 2: Economic Value Added (EVA)

#### 2.1 Fundamentos conceptuales

El EVA (Economic Value Added), desarrollado y popularizado por Stern Stewart & Co. (1991), supera las limitaciones del análisis contable tradicional al incorporar el costo de oportunidad del capital propio. Su premisa central es que una empresa crea valor solo cuando su retorno sobre el capital invertido supera el costo de ese capital.

**Fórmula base:**
```
EVA = NOPAT − (WACC × Capital Invertido)
```
Donde:
- **NOPAT** = Net Operating Profit After Taxes (utilidad operativa después de impuestos)
- **WACC** = Weighted Average Cost of Capital (costo promedio ponderado de capital)
- **Capital Invertido** = Activos operativos netos (activos totales − pasivos operativos sin costo)

#### 2.2 Estimación del WACC para PYMEs

La estimación del WACC en PYMEs presenta desafíos metodológicos específicos, dado que no cotizan en bolsa y no tienen un beta observable. La literatura propone tres alternativas:

1. **Beta de empresas comparables:** Usar el beta desapalancado de empresas comparables cotizadas en el sector, re-apalancar con la estructura de capital de la PYME.
2. **CAPM ajustado:** Incorporar una prima de riesgo por tamaño (small cap premium) y una prima de riesgo específico de la empresa.
3. **Build-Up Method:** Sumar la tasa libre de riesgo + prima de mercado + prima de industria + prima de tamaño + prima específica.

Para el caso de Q Foods, se utilizará el **método de empresas comparables** con datos de Damodaran (2025) para el sector Food Processing - Emerging Markets, ajustado por el riesgo país de Perú.

#### 2.3 Interpretación del EVA en contexto PYME

Un EVA negativo no implica necesariamente que la empresa esté destruyendo valor en términos absolutos, sino que el retorno no cubre el costo de oportunidad del capital. Para PYMEs con restricciones de financiamiento, un EVA negativo puede coexistir con utilidades contables positivas, lo que genera una señal de alerta que el análisis contable tradicional no captura.

---

### Capítulo 3: Modelo Altman Z-Score

#### 3.1 Evolución del modelo

Edward Altman desarrolló en 1968 el primer modelo discriminante multivariado para predecir quiebras empresariales, utilizando una muestra de 66 empresas manufactureras cotizadas en EE.UU. El modelo original (Z-Score) fue diseñado para empresas manufactureras cotizadas. Posteriormente, Altman (1983, 1995) desarrolló versiones adaptadas:

- **Z'-Score:** Para empresas no cotizadas (sustituye el valor de mercado del equity por el valor en libros)
- **Z''-Score:** Para empresas no manufactureras y de mercados emergentes

Given the context of Q Foods (PYME no cotizada, sector alimentario, mercado emergente), se aplicará la versión **Z''-Score** con los ajustes sugeridos por Altman para mercados emergentes.

#### 3.2 Modelo Z''-Score (Altman para no cotizadas y emergentes)

```
Z'' = 6.56·X1 + 3.26·X2 + 6.72·X3 + 1.05·X4
```
Donde:
- **X1** = Capital de trabajo / Activos totales
- **X2** = Utilidades retenidas / Activos totales
- **X3** = EBIT / Activos totales
- **X4** = Patrimonio en libros / Pasivo total

**Zonas de clasificación:**
- Z'' > 2.6 → Zona segura
- 1.1 < Z'' < 2.6 → Zona gris (riesgo moderado)
- Z'' < 1.1 → Zona de distress financiero

---

### Capítulo 4: Pecking Order Theory

#### 4.1 Postulados fundamentales

Myers y Majluf (1984) argumentan que las asimetrías de información entre gerentes y mercado generan una jerarquía en las preferencias de financiamiento:

1. **Financiamiento interno** (utilidades retenidas, depreciación)
2. **Deuda financiera** (banco, bonos)
3. **Capital externo** (emisión de acciones)

Esta jerarquía implica que las empresas no tienen una estructura de capital objetivo óptima, sino que la estructura de capital observada es el resultado acumulado de las decisiones de financiamiento históricas.

#### 4.2 Aplicación en PYMEs

En PYMEs, la Pecking Order Theory tiene mayor poder predictivo que la Trade-Off Theory (Modigliani-Miller), principalmente porque:
- Las asimetrías de información son más severas
- El acceso a mercados de capitales es limitado o inexistente
- Los costos de emisión de equity son proporcionalmente más altos
- La relación banco-empresa tiene características relacionales antes que transaccionales

---

## SECCIÓN II: ESTADO DEL TRABAJO DE CAMPO

### Datos Recolectados (al 50% de avance)

- ✅ Estados financieros de Q Foods: períodos 2019–2024 (Balance General, Estado de Resultados, Flujo de Caja)
- ✅ Benchmarks sectoriales: ratios promedio del sector alimentario peruano (fuente: Damodaran, SBS)
- ✅ Tasa libre de riesgo Perú (bono soberano 10 años)
- ✅ Prima de riesgo país (EMBI+)
- ✅ Beta desapalancado sector Food Processing - Emerging Markets (Damodaran 2025)
- ✅ Entrevista inicial con gerencia general de Q Foods completada
- 🔄 Entrevista con gerencia financiera: en proceso
- 🔄 Cálculo del WACC: en proceso
- ⏳ Cálculo EVA: pendiente
- ⏳ Cálculo Altman Z''-Score: pendiente
- ⏳ Diseño del SROD: pendiente

---

## Referencias del Marco Teórico

- Altman, E. I. (1968). Financial ratios, discriminant analysis and the prediction of corporate bankruptcy. *Journal of Finance*, 23(4), 589–609.
- Altman, E. I., & Hotchkiss, E. (2005). *Corporate Financial Distress and Bankruptcy* (3rd ed.). Wiley.
- Damodaran, A. (2025). *Damodaran Online: Data*. NYU Stern. http://pages.stern.nyu.edu/~adamodar/
- Gitman, L. J., & Zutter, C. J. (2012). *Principios de Administración Financiera* (13th ed.). Pearson.
- Myers, S. C., & Majluf, N. S. (1984). Corporate financing and investment decisions when firms have information that investors do not have. *Journal of Financial Economics*, 13(2), 187–221.
- PRODUCE (2023). *Anuario Estadístico Industrial, MIPYME y Comercio Interno 2023*. Ministerio de la Producción del Perú.
- Ross, S. A., Westerfield, R. W., & Jordan, B. D. (2019). *Fundamentals of Corporate Finance* (12th ed.). McGraw-Hill.
- Stewart, G. B. (1991). *The Quest for Value*. HarperBusiness.
