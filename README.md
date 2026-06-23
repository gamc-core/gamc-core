# Gonzalo Montero · Arquitectura Simbiótica

> Artefactos públicos sobre continuidad, reconstrucción y ejecución estructurada.


Lo que suele perderse primero no es el resultado.

Meses después de una decisión todavía podemos ver qué ocurrió. Lo difícil suele ser reconstruir cómo ocurrió, qué cambió y qué permanece después del cambio.

Cuando esa capacidad se pierde aparecen problemas reales: conocimiento difícil de transferir, sistemas difíciles de mantener, decisiones difíciles de revisar y procesos difíciles de continuar.

Aunque los dominios cambien, ese problema suele repetirse.

De ahí surge una pregunta:


## ¿Qué debe permanecer para que un cambio siga siendo comprensible a través del tiempo?


Gran parte de mi trabajo consiste en construir mecanismos para registrar, cerrar y reconstruir ejecuciones después de que ocurrieron.

Las familias de artefactos publicadas aquí reúnen mecanismos construidos alrededor de distintas partes de esa pregunta.

Representan condiciones, ejecuciones y evidencias preservadas alrededor de problemas específicos.

Cada artefacto responde una pregunta acotada.


---

## Navegación

### ¿Qué debe ocurrir para que una estructura pueda persistir a través del tiempo?

[CE — Conditions of Executability](#ce--conditions-of-executability)

### ¿Cómo se comporta un sistema frente a distintos estados operativos?

[CPR — Conditions of Operational Regulation](#cpr--conditions-of-operational-regulation)

### ¿Cuándo una unidad puede considerarse un artefacto?

[AF — Artifact Qualification](#af--artifact-qualification)

### ¿Cómo puede observarse una ejecución después de que ocurrió?

[ENDO — Execution History](#endo--execution-history)


---

## CE — Conditions of Executability

CE reúne mecanismos mínimos para registrar, cerrar y continuar estructuras preservando su historia.

Cada artefacto responde una condición distinta:

**registro → cierre → continuidad**

| Artefacto | Pregunta |
|------------|------------|
| [CE-01](https://github.com/gamc-core/CE01-executable-structural-cell) | ¿Cómo registrar una unidad persistente y verificable? |
| [CE-02](https://github.com/gamc-core/CE02-Deterministic-Cycle-Engine) | ¿Cómo cerrar un conjunto de unidades bajo una condición explícita? |
| [CE-03](https://github.com/gamc-core/CE03-Generational-Structural-Runtime) | ¿Cómo continuar sin modificar lo ya cerrado? |


---

## CPR — Conditions of Operational Regulation

CPR reúne ejecuciones orientadas a observar cómo un regulador modifica su comportamiento frente a distintos estados operativos.

Cada artefacto preserva una condición operativa observada sobre un entorno Windows real.

**intervención → retirada → recuperación → saturación → reconsideración**

| Artefacto | Pregunta |
|------------|------------|
| [CPR-006](https://github.com/gamc-core/CPR-006-Homeostatic-regulation-with-structural-distinction) | ¿Dónde intervenir cuando la causa dominante no debe modificarse directamente? |
| [CPR-009](https://github.com/gamc-core/CPR-009-Baseline-relative-withdrawal) | ¿Cuándo debe retirarse una intervención? |
| [CPR-013](https://github.com/gamc-core/CPR-013-Confirmed-recovery-dissipative-memory) | ¿Cuándo puede considerarse recuperado un sistema? |
| [CPR-014](https://github.com/gamc-core/CPR-014-Operational-Saturation-Clamp) | ¿Cuándo deja de tener sentido seguir interviniendo? |
| [CPR-015](https://github.com/gamc-core/CPR-015-Post-clamp-meta-regulation) | ¿Cuándo debe reconsiderarse una detención previa? |


---

## AF — Artifact Qualification

AF explora las condiciones necesarias para que una unidad pueda calificarse como artefacto y los mecanismos utilizados para verificarlo.

**protocolo → validación**

| Artefacto | Pregunta |
|------------|------------|
| [AF01](https://github.com/gamc-core/AF01-Artifact_Structural_Protocol) | ¿Qué condiciones debe cumplir una unidad para calificar como artefacto? |
| [AF02](https://github.com/gamc-core/AF02-Artifact-Validator-Engine) | ¿Cómo verificar esas condiciones de forma determinista? |


---

## ENDO — Execution History

Ventana observable sobre la historia registrada por un sistema de ejecución persistente y cierre generacional.

Cada generación conserva registros, estados y artefactos derivados sin modificar lo ya cerrado.

**registro → generación → trayectoria**

| Repositorio | Pregunta |
|------------|------------|
| [ENDO](https://github.com/gamc-core/ENDO) | ¿Qué puede reconstruirse de una ejecución después de que fue registrada y cerrada? |


---

## Alcance

Los artefactos publicados permanecen accesibles en el estado en que fueron cerrados.

Esta capa pública muestra preguntas, mecanismos, ejecuciones y evidencia derivada.

No pretende describir la arquitectura completa ni la totalidad de sus procesos internos.

Tampoco pretende establecer modelos universales ni afirmar que las condiciones observadas sean válidas fuera de los contextos donde fueron ejecutadas.

Otras familias y mecanismos continúan en proceso de documentación o publicación.

---

GAMC
