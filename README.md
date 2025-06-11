nome_de_sua_cidade = input(" qual o nome de sua cidade: ") 
temperatura = float(input("qual a temperatura atual : "))
if  20<= temperatura <=40:
 print(f"{nome_de_sua_cidade} está derretendo")
elif  20> temperatura >=5:
 print(f"{nome_de_sua_cidade} tá friozionho")
elif 0 < temperatura <5:
 print(f"{nome_de_sua_cidade} era do gelo")
else : 
  print(f"{nome_de_sua_cidade} congelou o bumbum")




  nome = input("qual seu nome: ")
peso = float(input("qual seu peso: "))
altura = float(input("qual sua altura: "))

IMC = peso/(altura*altura)
 
if IMC <18.5: 
    print(f"{nome} está abaixo do peso seu imc é : {IMC}" )
elif IMC <24.9:
    print(f"{nome} está no peso normal seu imc é : {IMC}")
elif IMC <29.9:
    print(f"{nome} está com sobrepeso seu imc é : {IMC}")
elif IMC <34.9:
    print(f"{nome} está com obesidade grau 1 seu imc é : {IMC}")
elif IMC <39.9:
    print(f"{nome} está com obesidade grau 2 seu imc é : {IMC}")
else :
    print(f"{nome} está com obesidade grau 3 mórbida seu imc é : {IMC}")
