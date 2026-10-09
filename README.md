# Proyecto integrador: nodos sensores

Este repositorio contiene los proyectos de firmware de los nodos sensores y el
servicio de recepción de datos:

- `NodoSensor1/`: firmware ESP-IDF del nodo sensor LoRa.
- `NodoSensor2/`: firmware ESP-IDF del segundo nodo y archivos del servicio
  receptor en `server/`.

## Compilación

Abre el directorio del nodo deseado como proyecto ESP-IDF y compílalo con
`idf.py build` o desde la extensión ESP-IDF de VS Code.

## Configuración local

Los archivos `sdkconfig`, las carpetas de compilación y
`NodoSensor1/main/wifi_credentials_local.h` son locales y no se versionan.
Configura las credenciales Wi-Fi en tu entorno local usando
`NodoSensor1/main/wifi_credentials.example.h` como referencia.
