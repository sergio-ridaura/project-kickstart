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
3. **Crea una rama para tu contribución**, a partir de la rama `staging`, siguiendo la convención de ramas:

   ```bash
   # Cambiar a la rama staging
   git checkout staging

   # Crear nueva rama desde staging
   git checkout -b type/task-name
   ```

4. **Esta nueva tarea, que no está en el plan**, añádela al [Plan de Acción](ACTION_PLAN.md) y adapta las métricas correspondientes (número de tareas, horas estimadas, etc.).
5. **Realiza los cambios necesarios**.
6. **Antes de confirmar los cambios**, asegúrate de que tu código sigue los estándares del proyecto, actualiza al estado adecuado el documento de la tarea realizada y el plan de acción (marcar como completada, actualizar horas, criterios de aceptación y métricas del plan).
7. **Confirma tus cambios** siguiendo la convención de mensajes:
   ```bash
   # Confirmar cambios con nombre de la tarea
   git commit -m "type:task-name"
   ```
8. **Sube los cambios a tu fork**:
   ```bash
   # Subir rama al fork en GitHub
   git push origin type/task-name
   ```
9. **Abre un Pull Request** desde tu rama hacia la rama `staging` del repositorio principal.

### Flujo de Ramas

Para garantizar la estabilidad del código y facilitar el trabajo en paralelo, seguimos un modelo de flujo de ramas Git Flow adaptado:

```
main (producción estable)
└── staging (preparación para producción)
    ├── feat/authentication-system
    ├── fix/form-validation-error
    └── docs/installation-guide
```

- **`main`**: Contiene la versión de producción del proyecto. Siempre debe estar estable y lista para ser desplegada.
- **`staging`**: Es la rama de preparación para producción. Integra todas las funcionalidades y correcciones de manera continua.
- **`type/task-name`**: Son las ramas de desarrollo, creadas a partir de `staging`. Cada nueva funcionalidad, corrección o cambio se desarrolla en su propia rama para aislar el trabajo.

### Nombres de Ramas

Utiliza el formato `type/task-name`, donde `type` puede ser:

- `feat`: Nueva funcionalidad.
- `fix`: Corrección de un error.
- `docs`: Cambios en la documentación.
- `style`: Ajustes de formato (espacios, comas, etc.).
- `refactor`: Refactorización de código existente.
- `test`: Añadir o modificar tests.
- `config`: Cambios en archivos de configuración.
- `chore`: Tareas de mantenimiento.

### Mensajes de Commit

Los mensajes de commit deben seguir el formato `type: task-name`, utilizando los mismos tipos que las ramas. Esto facilita la lectura del historial y la automatización de tareas.

**Ejemplos**:

```bash
feat: authentication-system
fix: form-validation-error
docs: installation-guide
```

## Calidad del Código

Para mantener la consistencia y la legibilidad del código, es fundamental seguir las siguientes pautas:

- **Estilo de Código**: Este proyecto utiliza [Prettier](https://prettier.io/) para formatear el código Markdown. Se recomienda usar la extensión [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) para Visual Studio Code para formatear automáticamente los archivos.
- **Consistencia**: Al editar la documentación, por favor, sigue el estilo y la estructura de los archivos existentes. Esto incluye la forma en que se usan los encabezados, las listas y otros elementos de Markdown.

## Revisiones y Aprobaciones

- El desarrollador debe verificar localmente que los criterios de aceptación se cumplen y que no se ha roto ninguna funcionalidad existente.
- Los mantenedores revisarán tu Pull Request lo antes posible.
- Si se necesitan ajustes, se te notificará a través de comentarios en el Pull Request.

## Recursos Adicionales

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [About pull requests](https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

## Agradecimientos

¡Gracias por tu interés en contribuir a este proyecto! Tu participación es valiosa y ayuda a mejorar la calidad y funcionalidad del mismo. Si tienes alguna pregunta o necesitas ayuda, no dudes en contactar a los mantenedores del proyecto.
