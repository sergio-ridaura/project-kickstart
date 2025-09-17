# Contribuciones

¡Gracias por considerar contribuir a nuestro proyecto! Aquí encontrarás toda la información necesaria para comenzar a colaborar de manera efectiva.

## Requisitos Previos

Antes de comenzar, asegúrate de cumplir con los siguientes requisitos:

- Tener [Git](https://git-scm.com/) instalado en tu sistema.
- Tener una cuenta en [GitHub](https://github.com).
- Haber leído la documentación de [Léeme](../README.md) y los documentos de la carpeta `docs`.

## ¿Cómo Puedes Contribuir?

Puedes colaborar en las siguientes áreas:

- **Corrección de Errores**: Ayuda a mejorar la estabilidad del proyecto solucionando errores existentes. Puedes encontrar una lista de errores conocidos en la sección de [issues](https://github.com/sergio-ridaura/project-kickstart/issues) etiquetados como `bug`.
- **Nuevas Funcionalidades**: ¿Tienes una idea para una nueva funcionalidad? Revisa las [issues](https://github.com/sergio-ridaura/project-kickstart/issues) etiquetadas como `enhancement` para ver si tu idea ya está en discusión. Si no, ¡no dudes in abrir una nueva issue para proponerla!
- **Mejoras en la Documentación**: Una buena documentación es clave para cualquier proyecto. Si encuentras áreas que se puedan mejorar o ampliar en el [Léeme](../README.md) o en otros documentos de la carpeta `docs`, tus contribuciones son bienvenidas.
- **Revisión de Código**: Colabora revisando los [Pull Requests](https.github.com/sergio-ridaura/project-kickstart/pulls) abiertos. Ofrecer una segunda opinión y sugerir mejoras es una excelente manera de asegurar la calidad del código.

## Mejores Prácticas

- **Nombres de ramas**: Utiliza un formato descriptivo que incluya el tipo de cambio y el nombre de la tarea. El nombre de la rama debe seguir el formato `tipo/nombre-de-la-tarea`.
  - **Ejemplos**:
    ```bash
    feat/user-authentication
    fix/login-validation
    docs/readme-document
    task/github-configuration
    ```
- **Mensajes de commit**: Escribe mensajes claros usando el mismo formato que las ramas pero con `:` en lugar de `/`. El formato es `tipo: nombre-de-la-tarea`.
  - **Ejemplos**:
    ```text
    feat: user-authentication
    fix: login-validation
    docs: readme-document
    task: github-configuration
    ```
- **Tipos permitidos**:
  - `feat`: para nuevas funcionalidades.
  - `fix`: para correcciones de errores.
  - `docs`: para cambios en la documentación.
  - `task`: para tareas específicas del proyecto.
  - `style`: para cambios de formato (espaciado, etc.).
  - `refactor`: para reestructuración de código sin cambiar el comportamiento.
  - `test`: para agregar o modificar pruebas.
  - `chore`: para tareas de mantenimiento.
- **Estilo de código**: Sigue las reglas de formato definidas por [Prettier](https://prettier.io/) en el proyecto.

## Flujo de Trabajo

1. **Haz un fork del repositorio**.
2. Antes de comenzar, **abre un [issue](https://github.com/sergio-ridaura/project-kickstart/issues)** para describir tu propuesta. Esto permite al equipo discutir la contribución y asegurar que se alinea con los objetivos del proyecto antes de que inviertas tiempo en el desarrollo.
3. **Si es una nueva tarea que no está en el plan**, añádela al [Plan de Acción](ACTION_PLAN.md) y adapta las métricas correspondientes (número de tareas, horas estimadas, etc.).
4. **Crea una rama para tu contribución** siguiendo la convención de nombres:
   ```bash
   git checkout -b tipo/nombre-de-la-tarea
   ```
5. **Realiza los cambios necesarios**.
6. **Antes de confirmar los cambios**, actualiza al estado adecuado el documento de la tarea realizada y el plan de acción (marcar como completada, actualizar horas, criterios de aceptación y métricas del plan).
7. **Confirma tus cambios** siguiendo la convención de mensajes:
   ```bash
   git commit -m "tipo: nombre-de-la-tarea"
   ```
8. **Sube los cambios a tu fork**:
   ```bash
   git push origin tipo/nombre-de-la-tarea
   ```
9. **Abre un Pull Request** desde tu rama hacia el repositorio principal.

## Revisiones y Aprobaciones

- Los mantenedores revisarán tu Pull Request lo antes posible.
- Si se necesitan ajustes, se te notificará a través de comentarios en el Pull Request.

## Código de Conducta

Este proyecto está regido por un [Código de Conducta](CODE_OF_CONDUCT.md). Por favor, léelo y síguelo para garantizar un ambiente respetuoso y colaborativo.

## Recursos Adicionales

- [Guía de GitHub para Crear un Pull Request](https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

## Agradecimientos

¡Gracias por tu interés en contribuir a este proyecto! Tu participación es valiosa y ayuda a mejorar la calidad y funcionalidad del mismo. Si tienes alguna pregunta o necesitas ayuda, no dudes en contactar a los mantenedores del proyecto.
