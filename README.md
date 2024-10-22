for andar in range(1, 21):
    if andar == 13:
        continue  # Pula para a próxima iteração se o andar for 13
    print(andar)

# Imprimindo os andares em ordem decrescente
for andar in range(20, 0, -1):
    if andar == 13:
        continue
    print(andar)
    

# Imprimindo os andares de 1 a 20, pulando o 13
andar = 1
while andar <= 20:
    if andar != 13:
        print(andar)
    andar += 1

# Imprimindo os andares em ordem decrescente
andar = 20
while andar >= 1:
    if andar != 13:
        print(andar)
    andar -= 1


    
