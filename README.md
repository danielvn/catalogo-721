# Catálogo PDF

Página web estática para visualizar y descargar un catálogo en formato PDF, optimizada para funcionar en navegadores de redes sociales.

## ✨ Características

- 📱 **Compatible con todas las redes sociales**: Instagram, Facebook, TikTok, WhatsApp, Twitter, LinkedIn, Snapchat, Telegram y más
- 🔍 **Detección automática** de navegadores in-app de redes sociales
- 💾 **Múltiples estrategias de descarga** con fallback automático
- ⚡ **Timeout inteligente** para evitar cargas infinitas
- 🎯 **Instrucciones contextuales** para abrir en navegador externo
- 📖 **Visualizador de PDF integrado** con navegación por páginas
- 📱 **100% responsive** para móviles, tablets y desktop
- ⚠️ **Alertas informativas** cuando se detecta un navegador in-app

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

**Solución:** Esto es normal. Los navegadores in-app de redes sociales tienen restricciones de seguridad. Cuando detectes el mensaje de alerta amarillo:

1. Toca los **tres puntos (•••)** en la esquina superior de la app
2. Selecciona **"Abrir en navegador"** o **"Abrir en Chrome/Safari"**
3. El catálogo se abrirá en tu navegador predeterminado y podrás descargarlo

### No veo el PDF, solo un mensaje de carga

**Causas posibles:**

- Conexión lenta a internet
- Navegador in-app bloqueando el contenido
- Archivo PDF muy grande

**Solución:**

- Abre la página en tu navegador web (Chrome, Safari, Firefox)
- Toca el botón "Cómo abrir" para ver instrucciones específicas

### El botón de descarga se queda "Descargando..."

**Solución:**

- La página tiene un timeout de 5 segundos
- Si tu conexión es lenta, intenta usar el botón "Cómo abrir"
- Abre la página directamente en un navegador web

## 🔒 Compatibilidad

### ✅ Navegadores Web (Compatibilidad Total)

- Chrome / Edge / Brave
- Safari
- Firefox
- Opera
- Samsung Internet

### ⚠️ Navegadores In-App (Funcionalidad Limitada)

- Instagram (requiere "Abrir en navegador")
- Facebook (requiere "Abrir en navegador")
- TikTok (requiere "Abrir en navegador")
- WhatsApp Web
- Twitter/X
- LinkedIn
- Snapchat
- Telegram

**Nota:** Los navegadores in-app pueden visualizar el PDF pero pueden tener restricciones para descargarlo directamente. Por eso incluimos detección automática y alertas con instrucciones.
