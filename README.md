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
