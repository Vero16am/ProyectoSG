# Protocolo de gestión y monitoreo en GitHub | Ruta Joven San Gabriel

## 1. Unidad de trabajo y trazabilidad

El **README** explica el proyecto; cada **Issue** describe una actividad, riesgo o verificación; el **Project** permite administrar el trabajo de forma integrada. Los archivos de evidencia y el registro de decisiones permiten auditar el avance.

Cada Issue de actividad sigue la misma estructura: componente, actividad, responsable funcional, prioridad, entregable esperado, criterios de cierre, dependencias y estado actual. Además, debe quedar registrado el periodo de ejecución, los comentarios de avance y el enlace a la evidencia.

## 2. Estados del Project

| Estado | Regla de uso |
| --- | --- |
| Pendiente | Actividad registrada y aún sin ejecución |
| En curso | Trabajo iniciado; se registra qué se ha hecho |
| Bloqueada | Hay un impedimento identificable (por ejemplo, una dependencia sin cerrar) y una acción de desbloqueo |
| En revisión | Entregable disponible y a la espera de verificación del equipo |
| Finalizada | Criterio de cierre satisfecho y evidencia comprobada |

El estado **abierto/cerrado** de un Issue no equivale a estos cinco estados. El estado detallado se administra en el campo **Status** del Project.

## 3. Campos del Project

| Campo | Tipo sugerido | Valores o uso |
| --- | --- | --- |
| Status | Selección única | Cinco estados de la tabla anterior |
| Prioridad | Selección única | Alta, Media, Baja |
| Componente | Selección única | Planeación, Convocatoria e inscripción, Diagnóstico, Empleabilidad, Emprendimiento, Articulación institucional, Seguimiento y cierre, Riesgos, Control |
| Fecha de inicio | Fecha | Día de inicio acordado |
| Fecha objetivo | Fecha | Día límite acordado |

**Assignees** se gestiona desde cada Issue. Solo deben usarse cuentas con acceso real al repositorio.

## 4. Vistas

- **Tabla de gestión:** lista completa de Issues, responsables, prioridad, fechas, componente y estado.
- **Tablero de estados:** agrupado por Status para mover una actividad entre estados.
- **Cronograma / Roadmap:** construido con las fechas de inicio y objetivo acordadas.

Crear un Issue no lo añade automáticamente al Project; debe incorporarse desde el panel lateral del Issue o desde el Project.

## 5. Rutina semanal

1. Revisar actividades vencidas, próximas y bloqueadas.
2. Solicitar a cada responsable un avance concreto y el enlace a la evidencia.
3. Revisar dependencias antes de cambiar una fecha (por ejemplo, ACT-06 depende de ACT-03 y ACT-05).
4. Registrar en `Decisiones.md` toda decisión que altere alcance, secuencia o condiciones.
5. Verificar criterios de cierre y conservar la trazabilidad.

## 6. Formato breve de comentario de avance

**Corte:** AAAA-MM-DD  
**Avance comprobable:** qué se elaboró o revisó.  
**Dificultad / riesgo:** hecho observado, si existe.  
**Decisión / acción siguiente:** responsable y compromiso.  
**Evidencia:** enlace directo al documento o registro.

## 7. Cierre y reapertura

- Pasar un Issue a **Finalizada** sin verificar el producto da una apariencia engañosa de avance.
- Un Issue cerrado puede reabrirse si la evidencia falta, es inaccesible o incumple el criterio.
- Los productos con participantes deben indicar expresamente que los datos son simulados y usar códigos artificiales, nunca datos personales.

**Autoría:** equipo Ruta Joven San Gabriel.
