# sensor-temperatura-con-Wemos-D1-mini
Este es un programa para utilizar con la tarjeta Wemos D1 Mini.
Utiliza 6 sensores de temperatura 18B20 para tomar la temperatura de IDA y de RETORNO de cada una de las 3 zonas 
de radiadores que tiene la casa.

Utiliza una LDR (resistencia variable con la luz) para saber cuando se enciende la caldera y consume gas.

Las metricas de los sensores de temperatura y de luz (LDR) se envian mediante el protocolo MQTT a un servidor.
Esas metricas son recogidas por NODE-RED y guardadas en una base de datos de POSTGRESQL.

