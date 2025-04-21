# Taller HTML - Mateo Herrera Londoño -APIpokemon

## Descripción del proyecto

Este proyecto es una aplicación web sencilla desarrollada con HTML, CSS y JavaScript, que permite buscar información de cualquier Pokémon en tiempo real utilizando la API pública PokeAPI. La aplicación muestra datos relevantes como nombre, tipo, habilidades, estadísticas y más.

Fue creado como parte de un taller práctico con el objetivo de aplicar los conocimientos adquiridos sobre consumo de APIs y diseño responsivo básico.

## ¿Cómo usar esta aplicación?

1. Abre `pokenapi.html` en tu navegador.
2. Ingresa el nombre de un Pokémon en el campo de búsqueda.
3. Presiona el botón "Buscar" o simplemente la tecla Enter para ver la información del Pokémon.
4. Visualiza los detalles del Pokémon como su imagen, habilidades, estadísticas, hábitat y evolución.

## Funcionalidades Principales

- Búsqueda por nombre (insensible a mayúsculas).
- Muestra habilidades, movimientos, estadísticas, tipo, altura, peso y más.
- Imagen oficial del Pokémon.
- Mensajes de error personalizados en caso de escritura incorrecta o si el Pokémon no existe.
- Estilos visuales amigables y responsivos con CSS.

## Tecnologías utilizadas

- HTML5 – Estructura de la aplicación.
- CSS3 – Estilización básica y diseño visual.
- JavaScript – Lógica, consumo de API.
- PokeAPI – API RESTful pública para obtener los datos de los Pokémon.

## Consideraciones adicionales

- Se utiliza Promise.all para realizar dos peticiones simultáneas: una para obtener los datos generales del Pokémon y otra para detalles adicionales como evolución, hábitat y tasa de captura.
- Se incluyó validación de entrada para mejorar la experiencia del usuario.
- El diseño está centrado para una visualización cómoda en pantallas de escritorio.

## Archivos incluidos

- index.html: Código principal de la aplicación.
- style.css: Hojas de estilo para el diseño visual.
- No se requiere instalación de frameworks adicionales.

## Autor

Mateo Herrera Londoño  
Correo: mateo.herrera2@udea.edu.co
