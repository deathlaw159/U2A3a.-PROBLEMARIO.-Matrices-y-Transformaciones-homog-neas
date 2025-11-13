# U2A3a.-PROBLEMARIO.-Matrices-y-Transformaciones-homog-neas

## Descripción del sistema robótico
El sistema robótico analizado corresponde a un manipulador con tres articulaciones principales que combinan movimientos rotacionales y prismáticos. Su estructura en cadena abierta permite describir la posición y orientación de cada eslabón respecto al anterior mediante el uso de parámetros Denavit–Hartenberg (DH).  
A través de estos parámetros se definen las matrices de transformación homogénea, las cuales permiten determinar la posición final del efector del robot respecto a su base.

---

## Estructura del código

El siguiente código implementa el cálculo simbólico de las matrices de transformación homogénea para el sistema robótico propuesto, utilizando la librería SymPy en un entorno Jupyter Notebook.  

Cada paso del código cumple una función específica para modelar el comportamiento cinemático del manipulador.

---

### Paso 2: Importación de librerías necesarias
En este paso se importa la librería SymPy, la cual se utiliza para realizar operaciones simbólicas, definir variables algebraicas y construir las matrices DH.  
Esto permite obtener expresiones generales sin asignar valores numéricos, facilitando el análisis teórico del robot.

```python
import sympy as sp
