# Exercicio026.py
#Faça um programa que leia uma frase pelo teclado e mostre quantas vezes aparece a letra “A”, em que posição ela aparece a primeira vez e em que posição ela aparece a última vez.

n = str(input('Digite uma frase')).upper().strip()

print(n.count('A'))
print(n.find('A')+1)
print(n.rfind('A')+1)
