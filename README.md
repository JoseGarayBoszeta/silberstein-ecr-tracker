# ECR Tracker - Instrucciones para GitHub Pages

## Estructura del Website

```
website/
├── index.html              # Dashboard principal (vista del maestro)
├── estudiantes/            # Carpeta con páginas individuales
│   ├── Arguelles_Yuliana.html
│   ├── Avila_Eddie.html
│   └── ... (21 archivos total)
└── README.md               # Este archivo
```

## Cómo Subir a GitHub Pages

### Paso 1: Crear cuenta de GitHub (si no tienes una)
1. Ve a https://github.com
2. Haz clic en "Sign up"
3. Sigue las instrucciones para crear tu cuenta

### Paso 2: Crear un nuevo repositorio
1. Una vez en GitHub, haz clic en el botón verde "New" o ve a https://github.com/new
2. Nombre del repositorio: `ecr-tracker` (o el nombre que prefieras)
3. Selecciona "Public" (necesario para GitHub Pages gratis)
4. NO selecciones "Add a README file"
5. Haz clic en "Create repository"

### Paso 3: Subir los archivos
**Opción A - Desde la web (más fácil):**
1. En tu nuevo repositorio, haz clic en "uploading an existing file"
2. Arrastra toda la carpeta `website` al área de carga
3. O haz clic en "choose your files" y selecciona todos los archivos
4. Haz clic en "Commit changes"

**Opción B - Usando Terminal:**
```bash
cd "/Users/josegarayboszeta/Documents/(Silberstein 2025-26)/SLAR/ECR-Tracker/website"
git init
git add .
git commit -m "ECR Tracker website"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/ecr-tracker.git
git push -u origin main
```

### Paso 4: Activar GitHub Pages
1. En tu repositorio, ve a "Settings" (engranaje)
2. En el menú izquierdo, busca "Pages"
3. En "Source", selecciona "Deploy from a branch"
4. En "Branch", selecciona "main" y "/ (root)"
5. Haz clic en "Save"
6. Espera 1-2 minutos

### Paso 5: Obtener tu URL
Tu sitio estará disponible en:
```
https://TU_USUARIO.github.io/ecr-tracker/
```

## URLs para Compartir con Estudiantes

### Dashboard del Maestro:
```
https://TU_USUARIO.github.io/ecr-tracker/index.html
```

### Links Individuales por Estudiante:
| Estudiante | URL |
|------------|-----|
| Arguelles, Yuliana | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Arguelles_Yuliana.html` |
| Avila, Eddie | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Avila_Eddie.html` |
| Carias Andino, Orlin | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Carias_Andino_Orlin.html` |
| Conejo Perez, Rubi | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Conejo_Perez_Rubi.html` |
| Cu Tubac, Yoselin | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Cu_Tubac_Yoselin.html` |
| Diaz Castro, Antonis | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Diaz_Castro_Antonis.html` |
| Espinoza, Ever | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Espinoza_Ever.html` |
| Fernandez, Adam | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Fernandez_Adam.html` |
| Garcia Mancilla, Angela | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Garcia_Mancilla_Angela.html` |
| Hernandez Martinez, Emely | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Hernandez_Martinez_Emely.html` |
| Lopez Melgar, Frelyn | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Lopez_Melgar_Frelyn.html` |
| Mejia Orellana, Yahely | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Mejia_Orellana_Yahely.html` |
| Melendez, Sofia | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Melendez_Sofia.html` |
| Morales Mejia, Marian | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Morales_Mejia_Marian.html` |
| Morales, Stephanie | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Morales_Stephanie.html` |
| Munoz Gamez, Nazly | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Munoz_Gamez_Nazly.html` |
| Perez Zuniga, Kimberly | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Perez_Zuniga_Kimberly.html` |
| Reyes Minier, Perla | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Reyes_Minier_Perla.html` |
| Torres Morales, Brayon | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Torres_Morales_Brayon.html` |
| Vargas Toledo, Samantha | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Vargas_Toledo_Samantha.html` |
| Vega Ortega, Martha | `https://TU_USUARIO.github.io/ecr-tracker/estudiantes/Vega_Ortega_Martha.html` |

## Cómo Actualizar Después de Nuevos Ensayos

1. Cuando tengas nuevos ensayos calificados, los archivos HTML actualizados estarán en la carpeta `website/estudiantes/`
2. En GitHub, ve a tu repositorio
3. Navega a la carpeta `estudiantes`
4. Haz clic en "Add file" → "Upload files"
5. Sube los archivos actualizados (reemplazarán los existentes)
6. Haz clic en "Commit changes"
7. El sitio se actualizará automáticamente en 1-2 minutos

## Tips para Google Classroom

### Opción 1: Un link por estudiante (Recomendado)
- Crea una tarea individual para cada estudiante
- Incluye su link personal en la descripción
- Cada estudiante solo ve su propio tracker

### Opción 2: Mensaje privado
- Usa la función de comentarios privados
- Envía a cada estudiante su link personal

### Opción 3: Material del curso
- Publica el link del dashboard como material
- Los estudiantes buscan su nombre y hacen clic en su tarjeta
