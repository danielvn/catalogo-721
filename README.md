# Catálogo PDF

Página web estática para visualizar y descargar un catálogo en formato PDF.

## 🚀 Desplegar en GitHub Pages

### Opción 1: Usando la Interfaz Web de GitHub (Más fácil)

1. **Crear un nuevo repositorio en GitHub:**

   - Ve a [github.com](https://github.com) e inicia sesión
   - Haz clic en el botón "+" (arriba a la derecha) → "New repository"
   - Nombre del repositorio: `catalogo` (o el que prefieras)
   - Marca como **Público** (GitHub Pages gratuito requiere repositorios públicos)
   - **NO** marques "Initialize with README"
   - Haz clic en "Create repository"

2. **Subir los archivos:**

   - En la página del repositorio, haz clic en "uploading an existing file"
   - Arrastra `index.html` y `catalogo.pdf` a la página
   - Haz clic en "Commit changes"

3. **Activar GitHub Pages:**
   - Ve a **Settings** (Configuración) del repositorio
   - En el menú lateral, busca **Pages**
   - En "Source", selecciona la rama `main` (o `master`)
   - En "Folder", selecciona `/ (root)`
   - Haz clic en **Save**
   - Espera unos minutos y tu página estará disponible en:
     `https://tu-usuario.github.io/catalogo/`

### Opción 2: Usando Git desde la Terminal (Más profesional)

1. **Inicializar Git en tu proyecto:**

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Catálogo PDF"
   ```

2. **Crear repositorio en GitHub:**

   - Ve a [github.com](https://github.com) y crea un nuevo repositorio (sin inicializar)
   - Copia la URL del repositorio (ejemplo: `https://github.com/tu-usuario/catalogo.git`)

3. **Conectar y subir:**

   ```bash
   git branch -M main
   git remote add origin https://github.com/tu-usuario/catalogo.git
   git push -u origin main
   ```

4. **Activar GitHub Pages:**
   - Ve a Settings → Pages en tu repositorio
   - Selecciona la rama `main` y la carpeta `/ (root)`
   - Guarda los cambios

## 📝 Notas Importantes

- El archivo debe llamarse `index.html` (ya está correcto)
- El PDF debe estar en la misma carpeta raíz
- GitHub Pages puede tardar 1-5 minutos en actualizar los cambios
- La URL será: `https://tu-usuario.github.io/nombre-del-repositorio/`

## 🔄 Actualizar el Catálogo

Si necesitas actualizar el PDF:

1. Reemplaza `catalogo.pdf` con el nuevo archivo
2. Sube el archivo nuevo al repositorio (usando la interfaz web o Git)
3. Espera unos minutos para que GitHub Pages actualice
