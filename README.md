# cajero-hashMap
Este es el repositorio para crear un cajero automático con HashMap

## Avances:
- interfaz grafica con pantalla, botones(Limpiar, retroceso y retirar) y tabla de billetes funcionando
- HashMap con 100 billetes por cada denominacion
- tabla llena desde el mapa
- validacion del monto(minimo 10.000 a maximo 1.000.000 y que sean multiplos de 10)

## Pendiente:
- Distribucion de billetes con las reglas especiales.
- verificacion de saldo
- actualizacion de la tabla tras cada retiro

## Decisiones e initerpretacion:
Los montos deben ser múltiplos de 10, ejemplo 15.000 pasa la validación aunque no se puede armar con los billetes disponibles.

## Ejecucion:
Copiar o descargarlo para montarlo en NetBeans y ejecutar el main interfaz_cajero.
