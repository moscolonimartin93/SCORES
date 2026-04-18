# Scores POP – Hospital Alemán

Aplicación web para seguimiento de scores funcionales postoperatorios en Traumatología.

## Scores incluidos

| Región | Scores |
|--------|--------|
| Tobillo / Pie | AOFAS Ankle-Hindfoot, FADI |
| Rodilla | Tegner-Lysholm, KSS, KOOS |
| Cadera | Harris Hip Score |
| Hombro / Clavícula | Constant Shoulder Score, ASES |
| Fémur / Diafisarias | SF-12 Funcional |
| Húmero / Codo | Mayo Elbow Score, Quick-DASH |

---

## Cómo subir a GitHub y publicar con Vercel

### Paso 1 – Subir a GitHub

1. Ir a **github.com** → iniciar sesión
2. Clic en el botón verde **"New"** (repositorio nuevo)
3. Nombre: `scores-pop` → clic en **"Create repository"**
4. En la página del repositorio vacío, clic en **"uploading an existing file"**
5. Arrastrar **todos los archivos y carpetas** de esta carpeta
6. Clic en **"Commit changes"**

### Paso 2 – Publicar con Vercel

1. Ir a **vercel.com** → iniciar sesión con la misma cuenta de GitHub
2. Clic en **"Add New Project"**
3. Seleccionar el repositorio `scores-pop`
4. Clic en **"Deploy"** (sin cambiar nada)
5. En ~30 segundos Vercel da un link: `scores-pop.vercel.app`

¡Listo! Ese link funciona desde cualquier celular sin instalar nada.

---

## Próximos pasos opcionales

- [ ] Base de datos compartida con Supabase (todos los colegas ven los mismos pacientes)
- [ ] Login por médico
- [ ] Exportar a Google Sheets
- [ ] Gráficos de evolución por paciente
