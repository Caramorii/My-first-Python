palavra = input("Digite uma palavra: ")
invertida = ""
for letra in palavra:
    invertida = letra + invertida

if palavra == invertida:
        print(f'A palavra "{palavra}" é um polindromo')
else:
        print(f'A palavra "{palavra}" não é um polindormo')

print("Palavra invertida:", invertida)

