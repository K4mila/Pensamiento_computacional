    Algoritmo sin_titulo
      nombre<-""
      cal1<-0
      cal2<-0
      cal3<-0
      cal4<-0
      promedio<-0
      Escribir "ingresa nombre del alumno"
      Leer nombre
      Escribir "ingrese calificacion 1"
      Leer cal1

      Escribir "ingrese calificacion 2"
      Leer cal2

      Escribir "ingrese calificacion 3"
      Leer cal3

      Escribir "ingrese calificacion 4"
      Leer cal4

      promedio=(cal1+cal2+cal3+cal4)/4

      Si promedio>5 Entonces
        Escribir "aprobo"
      SiNo
        Escribir "reprobo"
      Fin Si
    FinAlgoritmo
