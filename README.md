# coltrane-prime-theme

Funcionalidades Principales
---------------------------

*   **Theme Personalizado:** Incluye estilos y componentes diseñados para mejorar la apariencia y la experiencia del usuario en aplicaciones web.
    
*   **Soporte Multi-Framework:** Este theme está diseñado inicialmente para Angular, pero se planea expandir su compatibilidad a otros frameworks como React y Vue.js en futuras versiones.
    
*   **Fácil Integración:** Los desarrolladores pueden clonar este repositorio y seguir las instrucciones sencillas para incorporar el theme en sus proyectos existentes.


Instalación
-----------

Sigue estos pasos para integrar el theme en tu proyecto Angular:

1.  **Clona el Repositorio:**
    
    ```javascript
    
    git clone https://github.com/tu-usuario/tu-repositorio.git

    ```
2. **Agregar carpeta del theme en el tu proyecto primeNg:**
    En tu proyecto primeNg existe una carpeta en node_modules/primeng/resources/themes
    
Estilos
-------

Los estilos del tema y del núcleo son archivos CSS necesarios para los componentes. Consulta la sección de Temas para ver la lista completa de temas disponibles y elegir el adecuado. Los estilos pueden importarse en el archivo angular.json o en el archivo src/styles.css.

### Con angular.json

```javascript

... "styles": [     "node_modules/primeng/resources/themes/coltrane-prime-theme/theme.css",     "node_modules/primeng/resources/primeng.min.css",     ... ]
```

### Con styles.css

En el archivo `styles.css`, añade las siguientes líneas:

cssCopy code

```css
@import "primeng/resources/themes/coltrane-prime-theme/theme.css";
@import "primeng/resources/primeng.css";

```

Estas instrucciones te indican cómo importar los archivos CSS necesarios para el tema y los estilos principales de los componentes. Asegúrate de seguir estos pasos para integrar correctamente los estilos en tu proyecto Angular.

Uso
---

Cada componente puede importarse individualmente para que solo incluyas lo que necesitas. La ruta de importación está disponible en la documentación del componente correspondiente.

### Ejemplo de Importación

Para importar el módulo `ButtonModule` en tu archivo de componente o módulo en Angular, añade la siguiente línea:

```javascript

import { ButtonModule } from 'primeng/button';

```

Este es solo un ejemplo, y puedes realizar importaciones similares para otros componentes según tus necesidades específicas. Consulta la documentación del componente correspondiente para obtener información detallada sobre las rutas de importación y cómo utilizar cada componente de manera efectiva en tu proyecto.
