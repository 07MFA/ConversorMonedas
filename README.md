# Conversor de Monedas

Este proyecto es una aplicación escrita en Java que permite realizar conversiones entre diferentes monedas utilizando la API de ExchangeRate-API.

## Características

- Convierte entre las siguientes monedas:
  - Dólar (USD) y Peso Argentino (ARS)
  - Dólar (USD) y Real Brasileño (BRL)
  - Dólar (USD) y Peso Colombiano (COP)
- Interfaz simple basada en consola para seleccionar opciones y realizar conversiones.

## Requisitos

- Java 8 o superior.
- Una clave de API de [ExchangeRate-API](https://www.exchangerate-api.com/).
- Biblioteca [Gson](https://github.com/google/gson) para manejar JSON.

## Instalación

1. Clona este repositorio o descarga el código fuente.
2. Asegúrate de tener Java y el compilador `javac` instalados.
3. Incluye la biblioteca `Gson` en tu proyecto. Puedes hacerlo agregando el archivo `gson.jar` a tu classpath o utilizando un gestor de dependencias como Maven o Gradle.
4. Obtén tu clave de API desde [ExchangeRate-API](https://www.exchangerate-api.com/) y reemplaza `TU_API_KEY` en el código fuente con tu clave.

## Uso

1. Compila el archivo fuente:

    ```bash
    javac ConversorMonedas.java
    ```

2. Ejecuta la aplicación:

    ```bash
    java ConversorMonedas
    ```

3. Sigue las instrucciones en la consola para seleccionar la conversión deseada y proporcionar la cantidad a convertir.

4. Ingresa el numero "0" para salir del conversor.

## El proyecto continua en desarrollo
