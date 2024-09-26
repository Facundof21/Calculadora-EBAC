valor = input("Digite um número aqui:")
print(valor)

outro_valor = input("Agora digite outro número: ")
print(outro_valor)

valor_convert = int(valor)
outro_valor_convert = int(outro_valor)


soma = valor_convert + outro_valor_convert

subtração = valor_convert - outro_valor_convert

multiplicação = valor_convert * outro_valor_convert

divisão = valor_convert / outro_valor_convert

escolha = input(" Escolha que tipo de operação matematica você quer fazer com esses números: soma, multiplicação, subtração ou divisão ")
if escolha == "soma":
  print("você escolheu a soma, então se sa gente somar esses dois números vai dará: ", soma)

elif escolha == "subtração": 
  print("Você escolheu subtração, se a gente subtrair esses dois números vai dará: ", subtração)

elif escolha == "multiplicação":
   print("Você escolheu multiplicação, se a gente multiplicar esses dois números dará ", multiplicação)

elif escolha == "divisão":
   print("Você escolheu divisão, se a gente dividir esses dois números dará: ", divisão)

else:
    print("Você não escolheu nenhuma das opções")
