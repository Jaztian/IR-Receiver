# IR-Receiver

Un receptor IR puede detectar ráfagas de luz infrarroja enviadas por un control remoto común (como para un televisor), y luego emitir un patrón de señales altas/bajas a un pin de E/S de Propeller.

# Circuito

El receptor de infrarrojos necesita tres conexiones: 5 V, GND y un pin de E/S para leer la señal que envía. El circuito dentro del receptor infrarrojo hace que sea seguro conectar su pin de señal al pin Propeller I/O con una pequeña resistencia, aunque el sensor esté alimentado por 5 V.
