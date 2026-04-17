# Patitas Felices 🐾

## Descripción del Proyecto

**Patitas Felices** es un sitio web diseñado para un refugio de animales de compañía. La plataforma permite a los visitantes:

- Explorar animales disponibles para adopción (perros y gatos)
- Conocer historias personalizadas de cada animal rescatado
- Ver información de salud y comportamiento de los animales
- Acceder a una galería de eventos y rescates
- Conocer la misión y labor del refugio
- Encontrar formas de colaborar: adoptar, donar y participar como voluntario
- Ponerse en contacto con la organización

El sitio contiene perfiles detallados de animales adoptables, distinguiendo entre los disponibles para adopción y los ya adoptados.

## Características Principales

- **Página de Inicio**: Banner principal con opciones rápidas de navegación
- **Galería**: Fotos de rescates y eventos del refugio
- **Perfiles de Animales**: Información completa de cada mascota:
  - Historia personal
  - Estado de salud (vacunas, desparasitación, etc.)
  - Descripción de comportamiento
  - Estado de adopción
- **Navegación intuitiva**: Menú superior con acceso a todas las secciones

## Instrucciones de Ejecución

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación de dependencias adicionales

### Pasos para ejecutar

1. **Descargar o clonar el proyecto**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd Patitas-felices
   ```

2. **Abrir en el navegador**
   - Opción 1: Hacer doble clic en el archivo `index.html`
   - Opción 2: Abrir una terminal en la carpeta del proyecto y ejecutar:
     ```bash
     start index.html
     ```
   - Opción 3: Usar un servidor local (recomendado):
     ```bash
     python -m http.server 8000
     ```
     Luego abrir el navegador en `http://localhost:8000`

3. **Navegar por el sitio**
   - Desde la página de inicio, utilizar el menú de navegación
   - Hacer clic en "Galería" para ver fotos de rescates
   - Hacer clic en "Adopta" para ver animales disponibles
   - Consultar la sección "Conócenos" para conocer la misión del refugio

## Estructura de Archivos

```
Patitas-felices/
├── index.html           # Página principal
├── galeria.html         # Galería de eventos y rescates
├── Bella.html           # Perfil de animal: Bella
├── Max.html             # Perfil de animal: Max
├── Luna.html            # Perfil de animal: Luna
├── Milo.html            # Perfil de animal: Milo
├── Nina.html            # Perfil de animal: Nina
├── Rex.html             # Perfil de animal: Rex
├── Rocky.html           # Perfil de animal: Rocky
├── Toby.html            # Perfil de animal: Toby
├── styles.css           # Estilos principales
├── Adoptado.css         # Estilos para animales adoptados
├── Disponible.css       # Estilos para animales disponibles
├── img/                 # Carpeta de imágenes
└── README.md            # Este archivo

```

## Tecnologías Utilizadas

- **HTML5**: Estructura y contenido
- **CSS3**: Diseño y estilos responsivos
- **Imágenes externas**: Almacenadas en servicios como Unsplash y Pinimg

## Notas Importantes

- El sitio utiliza imágenes de fuentes externas (URLs de internet)
- Los botones de adopción están deshabilitados con propósitos de demostración
- El diseño es responsivo y se adapta a diferentes tamaños de pantalla

## Contacto y Colaboración

Para colaborar con Patitas Felices, puedes:
- Adoptar un animal visitando la sección de adoptables
- Donar para apoyar el refugio
- Participar como voluntario
- Contactar a través del formulario en la página principal

---


