# Portfolio Hotel Sol · Agustín Scandolo

Portfolio personal con dos trabajos independientes:

- **Aplicación de escritorio:** consulta habitaciones, filtros y estados con Java 21, JavaFX y datos XML.
- **Experiencia web 3D:** recorrido inmersivo, fichas de habitaciones y asistente virtual Lucía. [Abrir la demo](https://neon-hummingbird-62cf0a.netlify.app/).

## Estructura

La página presenta cada trabajo en su propia sección. La experiencia 3D usa una captura real del recorrido. La primera parte desarrolla la aplicación de escritorio; la segunda presenta la experiencia web 3D.

## Abrir el portfolio

Abre index.html en un navegador moderno. No requiere instalación ni servidor. Google Fonts necesita conexión; si no está disponible, se usan fuentes locales de reserva.

## Ejecutar la aplicación Java

Necesitas JDK 21 y Maven 3.9 o posterior. Desde HotelSolReservas/HotelSolReservas, ejecuta:

    mvn clean javafx:run

La primera ejecución descarga las dependencias de JavaFX desde Maven Central.

## Publicarlo en un repositorio nuevo

Crea un repositorio vacío en GitHub y, desde esta carpeta, ejecuta:

    git init -b main
    git add .
    git commit -m "Añadir portfolio y experiencia web 3D"
    git remote add origin URL_DEL_REPOSITORIO_NUEVO
    git push -u origin main

La carpeta target/ de Maven queda excluida; el código fuente y pom.xml están incluidos.
