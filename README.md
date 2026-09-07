# Psicología Educacional · Materiales de estudio

Repositorio con los materiales completos del curso **Psicología Educacional** (2° A, 2026) – Profesorado de Educación Inicial · Instituto Superior Terciario Fátima Soldati.

Incluye ambas partes del cuatrimestre: primera parte (clases 1‑9) y segunda parte (clases 10‑14), así como evaluativos, materiales complementarios y programación.

🌐 **Sitio publicado (GitHub Pages):** https://jjgarcia-cpu.github.io/psico-educ/

---

## 📂 Estructura del repositorio

```
/ (raíz)
├── README.md                 # Este archivo
├── PROGRAMA_2026.pdf         # Programa oficial de la materia
├── 1era-parte/               # Clases 1 a 9 (primer cuatrimestre / primera parte)
│   ├── clase-01-introduccion/          # Lecturas, actividades, recursos
│   ├── clase-02-desarrollo-infantil/
│   ├── clase-03-teorias-del-aprendizaje/
│   ├── clase-04-motivacion-y-emociones/
│   ├── clase-05-contextos-sociales/
│   ├── clase-06-inclusion-y-diversidad/
│   ├── clase-07-evaluacion-educativa/
│   ├── clase-08-tic-en-la-educacion/
│   ├── clase-09-proyectos-y-practicas/
│   ├── evaluativos/
│   │   ├── 1er-parcial.docx
│   │   └── 1er-parcial.pdf
│   ├── materiales-complementarios/
│   │   ├── Materiales-Psicoedu.pdf
│   │   └── Plan-de-clases.pdf
│   └── sueltos/              # Archivos diversos de la carpeta “Sueltos”
├── 2nda-parte/               # Clases 10 a 14 (segunda parte)
│   ├── clase-10-estilos-y-enfoques/
│   │   ├── lecturas/
│   │   ├── actividades/      # (si hubiera)
│   │   └── rúbricas/         # (si hubiera)
│   ├── clase-11-motivacion-y-autoestima/
│   ├── clase-12-resiliencia-y-autoestima/
│   ├── clase-13-creatividad/
│   │   ├── modelos/          # Carpeta “Modelos” de la 2nda parte
│   │   └── ... (lecturas, actividades)
│   ├── clase-14-fracaso-escolar/
│   ├── evaluacion-formativa/
│   │   ├── Evaluacion-formativa-El-motor-de-aprender-09-10.docx
│   │   └── Evaluacion-formativa-El-motor-de-aprender-09-10.pdf
│   └── textos-para-classroom/
│       └── Textos_Classroom_Clases11-14.docx
└── .gitignore                # Excluye temporales y archivos no deseados
```

> **Nota sobre nombres de carpetas**: se usan minúsculas, guiones y numeración fija (`clase-01`, `clase-02`, …) para evitar problemas con espacios/acentos. Los descriptivos detrás del guion reflejan el tema de cada clase (pueden ajustarse si es necesario).

---

## 📖 Cómo usar este repositorio

- **Clonar o actualizar**:  
  ```bash
  git clone https://github.com/jjgarcia-cpu/psico-educ.git
  cd psico-educ
  git pull origin main   # para mantenerse al día
  ```

- **Navegar por las clases**: cada carpeta `clase-XX-*` contiene los materiales de esa sesión (lecturas en PDF, PPT, guías, actividades, etc.).  
- **Evaluativos**: se encuentran en `1era-parte/evaluativos/` (primer parcial) y `2nda-parte/evaluacion-formativa/` (evaluación formativa del 09‑10).  
- **Materiales complementarios**: en `1era-parte/materiales-complementarios/` (plan de clases, material de lectura general).  
- **Textos para Classroom**: listos para copiar y publicar en Google Classroom (`2nda-parte/textos-para-classroom/`).  

---

## 🛠️ Cómo contribuir (si tenés permisos de escritura)

1. Crear una rama desde `main`:  
   ```bash
   git checkout -b mi-feature
   ```
2. Agregar o modificar archivos según corresponda.  
3. Hacer commit con mensaje descriptivo:  
   ```bash
   git add -A
   git commit -m "feat: agregar material de Clase 5 – contextos sociales"
   ```
4. Push y abrir Pull Request hacia `main`:  
   ```bash
   git push origin mi-feature
   ```
   Luego, en GitHub, crear el PR y esperar revisión (si aplica).

---

## 🚦 Convenciones

- **Solo materiales para estudiantes**: no se suben archivos con respuestas, guion docente o versiones “para proyectar” que contengan información sensible.  
- Los archivos PDF y PPT pueden contener material de estudio completo; se asume que son de distribución libre dentro del contexto del curso.  
- Mantener los nombres de archivo tal como provienen del material original (no renombrar arbitrariamente) para facilitar trazabilidad.  
- Si se agrega una nueva clase o tema, seguir la nomenclatura `clase-XX-descriptivo-tema` y colocar dentro las subcarpetas `lecturas/`, `actividades/`, `rúbricas/` según corresponda.  
- Los archivos temporales de Office (`~$*`), `Thumbs.db`, y borradores personales (`*_borrador.*`) deben quedar fuera del versionado mediante `.gitignore`.  

---

## 📧 Contacto

Para consultas sobre el contenido o el repositorio, contactar al docente:  
**Juan José García** – jjgarcia@terciariofatimasoldati.edu.ar  

---

¡Gracias por usar y mejorar estos recursos!  
