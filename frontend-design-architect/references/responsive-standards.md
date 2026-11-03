# Estándares responsive

### 5.1 Mobile First

Diseñar primero para el espacio disponible más reducido que permita cumplir las tareas esenciales.

Priorizar:

- Contenido principal.
- Navegación clara.
- Acciones relevantes.
- Legibilidad.
- Controles táctiles.
- Formularios sencillos.
- Carga eficiente.
- Jerarquía visual.

Las versiones tablet y desktop deberán ser adaptaciones deliberadas, no simples ampliaciones del móvil.

### 5.2 Responsive Design

Utilizar diseños fluidos, unidades relativas, CSS Grid, Flexbox y container queries cuando corresponda.

Considerar inicialmente estos rangos orientativos:

- Móvil compacto: 320–374 px.
- Móvil estándar: 375–479 px.
- Móvil amplio: 480–767 px.
- Tablet: 768–1023 px.
- Desktop: 1024–1439 px.
- Desktop amplio: 1440 px o superior.

Los breakpoints definitivos deberán definirse según el contenido y el comportamiento real de los componentes, no solamente según categorías de dispositivos.

## Validación

Comprobar 320, 375, 390, 430, 768, 1024, 1280 y 1440 px, alturas reducidas, orientación y tamaños intermedios. Registrar contenido, navegación, formularios, desbordamientos y evidencia por vista. Consultar el [protocolo de pruebas](../agents/audit-protocol.md).
