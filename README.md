# GOMAS DE SANDÍA

En este informe se abordará la sistematización del emprendimiento de gomas elaboradas a partir de la cáscara de sandía, destacando tanto el desarrollo del producto como las tecnologías que acompañarán el proceso.

## Hardware

Para iniciar, se ha planteado el diseño de un invernadero inteligente, orientado a producir sandías con un sabor más intenso y una cáscara de mejor textura, adecuada para la elaboración de las gomas. Este invernadero integrará sensores y sistemas de control que permitan monitorear variables críticas como temperatura, humedad, riego y nutrientes, optimizando las condiciones de cultivo.

El objetivo es generar un proyecto autosostenible, en el cual se combine el aprovechamiento de recursos naturales con la tecnología.
Ahora se explicara el hadware mas a fondo 

### Sensores 

Humedad del suelo (capacitivos): control de riego.
pH y conductividad eléctrica (EC): control de fertilización.
Temperatura y humedad ambiental (BME280/DHT22): regulación del microclima.
Intensidad lumínica (BH1750): control de sombreamiento y luz suplementaria.
CO₂ (MH-Z19): optimización de fotosíntesis.
Refractómetro manual (°Brix): validación de dulzor en laboratorio de campo.

### Actuadores

Válvulas solenoides para riego por goteo.
Bombas peristálticas para fertirrigación.
Ventiladores y extractores para control de temperatura.
Sombrillas motorizadas o mallas retráctiles.
Relés de control y fuente de alimentación segura.

### Controladores

ESP32: lectura de sensores y control de actuadores.
Raspberry Pi (opcional): gateway IoT y servidor local.
