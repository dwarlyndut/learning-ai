# Program

> Plan mensual de aprendizaje. Tema central + actividades, con estado simple y arrastre cuando un mes se queda corto.

---

## Cómo funciona

### El ciclo mensual

```
Reunión mensual (30 min) → Cerrar mes anterior + planear mes nuevo
   ↓
Mes en curso → Estudiar, marcar actividades como hechas
   ↓
Final de mes → Lo que quedó pendiente se arrastra al siguiente
   ↓
Siguiente reunión → Repetir
```

### Cada mes tiene

1. **Tema central** — el skill de fondo del mes (puede continuar de meses previos)
2. **Objetivo del mes** — una frase concreta de qué se sube
3. **Actividades del tema central** — el trabajo principal
4. **Actividades complementarias** — del roadmap general, para no saturar
5. **Pendientes arrastrados** — lo que no se cerró el mes anterior

---

## Cómo crear un mes nuevo

1. Copia `_template.md` a `YYYY-MM.md`
   - Ejemplo: `2026-06.md` para junio 2026
2. Llena la cabecera (tema, objetivo)
3. Lista las actividades como checkboxes
4. Cada actividad puede tener:
   - 📄 Link a artículo/paper público
   - 📝 Link a doc privado en Drive (carpeta `learning-ai-private/YYYY-MM/`)
   - 📓 Link a notebook
   - 🎥 Link a video
5. Guarda y commitea

---

## Estados de las actividades

Solo hay dos estados, con checkbox markdown:

```markdown
- [ ] Actividad pendiente
- [x] Actividad completada
```

Si quieres marcar algo en progreso, agrega un comentario al lado:

```markdown
- [ ] Implementar self-attention desde cero *(en progreso)*
```

---

## Qué pasa cuando un mes se queda corto

Es la realidad — temas como Transformers no se dominan en 4 semanas.

**Al cerrar el mes (en la reunión mensual):**

1. Las actividades sin marcar se mueven al bloque "Continúa de" del mes siguiente
2. El "tema central" puede mantenerse igual (parte 2, parte 3) o cambiar
3. Se anota explícitamente al final del archivo cerrado:

```markdown
## Cierre del mes
**Cerrado el:** YYYY-MM-DD (en reunión mensual)
**Completado:** 5/8 actividades
**Arrastra a junio:** ver `2026-06.md` sección "Continúa de"
```

---

## Privacidad — Drive sí o sí

Los docs privados (notas crudas, ejercicios, ideas no maduras) viven en Google Drive en la carpeta:

```
learning-ai-private/
├── 2026-05/
├── 2026-06/
└── ...
```

El sitio público solo tiene los **links**. Quien hace clic sin permisos ve "necesita acceso". Manuel y Dwarlyn tienen acceso, nadie más.

---

## Conexión con otras secciones del repo

- **Library** → cuando subes un paper a la library, lo enlazas desde la actividad correspondiente del mes
- **Log** → cuando estudias una actividad, dejas entrada en log con la fecha
- **Meetings** → cada reunión cierra un mes y abre el siguiente
- **Roadmap** → cuando completas un tema del mes, marcas el item correspondiente del roadmap

---

## Convenciones

- Un archivo por mes, formato `YYYY-MM.md`
- El mes se crea **antes** de empezarlo (no a mitad de mes)
- Si un mes se queda sin tocar, se cierra vacío con nota explicativa — no se borra
- Los enlaces a Drive deben usar URLs completas (`https://docs.google.com/...`), no atajos
