# Guía de Usuario

Esta guía explica cómo utilizar la aplicación de manera efectiva, cubriendo desde la configuración inicial hasta el flujo de trabajo recomendado.

## Introducción

Project Kickstart es una plantilla ligera y optimizada para iniciar proyectos de cualquier tipo, con configuraciones estándar para GitHub y Visual Studio Code. Su objetivo es reducir el tiempo de configuración inicial y mejorar la consistencia en los entornos de desarrollo, permitiendo a los desarrolladores enfocarse en lo importante desde el primer momento.

Para una visión general del proyecto consulta el [Léeme](../README.md) principal.

## Flujo de Trabajo

Esta sección te guía paso a paso en la personalización de la plantilla, siguiendo un flujo de trabajo estructurado que abarca desde la definición inicial hasta la fase de desarrollo. La metodología propuesta está optimizada tanto para desarrolladores individuales como para equipos pequeños.

La [Guía de Desarrollo](DEVELOPMENT_GUIDE.md) contiene los estándares técnicos y metodología completa. Este flujo se enfoca en cómo usar la plantilla para crear tu proyecto:

```
┌─────────────┐    ┌───────────┐    ┌───────────────┐    ┌────────────┐
│ Repositorio │ -> │ Propuesta │ -> │ Planificación │ -> │ Desarrollo │
└─────────────┘    └───────────┘    └───────────────┘    └────────────┘
```

### 1. Repositorio

Para empezar a usar la plantilla es muy sencillo.

1. Haz clic en **Use this template** en la [página del proyecto](https://github.com/sergio-ridaura/project-kickstart) o clona el repositorio:

   ```bash
   # Clonar la plantilla con el nombre de tu proyecto
   git clone https://github.com/sergio-ridaura/project-kickstart.git mi-proyecto

   # Navegar al directorio del proyecto
   cd mi-proyecto

   # Abrir en Visual Studio Code
   code .

   # Inicializar nuevo repositorio Git
   git init
   ```

2. **Organizar la plantilla** para separar la documentación de la plantilla de tu proyecto:

   ```bash
   # Crear carpeta para archivar la plantilla
   mkdir -p project-kickstart

   # Mover la documentación de la plantilla
   mv docs project-kickstart/
   mv README.md project-kickstart/
   ```

Utiliza los documentos de la plantilla como referencia y guía para crear la documentación de tu proyecto. Adapta y personaliza cada documento según las necesidades específicas de tu desarrollo, manteniendo una estructura clara y profesional.

### 2. Propuesta

Esta es la fase donde defines la idea del proyecto. Es el momento de conceptualizar qué problema resuelves y cómo lo vas a abordar.

- **[Propuesta](PROPOSAL.md)**: Crea este documento para definir el problema que resuelves, la solución propuesta y el alcance del proyecto. Es el punto de partida que valida si la idea tiene sentido y merece la pena desarrollarla.
- **[Licencia](../LICENSE)**: Decide qué licencia usar para tu proyecto. La plantilla incluye MIT por defecto, pero puedes cambiarla según tus necesidades.

Antes de continuar, es esencial que el equipo de desarrollo revise, participe activamente y apruebe la propuesta para asegurar su viabilidad técnica y alineación con los objetivos del proyecto.

### 3. Planificación

Una vez validada la propuesta, organiza el proyecto y establece cómo se ejecutará y medirá el éxito.

- **[Plan de Acción](ACTION_PLAN.md)**: Define las fases, hitos, recursos necesarios y cronograma del proyecto. Establece cómo medirás el éxito y qué criterios usarás para validar los resultados.
- **[Tareas](tasks/)**: Desglosa el trabajo en tareas específicas y manejables. Cada tarea debe tener criterios de aceptación claros y estimaciones de tiempo.
- **[Validación](VALIDATION.md)**: Define los criterios de aceptación y el proceso para verificar que los resultados cumplen con los objetivos establecidos en la propuesta.

Por defecto hay que iniciar con las mismas que hay en el template antes de iniciar propiamente tu proyecto. Si has seguido los pasos anteriores, debes de tener completadas las de la configuración inicial. Despues de esta lista de tareas por defecto añade las propias de tu proyecto.

Es fundamental que todo el equipo revise y valide colectivamente el plan de acción, incluyendo las tareas definidas, los criterios de éxito y la metodología de validación. Esta revisión colaborativa asegura la viabilidad técnica, confirma la alineación con los objetivos del proyecto y garantiza el compromiso de todos los miembros antes de proceder a la siguiente fase.

### 3. Desarrollo

Ya puedes iniciar las tareas previstas en el [Plan de Acción](ACTION_PLAN.md).

Recuerda que la documentación es un componente vivo del proyecto. Cada vez que se realicen cambios significativos en la documentación y el código, es una buena práctica **revisar y actualizar todos los documentos relevantes** para asegurar que la información se mantenga precisa y útil para todo el equipo.

Mantén actualizado el [Plan de acción](ACTION_PLAN.md), el registro de [Tareas](tasks/) y el [Léeme](../README.md).

La [Validación](VALIDATION.md) es una fase crítica que se ejecuta al finalizar el proyecto o al liberar una versión estable (release), típicamente en la versión 1.0.0. Esta etapa asegura que todos los objetivos y criterios de aceptación definidos inicialmente se han cumplido satisfactoriamente.

Cuando ya no necesites los archivos de la plantilla, puedes eliminarlos de forma segura.

## Preguntas Frecuentes

**¿Puedo usar esta plantilla para cualquier lenguaje de programación?**
¡Sí! La plantilla es agnóstica al lenguaje. Simplemente empieza a añadir tu código en la carpeta `src/`.

**¿Qué hago si no quiero toda la documentación?**
Puedes eliminar o modificar los documentos que no necesites. Sin embargo, te recomendamos mantener al menos `README.md`, `LICENSE` y `CONTRIBUTING.md` para tener un proyecto bien documentado.

**¿Qué hago si determino que el proyecto no es viable?**
Si concluyes que el proyecto no es viable, puedes detener su desarrollo en cualquier momento. Utiliza el documento de **[Propuesta](PROPOSAL.md)** para documentar el análisis y la decisión, manteniendo un registro claro para el equipo.

**¿Cómo reporto un problema o sugiero una mejora para la plantilla?**
Puedes abrir un [issue](https://github.com/sergio-ridaura/project-kickstart/issues) en el repositorio original de la plantilla.
Tienes más información en el documento de [Contribución](CONTRIBUTING.md).

¡Gracias por usar Project Kickstart! Esperamos que te ayude a construir proyectos increíbles.
