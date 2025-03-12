# VHDL_AI_YT1
Repositorio con el proyecto de Quartus y los prompts utilizados en los videos de YouTube sobre cómo utilizar la Inteligencia Artificial para generar VHDL para FPGA y CPLD.

Enlaces a los videos:

# PRUEBA 1 (Multiplexor de 8 a 1):
Genera el código en VHDL totalmente compatible con Quartus de:
Un multiplexor de 8 a 1. La entidad deberá tener únicamente:
-8 entradas de datos separadas, nada de vectores o buses. Estas entradas son activas a nivel bajo, es decir que cuando hay presente en las entradas de datos un 0, este debería interpretarse como un 1 y viceversa
-3 entradas de selección de datos, nada de vectores o buses.
-Una única salida de datos
No habrá ninguna entrada auxiliar como enable o reset.
La entidad debe llamarse mux8q

# PRUEBA 2 (Divisor de frecuencia /50k):
Dame el codigo VHDL totalmente compatible con quartus de:
Un divisor de frecuencia cuya señal de entrada irá a 50 Mhz. La salida será de 1 hz.
No habrá más entradas ni salidas auxiliares como enable, reset ni nada parecido.
La entidad debe llamarse divfrecq

# PRUEBA 3 (Generador PWM de 8 bits a 1kHz controlado por pulsadores):
Genera el código VHDL totalmente compatible con quartus de:
Una entidad que genera una señal PWM:
-La entidad deberá tener una entrada de reloj de 50MHz 
-8 entradas separadas, serán 8 pines diferentes (sin vectores ni buses), activos a nivel bajo, que en función del número que codifique se generará un factor de trabajo comprendido entre 0 y 100% (entre 0 y 255). 
-Una señal de salida modulada por anchura de pulso en función del valor de las 8 entradas descritas anteriormente. La señal será de 1khz 
-La entidad no tendrá más entradas ni salidas auxiliares tipo reset o enable
La entidad debe llamarse pwmq
