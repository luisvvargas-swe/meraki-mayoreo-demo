# Meraki · Configurador mayorista

Aplicación de Luis Armando Vargas Peña basada en el selector de mayoreo de su proyecto universitario Meraki B2B. Esta implementación independiente, desarrollada con asistencia de IA, permite probar las reglas de volumen y descargar una solicitud de muestra. [Proyecto original](https://github.com/Luisvvargas/meraki-b2b) · [Reglas del catálogo usadas en esta versión](https://github.com/Luisvvargas/meraki-b2b/blob/00dcabb24cb939c96b71b674067f6a15ab9f9c81/src/data/product.ts)

[Probar la aplicación](https://luisvvargas-swe.github.io/meraki-mayoreo-demo/) · [Portafolio](https://luisvvargas-swe.github.io/)

## Preparar un borrador

1. Elige uno de los tres niveles e introduce una cantidad de botellas dentro del intervalo.
2. Selecciona un establecimiento de ejemplo y genera el borrador.
3. Descarga el archivo de texto con establecimiento, producto, nivel, cantidad y volumen total. Si cambias la cantidad o el establecimiento, genera un nuevo borrador.

El catálogo contiene vinagreta de tequila en botellas de 700 ml. La presentación de caja es de seis botellas y el selector acepta botellas individuales dentro de cada intervalo.

| Nivel | Botellas |
| --- | --- |
| Inicial | 6–11 |
| Restaurante | 12–23 |
| Hotelería | 24–999 |

Por ejemplo, 20 botellas equivalen a 14 litros y pertenecen al nivel Restaurante. El precio mayorista queda bajo petición. Los establecimientos son ficticios. El navegador genera la solicitud y su descarga de manera local.

## Ejecución local

Descarga el repositorio y abre `index.html`. La página, la ilustración en CSS y la lógica de validación funcionan sin instalar herramientas ni configurar cuentas. Las reglas y la generación del archivo de texto se encuentran en `app.js`.
