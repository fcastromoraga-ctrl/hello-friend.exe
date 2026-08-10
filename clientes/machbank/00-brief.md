# MACHBANK — Brief de entrada

**Estado:** `BLOQUEADO PARCIAL` — diagnóstico preliminar construido con fuentes
públicas. Faltan datos internos para cerrar Bloque 2 en adelante.
**Última actualización:** 2026-08-10

---

## 1. Identificación

| Campo | Dato | Fuente |
|---|---|---|
| Marca | MACHBANK (antes MACH) | Público |
| Dominio | machbank.cl / somosmach.com | Público |
| Propietario | Banco de Crédito e Inversiones (Bci) | DF, Fintechile |
| Origen | Fundada 2017 como billetera digital dentro de Bci | Público |
| Regulación | CMF, vía Bci | Público |
| Core bancario | Mambu | LatamFintech |
| Base de usuarios | 4,2 millones | DF (ene-2025) |
| Tagline vigente | "La banca digital que crece contigo" | machbank.cl |

## 2. Hitos que definen el problema estratégico

| Fecha | Hito |
|---|---|
| 2017 | Nace MACH como billetera de prepago. Producto estrella de Bci. |
| 2025-01-20 | Anuncio de cambio de nombre **MACH → MACHBANK** + lanzamiento tarjeta de crédito. |
| 2025 S2 | Lanzamiento de créditos de consumo. Meta declarada: 50.000 tarjetas de crédito en 2025. |
| 2026-01 | Lanzamiento tarjeta de crédito virtual. |
| 2026 | Migración masiva de prepago → Cuenta Corriente con débito Visa. |
| 2026-12-31 | Fecha límite de la promesa "$0 mantención para siempre". |

## 3. Oferta verificada

| Producto | Condición conocida |
|---|---|
| Cuenta corriente | Apertura gratis, sin costo de mantención. $0 para siempre si se registra antes del 31-dic-2026. |
| Tarjeta de débito Visa | Física y virtual. |
| Tarjeta de crédito | Lanzada ene-2025; versión virtual ene-2026. |
| Créditos de consumo | Desde S2-2025. |
| Cuenta Futuro | Ahorro con intereses desde $1.000. |
| Transferencias | Sin costo a cualquier banco nacional. |
| Cajeros | Giro sin cargo adicional en toda la red. |
| Pago de servicios | +150 servicios. |
| Cashback | Vía programa BCI Plus+. |

## 4. Brechas abiertas — bloquean el avance

Ordenadas por impacto sobre el entregable. Las cuatro primeras impiden cerrar el
Bloque 2 (Brand Core) con rigor.

| # | Brecha | Por qué bloquea | Prioridad |
|---|---|---|---|
| 1 | **¿Cuál es el problema de negocio real que motiva este trabajo?** ¿Adquisición estancada, churn post-migración, baja conversión a crédito, canibalización con Bci, o percepción de marca? | Sin esto, cualquier plataforma de marca es decorativa. Es el único dato del que no puedo prescindir. | 🔴 Crítica |
| 2 | **¿Cuál es tu rol y tu mandato?** ¿Trabajas en MACHBANK, en Bci, en agencia, o es un ejercicio de análisis/pitch? | Define si el entregable debe ser ejecutable internamente o persuasivo hacia afuera. Cambia por completo la forma. | 🔴 Crítica |
| 3 | **Métricas base:** MAU vs. usuarios registrados, ARPU, CAC por canal, tasa de activación de la cuenta corriente, % de base que tomó crédito, churn post-migración. | Sin baseline no hay forma de defender la estrategia ante finanzas ni de medir si funcionó. | 🔴 Crítica |
| 4 | **Segmentación real de la base.** ¿Quiénes son los 4,2M? Edad, bancarización previa, ingreso, uso principal. | El posicionamiento se construye sobre un segmento, no sobre un promedio. | 🔴 Crítica |
| 5 | ¿Existe investigación cualitativa reciente (brand tracking, focus, NPS por segmento)? | Evitaría reconstruir insights desde fuentes públicas. | 🟠 Alta |
| 6 | ¿Qué tan negociable es la marca? ¿Se puede revisar el nombre "MACHBANK", o es una decisión cerrada? | Determina si el diagnóstico del §4.1 del análisis es accionable o informativo. | 🟠 Alta |
| 7 | ¿Qué relación de arquitectura se busca con Bci a 3 años: endoso permanente, independización, o absorción? | Bloquea la decisión de arquitectura de marca. | 🟠 Alta |
| 8 | Restricciones de presupuesto, plazo y capacidad de ejecución. | Una estrategia que la operación no sostiene es un entregable inútil. | 🟡 Media |

## 5. Incógnitas de mercado a verificar

| Incógnita | Estado | Cómo se resuelve |
|---|---|---|
| Situación de licencia bancaria de Tenpo en Chile | **Sin verificar.** Afecta directamente el claim "primer banco 100% digital". | Consulta registro CMF. |
| Cifras de MAU real vs. usuarios registrados de los competidores | Sin verificar | Reportes CMF / memorias anuales. |
| Desempeño de la meta de 50.000 tarjetas de crédito 2025 | Sin verificar | Dato interno o memoria Bci. |
| Penetración post-migración a cuenta corriente | Sin verificar | Dato interno. |

## 6. Nota de acceso a fuentes

El proxy de red de este entorno bloquea el acceso directo a `machbank.cl`,
`apps.apple.com` y `tasas.cl`. El diagnóstico se construyó con resultados de
búsqueda y prensa especializada. **Consecuencia:** el análisis de tono de voz y
copy literal del sitio está pendiente. Si pegas el copy de la home, el
onboarding y 3–4 pantallas de la app, cierro el Bloque 3 con material real en
lugar de inferencia.
