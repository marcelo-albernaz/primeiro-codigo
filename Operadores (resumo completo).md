 ###Unarios (opera em cima de 1 unico operando )

y = 4

print (not False)   # == True 
print (not True)    # == False


print(-3)        #valor literal

print(-y) 

print(--3)  #invertendo sinais
print(--y) #invertendo sinais

print(+3)

não existe operador de incremento e decremento no python
-===========================================================================================
	#### Atirimeticos 

+3 =  prefix
x+y = infix 
3++ = postfix

x = 10 
y = 3

print(x + y)   =>13
print(x - y)   =>7
print(x * y)   =>30
print(x / y)   =>3.3333
print(x % y)   =>1


print(int(x/y))     #tive que colocar o inteiro aqui porque ele quebrava para float        =>



par = 34
impar = 33

print(par % 2 == 0)  => True
print(impar % 2 == 1) => True

====================================================================================================

		##relacionais

x = 7
y = 5

print (x > y)   #True
print (x >= y)  #True
print (x <= y)  #False
print (x < y)   #False
print (x == y)  #False
print (x != y)  #True

print('5' != 5) #True         

em java script existe o === (estritamente igual)

print('5' != 5) seria false, porque ele vê o conteúdo da string,
porem 
print('5' === 5) seria false, porque eles não são do mesmo tipo

======================================================================================================
		##Atribuição

resultado = 2    #Atribuído o valor 2 a variavel resultado

resultado += resultado
resultado += 3   #resultado = resultado + 3
resultado -= 1   #resultado = resultado - 1
resultado *= 4   #resultado = resultado * 4
resultado /= 2   #resultado = resultado / 2
resultado %= 6   #resultado = resultado % 6

print(resultado)

=============================================================================================================

			##termario

lockdown = False
grana = 30

status = 'Em casa' if lockdown or grana <=100 else 'Uhuuuu'
print(f'O status é : {status}')
