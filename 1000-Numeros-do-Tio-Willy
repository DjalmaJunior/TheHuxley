import sys

x = [] #Lista para as entradas
k = 0  #Iterador
while True:
    try:
        for i in range(1000):
            x.append(int(input())) #Armazenamento das entradas
            if (i == 0) and (x[0] == -1): #O programa para quando o primeiro inteiro dos 1000 for igual a -1.
                sys.exit()
        n = int(input()) #Entrada do numero a ser contado
        for i in x: #Leitura da lista para que seja feita a contagem dos numeros iguais
            if i == n:
                k += 1

        print(n, 'appeared', k, 'times')
        x.clear() #Limpando para um novo pacote de 1000 inteiros
        k = 0 #Resetando a variavel de iteração

    except EOFError:
        break
