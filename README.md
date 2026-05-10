# learning-ai

> Mentorship hub para aprender IA a nivel profundo y prepararse para roles en big tech.
> **Sitio:** https://dwarlyndut.github.io/learning-ai/

---

## ¿Qué es esto?

Un espacio compartido entre **Dwarlyn (aprendiz)** y **Manuel (mentor)** para colaborar en el aprendizaje de IA. Sin jerarquías técnicas en el sistema — los dos pueden hacer todo.

El objetivo: preparación profunda para cuando llegue la ola de big tech contratando talento técnico en LATAM.

---

## Estructura del repo

```
learning-ai/
├── index.html          ← landing del sitio
├── README.md           ← este archivo
├── roadmap.md          ← mapa vivo de aprendizaje
├── library/            ← artículos y papers compartidos
│   ├── README.md
│   └── _template.md
├── log/                ← bitácora de estudio
│   ├── README.md
│   └── _template.md
└── meetings/           ← actas de las reuniones mensuales
    ├── README.md
    └── _template.md
```

---

## Cómo trabajamos

### 1. Library — `/library/`

Cuando alguno encuentra un artículo, paper o recurso valioso:

1. Copia `library/_template.md` con un nombre descriptivo
2. Formato: `YYYY-MM-titulo-corto.md`
3. Llena el bloque inicial (link, autor, por qué lo subes)
4. Si el otro quiere comentar, agrega su sección al pie con su nombre

**No hay aprobación, no hay revisión.** Si lo subes, queda. Si después se agrega contexto, se edita.

### 2. Learning Log — `/log/`

Cuando estudias algo, dejas una entrada:

1. Copia `log/_template.md`
2. Nombre: `YYYY-MM-DD-tema.md` (la fecha real del estudio)
3. Llenas qué aprendiste, qué dudas tienes, qué quieres profundizar

**No hay frecuencia obligatoria.** Si hay semanas sin entradas, el log no se queja. Vuelves cuando puedes.

### 3. Roadmap — `/roadmap.md`

Documento vivo con los temas a cubrir, organizados por nivel y área. Marca lo que vas tocando con `[x]`. Cualquiera puede agregar temas nuevos cuando descubre que algo es importante para la meta.

### 4. Meetings — `/meetings/`

Cada mes, antes de la reunión:

1. Crea `meetings/YYYY-MM-reunion.md` desde el template
2. Ambos llenan el bloque "Antes" con preguntas, temas, dudas
3. Durante los 30 min se captura en vivo el bloque "Durante"
4. Justo después se cierra el bloque "Después" con acciones para el mes

El archivo queda como historial permanente de lo discutido.

---

## Reglas implícitas

- **Commits con mensaje claro** — usar el imperativo: "Add paper sobre transformers", "Update roadmap with deep learning topics"
- **Markdown limpio** — encabezados, listas, código en bloques. Nada de HTML inline en archivos `.md`
- **Cada uno firma sus comentarios** — en archivos compartidos (library, meetings) usar `**[D]** texto...` o `**[M]** texto...` para identificar quién dijo qué
- **No borrar lo del otro** — solo agregar o comentar. Si algo está mal, se discute en la reunión

---

## Stack

- **Markdown** para todo el contenido — buscable, editable, versionado
- **GitHub Pages** para publicar la landing
- **Git** para el historial completo
- Sin dependencias, sin build, sin servidor

---

## Equipo

- **Dwarlyn Urrutia** ([@dwarlyndut](https://github.com/dwarlyndut))
- **Manuel Correa** — Mentor 

---

*v0.2.0 · 2026*
