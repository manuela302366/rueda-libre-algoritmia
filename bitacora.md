# Bitácora - Rueda Libre - Algoritmia

Problema
En taquilla cada persona atiende distinto.

Solución
Crear algoritmo Kilómetro 0 con pasos ordenados.
Entrada: documento, tipo de bicicleta, horas,recorrido
Salida: bicicleta entregada + recibo.

 Pasos para alquilar una bicicleta

Proceso completo desde que el cliente llega hasta que sale con bicicleta, casco y candado:

1. El cliente llega al local Rueda Libre.
2. Saludar y pedir el documento de identidad (requisito obligatorio para el préstamo).
3. Preguntar qué tipo de bicicleta necesita: Urbana, Montaña o Eléctrica.
4. Preguntar por cuánto tiempo la necesita: 1 hora, Medio día (4 horas) o Día completo.
5. Consultar las tarifas oficiales.
6. Preguntar si desea un recorrido guiado (Río y parques, Sabores de barrio, Reto las Palmas o Ningún recorrido).
7. Calcular el valor total sumando: tarifa de alquiler + tarifa del recorrido.
8. Cobrar el dinero y entregar el recibo con el detalle.
9. Entregar la bicicleta, el casco y el candado, verificando el estado de la bici junto con el cliente.
10. Registrar todo en el cuaderno y el cliente sale del local con su equipo completo.


Prueba con compañero
Intercambiamos pasos y al seguirlos literalmente encontramos estas ambigüedades:
- No validaba documento
- No validaba si había stock de bicis
- No verificaba pago
- No especificaba talla de casco

Algoritmo corregido 
Se corrigió agregando decisiones SI/ENTONCES/SINO y asegurando que siempre llega a FIN.
