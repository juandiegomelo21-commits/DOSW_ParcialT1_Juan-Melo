
# PUNTO 1

Diagrama de contexto de eciPaymentsHUB

![img_1.png](img_1.png)


# Punto 2

los patrones de diseño elejidos son 

# Adapter
al tener tantos provedores de pagos debe existir un metodo para manejar la informacion y unificarlas para asi garantizar que los datos puedan ser procesados de manera correcta segun la entrada esperada

# Abstract Factory 
al existir tantos tipos de certificado , que aunque son parecidos , son realmente diferentes debe exsitir un metodo de devolver al usuario de acuerdo a sus requerimientos.
para esto usaremos interfaces para establecer contratos y que los certificados cumplan con requisitos.


# Punto 3

Identifique 5 requerimientos del sistema y clasifíquelos en funcionales (3) y
no funcionales (2). Garantice que al menos un requerimiento funcional
seleccionado utilice uno o los dos patrones identificados. (Añadirlo al
README.md)

## los requerimientos funcionales
1. se requiere que la informacion de pago se guarde en los servicios de aws
2. se requiere que cuando los pagos sean en usd se puedan hacer unicamente por stripe
3. 13221

## los requerimientos no funcionales

1.fa
2.dasd


