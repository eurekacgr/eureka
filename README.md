# EUREKA – Sitio web oficial

> Este es el sitio web del **Eureka Team** (CGR). Aquí se publican y organizan los materiales del proyecto: páginas informativas, presentaciones, imágenes y videos de demostración.

---

## Tabla de contenido
- [🌟 Objetivo](#-objetivo)
- [📁 Estructura del repositorio](#-estructura-del-repositorio)
- [🚀 Vista rápida (Quick Start)](#-vista-rápida-quick-start)
- [🌐 Publicación con GitHub Pages](#-publicación-con-github-pages)
- [📄 Licencia](#-licencia)

---

## 🌟 Objetivo
Centralizar el **sitio público** del equipo y servir como punto de acceso a:
- Presentaciones y demos del proyecto.
- Material visual (imágenes, logos, capturas y videos).
- Páginas informativas del equipo y las iniciativas.

---

## 📁 Estructura del repositorio

```
eureka/
├─ index.html              # Página principal del sitio
├─ presentacion.html       # Página con la presentación / demo
├─ media/                  # Recursos estáticos (imágenes, videos, logos)
│  ├─ img/                 # (Opcional) subcarpeta para imágenes
│  ├─ video/               # (Opcional) subcarpeta para videos
│  └─ docs/                # (Opcional) PDFs u otros adjuntos
└─ README.md               # Este archivo
```

- index.html: landing principal del sitio.

- presentacion.html: sección dedicada a la presentación (puede abrirse desde botones como “Ver presentación”).

- media/: carpeta para todos los assets (banner, logos, capturas, videos, etc.). Mantén nombres claros y sin espacios.

## 🚀 Vista rápida (Quick Start)

### Clona el repo:
```
git clone https://github.com/eurekacgr/eureka.git
cd eureka
```

### Abre localmente:

- Doble clic en index.html (funciona offline).

- O sirve con un server estático (opcional):

### Python 3
```
python -m http.server 8080
```
- Luego abre http://localhost:8080

### 🌐 Publicación con GitHub Pages

- Ve a Settings → Pages. En Build and deployment, selecciona:

- Source: Deploy from a branch

- Branch: main (o la que uses) y carpeta /root.

Guarda y espera a que aparezca la URL pública del sitio.

> Cada vez que hagas push a main, GitHub Pages reconstruye el sitio automáticamente.

## 📄 Licencia

Uso interno como parte de la presentación de Innovatón
