numeros = [] #Lista das entradas
media = 0   #Media das entradas
soma = 0    #Soma das entradas
iterador = 0  #Soma dos numeros maiores que a média
numerosi = [] #Lista dos numeros maiores que a média
stringn = ''  #Armazena em string os números da lista numerosi
j = 0 #Auxiliar
loop = int(input('Digite a quantidade de entradas: '))
for i in range(loop):
    x = int(input('Digite um numero:'))
    numeros.append(x)
    soma += x
#Fazer a média
media = soma/loop
#Armazenamento dos números maiores que a média
for i in range(0, len(numeros)):
    if numeros[i] > media:
        iterador += 1
        numerosi.append(numeros[i])
#Iteração dos números maiores que a média para string
for i in numerosi:
    j += 1
    if j == 1:
        stringn = str(i)
    else:
        stringn = stringn + ',' + str(i)
print('Quantidade de números maior que a média: ',iterador,'\nNúmeros maiores que a média:', stringn)
