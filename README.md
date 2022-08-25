# Informe_Tarea8
Resolución de ejercicios Capítulo 15 y 16 del Libro de Floyd (Octava edición)

### Circuitos RC (Capitulo 15)

### Circuitos RL (Capitulo 16)

### 1. OBJETIVOS

#### Objetivos generales

#### Objetivos especificos

### 2. MARCO TEORICO

## Circuitos RC (Capitulo 15)

#### Circuitos en Serie

![image](https://user-images.githubusercontent.com/105259381/185812920-55615ad1-1c6f-4f88-86ce-49aa9856df73.png)

#### Circuitos en Paralelo

![image](https://user-images.githubusercontent.com/105259381/186506868-d69bbb2b-310e-4fcf-b2c9-6fcb462d3bae.png)

![image](https://user-images.githubusercontent.com/105259381/186506681-563e88c0-7d06-47c1-a2fb-7521a9e7a08f.png)

#### CIrcuitos en Serie- Paralelo

La impedancia de componentes dispuestos en serie es más fácil de expresar en forma rectangular, y la impedancia de componentes dispuestos en paralelo se encuentra mejor utilizando la forma polar. 

El método es expresar primero cada impedancia de rama en forma rectangular y luego convertir cada una de estas impedancias a forma polar. A continuación, se calcula cada corriente de rama utilizando notación polar. Una vez que se conocen las corrientes de rama, se puede encontrar la corriente total sumando las dos corrientes de rama en forma rectangular. En este caso particular, no se requiere la impedancia total.

Ejemplo: 

Determine todas las corrientes mostradas en la figura. Trace un diagrama fasorial de corriente.

![image](https://user-images.githubusercontent.com/105259381/186515912-a6271bfb-5c1b-4400-bea1-db36ce1d65b0.png)

![image](https://user-images.githubusercontent.com/105259381/186515550-4d452156-95e8-48c9-9ee5-4fa3438093c3.png)

![image](https://user-images.githubusercontent.com/105259381/186515598-5073d385-6e7f-4b4e-8f6d-656943e6d24b.png)

![image](https://user-images.githubusercontent.com/105259381/186515725-2d236cb7-e24e-421e-8649-cc5c9b1c76ad.png)

![image](https://user-images.githubusercontent.com/105259381/186518685-4fffeafa-e255-4840-83a8-fe36d41a02d8.png)

- Medición del ángulo de fase, θ

Para medir el ángulo de fase, el voltaje de la fuente y la corriente total deben aparecer en la pantalla del osciloscopio en la relación de tiempo apropiada. Dos tipos básicos de puntas de prueba están disponibles para medir las cantidades con un osciloscopio: la punta de prueba de voltaje y la punta de prueba de corriente. La punta de prueba de corriente es un dispositivo conveniente, pero a menudo no tan disponible como el de voltaje. La técnica de medición de fase se limitará al uso de puntas de prueba de voltaje junto con el osciloscopio. Aunque existen métodos de aislamiento especiales, una punta de prueba de voltaje tiene dos puntas que se conectan al circuito: la de detección y la de tierra. Por tanto, todas las mediciones de voltaje deben ser referidas a tierra. Como sólo se tienen que utilizar puntas de prueba de voltaje, no es posible medir la corriente directamente. Sin embargo, para mediciones de fase, el voltaje a través de R1 está en fase con la corriente total y puede ser utilizado para establecer el ángulo de fase de la corriente.

Se puede calcular el ángulo de fase con la siguiente ecuación:

![image](https://user-images.githubusercontent.com/105259381/186519405-0086720d-083c-4e92-8eef-b7be1ea3fadf.png)

#### Temas Especiales

Potencia en circuitos RC

En un circuito de ca puramente resistivo, la resistencia disipa toda energía suministrada por la fuente en forma de calor. En un circuito de ca puramente capacitivo, el capacitor guarda toda energía suministrada por la fuente durante una parte del ciclo de voltaje y luego la regresa a la fuente durante otra parte del ciclo, de modo que no hay conversión de energía en calor.

Cuando hay tanto resistencia como capacitancia, ésta guarda y regresa alternadamente una parte de la energía y la resistencia disipa otra parte.

Las fórmulas para el cálculo de la potencia en un resistor, en ocasiones llamada potencia real (Preal), y la potencia en un capacitor, llamada potencia reactiva (Pr)

![image](https://user-images.githubusercontent.com/105259381/186520326-eceefc7b-4011-4325-b7df-5c00ac9eff97.png)

El triángulo de potencia para circuitos RC

Un diagrama similar también puede representar una relación fasorial en el caso de potencias porque las magnitudes respectivas de éstas, Preal y Pr, difieren de R y XC por un factor de I2.

![image](https://user-images.githubusercontent.com/105259381/186520853-3ffdbd16-a3db-4114-8d25-55608c3f0679.png)

![image](https://user-images.githubusercontent.com/105259381/186521192-784c8f21-4f28-44a8-a77f-2b36c584addc.png)

El factor de potencia

El término cos θ se llama factor de potencia y se establece como

![image](https://user-images.githubusercontent.com/105259381/186521426-0b2dcf49-7324-45ec-8607-0a09965879fa.png)

Conforme el ángulo de fase entre el voltaje aplicado y la corriente total se incrementa, el factor de potencia disminuye, lo cual indica la existencia de un circuito crecientemente reactivo.

El oscilador de desplazamiento de fase

Un oscilador es un circuito que genera una forma de onda periódica, y resulta muy importante en muchos sistemas electrónicos. Se estudiarán los osciladores en cursos de dispositivos, por lo cual aquí el enfoque se concentra en la aplicación de circuito RC para desplazamiento de fase. El requerimiento es que una fracción de la salida del oscilador sea regresada hacia la entrada (llamada “retroalimentación”) en la fase apropiada para reforzar la entrada y mantener las oscilaciones. Por regla general, el requerimiento es retroalimentar la señal con un total de 180° de desplazamiento de fase.

## Circuitos RL (Capitulo 16)














### 3. EXPLICACIÓN O RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

## Resolución de los ejercicios Capitulo 15

#### PARTE 1: CIRCUITOS EN SERIE

#### SECCIÓN 15–1 El sistema de los números complejos

2. Localice los siguientes números en el plano complejo:

![image](https://user-images.githubusercontent.com/105259381/186541093-a0d7f7f0-e76a-451b-a112-d7e7e3705f89.png)

![image](https://user-images.githubusercontent.com/105259381/186541127-308fa9a7-b56e-4a22-8ace-7a0170e2471c.png)

![image](https://user-images.githubusercontent.com/105259381/186541169-76e77c24-1aa7-4eb0-8e92-2b536c50d9eb.png)

4. Determine las coordenadas de cada punto que tenga igual magnitud, pero esté localizado a 180° de cada uno de los puntos del problema 3.

![image](https://user-images.githubusercontent.com/105259381/186541362-8fc61df7-9839-4dd0-bb05-23ef67a40161.png)

6. A continuación se describen puntos localizados en el plano complejo. Exprese cada punto como un número complejo en forma rectangular:

(a) 3 unidades a la derecha del origen sobre el eje real, y 5 unidades hacia arriba sobre el eje j. 

![image](https://user-images.githubusercontent.com/105259381/186541454-f09f8ad7-ace8-4ba6-bc5f-eeaab94736c7.png)

(b) 2 unidades a la izquierda del origen sobre el eje real, y 1.5 unidades hacia arriba sobre el eje j. 

![image](https://user-images.githubusercontent.com/105259381/186541524-70405f06-2ccb-4e10-b5a0-87e612815020.png)

(c) 10 unidades a la izquierda del origen sobre el eje real, y 14 unidades hacia abajo sobre el eje -j.

![image](https://user-images.githubusercontent.com/105259381/186541570-4a4a0b3a-fec0-4e5a-a96f-c2edc44d6371.png)

8. Convierta cada uno de los siguientes números rectangulares a forma polar:

![image](https://user-images.githubusercontent.com/105259381/186541938-db3471d5-a2d2-4ae2-a5b6-8436e5cf70f7.png)

10. Exprese cada uno de los siguientes números polares utilizando un ángulo negativo para reemplazar al positivo.

![image](https://user-images.githubusercontent.com/105259381/186542496-0ee5c60c-f377-4de3-b673-0c430b2ecef2.png)

12. Identifique el cuadrante en el cual se localiza cada uno de los puntos del problema 10. 

![image](https://user-images.githubusercontent.com/105259381/186542760-b382cc28-3bc1-4e64-8e05-ddabe49c207b.png)

14. Sume los siguientes conjuntos de números complejos:

![image](https://user-images.githubusercontent.com/105259381/186542855-65250ad6-dae1-4e1f-9785-47071f6ae31d.png)

![image](https://user-images.githubusercontent.com/105259381/186543112-678940fc-84df-4be1-940e-0c8ab4a5f88d.png)

16. Multiplique los siguientes números:

![image](https://user-images.githubusercontent.com/105259381/186543434-633b9b41-781a-4a40-ba8d-e034be01226d.png)

![image](https://user-images.githubusercontent.com/105259381/186543644-7cefa308-d138-4d70-b081-8d329007d27d.png)

18. Realice las siguientes operaciones:

![image](https://user-images.githubusercontent.com/105259381/186543934-e0e4c6c6-917a-49b0-9e37-8c9edf1e0b9b.png)

![image](https://user-images.githubusercontent.com/105259381/186543967-33b030d5-b306-4b42-8a11-ae73066573be.png)

![image](https://user-images.githubusercontent.com/105259381/186543990-7f86a8ed-8fc4-452f-9833-4056d1a6077c.png)

#### SECCIÓN 15–2 Respuesta sinusoidal de circuitos RC en serie

20. ¿Cuál es la forma de onda de la corriente en el circuito del problema 19?

La corriente es sinusoidal

#### SECCIÓN 15–3 Impedancia de circuitos RC en serie

22. Determine la magnitud de la impedancia y el ángulo de fase en cada circuito de la figura 15-85.

![image](https://user-images.githubusercontent.com/105259381/186544194-8a54578a-aee9-4396-aab0-426051f9badd.png)

Para el literal a 

![image](https://user-images.githubusercontent.com/105259381/186544305-eebd89b8-e395-4cc3-9c8e-91cd7f8981e1.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/186544368-3f5eb9c7-69a9-44a1-be7f-97c1bdd898d0.png)

Para el literal c

![image](https://user-images.githubusercontent.com/105259381/186544532-6c0fa860-382c-4317-a7cb-fb81a3bf667e.png)

24. Repita el problema 23 con C= 0.0047 mF. 

![image](https://user-images.githubusercontent.com/105259381/186544610-009a0163-2a69-4755-a32b-7ba3e3c91758.png)

![image](https://user-images.githubusercontent.com/105259381/186544823-10b267d4-9bf4-4e64-a9d9-dd9dbb3b0738.png)

![image](https://user-images.githubusercontent.com/105259381/186544972-2c273728-8efc-4c6c-8da2-bb584d1bd076.png)

#### SECCIÓN 15–4 Análisis de circuitos RC en serie

26. Exprese la corriente en forma polar para cada circuito de la figura 15-84

![image](https://user-images.githubusercontent.com/105259381/186545164-101be6df-7108-403f-8e5f-f05ae49e8f17.png)

Para el literal a 

![image](https://user-images.githubusercontent.com/105259381/186545229-6bc9a21e-c294-41fc-be1b-9e68af29a4f3.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/186545267-3d61046d-34a2-4bfc-bc6c-0c1ccd28aa54.png)

28. Determine el ángulo de fase entre el voltaje aplicado y la corriente para cada circuito de la figura 15-85.

![image](https://user-images.githubusercontent.com/105259381/186545397-f7555613-e914-42f8-a55b-d3b48ebeb7d1.png)

Para el literal a 

![image](https://user-images.githubusercontent.com/105259381/186545745-c978df8e-69a3-46d3-bfa4-d49c19301575.png)

Para el literal b 

![image](https://user-images.githubusercontent.com/105259381/186545789-c5c23758-3569-4755-ba52-c2d195a9cda1.png)

Para el literal c

![image](https://user-images.githubusercontent.com/105259381/186545815-1dacc01e-20c2-41fd-bfff-ccb035d33b0e.png)

30. Para el circuito de la figura 15-87, trace el diagrama fasorial que muestre todos los voltajes y la corriente total. Indique los ángulos de fase.

![image](https://user-images.githubusercontent.com/105259381/186545883-4a260ab5-f1cf-49b8-879b-eaa8c3ef3c79.png)

![image](https://user-images.githubusercontent.com/105259381/186546002-9641bacd-60c5-4dd1-98ac-54322dc5e3cc.png)

Diagrama fasorial:

![image](https://user-images.githubusercontent.com/105259381/186546388-4c2fca24-c0f3-4d05-b028-569bf1a1bd26.png)

32. ¿A qué valor se debe ajustar el reóstato de la figura 15-89 para hacer que la corriente total sea de 10 mA? ¿Cuál es el ángulo resultante?

![image](https://user-images.githubusercontent.com/105259381/186546584-2f678ef4-20b1-4f4e-a3ec-fd275c635a78.png)

![image](https://user-images.githubusercontent.com/105259381/186546624-e4a8c28c-eb42-4654-8d9b-40c019cc7680.png)

34. Para el circuito de retraso de la figura 15-91, determine el desplazamiento de fase entre el voltaje de entrada y el voltaje de salida para cada una de las siguientes frecuencias:

![image](https://user-images.githubusercontent.com/105259381/186546685-ab51f48e-5c1f-4a34-95a9-792d21185021.png)

![image](https://user-images.githubusercontent.com/105259381/186547518-e8f8b377-79cd-4a6d-bdf2-a85814db5851.png)

36. Repita el problema 34 para el circuito de adelanto de la figura 15-92

![image](https://user-images.githubusercontent.com/105259381/186547656-fa38edd9-fa26-464c-a39f-262ab7d2babb.png)

![image](https://user-images.githubusercontent.com/105259381/186548006-40a40ad5-c3bf-4156-96ac-c809366a42d0.png)

38. Trace el diagrama fasorial de voltaje para el circuito de la figura 15-91 para una frecuencia de 5 kHz con Vs = 1 V rms. 

![image](https://user-images.githubusercontent.com/105259381/186548106-60d863ff-865f-4ddf-ad02-a27730e02ab3.png)

![image](https://user-images.githubusercontent.com/105259381/186548205-2882dea3-486f-4ae5-9907-d6db41501d14.png)

#### PARTE 2: CIRCUITOS EN PARALELO

#### SECCIÓN 15–5 Impedancia y admitancia de circuitos RC en paralelo 

40. Determine la impedancia y exprésela en forma polar para el circuito de la figura 15-93

![image](https://user-images.githubusercontent.com/105259381/186548326-3c31f9a2-e51c-4840-9db5-4c308f189e6b.png)

![image](https://user-images.githubusercontent.com/105259381/186548414-d671977f-5c1d-4d58-b0da-0ade6b8e8451.png)

42. Repita el problema 41 para las siguientes frecuencias:

![image](https://user-images.githubusercontent.com/105259381/186548481-9d20f8c3-7c30-48aa-9c2e-210d33abd68e.png)

![image](https://user-images.githubusercontent.com/105259381/186548746-e4062661-6538-404e-98e2-11ae6ab5c9aa.png)

![image](https://user-images.githubusercontent.com/105259381/186548782-61b5a594-eb21-4b34-ad7d-26d83a59625b.png)

#### SECCIÓN 15–6 Análisis de circuitos RC en paralelo

44. Para el circuito en paralelo de la figura 15-96, encuentre la magnitud de cada corriente de rama y la corriente total. ¿Cuál es el ángulo de fase entre el voltaje aplicado y la corriente total?

![image](https://user-images.githubusercontent.com/105259381/186548897-02cca0eb-cbaf-4f01-8fb7-afa34d893384.png)

![image](https://user-images.githubusercontent.com/105259381/186549004-2d126b14-13b3-4135-b12f-9202ee534f0f.png)

46. Repita el problema 45 con R =  5.6 kΩ, C1 = 0.047 mF, C2 = 0.022 mF, y f = 500 Hz

![image](https://user-images.githubusercontent.com/105259381/186549180-2d568f16-82af-42fe-9bb6-4981065e614e.png)

![image](https://user-images.githubusercontent.com/105259381/186549357-d7bed355-1fae-4aa9-b068-02df3271eef0.png)

48. Determine el valor al cual R1 debe ser ajustado para obtener un ángulo de fase de 30° entre el voltaje de fuente y la corriente total en la figura 15-99.

![image](https://user-images.githubusercontent.com/105259381/186549454-39ca36f0-980f-4254-a9ae-ea6c47e6d5b3.png)

![image](https://user-images.githubusercontent.com/105259381/186549635-11590807-9915-442b-82a0-ad3cafb1e710.png)

#### PARTE 3: CIRCUITOS EN SERIE-PARALELO

#### SECCIÓN 15–7 Análisis de circuitos RC en serie-paralelo

50. ¿Es el circuito de la figura 15-100 predominantemente resistivo o predominantemente capacitivo?

![image](https://user-images.githubusercontent.com/105259381/186550065-b7d2622e-04fe-4619-8fb7-4ab48cd9a83d.png)

![image](https://user-images.githubusercontent.com/105259381/186549877-1560ae7e-6dd2-44a3-8b42-f57e9e276ee1.png)

![image](https://user-images.githubusercontent.com/105259381/186550157-ad1fac4c-150a-485f-8d06-7a2ff56a76d8.png)

Por lo tanto, el circuito es predominantemente resistivo

52. Para el circuito de la figura 15-101, determine lo siguiente:

![image](https://user-images.githubusercontent.com/105259381/186550397-71299452-e51b-4d01-a065-bae18626025e.png)

![image](https://user-images.githubusercontent.com/105259381/186550491-b55696bc-9a89-4ff7-9ab3-bd724d7a7462.png)

![image](https://user-images.githubusercontent.com/105259381/186551155-8a586c44-9d0f-40d7-bb7b-8c9903c69b40.png)

![image](https://user-images.githubusercontent.com/105259381/186551838-58cf0694-c7b1-463e-a1f5-40293df95ca6.png)

54. Determine el voltaje y su ángulo de fase en cada punto rotulado en la figura 15-103.

![image](https://user-images.githubusercontent.com/105259381/186552118-29a9fe5f-1fe5-4679-a378-080e97f664ba.png)

![image](https://user-images.githubusercontent.com/105259381/186552254-5f4e4d2f-8ea4-4281-bf6b-f9d390aba00e.png)

![image](https://user-images.githubusercontent.com/105259381/186552326-e6111fa3-77a5-409a-b003-fada9faa63d2.png)

56. Trace el diagrama fasorial de voltaje y corriente para la figura 15-103. 

![image](https://user-images.githubusercontent.com/105259381/186552118-29a9fe5f-1fe5-4679-a378-080e97f664ba.png)

![image](https://user-images.githubusercontent.com/105259381/186552402-954933ee-329d-46ea-8e44-b06ace20bb8b.png)

#### PARTE 4: TEMAS ESPECIALES

#### SECCIÓN 15–8 Potencia en circuitos RC

58. En la figura 15-88, ¿cuáles son la potencia real y la potencia reactiva?

![image](https://user-images.githubusercontent.com/105259381/186552622-35b9e63e-ab57-4fbe-a42d-5dd858d8d2b7.png)

![image](https://user-images.githubusercontent.com/105259381/186552730-03a5c795-cdd5-400b-99f1-63d7a440915d.png)

60. Determine Preal, Pr, Pa, y FP para el circuito de la figura 15-101. Trace el triángulo de potencia.

![image](https://user-images.githubusercontent.com/105259381/186552896-88f47eea-b496-435d-b9f9-d7e61145ac28.png)

![image](https://user-images.githubusercontent.com/105259381/186553111-d2117754-d546-4fc8-8e03-9147c6540464.png)

![image](https://user-images.githubusercontent.com/105259381/186553212-03a359a8-6a90-4dd8-882b-7829ad973c99.png)

#### SECCIÓN 15–9 Aplicaciones básicas 

62. Calcule la frecuencia de oscilación para el circuito de la figura 15-62 si todos los capacitores son de 0.0022 mF y todos los resistores de 10 kΩ.

![image](https://user-images.githubusercontent.com/105259381/186553446-5822d6ae-0ac1-4e27-a5e2-d7d2a090bb16.png)

![image](https://user-images.githubusercontent.com/105259381/186553603-2d8cc610-86e8-47c6-bc99-103120328ca7.png)

64. El valor rms del voltaje de señal que sale del amplificador A en la figura 15-105 es de 50 mV. Si la resistencia de entrada al amplificador B es de 10 kΩ, ¿qué tanto de la señal se pierde debido al capacitor de acoplamiento cuando la frecuencia es de 3 kHz?

![image](https://user-images.githubusercontent.com/105259381/186553784-7ae20892-28ae-4045-87e3-c7c37d2e8fe6.png)

![image](https://user-images.githubusercontent.com/105259381/186554031-ada8d3ff-4e86-4243-8b32-55a134489edd.png)

La pérdida de señal es la caida de tensión en C

![image](https://user-images.githubusercontent.com/105259381/186554121-529d148b-3b6a-4995-94d5-9704b012fdad.png)

#### SECCIÓN 15–10 Localización de fallas

66. Los capacitores de la figura 15-107 han desarrollado un resistencia de fuga de 2 kÆ. Determine los voltajes de salida en esta condición para cada circuito.

![image](https://user-images.githubusercontent.com/105259381/186554291-80c3a9b9-2df9-4e93-8a3d-4e130bdf4ca0.png)

Para el literal a

![image](https://user-images.githubusercontent.com/105259381/186554509-79a35d39-38e5-4f17-bf07-b7be8d78973a.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/186554567-a28ed47e-90fa-4542-9588-958c4bbbd4a7.png)

68. Determine el voltaje de salida para el circuito de la figura 15-107(b) para cada uno de los siguientes modos de falla, y compárelo con la salida correcta:

![image](https://user-images.githubusercontent.com/105259381/186554291-80c3a9b9-2df9-4e93-8a3d-4e130bdf4ca0.png)

![image](https://user-images.githubusercontent.com/105259381/186555742-d739c99f-66ed-4202-b88a-d0f2616e3c52.png)

## Resolución de los ejercicios Capitulo 16

#### PARTE 1: CIRCUITOS EN SERIE

#### SECCIÓN 16–1 Respuesta sinusoidal de circuitos RL en serie

2. ¿Cuáles son las formas de onda de I, VR y VL en el problema 1?

I, VR y VL, son ondas de forma sinusoidal

#### SECCIÓN 16–2 Impedancia de circuitos RL en serie

4. Determine la magnitud de la impedancia y el ángulo de fase en cada circuito de la figura 16-55. Trace los diagramas de impedancia

![image](https://user-images.githubusercontent.com/105259381/186556314-a4bfc764-e56f-4b72-9717-127e105a4233.png)

Para el literal a

![image](https://user-images.githubusercontent.com/105259381/186556469-548d2816-5bc7-497d-a4b4-9cf25ac2a5cb.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/186556498-6f853548-4629-4b23-b21a-87f5ba76ecb9.png)

6. Determine los valores de R y XL en un circuito RL en serie con los siguientes valores de impedancia total:

![image](https://user-images.githubusercontent.com/105259381/186560178-f8794cfb-7aaf-4433-bcef-d47b1f661616.png)

#### SECCIÓN 16–3 Análisis de circuitos RL en serie

8. Se aplica un voltaje sinusoidal de 5 V, 10 kHz al circuito de la figura 16-57. Calcule el voltaje a través de la resistencia total encontrada en el problema 7.

![image](https://user-images.githubusercontent.com/105259381/186560922-a1f5fbec-87cc-451c-9a2f-6aecad70531a.png)

![image](https://user-images.githubusercontent.com/105259381/186560835-2cef46a8-41db-440c-b7dd-65ffeb551249.png)

10. Exprese la corriente en forma polar para cada circuito de la figura 16-54.

![image](https://user-images.githubusercontent.com/105259381/186564870-19bc917f-0ec3-41f8-a95c-63cbbf9ade51.png)

Para el literal a

![image](https://user-images.githubusercontent.com/105259381/186565062-f8b05c54-e080-49ff-998d-591579bb3aa5.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/186565112-efcf9d45-b194-443f-870c-2606406a04bd.png)

12. Determine u para el circuito de la figura 16-58

![image](https://user-images.githubusercontent.com/105259381/186565281-fdd33011-a6d2-46e4-850b-59498ab8c9cb.png)

![image](https://user-images.githubusercontent.com/105259381/186565385-c7e929ab-8a10-469c-a258-864e3c3095bf.png)

14. Trace las formas de onda de Vs, VR y VL en la figura 16-58. Muestre las relaciones de fase apropiadas.

![image](https://user-images.githubusercontent.com/105259381/186565508-b1d2538c-1b2f-4029-964a-0d6a15761506.png)

![image](https://user-images.githubusercontent.com/105259381/186565608-0f7ec1d2-79fc-461d-8e39-8c6033bb18a3.png)

16. Determine la magnitud y el ángulo de fase del voltaje de fuente en la figura 16- 60

![image](https://user-images.githubusercontent.com/105259381/186565923-211444d0-e9b0-48b1-b5ae-ca5a992a32b4.png)

![image](https://user-images.githubusercontent.com/105259381/186566341-47cb291e-838b-49db-939a-973c803af255.png)

18. Repita el problema 17 para el circuito de adelanto para encontrar el adelanto de fase en la figura 16-62

![image](https://user-images.githubusercontent.com/105259381/186566471-f4e2a889-7921-4551-985b-e1fcf7102321.png)

![image](https://user-images.githubusercontent.com/105259381/186568102-1d316160-a2f6-420e-8e5c-e7d67b24e177.png)

#### PARTE 2 CIRCUITOS EN PARALELO

#### SECCIÓN 16–4 Impedancia y admitancia de circuitos RL en paralelo

20. Repita el problema 19 para las siguientes frecuencias:

![image](https://user-images.githubusercontent.com/105259381/186568289-cfd0cfc4-a081-477f-b7de-add3f2f85723.png)

![image](https://user-images.githubusercontent.com/105259381/186568726-b82cc600-e099-4784-a3a2-0d98dd74c5cc.png)

![image](https://user-images.githubusercontent.com/105259381/186569995-901e06c2-f214-4a81-a79b-df1bf182f6f1.png)

![image](https://user-images.githubusercontent.com/105259381/186570445-805550f0-98b8-4e22-a19a-94deebaf8d35.png)

#### SECCIÓN 16–5 Análisis de circuitos RL en paralelo

22. Encuentre la corriente total y cada corriente de rama en la figura 16-64

![image](https://user-images.githubusercontent.com/105259381/186570658-f5355f1a-955a-4586-8221-6e1eb3d3d950.png)

![image](https://user-images.githubusercontent.com/105259381/186571124-a6531382-e937-4482-b27c-248675a18388.png)

24. Repita el problema 23 para R = 56 Ω y L = 330 µH.

![image](https://user-images.githubusercontent.com/105259381/186571283-21d11f75-6650-446f-8439-82ceeaa37df9.png)

![image](https://user-images.githubusercontent.com/105259381/186572228-b9001b7c-09c9-49c4-9619-d3f4107c1241.png)

![image](https://user-images.githubusercontent.com/105259381/186572284-bcc4d7e9-3f5d-4cc0-9f6a-05c88f6a114b.png)

26. Determine la magnitud y el ángulo de fase de la corriente total que aparece en la figura 16-67.

![image](https://user-images.githubusercontent.com/105259381/186573053-89841175-8eb4-457c-8264-af4aafce91b9.png)

![image](https://user-images.githubusercontent.com/105259381/186573262-73b38b5a-95da-406f-a85d-9e21d7f224d0.png)

#### PARTE 3: CIRCUITOS EN SERIE-PARALELO

#### SECCIÓN 16–6 Análisis de circuitos RL en serie-paralelo

28. ¿Es el circuito de la figura 16-68 predominantemente resistivo o predominantemente inductivo?

![image](https://user-images.githubusercontent.com/105259381/186573489-fa68f201-3ea3-49f7-b4af-6557c6f68ff8.png)

![image](https://user-images.githubusercontent.com/105259381/186573767-e5883f69-64cc-4eb2-9dd9-47f6f0d4ceb6.png)

30. Para el circuito de la figura 16-69, determine lo siguiente:

![image](https://user-images.githubusercontent.com/105259381/186574090-23d2473d-fba1-45eb-a0b8-0b57d396a915.png)

![image](https://user-images.githubusercontent.com/105259381/186575095-57b34491-9654-49b3-9ad8-c9254481e4ca.png)







