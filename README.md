# GOMAS DE SANDÍA

En este informe se abordará la sistematización del emprendimiento de gomas elaboradas a partir de la cáscara de sandía, destacando tanto el desarrollo del producto como las tecnologías que acompañarán el proceso.

## Hardware

Para iniciar, se ha planteado el diseño de un invernadero inteligente, orientado a producir sandías con un sabor más intenso y una cáscara de mejor textura, adecuada para la elaboración de las gomas. Este invernadero integrará sensores y sistemas de control que permitan monitorear variables críticas como temperatura, humedad, riego y nutrientes, optimizando las condiciones de cultivo.

El objetivo es generar un proyecto autosostenible, en el cual se combine el aprovechamiento de recursos naturales con la tecnología.
Ahora se explicara el hadware mas a fondo 

### Sensores 

Humedad del suelo (capacitivos): control de riego. <br>
pH y conductividad eléctrica (EC): control de fertilización.<br>
Temperatura y humedad ambiental (BME280/DHT22): regulación del microclima.<br>
Intensidad lumínica (BH1750): control de sombreamiento y luz suplementaria.<br>
CO₂ (MH-Z19): optimización de fotosíntesis.<br>
Refractómetro manual (°Brix): validación de dulzor en laboratorio de campo.<br>

### Actuadores

Válvulas solenoides para riego por goteo.<br>
Bombas peristálticas para fertirrigación.<br>
Ventiladores y extractores para control de temperatura.<br>
Sombrillas motorizadas o mallas retráctiles.<br>
Relés de control y fuente de alimentación segura.<br>

### Controladores

ESP32: lectura de sensores y control de actuadores.<br>
Raspberry Pi (opcional): gateway IoT y servidor local.<br>

### Costos Hadware 

| Ítem                                      | Cantidad | Precio unitario (USD) | Subtotal (USD) | Notas                                      |
|-------------------------------------------|:--------:|-----------------------:|---------------:|--------------------------------------------|
| ESP32 (placa de desarrollo)               |    2     |                   10   |            20  | Nodos de adquisición y control             |
| Sondas de humedad (capacitivas)           |    4     |                   10   |            40  | Una por zona/porcentaje de plantas         |
| Sensor pH + electrónica                   |    1     |                   40   |            40  | Calibrable                                 |
| Sensor EC (conductividad)                 |    1     |                   40   |            40  | Para fertirrigación                        |
| Sensor BME280 (temp + HR + presión)       |    1     |                   10   |            10  | Control microclima                         |
| Sensor CO₂ (MH-Z19 u equivalente)         |    1     |                   60   |            60  | Opcional según estrategia                  |
| Válvulas solenoides                       |    2     |                   30   |            60  | Riego por zonas                            |
| Bomba peristáltica (fertirrigación)       |    1     |                   50   |            50  | Dosificación de nutrientes                 |
| Raspberry Pi (gateway / broker opcional)  |    1     |                   70   |            70  | Broker MQTT, logging local                 |
| Material eléctrico e hidráulico           |    1     |                  150   |           150  | Tubos, conectores, cableado, válvulas etc. |
| Módulo relé (4/8 canales)                 |    1     |                   15   |            15  | Control de bombas/ventiladores             |
| Refractómetro portátil (°Brix)            |    1     |                   30   |            30  | Validación manual de dulzor                |
| ADC (ADS1115 u otro)                      |    1     |                   10   |            10  | Mejor lectura para sensores analógicos     |
| Fuente de alimentación (12/24 V)          |    1     |                   30   |            30  | Para bombas, válvulas y relés              |
| Caja estanca / montaje                     |    1     |                   40   |            40  | Protección de electrónica                  |
| **Total aproximado**                      |          |                        | **665**        | Precios aproximados — pueden variar        |

