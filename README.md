```mermaid
graph TD;
    User[Usuario] -->|Interactúa con| HTMLSystem[Sistema HTML];
    HTMLSystem -->|Administra contenido educativo| ContentManagement[Administración de contenido educativo];
    HTMLSystem -->|Visualiza páginas de contenido| ContentView[Páginas de contenido];
    HTMLSystem -->|Edita páginas de contenido| ContentEdit[Edición de contenido];
    HTMLSystem -->|Administra usuarios| UserManagement[Administración de usuarios];
    HTMLSystem -->|Proporciona soporte técnico| TechnicalSupport[Soporte técnico];
    HTMLSystem -->|Inscribe a cursos| CourseRegistration[Inscripción a cursos];
    HTMLSystem -->|Evalúa cursos| CourseEvaluation[Evaluación de cursos];
    HTMLSystem -->|Genera reportes| Reporting[Generación de reportes];
    HTMLSystem -->|Notificaciones| Notifications[Notificaciones];

    classDef actions fill:#f9f,stroke:#333,stroke-width:2px;
    class ContentManagement, ContentView, ContentEdit, TechnicalSupport, CourseRegistration, UserManagement, CourseEvaluation, Reporting, Notifications actions;

```