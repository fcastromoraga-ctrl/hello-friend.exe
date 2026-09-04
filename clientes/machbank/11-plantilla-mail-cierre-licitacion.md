# Plantilla — Mail de cierre de licitación (agencia no seleccionada)

**Estado:** `BORRADOR` · **Fecha:** 2026-09-04

Basada en el mail de referencia enviado en la licitación MACH 2023 (débito/cuenta
corriente, a TBWA). Mantiene su estructura y tono — directo, breve, sin cerrar
la puerta — y deja como variables lo que cambia de una licitación a otra.

Uso previsto: cierre de la licitación de campaña de Propuesta de Valor Integral
/ Abono Rem (`00-brief.md`, `decisiones.md` 2026-08-10) para las agencias no
seleccionadas. Reutilizable para cualquier licitación futura sin reescribir
la estructura.

---

## Variables a completar antes de enviar

| Variable | Qué va | En esta licitación |
|---|---|---|
| `[AGENCIA]` | Nombre de la agencia / equipo destinatario | `[SUPUESTO]` — pendiente de confirmar con el usuario |
| `[CAMPAÑA]` | Nombre de la campaña licitada | Propuesta de Valor Integral / Abono Rem |
| `[MOTIVO]` | Razón de la no selección, en una frase | Fit estratégico y ejecución de la propuesta |
| `[FIRMA]` | Nombre y cargo de quien envía | `[SUPUESTO]` — pendiente |

`[MOTIVO]` es el único bloque con opciones alternativas abajo — el resto del
mail no cambia según el motivo.

---

## Cuerpo del mail

```
Estimado team [AGENCIA]:

Quiero agradecerles por participar en el proceso de licitación para la
campaña [CAMPAÑA]. Valoramos el esfuerzo y el tiempo dedicado en la
preparación de su propuesta.

Lamentablemente, después de una revisión exhaustiva, hemos tomado la
decisión de seleccionar a otro proveedor para llevar a cabo la campaña.
[MOTIVO]

Quiero asegurarles que esta decisión no afecta nuestra percepción de su
capacidad y profesionalismo.

Agradecemos su participación en este proceso y esperamos poder contar con
ustedes en futuras oportunidades.

Muchas gracias.
Saludos!

[FIRMA]
```

---

## Opciones para `[MOTIVO]`

Reemplaza la línea `[MOTIVO]` del cuerpo por una de estas, según cuánto
detalle se quiera dar. Ninguna nombra a la agencia ganadora ni entra en
comparación directa — coherente con el criterio ya aplicado en el brief de
licitación de no exponer material de trabajo interno a un proceso
competitivo (`decisiones.md`, 2026-08-10).

**Opción A — general (equivalente a la referencia 2023):**
> Si bien su propuesta era sólida, la que seleccionamos finalmente cumplía
> mejor con nuestros requisitos específicos.

**Opción B — específica, con el motivo real de esta licitación:**
> La decisión se basó principalmente en el fit estratégico y la ejecución
> de la propuesta ganadora frente al desafío de negocio planteado.

Recomendación: usar la Opción B si la relación con la agencia amerita más
transparencia (por ejemplo, si se espera que compita en una próxima
licitación y le sirve el feedback para ajustar su approach); usar la
Opción A si se prefiere mantener el mail al mismo nivel de generalidad que
el precedente de 2023.

---

## Brechas abiertas

- Nombre(s) de la(s) agencia(s) no seleccionada(s) — sin confirmar.
- Si el mail se envía igual a todas las agencias no seleccionadas o se
  personaliza por agencia (ej. feedback distinto si el motivo real difirió
  entre ellas).
