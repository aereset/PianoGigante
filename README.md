# PianoGigante
Programa en PureData para que utilizar el piano gigante de Reset.

INSTRUCCIONES PARA CONECTAR EL PIANO Y QUE SUENE:
- Descargar PureData Extended de aquí: https://puredata.info/
- Cargar en un Arduino Mega el ejemplo de "StardardFirmata", de la librería Firmata que viene incluida con Arduino
- Abrir el programa de PureData "piano_botones"
- Cuando se abre el programa en PureData, arriba donde pone "serial port #" poner el COM que aparece en Arduino
- En la tabla de colores, poner como INPUT los pines del 30 al 42, pinchando en el cuadrado de la tabla para que se ponga en negro
- Si los pines son los que ponemos a continuación, no hay que hacer nada mas. Sino, habría que editar el programa para re-routear las señales a la nota correspondiente. Los pines son:

DO -> 37   
RE -> 36   
MI -> 35   
FA-> 34   
SOL -> 33  
LA -> 32
SI -> 31    
DO'-> 30    
DO# -> 41   
RE#-> 42  
FA# -> 38   
SOL# -> 39   
LA# -> 40
