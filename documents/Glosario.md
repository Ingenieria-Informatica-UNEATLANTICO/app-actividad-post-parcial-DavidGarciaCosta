# **Servicio de Transporte Público**

### **Glosario**

1. **Persona**  
   Representa a cualquier individuo dentro del sistema, ya sea un pasajero o un conductor. Es una clase base común para ambos.

2. **Pasajero**  
   Clase derivada de **Persona**. Representa a una persona que utiliza el sistema de transporte público, ya sea pagando un boleto o abonando el servicio. Un pasajero puede utilizar diferentes medios de transporte, como autobuses o trenes.

3. **Conductor**  
   Clase derivada de **Persona**. Representa a la persona encargada de conducir el vehículo dentro del sistema de transporte público. El conductor sigue las rutas establecidas y reporta incidencias.

4. **Tarifa**  
   Define el costo de utilizar el transporte público. Está vinculada al pago que realiza un pasajero por usar el servicio.

5. **MetodoPago**  
   Representa el medio de pago que se utiliza para adquirir un boleto o abono del sistema de transporte público, como tarjetas de crédito, débito, o sistemas de pago electrónicos.

6. **Abono**  
   Representa un tipo de pago que permite a un pasajero utilizar el sistema de transporte durante un período determinado (por ejemplo, mensual). Un **Abono** está vinculado a un **MetodoPago**.

7. **Vehiculo**  
   Representa los medios de transporte del sistema, como autobuses, trenes, etc. Un **Vehiculo** es operado por un conductor y sigue una ruta definida.

8. **Ruta**  
   Define el trayecto o itinerario que los vehículos deben seguir. Cada **Ruta** tiene un horario de funcionamiento y paradas establecidas a lo largo del recorrido.

9. **Horario**  
   Define los tiempos específicos en los que los vehículos deben pasar por las paradas de cada **Ruta**.

10. **Parada**  
   Representa los puntos donde los pasajeros pueden abordar o descender del vehículo. Cada **Ruta** tiene varias **Paradas** definidas.

11. **Flota**  
   Representa el conjunto de vehículos que forman parte del sistema de transporte público. Los vehículos en una **Flota** son operados y gestionados de manera conjunta.

12. **Servicio**  
   Representa una operación o ruta específica dentro del sistema de transporte público. Un **Servicio** organiza las **Rutas** y gestiona las **Flotas** de vehículos.

13. **Incidencia**  
   Representa cualquier evento o problema que ocurra dentro del sistema de transporte público, como fallas en los vehículos, retrasos, o accidentes. Las **Incidencias** pueden ser reportadas por los conductores y pueden afectar a los pasajeros.

14. **Estadistica**  
   Clase que representa los datos generados a partir del sistema de transporte público. Esto incluye información sobre el uso del servicio, cantidad de pasajeros, incidencias, entre otros, que se generan para analizar el rendimiento del sistema.

