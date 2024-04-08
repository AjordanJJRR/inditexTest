# Servicio de Consulta de Precios en Comercio Electrónico

Este proyecto consiste en una aplicación/servicio desarrollado en SpringBoot que proporciona un endpoint REST para consultar precios en una base de datos simulada en memoria (tipo H2). La aplicación acepta parámetros de entrada como la fecha de aplicación, el identificador de producto y el identificador de cadena, y devuelve información sobre la tarifa aplicable, las fechas de aplicación y el precio final.

## Ejemplo de Uso

Para utilizar el servicio, se pueden enviar solicitudes HTTP al endpoint REST con los parámetros adecuados. A continuación, se muestran algunos ejemplos de solicitudes:

- **Petición 1:** Consulta a las 10:00 del día 14 del producto 35455 para la cadena 1 (ZARA).
- **Petición 2:** Consulta a las 16:00 del día 14 del producto 35455 para la cadena 1 (ZARA).
- **Petición 3:** Consulta a las 21:00 del día 14 del producto 35455 para la cadena 1 (ZARA).
- **Petición 4:** Consulta a las 10:00 del día 15 del producto 35455 para la cadena 1 (ZARA).
- **Petición 5:** Consulta a las 21:00 del día 16 del producto 35455 para la cadena 1 (ZARA).

## Requisitos

Para ejecutar este servicio, se recomienda tener instalado Java 11 o superior.

## Instrucciones de Ejecución

1. **Clonar este repositorio.**
2. **Importar el proyecto en un IDE compatible con SpringBoot.**
3. **Ejecutar la aplicación desde el IDE o mediante el comando `./mvnw spring-boot:run`.**
4. **El servicio estará disponible en la dirección `http://localhost:8080`.**

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

- **src/main/java:** Contiene el código fuente de la aplicación.
- **src/main/resources:** Contiene archivos de configuración y datos de prueba.
- **src/test/java:** Contiene las pruebas unitarias y de integración.

## Tecnologías Utilizadas

- SpringBoot
- Spring Data JPA
- Lombok
- Oracle Driver
- Validación de datos
- Spring Boot Dev Tools

## Desarrollo y Pruebas

El desarrollo de este proyecto sigue las mejores prácticas de diseño y construcción de servicios REST. Se han incluido pruebas unitarias y de integración para validar el funcionamiento correcto del servicio en diferentes escenarios.

## Contribución

Las contribuciones son bienvenidas. Si desea contribuir a este proyecto, por favor abra un problema o envíe una solicitud de extracción con sus cambios propuestos.

## Licencia

Este proyecto está bajo la licencia MIT. Consulte el archivo LICENSE para obtener más detalles.
