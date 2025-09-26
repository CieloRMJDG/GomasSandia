# GOMAS DE SANDÍA

En este informe se abordará la sistematización del emprendimiento de gomas elaboradas a partir de la cáscara de sandía, destacando tanto el desarrollo del producto como las tecnologías que acompañarán el proceso.

##  Introducción
La sandía (Citrullus lanatus) es una fruta ampliamente cultivada en climas cálidos.  
Generalmente, se consume su pulpa roja, mientras que la **cáscara** (que representa hasta un 30–40 % del peso total del fruto) suele desecharse.  

Este proyecto propone aprovechar la **cáscara de sandía** como materia prima para elaborar **gomitas**, aportando innovación, sostenibilidad y valor agregado.

---

## 1. Cultivo de la sandía
- **Clima:** cálido, entre 25–30 °C, sin heladas.  
- **Suelo:** arenoso o franco-arenoso, suelto y bien drenado (pH 6.0–6.8).  
- **Siembra:** directa o por trasplante, con distancias de 1.5–2 m entre plantas y 2–3 m entre hileras.  
- **Ciclo:** entre 80 y 120 días desde la siembra hasta la cosecha.  
- **Partes de la fruta:** pulpa (roja), semillas y cáscara (verde externa y blanca interna).  

---

## 2. Propuesta del proyecto
- **Problema identificado:** la cáscara de sandía suele desecharse, generando residuos orgánicos.  
- **Solución propuesta:** transformación de la cáscara en **gomitas de consumo humano**.  
- **Justificación:**  
  - Contiene fibra, antioxidantes (como citrulina), vitaminas y minerales.  
  - Reduce desperdicio agroindustrial.  
  - Impulsa la economía circular y el emprendimiento sostenible.  

---

## 3. Proceso productivo de las gomitas
1. **Recolección** de las cáscaras después del consumo de la pulpa.  
2. **Limpieza y pelado**, utilizando la parte blanca interna.  
3. **Cocción y ablandado** de la cáscara ya sea
en olla a presion
4. **Mezcla** con azúcar, gelatina o agar-agar (versión vegana) y saborizantes naturales.  
5. **Moldeado** en diferentes formas.  
6. **Secado/enfriado** para lograr la textura deseada.  
12. **Empaque** para conservación y comercialización.  

---

##  4. Beneficios del proyecto
- **Ambientales:** reducción de desechos orgánicos.  
- **Económicos:** creación de un producto innovador y comercializable.  
- **Sociales:** fomento al emprendimiento y desarrollo sostenible.  
- **Nutricionales:** aporte de fibra y antioxidantes normalmente desaprovechados.  

---

##  5. Conclusión del proyecto
El aprovechamiento de la cáscara de sandía para elaborar gomitas es una alternativa innovadora que combina sostenibilidad, nutrición y economía circular.  
Este proyecto demuestra cómo un residuo puede transformarse en un producto con valor agregado, generando beneficios para el medio ambiente y la sociedad.

---

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

