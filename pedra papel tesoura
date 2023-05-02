import random

print('Seja bem-vindo ao jogo de Pedra, Papel e Tesoura!')
usuario = input('Digite o nome do jogador: ')


def escolha_bot():
    objetos = ['pedra', 'papel', 'tesoura']
    objeto = random.choice(objetos)
    return objeto


def empatou():
    print(f'EMPATOU! bot escolheu {objeto}, {usuario} escolheu {opcao}')


def venceu():
    print(f'VENCEU! bot escolheu {objeto}, {usuario} escolheu {opcao}')


def perdeu():
    print(f'PERDEU! bot escolheu {objeto}, {usuario} escolheu {opcao}')


while True:
    objeto = escolha_bot()
    opcao = input(f'{usuario} - Escolha uma - pedra|papel|tesoura: ')
    if opcao == objeto:
        empatou()
    elif opcao == 'pedra' and objeto == 'tesoura':
        venceu()
    elif opcao == 'pedra' and objeto == 'papel':
        perdeu()
    elif opcao == 'papel' and objeto == 'pedra':
        perdeu()
    elif opcao == 'papel' and objeto == 'tesoura':
        perdeu()
    elif opcao == 'tesoura' and objeto == 'pedra':
        perdeu()
    elif opcao == 'tesoura' and objeto == 'papel':
        venceu()
    else:
        print('resposta inválida, reiniciando o jogo')
