# Sitio Web Educativo

Bienvenido al repositorio del sitio web educativo, una plataforma diseñada para facilitar el aprendizaje en línea con recursos educativos de calidad.

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de un sitio web educativo que ofrece recursos, herramientas y materiales de aprendizaje para estudiantes de diferentes niveles. El sitio está construido con tecnologías web estándar como HTML, CSS y JavaScript.

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── productos.html      # Página de productos/servicios
├── contacto.html       # Formulario de contacto
├── registro.html       # Página de registro de usuarios
├── img/               # Directorio para imágenes
│   └── banner.jpg     # Imagen del banner principal
└── README.md          # Este archivo
```

## Equipo de Desarrollo

### Equipo del Proyecto

- **Almeida Coello Byron Omar** - Desarrollador Frontend
- **Andrade Loor Thalia Mercedes** - Diseñadora UI/UX
- **Jaramillo Rivera John David** - Desarrollador Backend
- **Mora Quijije Yaritza Cristhel** - Gestora de Contenidos

## Capturas

<div class="screenshots-grid">
  <div class="screenshot-card">
    <h3>Página de Inicio</h3>
    <div class="screenshot-container">
      <img src="./img/capturas/inicio.jpg" alt="Página de Inicio">
    </div>
    <p class="screenshot-desc">Presentación de la marca y productos destacados</p>
  </div>

  <div class="screenshot-card">
    <h3>Página de Productos</h3>
    <div class="screenshot-container">
      <img src="./img/capturas/productos.png" alt="Página de Productos">
    </div>
    <p class="screenshot-desc">Explora nuestra variedad de productos educativos</p>
  </div>

  <div class="screenshot-card">
    <h3>Formulario de Contacto</h3>
    <div class="screenshot-container">
      <img src="./img/capturas/contacto.png" alt="Formulario de Contacto">
    </div>
    <p class="screenshot-desc">Contáctanos para más información</p>
  </div>

  <div class="screenshot-card">
    <h3>Página de Registro</h3>
    <div class="screenshot-container">
      <img src="./img/capturas/registro.png" alt="Página de Registro">
    </div>
    <p class="screenshot-desc">Únete a nuestra comunidad educativa</p>
  </div>
</div>

<style>
.screenshots-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.screenshot-card {
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  transition: transform 0.3s ease;
}

.screenshot-card:hover {
  transform: translateY(-5px);
}

.screenshot-container {
  padding: 1rem;
  background: #f8f9fa;
  text-align: center;
}

.screenshot-container img {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.screenshot-card h3 {
  margin: 0;
  padding: 1rem;
  background: #f1f3f5;
  color: #212529;
  font-size: 1.1rem;
}

.screenshot-desc {
  padding: 1rem;
  margin: 0;
  color: #495057;
  font-size: 0.9rem;
  line-height: 1.5;
}

@media (max-width: 768px) {
  .screenshots-grid {
    grid-template-columns: 1fr;
  }
}
</style>

## Cómo Contribuir

1. Haz un fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Haz commit de tus cambios (`git commit -am 'Añadir nueva característica'`)
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más información.

---
*Última actualización: Diciembre 2025*
