---

---

# Proyectos
## [Proyecto 1](.\proyecto1.md)
Este es un proyecto en el que se realiza un análisis de las relaciones comerciales de Colombia.
## [Proyecto 2]()
Este es un proyecto en el que se desarrolla una librería de análisis de información. Se comparó el nivel de estudio de las personas con su respectivo sueldo para ver como su educación afectaba su nivel de vida.  
## [Proyecto 3]()
Este es un proyecto en el que se detecta el fraude a partir de un modelo de ML.
## [Proyecto 4]()
Este es un proyecto en el que se utiliza Python base para limpiar una base de datos, encontrándose datos de personas que han estado bajo arresto y viendo como dependiendo el aumento o disminución de condenas han aumentado o disminuido el número de personas en la cárcel. También se analiza que tanto afecta el nivel de educación en relación a estar bajo arresto.

## [Proyecto 5]()

## [Proyecto 6]()

## [Proyecto 7]()

## [Proyecto 8]()

## [Proyecto 9]()

## [Proyecto 10]()

## [Proyecto 11]()

## [Proyecto 12]()

https://colab.research.google.com/drive/1cKMgsVz_fzFKlPPZ5b5U7E3uhn7-cSNB#scrollTo=poQrdSX0l93r.



# Primer corte

## Clase 1: MLxE

> Por medio de la plataforma Python se realizaron algunos Rudimentos, operadores aritméticos, operadores de comparación, operadores lógicos, variables y tipos de datos como lenguaje básico del programa.


```print('Hola,mundo)

## Clase 2:

> Se conoció la función de diccionario utilizando el flujo de control (condicionales)  
Los bucles (For and while), listas (list), while condition y como digitar funciones (def).

```def par_impar(x):   #Así se verifica si es par o impar

```if x%2==0:
    print('par')
  else:
    print('impar')
    
## Clase 3:

 Se introdujeron algunas funciones anónimas, generadores y expresiones.

```for i in gen_cuads:
  print(i)

```import numpy as np

## Clase 4

 Se conocieron alguna clase de objetos (Orientados a procesos y funcional, crear objetos, luego se agrega el objeto que usualmente se escribe) para realizar atributos y estadistícos.

```class Estadisticos:
  def __init__(self,datos):
    self.datos=datos
  def media(self):
    return sum(self.datos)/len(self.datos)
  def varianza(self):
    media_x=self.media()
    vec=[(i-media_x)**2 for i in self.datos]
    return sum(vec)/(len(vec)-1)
  def desviacion_estandar(self):
    return self.varianza()**(1/2)

## Clase 5

 Se agregó la función *vec* y luego *np.array* para crear matrices
 Se utilizaron los conociminetos previamente adquiridos para desglozar los datos del sueldo mencionados en el proyecto 2  

```!pip install wooldridge

```class Estadisticos:
  def __init__(self,x2):
    self.x2=x2
  def media(self):
    return sum(self.x2)/len(self.x2)
  def mediana(self):
    self.x1.sort()
    num= len(self.x2)
    if num %2==0:
      print((self.x2[int(num/2)]+self.x1[int(num/2)-1])/2)
    else:
      print(self.x1[int(num/2-0.5)])
  def varianza(self):
    media_x=self.media()
    vec=[(i-media_x)**2 for i in self.x2]
    return sum(vec)/(len(vec)-1)
  def desviacion_estandar(self):
    return self.varianza()**(1/2)
  def coeficiente_variacion(self):
    return self.desviacion_estandar()/self.media()


# Segundo corte


