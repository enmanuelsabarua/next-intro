# Información sobre las siguientes tecnologías

## ESLint

Es una herramienta que nos ayuda a identificar y reportar patrones de códigos inadecuados con el fin de hacer nuestro código mas consistente y para evitar bugs.

## Tailwind CSS

Esta herramienta nos permite utilizar clases pre-construidas para facilitar y agilizar el diseño de nuestra aplicación web.

## Project Organization and File Colocation in NextJS

En la documentación se tratan diferentes temas los cuales incluyen:

- **Colocación segura por defecto:** En el directorio de la aplicación, la jerarquía de carpetas anidadas define la estructura de la ruta. Cada carpeta representa un segmento de ruta que se mapea a un segmento correspondiente en una ruta URL. Sin embargo, una ruta no es accesible públicamente hasta que se añade un archivo page.js o route.js a un segmento de ruta.

- **Carpetas privadas:** Puedes crear carpetas privadas añadiendo un guion bajo al principio del nombre de la carpeta: _nombreCarpeta. Esto indica que la carpeta es un detalle de implementación privado y no debe ser considerada por el sistema de enrutamiento.

- **Grupos de rutas:** Puedes crear grupos de rutas envolviendo una carpeta en paréntesis: (nombreCarpeta). Esto indica que la carpeta es para propósitos organizativos y no debe ser incluida en la ruta URL del camino.

- **Directorio src:** Next.js soporta almacenar el código de la aplicación (incluyendo app) dentro de un directorio src opcional.
