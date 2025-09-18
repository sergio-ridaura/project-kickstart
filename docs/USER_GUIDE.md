# Guía de Usuario

Esta guía proporciona instrucciones detalladas para usuarios finales sobre cómo utilizar la aplicación de manera efectiva.

Para una visión general del proyecto consulta el [Léeme](../README.md) principal, y si eres desarrollador y quieres contribuir al proyecto, revisa la [Guía de Desarrollo](DEVELOPMENT_GUIDE.md).

## Personalización

Esta sección te guía paso a paso para adaptar la plantilla a cualquier tipo de proyecto, siguiendo un proceso estructurado de 3 fases.

```
┌───────────┐    ┌───────────────┐    ┌────────────┐
│ Propuesta │ -> │ Planificación │ -> │ Desarrollo │
└───────────┘    └───────────────┘    └────────────┘
```

### 1. Propuesta

Para empezar, clona la plantilla y organiza su estructura siguiendo las indicaciones del [Léeme](../README.md). Este paso es clave para separar la documentación original de la plantilla y sentar una base limpia para tu proyecto.

Una vez configurado el entorno, utiliza los documentos de la plantilla como referencia para crear la documentación de tu propio proyecto.

Ahora que has preparado el entorno, es momento de conceptualizar la idea central de tu proyecto. En esta etapa, te enfocarás en definir claramente el problema a resolver, la solución que propones y el alcance de la implementación.

- **[Propuesta](PROPOSAL.md)**: Crea este documento para definir el problema que resuelves, la solución propuesta y el alcance del proyecto. Es el punto de partida que valida si la idea tiene sentido y merece la pena desarrollarla.
- **[Licencia](../LICENSE)**: Decide qué licencia usar para tu proyecto. La plantilla incluye MIT por defecto, pero puedes cambiarla según tus necesidades.

Antes de continuar, es esencial que el equipo de desarrollo revise, participe activamente y apruebe la propuesta para asegurar su viabilidad técnica y alineación con los objetivos del proyecto.

### 2. Planificación

Una vez validada la propuesta, organiza el proyecto y establece cómo se ejecutará y medirá el éxito.

- **[Plan de Acción](ACTION_PLAN.md)**: Define las fases, hitos, recursos necesarios y cronograma del proyecto. Establece cómo medirás el éxito y qué criterios usarás para validar los resultados.
- **[Tareas](tasks/)**: Desglosa el trabajo en tareas específicas y manejables. Cada tarea debe tener criterios de aceptación claros y estimaciones de tiempo.
- **[Validación](VALIDATION.md)**: Define los criterios de aceptación y el proceso para verificar que los resultados cumplen con los objetivos establecidos en la propuesta.

Continúa con el resto de tareas de la plantilla. Si has seguido los pasos anteriores, las tareas de configuración inicial ya estarán completadas.

- **[Créditos](CREDITS.md)**: Reconoce las contribuciones, herramientas utilizadas y agradecimientos del proyecto.
- **[README.md](../README.md)**: Crea el documento principal de tu proyecto que explique qué hace, cómo instalarlo y cómo usarlo. Este será el primer documento que vean los usuarios.
- **[Código de Conducta](CODE_OF_CONDUCT.md)**: Establece las normas de comportamiento y convivencia para la comunidad del proyecto.
- **[Guía de Seguridad](SECURITY.md)**: Define las políticas de seguridad, cómo reportar vulnerabilidades y procedimientos de respuesta.
- **[Guía de Contribución](CONTRIBUTING.md)**: Define cómo otros desarrolladores pueden contribuir a tu proyecto, incluyendo estándares de código y proceso de revisión.
- **[Guía de Usuario](USER_GUIDE.md)**: Documenta cómo los usuarios finales deben utilizar tu aplicación o producto, incluyendo ejemplos prácticos y casos de uso.
- **[Estructura del Proyecto](STRUCTURE.md)**: Documenta la arquitectura y organización de archivos y carpetas de tu proyecto.
- **[Guía de Desarrollo](DEVELOPMENT_GUIDE.md)**: Establece los estándares técnicos, convenciones de código y metodología de desarrollo para el equipo.

Es fundamental que todo el equipo revise y valide colectivamente el plan de acción, incluyendo las tareas definidas, los criterios de éxito y la metodología de validación, así como toda la documentación creada. Esta revisión colaborativa asegura la viabilidad técnica, confirma la alineación con los objetivos del proyecto y garantiza el compromiso de todos los miembros antes de proceder a la siguiente fase.

### 3. Desarrollo

Ya puedes comenzar con las tareas personalizadas que has añadido al [Plan de Acción](ACTION_PLAN.md).

Recuerda que la documentación es un componente vivo del proyecto. Cada vez que se realicen cambios significativos en la documentación y el código, es una buena práctica revisar y actualizar todos los documentos relevantes, para asegurar que la información se mantenga precisa y útil para todo el equipo.

Mantén actualizado el [Léeme](../README.md), el [Plan de acción](ACTION_PLAN.md) y el registro de [Tareas](tasks/).

La [Validación](VALIDATION.md) se ejecuta al finalizar el proyecto o al liberar una versión estable (release), típicamente en la versión 1.0.0. Este documento ayuda a que todos los objetivos y criterios de aceptación definidos inicialmente se han cumplido satisfactoriamente.

Cuando ya no necesites los archivos de la plantilla, puedes eliminarlos de forma segura.

## Preguntas Frecuentes

**¿Puedo usar esta plantilla para cualquier lenguaje de programación?**
¡Sí! La plantilla es agnóstica al lenguaje. Simplemente empieza a añadir tu código en la carpeta `src/`.

**¿Qué hago si determino que el proyecto no es viable?**
Si concluyes que el proyecto no es viable, puedes detener su desarrollo en cualquier momento. Utiliza el documento de **[Propuesta](PROPOSAL.md)** para documentar el análisis y la decisión, manteniendo un registro claro para el equipo.

**¿En qué orden debo crear los documentos?**
Sigue las 3 fases: primero la Propuesta, luego la Planificación y crea toda la documentación antes del Desarrollo.

**¿Puedo saltarme alguna de las 3 fases?**
Recomendamos seguir todas las fases, pero puedes adaptar el proceso según el tamaño y complejidad de tu proyecto.

**¿Qué hago si no quiero toda la documentación?**
Puedes eliminar o modificar los documentos que no necesites. Sin embargo, te recomendamos mantener al menos `README.md`, `LICENSE` y `CONTRIBUTING.md` para tener un proyecto bien documentado.

**¿Qué documentos son obligatorios vs opcionales?**
`README.md` y `LICENSE` son esenciales. El resto puedes adaptarlos según las necesidades de tu proyecto.

**¿Cómo reporto un problema o sugiero una mejora para la plantilla?**
Tienes varias opciones para reportar problemas o sugerir mejoras:

- **Issues**: Abre un [issue](https://github.com/sergio-ridaura/project-kickstart/issues) para reportar bugs o solicitar funcionalidades
- **Contribuciones**: Consulta la [Guía de Contribución](CONTRIBUTING.md) para el proceso completo de colaboración
- **Vulnerabilidades**: Para temas de seguridad, revisa el [Documento de Seguridad](SECURITY.md)

¡Gracias por usar Project Kickstart! Esperamos que te ayude a construir proyectos increíbles.
