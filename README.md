# CURSO CNYT CIENCIAS NATURALES Y TECNOLOGIA

## CALCULADORA NUMEROS COMPLEJOS

## JOHANN STEVEN BOGOTÁ VÉLEZ


## CONTENIDO:
   ## PROYECTO 1: Se realizo una libreria con las operaciones basicas de los numeros complejos
        0. imprimir(C) - Funcion para imprimir un numero complejos
        1. suma_C(C1,C2) - Funcion que realiza la suma de dos numeros complejos y lo retorna
        2. resta_C(C1,C2) - Funcion que realiza la resta de dos numeros complejos y lo retorna
        3. Mul_C(C1,C2) - Funcion que realiza la multiplicacion de dos numeros complejos y lo retorna
        4. Conju_C(C1) - Funcion que retorna el conjugado de un numero complejo, colocando su parte 
            imaginaria negativa
        5. Modu_C(C1) - Funcion que retorna el modulo de un numero complejo
        6. Div_C(C1, C2) - Funcion que retorna la division de numeros complejos utilizando otras funciones
            que hacen operaciones basicas como la suma y la multiplicacion
        7. Rec_Polar(C1) - Funcion que retorna dada una forma rectangular a una polar
        8. Polar_Rec(C1) - Funcion que retorna dada una forma polar a una rectangular
   ## PROYECTO 2: Se realizo una libreria con operaciones entre vectores y matrices complejas
        0. imprimir_vec(V1, tam) - Funcion que muestra los vectores complejos
        0.2 imprimir_mat(V1, fila1, columna1) - Funcion que imprime las matrices complejas
        1. adi_vectores(V1, V2) - Funcion que realiza la suma de dos vectores complejos
        2. Mul_esc_vect(e, V1) - Funcion que realiza la multiplicacion de dos vectores complejos
        3. inve_vector(V1) - Funcion que retorna el inverso aditivo de vector, es decir, cambiarle el signo a 
            la parte real y imaginaria de cada componente
        4. Adi_matrices(V1, V2) - Funcion que suma dos matrices complejas, es decir la suma componente a componente
        5. Mul_esc_matriz(e, V) - Funcion que realiza la multiplicacion por un escalar complejo
        6. inv_adi(M1) - Funcion que retorna el inverso aditivo de una matriz
        7. matriz_tran(M1) - Funcion que le realiza la transpuesta a una matriz compleja
        8. Matriz_conju(M1) - Funcion que le realiza la conjugada a una matriz compleja
        9. Matriz_adj(M1) - Funcion que le realiza la adjunta(Daga) a una matriz compleja
        10. mul_pivote(F1, F2) - Funcion auxiliar para poder realizar el producto entre matrices
             produc_matriz(M1, M2) - Funcion que realiza el producto entre matrices
        11. accion(M,V) - Funcion que realiza la accion de una matriz compleja sobre un vector complejo
        12. pro_punto(V1,V2) - Funcion que realiza el producto interno de dos vectores complejos
        13. norma_vec(V) - Funcion que realiza la norma de un vector complejo.
        14. distancia(V1,V2) - Funcion que retorna la distancia entre dos vectores complejos.
        15. mat_uni(M) - Funcion que retorna si una matriz es unitaria o no.
        16. mat_her(M) - Funcion que retorna si una matriz es hermitiana o no.
        17. producto_tensorial(M,V) - Funcion del prodcuto tensorial entre vector y matriz.
  ## PROYECTO 3: Se realizo una libreria resolviendo sistemas y su dinamica
        0. Sistema clasico/ dina_clasica(V,M,clicks) - Se pide estado inicial, matriz de adyacencia y clicks de tiempo para resolver el            sistema determinista
        1. Sistema probabilistico/ dina_probabilistica(V,M,clicks) - Se pide estado inicial, matriz de adyacencia y clicks de tiempo                para resolver el sistema probabilistico, para esto la matriz tiene que ser doblemente estocastica
        2. Sistema Cuantico/cuantico(V,M,clicks) - Se pide estado inicial, matriz de adyacencia y clicks de tiempo para resolver el                sistema cuantico, para esto la matriz tiene que ser unitaria
        3. Funcion que ensambla sistemas/ ensamble(V1, V2, M1,M2, clicks) - Se pide dos vectores iniciales ,dos matrices de adyacencia ,            y sus clicks de tiempo que determina el estado donde va a estar despues de cierto tiempo en sus dos sistemas
        4. Experimento de la doble rendija/ doble_ren(num_ren, num_blancos_pared, vector_prob) -  Funcion que determina la probabilidad            de un sistema en este caso de la doble rendija en estar en cierto estado dado sus rendijas y los numeros ed blancos en las              paredes
