#Primeiro código em Python
x = int(input('Numero de elementos na lista: '))
confirm = 0
contador = 1 #Começa em 1 por causa do número 2, que é o unico numero par a ser classificado como número primo.

for i in range (1,x+1):
  if (i == 2):#Trantando primeiro a exceção dos números pares.
    print(i,"->Número Primo")
  else:
    a = i #Variável auxiliar para o while.
    b = i #Variável auxiliar para substituir o i dentro dos IFs.
    #Tratando os numeros após o 2.
    while (a>2):
      b-=1
      a-=1      
      if (i%2 != 0):#Remoção de todos os numeros pares, exceto o 2. 
       #Todos os numeros pares são divisíveis por 2; portanto não podem ser primos - salvo exceção do próprio número 2 -.
        if(i%b != 0):
          confirm = 1
        else:    
          confirm = 0
          break
      else:
        confirm = 0
        break   #Cancelando o loop após definir que o número é par e não precisa ser testado. 
    if (confirm == 1):
      print(i,'->Número Primo')
      contador += 1 
    else:
      print(i)
print('Há ',contador,' números primos no intervalo de ',x,' números.')
print('Obrigado por utilizar o programa!')           
