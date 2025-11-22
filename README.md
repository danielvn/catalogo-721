# Catálogo PDF

Página web estática para visualizar y descargar un catálogo en formato PDF, optimizada para funcionar en navegadores de redes sociales.

## ✨ Características

- 📱 **Compatible con todas las redes sociales**: Instagram, Facebook, TikTok, WhatsApp, Twitter, LinkedIn, Snapchat, Telegram y más
- 🔍 **Detección automática** de navegadores in-app (funcionamiento silencioso)
- 💾 **Múltiples estrategias de descarga** con fallback automático
- ⚡ **Timeout inteligente** para evitar cargas infinitas (5 segundos)
- 📖 **Visualizador de PDF con scroll continuo** - todas las páginas visibles con scroll vertical
- 🖱️ **Navegación natural** - haz scroll con el ratón o desliza en móvil
- 📱 **100% responsive** para móviles, tablets y desktop
- ✨ **Interfaz limpia y profesional** sin alertas molestas
- 🚀 **Funciona simplemente haciendo clic** en el botón de descarga

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

## 🛠️ Solución de Problemas

### La descarga no funciona en Instagram/Facebook/TikTok

**Es normal:** Los navegadores in-app de redes sociales tienen restricciones de seguridad. La página está optimizada para funcionar en estos entornos.

**¿Qué hacer?**

1. Simplemente **toca el botón de descarga**
2. En algunos casos, el PDF se abrirá en una nueva pestaña dentro de la app
3. Si quieres descargarlo directamente a tu dispositivo:
   - Toca los **tres puntos (•••)** en la esquina superior
   - Selecciona **"Abrir en navegador"** o **"Abrir en Chrome/Safari"**
   - Ahora el botón de descarga funcionará al 100%

### No veo el PDF, solo un mensaje de carga

**Causas posibles:**

- Conexión lenta a internet
- Archivo PDF grande

**Solución:**

- Espera unos segundos, el PDF se cargará automáticamente
- Si persiste, abre la página en tu navegador web (Chrome, Safari, Firefox)
- Recarga la página

### El botón de descarga se queda "Descargando..."

**Solución:**

- La página tiene un timeout automático de 5 segundos
- Si tu conexión es muy lenta, el sistema usará un método alternativo automáticamente
- No te preocupes, el archivo se descargará de una u otra forma

## 🔒 Compatibilidad

### ✅ Navegadores Web (Compatibilidad Total)

- Chrome / Edge / Brave
- Safari
- Firefox
- Opera
- Samsung Internet

### ✅ Navegadores In-App de Redes Sociales (Optimizado)

- Instagram ✅
- Facebook ✅
- TikTok ✅
- WhatsApp ✅
- Twitter/X ✅
- LinkedIn ✅
- Snapchat ✅
- Telegram ✅

**Nota:** Los navegadores in-app pueden visualizar el PDF sin problemas. Para descargar directamente al dispositivo, es recomendable abrir en el navegador web usando el menú (•••) → "Abrir en navegador".
