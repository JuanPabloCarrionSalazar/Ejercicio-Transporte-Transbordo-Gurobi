# Ejercicio-Transporte-Transbordo-Gurobi
<div class="alert alert-info"> </h4> **Material preparado para la carrera de Ingeniería Civil Industrial | Universidad Católica del Norte | Escuela de Ingeniería - Campus Coquimbo | Curso - Cadena de Suministros.**
</h4> </div>

Corresponde a un ejercicio tipo de Network Optimization, con ejercicios de transporte y transbordo que involucran variables binarias para la elección de fabricas y centros de distribución.

# Video You Tube

* **Transporte:** [Video Tutorial](https://youtu.be/a9qQMnlUZ8E)
* **Transbordo:** [Video Tutorial](https://youtu.be/0APFjst2PWs)

# Enunciado

Verano-Feliz ha tenido un gran éxito con su modelo de negocio en la industria de los trajes de baños, por lo cual está expandiendo sus operaciones a un nuevo mercado, La Unión Europea. Con el fin de poder implementa su estrategia de manera exitosa, actualmente está diseñando su cadena de suministros para el mercado de Europa.

Verano-Feliz está planeando abrir nuevas fábricas en Chile, donde manufacturará los trajes de baños y desde ahí los enviará a las ciudades más importantes de Europa, donde los comercializará en malls y tiendas especializadas.

Las ciudades donde está planificando abrir fabricas son: La Serena, Coquimbo, Antofagasta, Vallenar y Copiapó. Cada Fabrica tiene costos de fijo de abrir, costo de manufactura por producto y capacidades específicas.
Mientras que en Europa algunas ciudades pueden ser centros de distribución, mientras que otras solo serán puntos de ventas que deberán ser abastecidas desde los DC. Los centros de distribución tienen un costo fijo de administración, un costo variable por mover productos en las instalaciones y una capacidad especifica.

Importante notar que el costo de transporte de Chile a Europa no depende de la distancia solamente de las unidades. Mientras que el costo de transporte dentro de Europa depende de las unidades y de la distancia que se deba recorrer.

La información asociada a las Fábricas, Centros de Distribución y Ciudades está disponible en el archivo Excel adjunto.


## **Parte 1:**

**Pregunta 1.** Primero verano feliz está analizando cuanto debería ser la cantidad de productos a
enviar mensualmente desde cada una de las fábricas directamente a cada una de las ciudades. Para
este análisis está suponiendo una capacidad de cada fabrica de 500 unidades mensuales. Si no
alcanza a cumplir todo el pedido, el faltante no puede ser más de 100 unidades en el mes. Y para su
función objetivo solo considere los costos de transporte a Europa, costo variable de producción y
costo fijo de las fabricas.
(por simplicidad y facilidad de resolución, las cantidades a enviar son continuas, es decir NO
números enteros).
¿Desde la Fabrica de la Serena, a qué ciudades debería enviar productos?

**Pregunta 2.** En base a la información anterior. Cuántas unidades debe enviar desde Copiapó a
Madrid. Ingrese su respuesta redondeando al entero más cercano, sin puntos o comas.

**Pregunta 3.** En base a la información anterior. ¿Cuál es el costo de este plan? Ingrese su respuesta
redondeando al entero más cercano, sin puntos o comas.

## **Parte 2:**
**Pregunta 1.** (Utilizar solo la información disponible el archivo con los datos). Verano- Feliz está
analizando como podría configurar su cadena de suministros utilizando solamente 2 plantas en
Chile, La Serena y Antofagasta. Junto con esto quiere decidir que centro de distribución debería abriro no para poder minimizar el costo de transporte y obtener una distancia promedio de menor a 800
Km desde cada DC a sus clientes y un nivel de servicio donde el 50% de los clientes este a menos de
800 Km. ¿Qué centros de distribución debería abrir?
Hint: Considere los costos fijos de los Centros de distribución, costo de transporte de chile al cd,
costo de transporte del CD al cliente y costo de mantención del CD.

**Pregunta 2.** (Utilizando solo la información disponible el archivo con los datos y en base a los datos
de la pregunta anterior). ¿a cuántas ciudades abastece Ámsterdam, sin incluirse a si misma?

**Pregunta 3.** (Utilizando solo la información disponible el archivo con los datos y en base a los datos
de la pregunta anterior). ¿Qué planta debería producir la mayor cantidad de productos?¨

**Pregunta 4.** (Utilizando solo la información disponible el archivo con los datos y en base a los datos
de la pregunta anterior). ¿Cuál es el costo total de envío de productos desde Chile a Europa?

**Pregunta 5.** (Utilizando solo la información disponible el archivo con los datos y en base a los datos
de la pregunta anterior). ¿Cuál es el costo total de la estrategia?


# Archivos

* **Ejercicio Gurobi Trans-Transbordo Base.ipynb**: Corresponde al ejercicio sin completar el código, es la base de todo el ejercicio
* **Ejercicio Gurobi Base-Transporte listo.ipynb**: El ejercicio con la parte 1(transporte) completa y con la parte 2(transbordo) sin completar
* **Ejercicio Gurobi Trans-Transbordo Solucion Cadena.ipynb**: Es la solución del ejercicio.
* **Verno Feliz en Europa-Coord.xlsx**: El archivo excel con los datos del ejercicio
