# Plataforma Colaborativa de Estudio (FP)

La idea es tener una web interactiva para que alumnos y profesores podamos subir apuntes, herramientas útiles, info de exámenes o simulacros y fichas de profesores con las materias que dan, puntos fuertes y cómo califican,separando bien por ciclo, promoción/curso y profesor para no mezclar y filtrando según necesidad.

También quiero hacerlo pensando en que sirva como **plantilla** para otros ciclos (como ASIX, DAW, etc.) o para que otro centro o programador lo pueda adaptar a sus FP si le interesa. Todo con moderación previa para que haya respeto siempre, cuidando la privacidad y los derechos de autor.

Estoy montando este proyecto poco a poco a lo largo del curso, aprovechando trabajos y prácticas de las asignaturas, empezando por **1º de DAM (2026–2027)** en el **Colegio Sant Josep Obrer**.

---

## Qué hay en este repositorio

* **Proyecto principal:** La base de la plataforma, la documentación y los archivos que iré añadiendo según avance el curso y vaya haciendo entregas de clase.
* **`secundaria/actividad-4-selector-fichas/`:** Aquí dejo la **Actividad 4 (Selector Dinámico de Fichas Técnicas)** hecha con Vite, como actividad complementaria dentro del mismo repositorio.

---

## Estructura del repositorio

plataforma-estudio-fp/              # Raíz del repositorio (proyecto principal)
├── .gitignore
├── README.md
├── docs/                           # Documentación del proyecto principal
│   ├── propuesta-proyecto.md
│   └── base-datos-seed.md
├── src/
└── secundaria/
    └── actividad4/                 # Actividad 4
        ├── .gitignore
        ├── README.md
        ├── index.html
        ├── asignatura.html
        ├── package.json
        ├── package-lock.json
        ├── vite.config.js
        └── src/
            ├── datos.js
            ├── main.js
            ├── asignatura.js
            └── style.css
