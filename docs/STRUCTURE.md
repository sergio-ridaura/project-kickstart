# Estructura del Proyecto

Este documento describe la organización de directorios y archivos del proyecto, explicando su propósito y función.

## Configuración GitHub

- **`/.github/`** - Contiene toda la configuración específica para GitHub.
  - **`ISSUE_TEMPLATE/`**: Almacena las plantillas para la creación de issues.
    - `bug_report.md`: Formato para reportar errores.
    - `feature_request.md`: Formato para proponer nuevas funcionalidades.
    - `question.md`: Formato para realizar preguntas.
  - **`PULL_REQUEST_TEMPLATE/`**: Contiene la plantilla para las pull requests.
    - `pull_request_template.md`: Checklist y formato estándar para las contribuciones de código.

## Configuración Visual Studio

- **`/.vscode/`** - Contiene la configuración recomendada para el entorno de desarrollo en Visual Studio Code.
  - `extensions.json`: Lista de extensiones de VSCode recomendadas para este proyecto.
  - `settings.json`: Ajustes de configuración del espacio de trabajo.
  - `cspell.json`: Configuración del corrector ortográfico CSpell, incluyendo diccionarios y reglas personalizadas.

## Documentación

- **`/docs/`** - Contiene toda la documentación del proyecto.
  - `ACTION_PLAN.md`: Plan de implementación detallado del proyecto.
  - `CODE_OF_CONDUCT.md`: Código de conducta para la comunidad.
  - `CONTRIBUTING.md`: Guía sobre cómo contribuir al proyecto.
  - `CREDITS.md`: Reconocimientos a colaboradores y herramientas.
  - `DEVELOPMENT_GUIDE.md`: Metodología completa de desarrollo.
  - `PROPOSAL.md`: Propuesta que define el problema, la solución y el alcance.
  - `SECURITY.md`: Políticas de seguridad y cómo reportar vulnerabilidades.
  - `STRUCTURE.md`: Este mismo archivo, que describe la estructura del proyecto.
  - `USER_GUIDE.md`: Guía para usar la herramienta.
  - `VALIDATION.md`: Documento para validar la propuesta y el proyecto.
  - **`/tasks/`**: Documentos que detallan tareas específicas del plan de acción.
    - `action-plan-document.md`: Tarea para crear el documento de plan de acción.
    - `action-plan-tasks.md`: Tarea para crear las tareas del plan de acción.
    - `code-of-conduct-document.md`: Tarea para crear el documento de código de conducta.
    - `contributing-document.md`: Tarea para crear el documento de contribución.
    - `credits-document.md`: Tarea para crear el documento de créditos.
    - `development-guide-document.md`: Tarea para crear la guía de desarrollo.
    - `github-configuration.md`: Tarea para configurar el repositorio de GitHub.
    - `github-repository.md`: Tarea para crear el repositorio de GitHub.
    - `proposal-document.md`: Tarea para crear el documento de propuesta.
    - `readme-document.md`: Tarea para crear el documento README.
    - `security-document.md`: Tarea para crear el documento de seguridad.
    - `structure-document.md`: Tarea para crear el documento de estructura.
    - `user-guide-document.md`: Tarea para crear la guía de usuario.
    - `validation-document.md`: Tarea para crear el documento de validación.
    - `vscode-configuration.md`: Tarea para configurar VSCode.

## Archivos en la Raíz

- `.gitignore`: Especifica los archivos y directorios que Git debe ignorar.
- `LICENSE`: La licencia principal de este proyecto (MIT).
- `README.md`: El punto de entrada principal del proyecto, con una visión general y enlaces clave.

## Estructura Después del Uso

Cuando sigas las instrucciones del README para organizar la plantilla, se creará la siguiente estructura:

- **`/project-kickstart/`** - Carpeta que contiene los archivos originales de la plantilla para referencia.
  - `docs/`: Toda la documentación original de la plantilla.
  - `README.md`: El README original de la plantilla.

**Nota**: Esta carpeta puede eliminarse una vez que ya no necesites los archivos de referencia de la plantilla.
