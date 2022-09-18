# Calculadora de numeros complejos, matrices y vectores, Programa de simulación de lo cuántico a lo clásico

A continuación se presentan dos programas: el primer programa se llama "calculadoraComplejos" y realiza ciertas operaciones para números complejos. Por otro lado, el programa "calculadoraVectoresMatrices" realiza las operaciones para matrices y vectores complejos (arreglos). Por último se presenta un programa de canicas, donde con matrices y vectores de puede calcular la posicion y probabilidad despues de un tiempo del objeto. 


## Como usar

***Programa para numeros Complejos

para la calculadora de números complejos, la funciones reciben como parámetros tuplas que contienen la parte real e imaginaria del número.  Cada función tiene como objetivo realizar una operación en específico como: suma, multiplicación, resta, división, módulo, conjugado, polar a cartesiano, cartesiano a polar y fase. Se recomienda hacer uso de la función PrintNumsCart para imprimir numeros cartesianos y PrintNumsPol para números en su forma polar.

`PrintNumsCart(SumComplex((2,3),(4,7)))`

`PrintNumsCart(MultComplex((2,3),(4,7)))`

`PrintNumsCart(RestComplex((3,-1),(1,4)))`

`PrintNumsCart(DivComplex((-2,1),(1,2)))`

`print(ModComplex((1,-1)))`

`PrintNumsCart(ConjComplex((3,2)))`

`PrintNumsCart(PolCartComplex((3,-1)))`

`PrintNumsPol(CartPolComplex((-3,-2)))`

`print("Fase:",end= ' ')`

`print(FaseComplex((-3,-2)))`

***Programa para matrices y vectores complejos

Para la calculadora de matrices y vectores, se deberá pasar como parámetros a las funciones, matrices y vectores con tuplas ya que este está hecho para números complejos, asi mismo, se recomienda hacer uso de la libreria tabulate() para que imprima la matríz de una forma más ordenada y para vectores se recomienda llamar a la función  Imprimir_vectores para que imprima de una manera más elegante. 
Este programa hace uso de la libreria de numeros complejos para realizar algunas operaciones en especifico, asi mismo este realiza las siguientes operaciones: 

Adición de vectores complejos.

Inverso (aditivo) de un vector complejo.

Multiplicación de un escalar por un vector complejo.

Adición de matrices complejas.

Inversa (aditiva) de una matriz compleja.

Multiplicación de un escalar por una matriz compleja.

Transpuesta de una matriz/vector

Conjugada de una matriz/vector

Adjunta (daga) de una matriz/vector

Producto de dos matrices (de tamaños compatibles)

Producto interno de dos vectores

Norma de un vector

Distancia entre dos vectores

Revisar si una matriz es unitaria

Revisar si una matriz es Hermitiana

Producto tensor de dos matrices/vectores


`Imprimir_Vectores(SumVect([(1,2),(3,4)],[(3,4),(6,7)]))`

`Imprimir_Vectores(InversoVect([(1,2),(3,4)]))`
    
`Imprimir_Vectores(MultEscalarVect(3,[(1,2),(3,4)]))`
   
`print(ProductInterVect([(1,2),(3,4)],[(3,4),(6,7)]),'\n')`
   
`Imprimir_Vectores(AdjuntaVect([(1,2),(3,4)]))`
   
`print(NormVect([(1,2),(3,4)]),'\n')`
   
`print(distanciaVect([(1,2),(3,4)],[(3,4),(6,7)]),'\n')`
    
`print(tabulate(SumMat([[(1,2),(3,4),(5,1)]],[[(6,7),(8,9),(10,3)]])),'\n')`
    
`print(tabulate(InversoMat([[(1,2),(3,4),(5,1)],[(6,7),(8,9),(10,3)]])),'\n')`
    
`print(tabulate(MultEscalarMat(3,[[(1,2),(3,4),(5,1)],[(6,7),(8,9),(10,3)]])),'\n')`
   
`print(tabulate(TraspuestaMat([[(1,2),(3,4),(5,1)],[(6,7),(8,9),(10,3)]])),'\n')`
  
`print(tabulate(ConjugadoMat(([[(1,2),(3,4),(5,1)],[(6,7),(8,9),(10,3)]]))),'\n')`
  
`print(tabulate(AdjuntaMat(([[(1,2),(3,4),(5,1)],[(6,7),(8,9),(10,3)]]))),'\n')`
   
`print(tabulate(ProductMat([[(1,2),(3,4),(10,-11)],[(4,5),(6,7),(12,4)]],[[(1,2),(3,4),(7,8),(-4,-6)],[(7,0),(0,1),(0,4),(7,10)],[(0,2),(4,0),(-1,-1),(0,-1)]])),'\n')`

`print(tabulate(ProductTensor([[(1,2),(3,4),(5,1)],[(1,1),(2,2),(3,3)]],[[(6,7),(8,9),(10,3)],[(1,2),(-3,3),(4,5)]])),'\n')`


## Autor

Andrea Camila Torres González
