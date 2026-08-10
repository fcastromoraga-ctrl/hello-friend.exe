# Segundo Cerebro — Brand Strategy

Repositorio de trabajo estratégico de marca. Persistente entre sesiones.

## Cómo funciona

`CLAUDE.md` se carga automáticamente al abrir cualquier sesión de Claude Code
en este repositorio. No hay que volver a pegar instrucciones: el rol, las
metodologías y las restricciones ya están activos.

## Estructura

| Ruta | Contenido |
|---|---|
| `CLAUDE.md` | Rol, metodologías, reglas de ejecución y convenciones. |
| `frameworks/` | Plantillas reutilizables, una por bloque metodológico. |
| `clientes/` | Un expediente por marca. |

## Expedientes activos

| Marca | Estado | Ruta |
|---|---|---|
| **MACHBANK** (`machbank.cl`) | Diagnóstico preliminar — brechas abiertas | [`clientes/machbank/`](clientes/machbank/) |

## Flujo de trabajo por marca

```
00-brief.md  →  01-diagnostico.md  →  02-brand-core.md
                                            ↓
        05-activacion.md  ←  04-messaging.md  ←  03-voz.md
```

Cada bloque depende del anterior. Saltarse el diagnóstico para llegar al tagline
produce mensajería sin fundamento — el error más común y más caro.

`decisiones.md` corre en paralelo a todo el flujo: registra qué se cerró, cuándo
y con qué fundamento. Se agrega, no se reescribe.

## Estados de un entregable

| Estado | Significado |
|---|---|
| `BORRADOR` | Propuesta abierta a discusión. |
| `EN VALIDACIÓN` | Entregado al usuario, pendiente de respuesta. |
| `APROBADO` | Cerrado y registrado en `decisiones.md`. |
| `BLOQUEADO` | Requiere un dato que no está disponible. Brecha en `00-brief.md`. |
