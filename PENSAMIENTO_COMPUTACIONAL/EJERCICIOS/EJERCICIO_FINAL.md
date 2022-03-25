Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo adivina_el_numero

    int<-10
    
    num_secreto <-5
    
    Escribir "Hola, vamos a jugar adivina el numero:"
    
    Leer num
    
    Mientras num_secreto!=num && int>1 Hacer
    
        Si num_secreto>num Entonces
        
            Escribir "El numero ingresado es muy bajo"
            
        Sino 
        
            Escribir "El numero ingresado es muy alto"
            
        FinSi
        
        int <- int-1
        
        Escribir "Te quedan ",int," intentos:"
        
        Leer num
        
    FinMientras
    
    Si num_secreto=num Entonces
    
        Escribir "Exacto! Adivinaste y te quedaron ",int," intentos."
        
    Sino
    
        Escribir "Perdiste! El numero era: ",num_secreto
        
    FinSi
    
FinAlgoritmo

![Numero secreto](https://user-images.githubusercontent.com/101203621/160159471-2f214b1a-b067-49a5-acb5-a9da8233a38a.png)



Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
