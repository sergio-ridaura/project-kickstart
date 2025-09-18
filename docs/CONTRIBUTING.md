# Contribuciones

¡Gracias por considerar contribuir a nuestro proyecto! Aquí encontrarás toda la información necesaria para comenzar a colaborar de manera efectiva.

## Requisitos Previos

Antes de realizar tu primera contribución, asegúrate de cumplir con los siguientes requisitos:

**Herramientas necesarias:**

- [Git](https://git-scm.com/) y cuenta en [GitHub](https://github.com)
- Editor de código (recomendamos [Visual Studio Code](https://code.visualstudio.com))

**Documentación esencial:**

- [Léeme](../README.md), [Guía de Usuario](USER_GUIDE.md) y [Guía de Desarrollo](DEVELOPMENT_GUIDE.md)
- [Código de Conducta](CODE_OF_CONDUCT.md) y [Seguridad](SECURITY.md)

**Conocimientos básicos:**

- Git, Markdown y objetivos del proyecto ([Propuesta](PROPOSAL.md))

## ¿Cómo Puedes Contribuir?

Puedes colaborar en las siguientes áreas:

- **Corrección de Errores**: Ayuda a mejorar la estabilidad del proyecto solucionando errores existentes. Puedes encontrar una lista de errores conocidos en la sección de [issues](https://github.com/sergio-ridaura/project-kickstart/issues) etiquetados como `bug`.
- **Nuevas Funcionalidades**: ¿Tienes una idea para una nueva funcionalidad? Revisa las [issues](https://github.com/sergio-ridaura/project-kickstart/issues) etiquetadas como `enhancement` para ver si tu idea ya está en discusión. Si no, ¡no dudes en abrir una nueva issue para proponerla!
- **Mejoras en la Documentación**: Una buena documentación es clave para cualquier proyecto. Si encuentras áreas que se puedan mejorar o ampliar en el [Léeme](../README.md) o en otros documentos de la carpeta `docs`, tus contribuciones son bienvenidas.
- **Revisión de Código**: Colabora revisando los [Pull Requests](https.github.com/sergio-ridaura/project-kickstart/pulls) abiertos. Ofrecer una segunda opinión y sugerir mejoras es una excelente manera de asegurar la calidad del código.

## Flujo de Trabajo

La [Guía de Desarrollo](DEVELOPMENT_GUIDE.md) describe la metodología general del proyecto. A continuación se detalla el flujo específico para colaboradores:

1. **Haz un fork del repositorio**.
2. Antes de comenzar, **abre un [issue](https://github.com/sergio-ridaura/project-kickstart/issues)** para describir tu propuesta. Esto permite al equipo discutir la contribución y asegurar que se alinea con los objetivos del proyecto antes de que inviertas tiempo en el desarrollo.
3. **Esta nueva tarea, que no está en el plan**, añádela al [Plan de Acción](ACTION_PLAN.md) y adapta las métricas correspondientes (número de tareas, horas estimadas, etc.).
4. **Crea una rama para tu contribución** siguiendo la convención de nombres, para más información ver el documento [Guía de Desarrollo](DEVELOPMENT_GUIDE.md):
   ```bash
   git checkout -b tipo/nombre-de-la-tarea
   ```
5. **Realiza los cambios necesarios**.
6. **Antes de confirmar los cambios**, actualiza al estado adecuado el documento de la tarea realizada y el plan de acción (marcar como completada, actualizar horas, criterios de aceptación y métricas del plan).
7. **Confirma tus cambios** siguiendo la convención de mensajes, para más información ver el documento [Guía de Desarrollo](DEVELOPMENT_GUIDE.md):
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

## Recursos Adicionales

- [Guía de GitHub para Crear un Pull Request](https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

## Agradecimientos

¡Gracias por tu interés en contribuir a este proyecto! Tu participación es valiosa y ayuda a mejorar la calidad y funcionalidad del mismo. Si tienes alguna pregunta o necesitas ayuda, no dudes en contactar a los mantenedores del proyecto.
