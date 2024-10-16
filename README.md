<div align="center">

# Conversor de Monedas

</div>

<p align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=Por%20Mejorar&color=LIGHTBLUE&style=for-the-badge" />
   <img src="https://img.shields.io/badge/language-Java-007396?style=for-the-badge"/>
</p>

¡Bienvenido/a al Conversor de Monedas! Este es un proyecto desarrollado en Java que te permite convertir entre varias monedas utilizando el tipo de cambio actual proporcionado por la API [ExchangeRate-API](https://www.exchangerate-api.com/).

## Funcionalidades

Este conversor te permite realizar conversiones entre las siguientes monedas:

1. Dólar (USD) ➡️ Peso Argentino (ARS)
2. Peso Argentino (ARS) ➡️ Dólar (USD)
3. Dólar (USD) ➡️ Nuevo Sol Peruano (PEN)
4. Nuevo Sol Peruano (PEN) ➡️ Dólar (USD)
5. Euro (EUR) ➡️ Dólar (USD)
6. Dólar (USD) ➡️ Euro (EUR)

Al seleccionar una de las opciones del menú, te solicita ingresar un monto y se realiza la conversión de la moneda seleccionada utilizando la información más reciente de la API ExchangeRate-API.


## 🔧 Tecnologías Utilizadas

- **Lenguaje de programación**: Java ☕
- **Entorno de desarrollo**: IntelliJ IDEA 🖥️
- **Gson (de Google)**: Librería utilizada para convertir los datos JSON obtenidos de la API en objetos Java y viceversa.
- **Api Open Exchange Rates:** Para optener los tipos de cambios actualizados

## Requisitos

- **Java 8 o superior**: El proyecto está desarrollado en Java, por lo que necesitarás tener instalado el JDK.
- **IntelliJ IDEA**: El proyecto se creó y se probó utilizando este IDE.
- **Conexión a internet**: La aplicación utiliza una API en línea para obtener los tipos de cambio actualizados.

## Instalación y Ejecución

1. **Clonar el repositorio**: 
   ```bash
   git clone https://github.com/usuario/conversor-monedas.git

## 🏠 Estructura del Proyecto

* El proyecto está organizado en los siguientes paquetes:

1. **main:** Contiene la clase `Main` que maneja el flujo de la aplicación y un metodo `showConversion` donde se le pasa dos variables monedabase y monedacambio para imprimir todo el proceso.
2. **solicitarcambio**: Contiene la clase `SolicitarCambio` aqui se realiza la solicitud HTTP a la API, en este caso como "ExChangerate" nos facilita un endpoint donde podemos colocar el tipo de cambio y el monto y nos envia la conversión la utilizamos.  
3. **cambio:** Coniente el record `Cambio` donde guardaremos y consultaremos el resultado que nos trae la solicitud HTTP.


## ✒️ Autores 

[<img src="https://avatars.githubusercontent.com/u/82422415?v=4" width=115><br><sub>Kurt Angeles</sub>](https://github.com/kurttck)

## 😊 Contacto 

* [Linkedin](https://www.linkedin.com/in/kurt-angeles-segura/).
* [GitHub](https://github.com/kurttck).
