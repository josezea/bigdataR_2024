
<div align="center">
    <img src="https://github.com/user-attachments/assets/26d27ab1-5508-43c5-a095-7c182174d11d" width="25%" />
</div>

# Proyecto de Big Data con R 🚀

¡Bienvenido a este emocionante proyecto de Big Data utilizando R! 🎉 Aquí exploraremos cómo R se puede integrar con herramientas poderosas como Google BigQuery y varios paquetes diseñados para manejar grandes volúmenes de datos. Esta charla está en enmarcada en el evento más grande de ciencia de datos de Colombia: https://stadatahub.com/

## ¿Por qué R para Big Data? 🤔

R no solo es un lenguaje estadístico, sino que también cuenta con un ecosistema robusto para el análisis de Big Data. Entre sus características más destacadas están:

- **Integración con BigQuery**: R puede conectarse fácilmente a Google BigQuery, permitiendo realizar consultas sobre grandes conjuntos de datos sin necesidad de descargarlos localmente. 🌐
- **Paquete `arrow`**: Este paquete permite una eficiente lectura y escritura de datos en formato Apache Arrow, lo que facilita el manejo de grandes volúmenes de datos. 📊
- **Paquete `duckdb`**: DuckDB es un motor de base de datos en memoria que permite realizar consultas SQL sobre grandes conjuntos de datos de manera eficiente. 🦆

## Datos 📊
- Pueden encontrar los datos en: [https://www.dropbox.com/scl/fo/8v04ytxh4g0pj32ir4c3l/AA3N_RMBtV916MXXoe_4stA/hogares?dl=0&rlkey=l5upmb0deodayh8lzzzrzfihm&subfolder_nav_tracking=1](https://www.dropbox.com/scl/fo/8v04ytxh4g0pj32ir4c3l/AFJvfv9KnhwfN5TJC2ztwZc?rlkey=l5upmb0deodayh8lzzzrzfihm&st=yq6tykok&dl=0)

- https://microdatos.dane.gov.co/index.php/catalog/643/data-dictionary

## Configuración del Entorno 🛠️

Para comenzar, asegúrate de tener instalados los siguientes paquetes:

```R
install.packages("DBI")
install.packages("bigrquery")
install.packages("arrow")
install.packages("duckdb")
