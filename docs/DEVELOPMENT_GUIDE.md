# Guía de Desarrollo

Esta guía explica cómo contribuir al desarrollo del proyecto de manera efectiva, cubriendo desde la configuración inicial hasta el flujo de trabajo completo para desarrolladores.

Para una visión general del proyecto consulta el [Léeme](../README.md) principal, y si quieres contribuir al proyecto, consulta la [Guía de Contribución](CONTRIBUTING.md).

## Metodología de Desarrollo

Este proyecto utiliza una metodología ágil adaptada para equipos pequeños o desarrolladores individuales, centrada en la claridad, la planificación y la calidad. El ciclo de vida del desarrollo se divide en 4 fases.

```
┌───────────┐    ┌───────────────┐    ┌────────────┐    ┌────────────┐
│ Propuesta │ -> │ Planificación │ -> │ Desarrollo │ -> │ Validación │
└───────────┘    └───────────────┘    └────────────┘    └────────────┘
```

### 1. Propuesta

Fase inicial donde se define el problema a resolver, se plantea una solución y se establece el alcance del proyecto. El objetivo es validar la viabilidad de una idea antes de invertir recursos en su desarrollo.

- **[Propuesta](PROPOSAL.md)**: Crea este documento para definir el problema que resuelves, la solución propuesta y el alcance del proyecto. Es el punto de partida que valida si la idea tiene sentido y merece la pena desarrollarla.
- **[Licencia](../LICENSE)**: Decide qué licencia usar para tu proyecto.

Antes de continuar, es esencial que el equipo de desarrollo revise, participe activamente y apruebe la propuesta para asegurar su viabilidad técnica y alineación con los objetivos del proyecto.

### 2. Planificación

Una vez aprobada la propuesta, se desglosa el trabajo en tareas concretas. Se crea un plan de acción detallado, se definen los criterios de aceptación y se estiman los plazos y recursos.

- **[Plan de Acción](ACTION_PLAN.md)**: Define las fases, hitos, recursos necesarios y cronograma del proyecto. Establece cómo medirás el éxito y qué criterios usarás para validar los resultados.
- **[Tareas](tasks/)**: Desglosa el trabajo en tareas específicas y manejables. Cada tarea debe tener criterios de aceptación claros y estimaciones de tiempo.
- **[Validación](VALIDATION.md)**: Define los criterios de aceptación y el proceso para verificar que los resultados cumplen con los objetivos establecidos en la propuesta.

Continúa con el resto de los documentos para establecer las reglas de desarrollo:

- **[Créditos](CREDITS.md)**: Reconoce las contribuciones, herramientas utilizadas y agradecimientos del proyecto.
- **[README.md](../README.md)**: Crea el documento principal de tu proyecto que explique qué hace, cómo instalarlo y cómo usarlo. Este será el primer documento que vean los usuarios.
- **[Código de Conducta](CODE_OF_CONDUCT.md)**: Establece las normas de comportamiento y convivencia para la comunidad del proyecto.
- **[Guía de Seguridad](SECURITY.md)**: Define las políticas de seguridad, cómo reportar vulnerabilidades y procedimientos de respuesta.
- **[Guía de Contribución](CONTRIBUTING.md)**: Define cómo otros desarrolladores pueden contribuir a tu proyecto, incluyendo estándares de código y proceso de revisión.
- **[Guía de Usuario](USER_GUIDE.md)**: Documenta cómo los usuarios finales deben utilizar tu aplicación o producto, incluyendo ejemplos prácticos y casos de uso.
- **[Estructura del Proyecto](STRUCTURE.md)**: Documenta la arquitectura y organización de archivos y carpetas de tu proyecto.
- **[Guía de Desarrollo](DEVELOPMENT_GUIDE.md)**: Establece los estándares técnicos, convenciones de código y metodología de desarrollo para el equipo.

### 3. Desarrollo

Fase de implementación donde el equipo escribe el código, actualiza la documentación y realiza las configuraciones necesarias, siguiendo los estándares y el plan definidos.

Recuerda que la documentación es un componente vivo del proyecto. Cada vez que se realicen cambios significativos en la documentación y el código, es una buena práctica revisar y actualizar todos los documentos relevantes, para asegurar que la información se mantenga precisa y útil para todo el equipo.

Mantén actualizado el [Léeme](../README.md), el [Plan de acción](ACTION_PLAN.md) y el registro de [Tareas](tasks/).

### 4. Validación

Etapa final donde se verifica que el resultado cumple con todos los criterios de aceptación y los objetivos del proyecto. En esta fase también se analizan los resultados para aprender tanto de los éxitos como de los errores, con el fin de mejorar en futuras iteraciones. Este proceso se realiza antes de un lanzamiento importante o al finalizar el proyecto.

## Estándares y Guías Técnicas

Para asegurar la coherencia, calidad y eficiencia en el desarrollo del proyecto, es imprescindible adherirse a los estándares y flujos de trabajo definidos en los siguientes documentos especializados. Esta sección actúa como un índice y recordatorio de las guías técnicas fundamentales.

- **Configuración del Entorno:** Para una puesta a punto rápida y correcta de tu espacio de trabajo local, consulta la sección de **[Inicio Rápido del README.md](../README.md#inicio-rápido)**. Aquí encontrarás las instrucciones detalladas para comenzar a desarrollar.

- **Estructura del Proyecto:** Comprender la organización interna del proyecto es clave. La **[Guía de Estructura](STRUCTURE.md)** detalla la disposición de directorios, archivos y componentes principales, facilitando la navegación y el mantenimiento.

- **Flujo de Trabajo de Contribución:** El proceso para realizar aportaciones al proyecto, desde la creación de ramas hasta la gestión de Pull Requests, se describe exhaustivamente en la **[Guía de Contribución](CONTRIBUTING.md)**. Este documento también cubre la estrategia de ramas, las convenciones de mensajes de commit y el ciclo de revisión.

  La rama `develop` es utilizada por los desarrolladores internos y se deriva de la rama `staging`. Esta rama está destinada a un desarrollo más flexible y experimental, permitiendo la integración de nuevas funcionalidades y pruebas iniciales antes de su consolidación. Además, facilita un entorno de trabajo cómodo para la comunicación y el desarrollo en el idioma materno.

- **Calidad y Estándares de Código:** Para mantener un código limpio, legible y consistente, las directrices de formato y las herramientas de análisis estático (`linting`) están especificadas en la sección "Calidad del Código" de la **[Guía de Contribución](CONTRIBUTING.md#calidad-del-código)**. Su cumplimiento es vital para la integración de nuevas funcionalidades.

El seguimiento riguroso de estas guías es un pilar fundamental para el éxito y la sostenibilidad del proyecto.

## Feedback y Mejoras

Esta guía es un documento vivo que evoluciona con el proyecto. Si tienes sugerencias para mejorarla, no dudes en abrir un [issue](https://github.com/sergio-ridaura/project-kickstart/issues) para discutirlo con el equipo.
