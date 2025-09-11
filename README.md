# 🚀 Guía de Herramientas para Desarrollar Proyectos Rápido, Sencillo

Este documento reúne algunas de las mejores herramientas que puedes usar para estructurar, diseñar y desarrollar proyectos de software de manera ágil, con calidad y manteniendo buenas prácticas.

---

## 🗂️ Modelado de Datos

### [DrawSQL](https://drawsql.app/)
- Herramienta online para **crear diagramas ER (Entidad-Relación)**.
- Permite **diseñar bases de datos visualmente** y exportarlas a SQL.
- Ideal para planear la arquitectura de datos antes de programar.

### [DBDiagram](https://dbdiagram.io/)
- Alternativa ligera a DrawSQL.
- Permite escribir el modelo de datos en un lenguaje simple y obtener un **diagrama visual automáticamente**.
- Útil para documentar y compartir esquemas de base de datos.

---

## ⚙️ Generación de Código

### [Blueprint](https://laravel-shift.com/blueprint)
- Librería para **Laravel** que convierte archivos YAML en:
  - Migraciones
  - Modelos
  - Controladores
  - Tests
- Excelente para **prototipar rápidamente** la estructura de un proyecto.

---

## 🎨 Interfaces y Paneles de Administración

### [Filament](https://filamentphp.com/)
- Framework de administración para **Laravel + Livewire**.
- Permite crear **CRUDs, dashboards y formularios complejos** en minutos.
- Ofrece:
  - Gestión de tablas
  - Widgets y gráficas
  - Integración con permisos
- Ideal para proyectos internos, MVPs y backoffices.

### [Laravel Nova](https://nova.laravel.com/)
- Alternativa premium a Filament.
- Potente, con muchos recursos pero de pago.

---

## 🧩 UI y Componentes

### [Tailwind CSS](https://tailwindcss.com/)
- Framework CSS **utilitario**.
- Permite maquetar interfaces de forma rápida y responsiva sin escribir CSS personalizado.
- Se integra perfectamente con Laravel, Filament y React.

### [Shadcn/UI](https://ui.shadcn.com/)
- Colección de **componentes de interfaz modernos** construidos con Tailwind y Radix.
- Muy útil para React, Next.js y proyectos modernos.

---

## 🛠️ Desarrollo Frontend

### [React](https://react.dev/)
- Librería para construir interfaces interactivas.
- Útil si necesitas ir más allá de Livewire y crear apps SPA/SSR.

### [Vite](https://vitejs.dev/)
- Bundler rápido y moderno.
- Viene integrado en Laravel para compilar JS, React, Vue y estilos.

---

## 📚 Documentación y Organización

### [Notion](https://www.notion.so/)
- Herramienta para **documentar proyectos** y trabajar en equipo.
- Útil para mantener especificaciones, requisitos y tareas.

### [Excalidraw](https://excalidraw.com/)
- Editor online para **diagramas rápidos y colaborativos**.
- Ideal para lluvias de ideas y mockups iniciales.

---

## ✅ Flujo Recomendado

1. **Diseño de la BD** → DrawSQL / DBDiagram  
2. **Generación de código base** → Blueprint  
3. **Backend & CRUD** → Laravel + Filament  
4. **UI/Frontend** → Tailwind + Shadcn/UI + (React opcional)  
5. **Documentación** → Notion / Excalidraw  

Con estas herramientas, puedes pasar de una idea a un producto funcional **mucho más rápido** y con calidad.

## Roles y permisos
https://filamentphp.com/plugins/bezhansalleh-shield
https://filamentphp.com/plugins/bezhansalleh-panel-switch
https://filamentphp.com/plugins/shane-rosenthal-panel-roles

## Email
https://app.mailgun.com/dashboard?tab=send

## Paquete de paises, estados y ciudades
https://packagist.org/packages/altwaireb/laravel-world

---

## 📌 Conclusión
Estas herramientas te ayudan a **estructurar, prototipar y lanzar proyectos** sin perder tiempo en lo repetitivo.  
La clave es combinarlas estratégicamente para cubrir **BD + Backend + Frontend + Documentación**.
