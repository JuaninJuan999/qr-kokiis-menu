# 🍔 Menú Digital Koky's - Comidas Rápidas

Menú digital interactivo para restaurante de comidas rápidas con integración directa a WhatsApp.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://juaninjuan999.github.io/qr-kokiis-menu/)
[![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)](https://pages.github.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🌐 Demo en Vivo

Visita el menú digital: [https://juaninjuan999.github.io/qr-kokiis-menu/](https://juaninjuan999.github.io/qr-kokiis-menu/)

## 📱 Características

- ✅ **Diseño Responsivo** - Adaptado para móviles, tablets y desktop
- ✅ **Integración WhatsApp** - Botón flotante y principal para pedidos directos
- ✅ **Galería Interactiva** - Modal para visualizar imágenes del menú ampliadas
- ✅ **Secciones Organizadas** - Promociones especiales y menú completo
- ✅ **Optimizado para QR** - Perfecto para códigos QR en mesas y carteles
- ✅ **Animaciones Suaves** - Efectos hover y transiciones profesionales
- ✅ **Iconos SVG** - WhatsApp oficial sin dependencias externas
- ✅ **SEO Básico** - Meta tags optimizados
- ✅ **Favicon Personalizado** - Logo en la pestaña del navegador

## 🚀 Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, Animaciones)
- JavaScript Vanilla
- GitHub Pages (Hosting)

## 📂 Estructura del Proyecto

qr-kokiis-menu/
├── index.html # Página principal
├── logo/
│ ├── logo.jpeg # Logo principal del header
│ └── favicon.png # Favicon del sitio
├── post.jpeg # Imagen promoción 1
├── 2.jpeg # Imagen promoción 2
├── promosalchipapas.jpeg # Imagen promoción 3
├── lashermanas.jpeg # Imagen promoción 4
├── menuhamburguesa.jpeg # Menú de hamburguesas
├── menupapas.jpeg # Menú de papas
├── menupicadas.jpeg # Menú de picadas
├── menuperros.jpeg # Menú de perros calientes
└── README.md # Este archivo

text

## 🎨 Capturas de Pantalla

### Desktop
![Desktop View](https://via.placeholder.com/800x400?text=Desktop+View)

### Móvil
![Mobile View](https://via.placeholder.com/400x800?text=Mobile+View)

## 🛠️ Instalación Local

Para trabajar con este proyecto localmente:

```bash
# Clonar el repositorio
git clone https://github.com/JuaninJuan999/qr-kokiis-menu.git

# Entrar al directorio
cd qr-kokiis-menu

# Abrir con tu editor favorito
code .

# O simplemente abrir index.html en tu navegador
📝 Personalización
Cambiar Número de WhatsApp
Busca y reemplaza en index.html:

xml
https://wa.me/573025683367
Actualizar Imágenes del Menú
Reemplaza las imágenes en la raíz del proyecto

Mantén los mismos nombres de archivo o actualiza las referencias en el HTML

Sube los cambios:

bash
git add .
git commit -m "Actualizar imágenes del menú"
git push
Modificar Colores
Busca estas variables en el CSS (dentro de <style>):

css
/* Naranja principal */
#ff6b35

/* Naranja secundario */
#f7931e

/* Verde WhatsApp */
#25D366
🚀 Despliegue
Este proyecto está configurado para desplegarse automáticamente en GitHub Pages.

Activar GitHub Pages
Ve a tu repositorio en GitHub

Settings → Pages

En Source, selecciona main branch

Selecciona / (root) folder

Click en Save

Tu sitio estará disponible en: https://[tu-usuario].github.io/qr-kokiis-menu/

Actualizar el Sitio
bash
# Hacer cambios en tu código local
# Agregar los cambios
git add .

# Commit
git commit -m "Descripción de los cambios"

# Push
git push

# Espera 2-5 minutos y tu sitio se actualizará automáticamente
📱 Generar Código QR
Para crear un código QR de tu menú:

Ve a QR Code Generator

Pega tu URL: https://juaninjuan999.github.io/qr-kokiis-menu/

Personaliza con tu logo (opcional)

Descarga en alta resolución (300+ DPI)

Imprime y coloca en tu restaurante

🎯 Uso
Para Clientes
Escanear el código QR con la cámara del celular

Navegar por las promociones y el menú completo

Hacer clic en el botón de WhatsApp para realizar el pedido

Click en las imágenes para verlas ampliadas

Para Administradores
Actualizar imágenes según promociones vigentes

Modificar número de WhatsApp si es necesario

Personalizar textos y colores según la marca

🔧 Mantenimiento
Agregar Nueva Promoción
Sube la nueva imagen al repositorio

Edita index.html, busca la sección de promociones:

xml
<div class="menu-item" onclick="openModal('nueva-promo.jpeg')">
    <img src="nueva-promo.jpeg" alt="Nueva Promoción" loading="lazy">
</div>
Guarda, commit y push

Eliminar una Promoción
Elimina la imagen del repositorio

Elimina el bloque correspondiente en el HTML

Guarda, commit y push

📊 Estadísticas del Proyecto
Tiempo de Carga: < 2 segundos

Tamaño Total: ~2-3 MB (depende de las imágenes)

Compatibilidad: Chrome, Firefox, Safari, Edge (últimas versiones)

Responsive: ✅ Móvil, Tablet, Desktop

🤝 Contribuciones
Las contribuciones son bienvenidas. Para cambios importantes:

Fork el proyecto

Crea una rama para tu feature (git checkout -b feature/AmazingFeature)

Commit tus cambios (git commit -m 'Add some AmazingFeature')

Push a la rama (git push origin feature/AmazingFeature)

Abre un Pull Request

📄 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo LICENSE para más detalles.

👤 Autor
JuaninJuan

GitHub: @JuaninJuan999

WhatsApp: +57 319 585 3885

🙏 Agradecimientos
Koky's - Comidas Rápidas por confiar en este proyecto

GitHub Pages por el hosting gratuito

Comunidad open source por las herramientas

📞 Contacto
Para consultas o soporte sobre este proyecto:

📱 WhatsApp: +57 3319 585 3885

🌐 Sitio Web: https://juaninjuan999.github.io/qr-kokiis-menu/
