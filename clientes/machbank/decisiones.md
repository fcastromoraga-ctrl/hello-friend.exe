# MACHBANK — Log de decisiones

Registro cronológico. **Se agrega, no se reescribe.** Una decisión revertida se
registra como entrada nueva que anula la anterior, dejando ambas visibles.

---

## 2026-08-10 — Apertura del expediente

| Campo | Detalle |
|---|---|
| **Decisión** | Abrir expediente MACHBANK y ejecutar Bloque 1 (Diagnóstico) con fuentes públicas. |
| **Fundamento** | El usuario aportó la marca sin brief interno. El diagnóstico de categoría y competencia es el único bloque construible sin datos internos. |
| **Estado** | Entregado. `01-diagnostico.md` en BORRADOR. |
| **Bloquea** | Bloques 2–5 hasta cerrar brechas 1–4 de `00-brief.md`. |

---

## Decisiones pendientes de validación del usuario

Ninguna de estas es una decisión tomada. Son propuestas del diagnóstico
esperando confirmación, rechazo o corrección.

| # | Propuesta | Origen | Estado |
|---|---|---|---|
| P1 | Abandonar la disputa por el liderazgo en la categoría "billetera digital" y reencuadrar la competencia. | §1.2 | ⏳ Sin validar |
| P2 | Descartar "primer banco 100% digital" como eje de posicionamiento — es un claim de cronología, no de posición. | §1.3 | ⏳ Sin validar |
| P3 | Descartar la gratuidad como diferenciador central; reencuadrarla como transparencia radical. | §1.3, §1.4-insight 4 | ⏳ Sin validar |
| P4 | Adoptar "historial crediticio para quien no lo tiene" como territorio de marca. | §1.3, §1.7 | ⏳ Sin validar — **requiere verificar el modelo de originación de crédito** |
| P5 | Arquitectura de dos niveles: "MACH" conversacional y de producto, "MACHBANK" institucional y regulatorio. | §1.5 | ⏳ Sin validar |
| P6 | Resolver la contradicción "agilidad fintech + 85 años de Bci" eligiendo una jerarquía explícita entre ambas. | §1.5 | ⏳ Sin validar |

---

## Riesgos registrados

| # | Riesgo | Severidad | Mitigación propuesta |
|---|---|---|---|
| R1 | Erosión del asset verbal "MACH" por el sufijo "BANK". Impacto silencioso sobre CAC, difícil de atribuir. | 🔴 Alta | P5 |
| R2 | La cohorte adquirida por "$0 hasta 31-dic-2026" puede tener retención estructuralmente peor que la base. | 🟠 Media | Medir churn de esa cohorte por separado desde ya. |
| R3 | El claim "primer banco 100% digital" depende de la situación regulatoria de Tenpo, sin verificar. | 🟠 Media | Verificar en registro CMF antes de cualquier uso en campaña. |
| R4 | El territorio P4 es falso si la originación de crédito usa scoring tradicional. | 🔴 Alta | Verificación interna antes de avanzar al Bloque 2. |
