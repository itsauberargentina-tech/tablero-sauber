# Tablero Sauber

## Descripción
Este proyecto funciona como un enrutador para el tablero de telemetría y métricas automatizadas de Sauber. Desarrollado como un entorno web estático en HTML y JavaScript[cite: 4, 5], su función principal es alternar automáticamente cada 30 segundos entre dos reportes alojados en Power BI (Presentismo y Licitaciones). Actualmente se encuentra desplegado en la nube mediante GitHub Pages.

## Arquitectura y Funcionamiento
El archivo `index.html` contiene un script que lee los parámetros de la URL para determinar qué tablero debe mostrarse. Utiliza temporizadores de JavaScript para programar la rotación y redirige a los visores de Power BI inyectando el parámetro `chromeless=1`, garantizando una visualización a pantalla completa sin los marcos de la plataforma.

## Requisitos Previos e Instalación
Al ser un proyecto de frontend estático, no requiere instalación de motores ni entornos virtuales complejos. Únicamente se necesita:
* Un navegador web moderno.
* Un editor de código (como VS Code) para realizar modificaciones.

## Ejecución Local
Para visualizar o probar la lógica del tablero localmente, simplemente basta con abrir el archivo `index.html` directamente en el navegador.