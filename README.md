# ESP32_CNC_SHIELD_V1.2_30PIN
 30PIN VERSION OF CNC SHIELD
 
 ![My Image](Images/Esp32_Cnc_Shield_30Pin_Front.png)

Estaba buscando devkits para el ESP32_CNC_SHIELD y encontré uno de 30 pines. Miré la disposición de pines y coincide casi al 100%.
Lo que cambia son los 8 pines que son duplicados o no se usa, así que hize esta versión. Lo hize tan grande porque nesecito espacio para las pistas y se pierde siempre algo cuando lo corta en la fresadora. Si funciona bien hago una versión SMD para encargar.

Voy a verificar si necesito poner MOSFET en el Nebulizador(Mist) y igual añadir unos pines de 5 Voltios para los finales de carrera y el probe.

Acaba de comprobar que todo funciona con esta configuración y publiqué el GCan_Cnc_Shield.h para copiar en Machines.

En cuanto me llegue el modulo de tarjeta SD, lo instalaré y comprobar que funciona correctamente. 
Llegó hoy y lo instalé, funcionó a la primera.

Instalé este ESP_Cnc_Shield sustituyendo un arduino uno con Cnc-Shield y copié los ajustes del viejo al nuevo, cambiando los pasos limites y dirección de la iniciación (Homing). Una maravilla poder trabajar desde un navegador y tarjeta SD.

Lo siguiente será poner un fuente de alimencación(Step Down) de 24V a 5 Voltios que necesita el Vin del ESP32, para que sea totelmente autónomo.
