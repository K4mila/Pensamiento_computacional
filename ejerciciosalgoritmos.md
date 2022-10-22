     1-inicio
     2-declarar letra<-""
     3-mostrar "ingresa una letra"
     4-asignar letra
     5-SI letra=="a"  ENTONCES 
     mostrar letra, " es vocal"
     SINO 
     mostrar letra," no es vocal"
     SI letra == "e"  ENTONCES
     mostrar letra," es vocal"
     SINO
     mostrar letra," no es vocal"
     SI letra=="i"  ENTONCES
     mostrar letra," es vocal"
     SINO
     mostrar letra," no es vocal"
     SI letra=="o"  ENTONCES
     mostrar letra," es vocal"  
     SINO
     mostrar letra," no es vocal"
     SI letra=="u"  ENTONCES
     mostrar letra," es vocal"  
     SINO
     mostrar letra," no es vocal"
     fin si
     --------------------------------------------------------------------------------------------------------------------------------
     Algoritmo sin_titulo
	num<-0
	Escribir "ingresa un numero del 1 al 7"
	Leer num 
	Segun num Hacer
	     1:
			Escribir "corresponde a lunes"
		2:
			Escribir "corresponde a martes"
		3:
			Escribir "corresponde a miercoles"
		4:
			Escribir "corresponde a jueves"
		5:
			Escribir "corresponde a viernes"
	     6:  
			Escribir "corresponde a sabado"
		7:
			Escribir "corresponde a domingo"
		De Otro Modo:
			Escribir "numero fuera de rango"
			Fin Segun
      FinAlgoritmo
      --------------------------------------------------------------------------------------------------------------------------------
      Algoritmo sin_titulo
	num1<-0
	num2<-2
	res<-0
	op<-0
	rep<-"s"
	Mientras rep="s" Hacer
	escribir "ingrese numero 1"
	leer num1 
	escribir "ingrese numero 2"
	leer num2
	escribir "ingrese una opcion suma 1 , resta 2, multiplicacion 3, division 4, salir 5"
	leer opc
	Segun opc Hacer
		1:
			res=num1+num2
			Escribir "suma es ", res
		2:
			res=num1-num2
			Escribir "resta es ", res
		3:
			res=num1*num2
			Escribir "multiplicacion es ", res
	    4:
			res=num1/num2
			Escribir "division es ", res
			
		De Otro Modo:
			Escribir "opcion incorrecta" 
	Fin Segun
	
	Escribir "quieres otra operación"
	leer rep
        Fin Mientras
        FinAlgoritmo
     
