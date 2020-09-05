1) Faça um fluxograma que:
a) Defina 3 variáveis com valores que armazenem:
i) O nome de uma fruta;
ii) O nome de verdura; e
iii) O nome de um legume.
b) Mostre uma mensagem “Aqui estão os nomes de uma fruta, uma verdura e um legume:”;
c) Mostre, após essa mensagem, o nome da fruta, da verdura e do legume, respectivamente.
Obs.: Lembre-se de usar nomes válidos de variáveis e que sejam representativos dos dados que irão
armazenar.
2) Altere o fluxograma anterior para conter mais três variáveis, com o preço unitário da fruta,
verdura e legume. Depois, mostre o preço de cada produto após o nome (nome ao lado do
preço, por exemplo: “Maçã: 10”)


Resposta em Python:

fruta= input ()
verdura= input ()
legume= input ()
print (' Aqui estão os nomes de uma fruta, uma verdura e um legume:', fruta,',', verdura, 'e', legume)

valor1= float  (10.32)
valor2= float  (8.50)
valor3= float  (3.54)
print ('Fruta:',fruta, '%.2f:' % valor1,'Verdura:', verdura, '%.2f' % valor2,'Legume:', legume, '%.2f' % valor3)
