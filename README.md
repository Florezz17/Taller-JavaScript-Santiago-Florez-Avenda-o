# PokéDex Interactiva ⚡

Este proyecto es una **PokéDex web** construida en **HTML, CSS y JavaScript** usando [PokéAPI](https://pokeapi.co/).  
Incluye dos versiones:

1. **Wiki Pokémon (Básica)** → Lista en tabla, paginación, modal de detalles.  
2. **PokéDex Avanzada** → Grid con tarjetas, filtros por tipo y generación, ordenamiento, favoritos, estadísticas y diseño oscuro.


## Características

### Versión Básica
- Paginación de Pokémon (10 por página).
- Tabla con **ID, imagen, nombre y tipos**.
- Botón “Ver Detalle” para abrir un **modal con estadísticas, habilidades y tipos**.
- Indicador de carga.
- Manejo simple de errores.

### Versión Avanzada
- **Barra de búsqueda** en tiempo real.
- **Filtros por tipo** (agua, fuego, planta, etc.).
- **Filtro por generación** (Kanto, Johto, Hoenn... hasta Paldea).
- **Ordenamiento** por ID, nombre, altura o peso.
- **Sistema de favoritos** (guardados en `localStorage`).
- **Grid responsivo** (1 columna en móvil, hasta 4 en desktop).
- **Modal de detalles** con estadísticas y habilidades.
- **Diseño oscuro** con colores morados y estilo moderno.

---

## 📂 Estructura del proyecto

│── taller.js/
│ │── index.html
│ │── styles.css
│ │── script.js
│ │── README.md (este archivo)
