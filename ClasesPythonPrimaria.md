# Clases de python

1. Introducción
  * Origen
  * Alcance y utilidad
1. Instalación y entorno
  * Consola online https://repl.it/languages/python3
1. Variables
  * Tipos
  * Conversión
1. Interacción con la pnatalla
  * Impresión en pantalla: print()
  * Recogida de datos: input
1. Formato e indentación
  Bloques
  ¿espacios o tabulador?
1. Condicionales
  * Comparación
  * Cuidado con los tipos 8888!="8888"
    * Representación interna de los valores
1. Bucles while con condiciones
1. Bucles Formato
1. Rangos
1. Funciones
1. Tutoriales
  * http://diwo.bq.com/course/python-curso/
  
  * https://www.pythonmania.net/es/2010/03/23/tutorial-pygame-introduccion/
  
Tareas

* Problema de las 20 preguntas
 [Teoria](https://www.c-sharpcorner.com/uploadfile/4a950c/20-questions-guessing-game-using-binary-trees/)

![esquema](https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/4a950c/20-questions-guessing-game-using-binary-trees/Images/2.gif)

[Codigo en python](http://openbookproject.net/py4fun/animal/animal.html)

Solucion de Miguel:
* Usamos un fichero llamado database.py y que tiene dentro:
    data = ['¿Le gusta comer huesos?','Perro','Paloma']
  Y lo importamos desde el fichero principal
    import "database.py"
    data = database.data # actualizamos los valores
* Usamos una estructura nodo:
    Pregunta,AnimalSi,AnimalNo
* Cuando se actualiza se guarda el nuevo fichero database.py
* Si llegamos a una respuesta que no es valida, pedimos una pregunta para ese nuevo animal y si la respuesta es si o no para re-ordenar
