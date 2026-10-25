Problema
En taquilla cada persona atiende distinto.

Solución
Crear algoritmo Kilómetro 0 con pasos ordenados.
Entrada: documento, tipo de bicicleta, horas,recorrido
Salida: bicicleta entregada + recibo.

Pasos para alquilar una bicicleta
ALGORITMO Kilometro 0 - Rueda Libre - Taquilla de Alquiler

1.El cliente llega al local Rueda Libre y se le pide su documento de identidad.
2.Se le pregunta qué tipo de bicicleta quiere alquilar: Urbana, Montaña o Eléctrica.
3.Se le pregunta por cuánto tiempo la quiere: 1 hora, medio día que son 4 horas, o día completo.
4.Se consulta el Cuadro 1 de Tarifas de Alquiler:Si es Urbana, el valor es de $10.000 por una hora, $30.000 por medio día y $50.000 por día completo. Si es Montaña, cuesta $15.000 una hora, $45.000 medio día y $70.000 día completo. Si es Eléctrica, cuesta $25.000 una hora, $70.000 medio día y $110.000 día completo.
4.Se le pregunta si quiere un recorrido guiado consultando el Cuadro 2 de recorridos. Puede elegir entre Río y parques que son 12 km, 2 horas, nivel fácil y vale $45.000 por persona. Sabores de barrio que son 18 km, 3 horas, nivel medio y vale $60.000 por persona. Reto las Palmas que son 25 km, 4 horas, nivel difícil y vale $85.000 por persona. O puede elegir ningún recorrido.
5.Se calcula el valor total a pagar sumando la tarifa del Cuadro 1 más la tarifa del recorrido del Cuadro 2.
6.Se cobra el dinero y se le entrega el recibo al cliente.
7.Se le entrega la bicicleta, el casco y el candado, verificando el estado de la bicicleta junto con él.
8.Se registra en el cuaderno el documento, el tipo de bicicleta, la duración, el recorrido y el total pagado.
9.Fin del proceso, el cliente sale con su bicicleta, casco y candado.

ALGORITMO Rueda Libre - VERSION 2 CORREGIDA

1.Se le pide al cliente su documento de identidad.
2.Si el cliente no tiene documento, se le informa que es un requisito obligatorio para el préstamo y el proceso termina ahí.Si sí tiene, se continúa.
3.Se le pregunta qué tipo de bicicleta desea: Urbana, Montaña o Eléctrica.
4.DECISIÓN: Se verifica si hay disponibilidad de ese tipo de bicicleta. Si no hay disponible, se le ofrece otro tipo de bicicleta o se termina el proceso. Si sí hay, se continúa.
5.Se le pregunta por cuánto tiempo la necesita: 1 hora, medio día que son 4 horas, o día completo.Se consulta el Cuadro 1 de tarifas de alquiler 2026. Urbana cuesta $10.000 una hora, $30.000 medio día y $50.000 día completo. Montaña cuesta $15.000 una hora, $45.000 medio día y $70.000 día completo. Eléctrica cuesta $25.000 una hora, $70.000 medio día y $110.000 día completo.Se le pregunta si desea recorrido guiado del Cuadro 2. Río y parques son 12 km, 2 horas, fácil, $45.000 por persona. Sabores de barrio son 18 km, 3 horas, medio, $60.000 por persona. Reto las Palmas son 25 km, 4 horas, difícil, $85.000 por persona. O ningún recorrido que vale $0.Se calcula el total sumando la tarifa del Cuadro 1 más la tarifa del Cuadro 2.Si el cliente no tiene el dinero suficiente, se le informa y el proceso termina.Si tiene el dinero, se cobra, se le entrega el recibo detallado y se le entrega la bicicleta, el casco verificando su talla y el candado, verificando el estado de la bici con el cliente.Se registra todo en el cuaderno: documento, tipo de bici, duración, recorrido y total.Fin. El cliente sale con su bicicleta, casco y candado, y el algoritmo siempre termina, sin quedarse a mitad.

