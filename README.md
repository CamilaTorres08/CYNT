Estudiante: Andrea Camila Torres González

Este programa está diseñado para calcular números complejos, este incluye 9 funciones en las cuales cada una realiza una operación en específico como: suma, multiplicación, división, resta, modulo, conjugado, cartesiano a polar, polar a cartesiano y hallar la fase del complejo.

Función "SumComplex": Esta función está compuesta de dos variables tipo entero: real e img. en la cual, cada una realiza la suma de reales e imaginarios respectivamente para retornar una tupla con lo que se guardó en dichas variables.

Función "MultComplex": Esta función está compuesta de dos variables tipo entero: real e img. en la cual, cada una realiza la multiplicación de reales e imaginarios de acuerdo con la propiedad de la multiplicación de complejos y retorna una tupla con el resultado.

Función "RestComplex": Esta función está compuesta de dos variables tipo entero: real e img. en la cual, cada una realiza la resta de reales e imaginarios respectivamente para retornar una tupla con lo que se guardó en dichas variables.

Función "DivComplex": Esta función está compuesta de tres variables tipo entero: result1,result2 y result3. -La variable result1 calcula la suma de los productos de las partes reales e imaginarias respectivamente. -La variable result2 calcula la suma de los cuadrados de la parte real e imaginaria del segundo parámetro que recibe la función, es decir, el segundo número complejo. -La variable result3 calcula la resta de los productos de la parte real con la imaginaria de cada número. Por último la función retorna una tupla que contiene la división de acuerdo con la propiedad de la división de complejos.

Función "ModComplex": Esta función está compuesta de dos variables tipo entero: a y b, en la cual, la primera representa el cuadrado de la parte real del complejo y la segunda, el cuadrado de la parte imaginaria. Por último, retorna un resultado tipo flotante que representa la raiz de la suma de las variables anteriormente mencionadas.

Función "ConjComplex": Esta función directamente retorna una tupla en la cual, multiplica la parte imaginaria por menos uno (-1) para cambiar el signo.

Función "PolCartComplex": Esta función está compuesta de dos variables tipo entero: a y b. en la cual, la primera realiza la multiplicación de p por el coseno del angulo dado y la segunda realiza la multiplicación de p por el seno del angulo dado.

Función "CartPolComplex": Esta función está compuesta de dos variables tipo entero: p y ang, la primera invoca la función "ModComplex" para realizar el módulo, y la segunda invoca la función "FaseComplex" para hallar la fase ó angulo en el que se encuentra el complejo. Por último, retorna una tupla con los resultados.

Función "FaseComplex": Esta función está retorna la fase ó angulo en el que se encuentra el complejo.

Función "PrintNumsCart": Esta función imprime el resultado sin la tupla, está compuesta por dos condiciones para que la salida se vea más estilizada. -Primera condición: esta condicion va enfocada para cuando la parte imaginaria es negativa, pues se imprime el número con su signo (-) junto con una "i". -Segunda condición: si la parte imaginaria es positiva, imprime un "+" antes del complejo junto con la "i" para indicar la parte imaginaria.

Función "PrintNumsPol": Esta función imprime el número en representación polar.
