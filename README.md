# COIL - Página Informativa sobre Emprendimiento

## Tecnologías Utilizadas
Pues para que la página se vea así de bien, usamos esto:
- **HTML5**: Pues la estructura de toda la vida.
- **CSS3 (Vanilla)**: Diseño premium con Glassmorphism, también metimos gradientes y animaciones.
- **JavaScript**: Entonces, aquí está la lógica de las partículas del fondo y el scroll suave.
- **Intersection Observer API**: Pues esto es para que las animaciones salten cuando vas bajando.

---

## Estructura del Proyecto
Pues así está organizado todo el cuento:
```text
PAGINA_WEB_INFORMATIVA_COIL/
├── CSS/
│   └── index.css          # Estilos globales y diseño de tarjetas.
├── HTML/
│   ├── index.html         # Pues la página principal.
│   ├── proyecto1.html     # Detalle del Proyecto 1.
│   ├── proyecto2.html     # Detalle del Proyecto 2.
│   └── proyecto3.html     # Detalle del Proyecto 3.
├── JS/
│   └── Index.js           # Fondo de partículas y animaciones.
└── README.md              # Pues este mismo archivo.
```

---

## Guía Para Agregar Información

### 1. Editar la Tarjeta en `index.html`
Busca la sección `<section id="Proyectos">`. Pues cada proyecto tiene un bloque así:
```html
<div class="Tarjetas-Proyectos fade-in-left">
    <
    <h3>Nombre de tu Proyecto</h3>
    <span class="team"> Integrante 1 & Integrante 2</span>
    <p>Breve descripción pues para que se entienda la idea.</p>
    <button class="proyecto-btn" onclick="window.location.href='proyectoX.html'">
        Ver Proyecto →
    </button>
</div>
```

### 2. Llenar la Página de Detalle (`proyecto1.html`, etc.)
Entonces, abre el archivo de tu proyecto en la carpeta `HTML/`. Pues ahí tienes que cambiar:
- **Resumen:** Pues explicas de qué trata.
- **Objetivos:** ¿Qué quieren lograr, pues?
- **Público Objetivo:** ¿Para quién es, entonces?
- **Propuesta de Valor:** Pues lo que los hace diferentes.

### 3. Cambiar Estilos o Colores
También, si quieres cambiar los colores, pues te vas a `CSS/index.css` y cambias las variables de arriba:
- `--accent-color`: Pues el color principal.
- `--highlight-color`: También el color de los detalles.

---

## ✨ Funciones Especiales
- **Fondo Dinámico:** Pues las partículas que siguen al mouse.
- **Navegación Inteligente:** Entonces el menú sabe dónde estás.
- **Filosofía Reorganizada:** Pues pusimos tarjetas modernas con números.
- **Diseño Responsivo:** Pues se ve bien en el celular también.

---

## Notas Finales
- **Imágenes:** Si quieres meter fotos, pues crea una carpeta `assets/` y ya está.

## IMPORTANTE:
- **Scripts:** NO TOQUEN `Index.js` A MENOS QUE SEPAN QUÉ HACEN.

---