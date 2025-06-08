import random

def saudacao(nome):
    return f"Olá, {nome}! Seja bem-vindo ao Projeto Maia."

def somar(a, b):
    return a + b

def mensagem_motivacional():
    frases = [
        "A luz que você procura está dentro de você.",
        "Respire fundo, o agora é tudo o que há.",
        "Você é capaz de tudo quando está presente.",
        "A vida sorri para quem caminha com fé.",
        "Desperte — o mundo precisa da sua luz."
    ]
    print(random.choice(frases))

def desafio_logico():
    a = int(input("Digite o primeiro número: "))
    b = int(input("Digite o segundo número: "))
    if a > b:
        print(f"{a} é maior que {b}")
    elif b > a:
        print(f"{b} é maior que {a}")
    else:
        print("Os dois números são iguais.")

def mantra_do_dia():
    mantras = [
        "Jesus: 'A minha paz vos dou.'",
        "Buda: 'Tudo o que somos é resultado do que pensamos.'",
        "Salmo 46:10 – 'Aquietai-vos e sabei que eu sou Deus.'",
        "O silêncio é a linguagem do Espírito.",
        "Você já é a presença que procura despertar."
    ]
    print("🧘 Mantra do dia:", random.choice(mantras))

def main():
    nome = "João Paulo"
    print(saudacao(nome))
    resultado = somar(10, 20)
    print(f"A soma de 10 + 20 é: {resultado}")
    mensagem_motivacional()
    mantra_do_dia()

if __name__ == "__main__"
