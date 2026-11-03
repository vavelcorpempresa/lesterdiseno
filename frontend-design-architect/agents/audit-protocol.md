# Protocolo de transferencia y auditoría

## 7. PROTOCOLO DE ENTREGA ENTRE AGENTES

Cada transferencia debe incluir:

1. Identificador de tarea.
2. Versión de especificación.
3. Responsable de origen.
4. Responsable de destino.
5. Objetivo.
6. Archivos afectados.
7. Componentes involucrados.
8. Criterios de diseño.
9. Criterios de aceptación.
10. Evidencias disponibles.
11. Problemas conocidos.
12. Estado de aprobación.

El sistema debe mantener trazabilidad entre las decisiones de Claude, el código de ChatGPT, la implementación de Antigravity y Gemini y los resultados de auditoría.

Las herramientas de cada agente deben utilizarse únicamente cuando estén realmente disponibles.

Si no existe integración automática entre agentes, generar un paquete de transferencia que pueda ser entregado manualmente.

---

## 8. PRUEBAS OBLIGATORIAS

### Pruebas visuales

- Consistencia tipográfica.
- Alineación.
- Espaciado.
- Colores.
- Estados.
- Composición.
- Ausencia de desbordamientos.
- Comparación con referencias aprobadas.

### Pruebas responsive

Comprobar al menos:

- 320 px.
- 375 px.
- 390 px.
- 430 px.
- 768 px.
- 1024 px.
- 1280 px.
- 1440 px.

Verificar también alturas reducidas, cambios de orientación y tamaños intermedios.

### Pruebas funcionales

- Navegación.
- Botones.
- Formularios.
- Validaciones.
- Menús.
- Modales.
- Interacciones táctiles.
- Estados de carga y error.

### Pruebas técnicas

- Compilación.
- Lint.
- Tipado.
- Pruebas de componentes.
- Pruebas de integración.
- Pruebas end-to-end donde corresponda.
- Accesibilidad automatizada y manual.
- Rendimiento.

Ningún agente debe declarar una prueba superada si no la ejecutó o no recibió evidencia verificable de su ejecución.

---

## 9. CRITERIOS DE ACEPTACIÓN

Para declarar APROBADO el frontend:

- Todos los requisitos críticos deben cumplirse.
- No deben existir errores críticos de compilación.
- No deben existir fallos bloqueantes de navegación.
- No deben existir incumplimientos conocidos de accesibilidad de severidad crítica.
- Las vistas obligatorias deben funcionar en los tamaños definidos.
- Los componentes deben respetar los tokens aprobados.
- Las desviaciones visuales deben estar justificadas y aprobadas.
- La auditoría de Claude debe estar documentada.

La calidad no se evaluará únicamente mediante una puntuación promedio: los requisitos críticos son condiciones de aprobación independientes.

---

## 10. ENTREGABLES

Generar, según el alcance y los permisos disponibles:

- `SKILLS_DESIGN_INVENTORY.md`
- `FRONTEND_ARCHITECTURE.md`
- `DESIGN_SYSTEM.md`
- `RESPONSIVE_SPEC.md`
- `COMPONENT_INVENTORY.md`
- `IMPLEMENTATION_PLAN.md`
- `IMPLEMENTATION_REPORT.md`
- `TEST_REPORT.md`
- `CHATGPT_QA_REPORT.md`
- `CLAUDE_DESIGN_AUDIT.md`

Los documentos deben reflejar el estado real del trabajo.

No generar informes que afirmen pruebas, implementaciones o auditorías inexistentes.

---
