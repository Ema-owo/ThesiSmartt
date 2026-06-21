# 📚 Proyecto Tesis — Estructura Base

# ThesiSmart

Aplicación web diseñada para acompañar a estudiantes universitarios en todo el proceso de elaboración de su tesis cuantitativa. Mediante plantillas con formatos oficiales, orientación metodológica contextualizada y herramientas de apoyo estadístico, ThesiSmart reduce errores frecuentes, tiempos de entrega y niveles de estrés durante el desarrollo de la investigación.

---

## 👥 Integrantes

| Apellidos y nombres              | Código       |
|----------------------------------|--------------|
| Antón Tasayco, Ruth Nayeli       | u20231c165   |
| Bardales Fernandez, Luis Angel   | u20241f315   |
| Barrera Gutierrez, Job Issai     | u202314473   |
| Casos Torre, Miguel Andre        | u202124030   |
| Chipana Huarancca, Emanuel Wilfredo | u202214074 |
| Diaz Luque, Rosa Esther          | u20241d443   |
| Quiñones Carhuaz, Liam Yostin   | u202427265   |

**Startup:** Nexo Research Lab  
**Curso:** IHC y Tecnologías Móviles (1ASI0385)  
**Docente:** Acosta Ticse, Deisy Lizbeth  
**Periodo:** 202610

---

## 👥 Asignación de páginas

| Pantalla              | Archivo HTML                | Responsable                     |
|-----------------------|-----------------------------|----------------------------------|
| Landing Page          | `index.html`                | Ruth Nayeli Antón Tasayco        |
| Dashboard Estudiante  | `dashboard-estudiante.html` | Rosa Esther Diaz Luque           |
| Gestionar Tesis       | `gestionar-tesis.html`      | Liam Yostin Quiñones Carhuaz     |
| Dashboard Asesor      | `dashboard-asesor.html`     | Luis Angel Bardales Fernandez    |
| Autenticación / Login | `auth.html`                 | Miguel Andre Casos Torre         |

---

## 📁 Estructura de carpetas

```
/proyecto-tesis
├── /images
│   ├── /landing
│   ├── /dashboard-estudiante
│   ├── /gestionar-tesis
│   ├── /dashboard-asesor
│   └── /auth
├── /styles
│   ├── global.css              ← NADIE edita solo
│   ├── landing.css
│   ├── dashboard-estudiante.css
│   ├── gestionar-tesis.css
│   ├── dashboard-asesor.css
│   └── auth.css
├── /scripts
│   ├── global.js               ← NADIE edita solo
│   ├── landing.js
│   ├── dashboard-estudiante.js
│   ├── gestionar-tesis.js
│   ├── dashboard-asesor.js
│   └── auth.js
├── index.html
├── dashboard-estudiante.html
├── gestionar-tesis.html
├── dashboard-asesor.html
└── auth.html
```

---

## 🎨 Colores del proyecto (`global.css`)

| Variable           | Hex       |
|--------------------|-----------|
| `--violeta`        | `#4F39F6` |
| `--verde`          | `#00A63E` |
| `--negro`          | `#101828` |
| `--morado`         | `#9810FA` |
| `--gris`           | `#989696` |
| `--verde-claro`    | `#DBFCE7` |
| `--naranja`        | `#E17100` |
| `--amarillo-claro` | `#FEF3C6` |

---

## 📋 Reglas de oro

1. **`global.css` y `global.js` son intocables** sin avisar al equipo.
2. Cada dev trabaja **solo en sus archivos** (html, css, js e images).
3. **No hay prefijos CSS** — cada archivo ya está aislado por nombre.
4. **IDs solo para JS**, nunca para estilos.
5. **PR a `main` al final** — 0 conflictos garantizados.
