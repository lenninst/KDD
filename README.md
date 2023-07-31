# KDD

# Proceso de descubrimiento en base de datos
[Colab Notebook](https://colab.research.google.com/drive/15kzE3kZWUEiJ4nHM0IWcjKHGrmKdHd4k?usp=drive_link)


El Descubrimiento de conocimiento en bases de datos = (kdd, del inglés Knowledge Discovery in Databases)

Proceso automático en el cual se combina descubrimiento y análisis. Proce que consiste en extraer patrones en forma de reglas o funciones, a partir de los datos, para que el usuario los analice 


- Se trata de preprocesar datos.
- hacer minenia de datos
- Presentar resultados

Ejemplo de uso común.
- Usado para determinar prefiles de clientes fraudulentos (evacion de impuestos).
- Permite relacionar situaciones exsistens entre sintomas y enfermedades
- Identificar grupo de personas o identificar patrones de compra de los clientes. 
---

# Etapas del proceso 
- Selección.
- Preprocesamiento/Limpieza.
- Transformación/Reducción.
- Minería de datos (data mining).
- Interpretación/evaluación.

---
## Seleccion

Se identifica lo mas relevante de un conjunto de datos, para ello se  selecciona todos los datos disponibles o una muestra. 

---
## Pre-procesamiento/limpieza 

Los datos son analizados y se eliminan los ruidos de datos (son datos nulos, duplicados), Se usa tecnicas de reemplazo para solucionarlo. 



### Datos ruidosos (noisy data):
*Valores fuera de rango*
	**Ejemplo:**
	 si al recolecar edades de personas y encontramos datos con numero negativos y mayores a 200. o en caso analizar temperatura en una region en Celsius es imposible que el rango sea de -50 a 200 puesto el rango de temperatura es menor en el mundo real. 
	**Causa**:
	 Se deben a errores humanos, de sistema o fuentes de información incorrecta.

### Datos desconocidos (empty) y (missing)
 Valores fuera del mundo real.
	**Ejemplo:**
	 Una encuesta con campos impletos.
	**Causa**:
	 Atributos no registrado, error de almacenamiento, opciones que no estuvieron disponibles durante la recoleccion de datos.
	 o datos no capturados


## Transformación/ reducción 

Busca características útiles para presentar datos,
Busca reducir o transformar los datos en variables o rangos.

### Reduccion horizontal
Eliminar filas dentro de una base de datos, sustituyendo por un rango de valores de mayor jearquia. Ejemplo se puede simplificar las edades de una base da datos por rango de edades.

### Reducción vertical
Consiste en eliminar columnas que no son relevantes para el análisis, por ejemplo supongamos que nuestra tabla tiene las columnas edad y fecha de nacimiento, estas son correspondientes de modo que al saber la edad podemos calcular la fecha de nacimiento relativo de modo que se puede eliminar la fina de `fecha de nacimiento `
Los histogramas permiten simplificar  datos ejemplo si tenemos la altura de varias personas en lugar de representarlas de manera individual se puede crear un histograma donde represente un o agrupar el numero de personas que tienen una cierta edad.

## Minería de datos 
Realiza busquedas o descubre patrones o secuencias de interés, 
Para ello se aplican algorimos de clasificación y busqueda de patrones secuencias 

### Modelos predictivos
El objetivo es obtener una predicción o un valor futuro usando algoritmos para procesar datos se usan dos variables. Una variable dependiente la cual depende de los datos históricos y una variable independiente esta variable depende de las características del dato.
Ejemplo Ejemplo el valor de una casa depende del lugar en donde se ubica, tamaño, etc. En este caso el valor dependiente es el precio la cual se defina según un historial, y las variables independiente son las características de la casa que pueden modificar el valor histórico.

### Modelos descriptivos
Se tratan de algoritmos  con la capacidad de encontrar patrones o secuencias en los datos analizados se enfocan en entender los datos existentes no hacer predicciones. Esto permite identificar grupos que están relacionados o que siguen un patrón. 
Ejemplo al analizar el historial de compra de un cliente se puede determinar los productos que consume regularmente.

## Etapa de interpretación 
Esta etapa es iterable de modo que si los resultados no son suficientes de puede iterar con el objetivo de encontrar nuevos patrones. En esta etapa se elimina patrones redundantes e irrelevantes. Con los patrones descubiertos se debe exponer de forma clara, en case de ser necesario se toman acciones para solucionar problemas o tomar decisiones.

Ejemplo 
este ejemplo fue tomado https://www.aprendemachinelearning.com/analisis-exploratorio-de-datos-pandas-python/
url: https://colab.research.google.com/drive/15kzE3kZWUEiJ4nHM0IWcjKHGrmKdHd4k?hl=es#scrollTo=lojk41ZoyedU


# Referencia
Timarán Pereira, Silvio Ricardo, Isabel Hernández Arteaga, Segundo Javier Caicedo Zambrano, Arsenio Hidalgo Troya, y Juan Carlos Alvarado Pérez. _Descubrimiento de patrones de desempeño académico con árboles de decisión en las competencias genéricas de la formación profesional_. Universidad Cooperativa de Colombia, 2016. [https://doi.org/10.16925/9789587600490](https://doi.org/10.16925/9789587600490).
