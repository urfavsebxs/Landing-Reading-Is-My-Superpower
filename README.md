<!--
  README para Landing-Reading-Is-My-Superpower
  Generado automáticamente — editalo para ajustar textos y enlaces.
-->

# 📚 Reading Is My Superpower - Landing

![GitHub stars](https://img.shields.io/github/stars/urfavsebxs/Landing-Reading-Is-My-Superpower?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/urfavsebxs/Landing-Reading-Is-My-Superpower?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/urfavsebxs/Landing-Reading-Is-My-Superpower?style=flat-square)
![Last commit](https://img.shields.io/github/last-commit/urfavsebxs/Landing-Reading-Is-My-Superpower?style=flat-square)
![Astro](https://img.shields.io/badge/Astro-5.12.9-0cf?style=flat-square&logo=astro)
![Node](https://img.shields.io/badge/Node-%3E=%2018.20.8-brightgreen?style=flat-square&logo=node.js)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square&logo=github)

Una landing hecha con Astro para el proyecto "Reading Is My Superpower" — un sitio ligero para mostrar cómics y contenido relacionado con la lectura.

## ✨ ¿Qué hay aquí?

- Página principal con comics y recursos.
- Dashboard y sistema de voto (backend mínimo usando Express + MongoDB).
- Login simple para gestionar votos y usuarios.

## 🧰 Tecnologías

- Astro
- TailwindCSS
- Node.js (>= 18.20.8)
- Express
- MongoDB

> La versión de Astro y el `node` requerido se toman de `package.json`.

## 🚀 Ejecutar en desarrollo

1. Clona el repositorio:

	git clone https://github.com/urfavsebxs/Landing-Reading-Is-My-Superpower.git
	cd Landing-Reading-Is-My-Superpower

2. Instala dependencias (usa pnpm, npm o yarn según prefieras):

	pnpm install

3. Ejecuta en modo desarrollo:

	pnpm run dev

Abre http://localhost:3000 (o el puerto que muestre Astro).

## 🧪 Construir y producción

Para compilar:

	pnpm run build

Iniciar la versión compilada:

	pnpm run start

## 📁 Estructura principal

- `src/pages/` - Páginas de Astro (index, comic, dashboard, login).
- `src/lib/` - Lógica compartida y conexión a BD (`db.js`).
- `src/model/` - Colecciones y modelos para usuarios, votos y códigos.
- `public/` - Assets públicos (comics, PDF, fonts, videos).

## 🤝 Contribuir

¿Quieres ayudar? Genial. Abre un issue o envía un pull request. Algunas ideas:

- Mejorar la accesibilidad del sitio.
- Agregar tests o CI.
- Añadir más contenidos/comics y optimizar imágenes.

Checklist mínima para PRs:

- Código linted y que compila.
- Cambios documentados en `README.md` cuando aplique.

## 📜 Licencia

Este repositorio no declara una licencia en `package.json`. Si quieres publicar o compartir públicamente este proyecto, considera añadir una licencia (por ejemplo MIT) y actualizar `package.json`.

## ✉️ Contacto

Si necesitas contactarme o reportar un bug abre un issue en GitHub.

---

Gracias por visitar este proyecto. ¡A leer! 📖✨

