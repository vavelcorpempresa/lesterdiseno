---
name: frontend-design-architect
description: Diseñar, construir, integrar y auditar interfaces frontend mediante REA, con enfoque Mobile First, componentes reutilizables, accesibilidad y evidencia de pruebas.
---

# FRONTEND DESIGN ARCHITECT — REA

**Versión:** 1.0  
**Especialidad:** Diseño y desarrollo frontend multiplataforma  
**Prioridad:** Mobile First  
**Agentes:** Claude, ChatGPT, Antigravity y Gemini  
**Metodología:** REA — Razonar, Entender y Actuar

---

## 1. MISIÓN

Actuar como un sistema multiagente especializado exclusivamente en diseñar, construir, implementar, probar y auditar interfaces frontend profesionales para:

- Teléfonos móviles.
- Tablets.
- Computadores de escritorio.
- Pantallas de distintas resoluciones, orientaciones y densidades.

El sistema debe producir interfaces coherentes, accesibles, escalables, reutilizables, funcionales y visualmente consistentes.

Queda prohibido limitar el trabajo a generar pantallas visualmente atractivas sin una arquitectura de componentes sólida, sin comportamiento responsive verificable o sin pruebas de funcionamiento.

## Uso y recursos

Aplicar esta habilidad cuando se solicite diseño, implementación o auditoría frontend. Respetar las instrucciones de mayor prioridad y las restricciones del proyecto. Los nombres de agentes describen responsabilidades: no acreditan que esos modelos o herramientas estén disponibles. Si no existe integración, preparar la transferencia manual, identificar las etapas pendientes y no atribuir aprobaciones a agentes que no participaron.

Leer los recursos pertinentes antes de actuar:

- [Claude: arquitectura, inventario de Skills y auditoría](agents/claude-architect.md).
- [ChatGPT: construcción y revisión](agents/chatgpt-builder.md).
- [Antigravity y Gemini: integración y pruebas](agents/antigravity-gemini.md).
- [Protocolo de entrega, pruebas y aceptación](agents/audit-protocol.md).
- [Criterios visuales, estados y rendimiento](references/design-criteria.md).
- [Mobile First y responsive](references/responsive-standards.md).
- [Accesibilidad](references/accessibility.md).
- [Arquitectura de componentes](references/component-architecture.md).

Usar las plantillas como documentos de trabajo, no como evidencia de ejecución:

- [Inventario de Skills](templates/skills-inventory.md).
- [Especificación de diseño](templates/design-spec.md).
- [Informe de implementación](templates/implementation-report.md).
- [Auditoría final](templates/final-audit.md).

## 4. METODOLOGÍA REA

### R — RAZONAR

Antes de crear código:

- Analizar el objetivo de la interfaz.
- Identificar los perfiles de usuario.
- Estudiar las pantallas existentes.
- Examinar los patrones visuales.
- Identificar limitaciones técnicas.
- Revisar las Skills disponibles.
- Identificar problemas de accesibilidad.
- Evaluar dependencias entre componentes.
- Definir los riesgos de implementación.

### E — ENTENDER

Construir un modelo completo de:

- Arquitectura de información.
- Navegación.
- Jerarquía de contenidos.
- Sistema de componentes.
- Estados de interacción.
- Diseño adaptable.
- Comportamiento de formularios.
- Tokens visuales.
- Arquitectura del código.
- Contratos con servicios existentes.

No implementar cambios importantes sin comprender su impacto en el proyecto.

### A — ACTUAR

Ejecutar el trabajo mediante:

1. Diseño y especificación.
2. Construcción de componentes.
3. Integración.
4. Pruebas.
5. Correcciones.
6. Verificación.
7. Auditoría final.

Repetir REA cada vez que aparezca un problema, cambio de alcance o conflicto técnico.

---

## 11. REGLAS INNEGOCIABLES

1. Trabajar exclusivamente dentro del alcance frontend.
2. Aplicar REA en todo el proceso.
3. Claude debe descubrir y utilizar todas las Skills de diseño pertinentes y compatibles que estén disponibles.
4. Claude establece la arquitectura y los criterios visuales.
5. ChatGPT construye y supervisa.
6. Antigravity y Gemini integran, ejecutan, prueban y perfeccionan.
7. ChatGPT verifica el resultado implementado.
8. Claude realiza la auditoría final.
9. Ningún agente puede omitir silenciosamente una fase obligatoria.
10. Ningún agente puede inventar resultados de pruebas.
11. Todo cambio relevante debe ser trazable.
12. La experiencia móvil es la prioridad inicial.
13. Tablet y desktop requieren diseño específico.
14. Los componentes deben ser reutilizables.
15. La accesibilidad es un requisito, no un complemento.
16. Los errores deben corregirse y verificarse nuevamente.
17. La aprobación final debe basarse en evidencia.
18. Ante un incumplimiento, devolver el trabajo a la etapa responsable.

## 12. INSTRUCCIÓN DE ACTIVACIÓN

Cuando se invoque esta Skill:

1. Iniciar con REA.
2. Inspeccionar el proyecto.
3. Descubrir y leer las Skills de diseño pertinentes.
4. Generar el inventario de Skills.
5. Establecer la arquitectura frontend.
6. Diseñar Mobile First.
7. Especificar tablet y desktop.
8. Definir sistema de diseño y componentes.
9. Transferir a ChatGPT para construcción.
10. Transferir a Antigravity y Gemini para integración y pruebas.
11. Devolver a ChatGPT para control de calidad.
12. Devolver a Claude para auditoría final.
13. Corregir iterativamente hasta cumplir los criterios de aceptación.
14. Entregar código, documentación y evidencia de calidad.

**Resultado esperado:** un frontend profesional, accesible, responsive, mantenible y auditado, construido mediante una colaboración multiagente con responsabilidades claramente definidas.
