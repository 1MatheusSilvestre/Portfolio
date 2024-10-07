import random

def jogar():
    opcoes = ["pedra", "papel", "tesoura"]
    computador = random.choice(opcoes)
    jogador = input("Escolha pedra, papel ou tesoura: ").lower()

    if jogador not in opcoes:
        print("Escolha inválida. Tente novamente.")
        return

    print(f"Computador escolheu: {computador}")
    print(f"Você escolheu: {jogador}")

    if jogador == computador:
        print("Empate!")
    elif (jogador == "pedra" and computador == "tesoura") or \
         (jogador == "papel" and computador == "pedra") or \
         (jogador == "tesoura" and computador == "papel"):
        print("Você venceu!")
    else:
        print("Você perdeu!")

while True:
    jogar()
    jogar_novamente = input("Quer jogar novamente? (s/n): ").lower()
    if jogar_novamente != 's':
        break
