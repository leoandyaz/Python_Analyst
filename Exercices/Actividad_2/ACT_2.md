###Realizar un programa que inicialice una lista con 10 valores aleatorios (del 1 al 10) y posteriormente muestre en pantalla cada elemento de la lista junto con su cuadrado y su cubo.


      import random
      lista_num =[]
      
      for lugar in range (0,10):
          lista_num.append(random.randint(1,10))
      
      print(lista_num)
      
      
      for i in range(0,10):
        print("***************")
        print(str(lista_num[i]) + ", " + str(lista_num[i]**2) + ", " + str(lista_num[i]**3))
