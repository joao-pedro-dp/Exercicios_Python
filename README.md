# Exercícios de Python - Básico e Intermediário

Este repositório contém uma coleção de exercícios de programação em Python, desenvolvidos com o objetivo de treinamento pessoal. Os exercícios foram criados para aprimorar minhas habilidades na linguagem, reforçando conceitos fundamentais e práticas essenciais.

## Sobre os Códigos

- Autorais → Todos os códigos são de minha autoria, desenvolvidos de forma independente.

- Foco no aprendizado → Os exercícios foram criados para aprofundar o conhecimento da linguagem Python.

## Estrutura do Repositório

- Os exercícios estão organizados em dois níveis:

1. Exercícios Básicos → Abrangem conceitos fundamentais, como:

Variáveis e tipos de dados.

Condicionais (if, else).

Laços de repetição (for, while).

Funções simples.

2. Exercícios Intermediários → Focam em tópicos mais avançados, como:

Manipulação de listas e dicionários.

Funções mais complexas e integração entre módulos.

Estruturas de dados e otimização de código.

## Exemplo:
Aqui está um exemplo simples de exercício executado.

    def cel_para_fah():
    """
    Converte uma temperatura fornecida em Celsius para Fahrenheit.
    Lida com entradas inválidas e solicita novamente até receber um número válido.
    
    Retorna:
    tuple: Temperatura em Fahrenheit (precisa e arredondada).
    """
    while True:
        try:
            # Solicita a temperatura em Celsius
            cel = float(input("Informe a temperatura em Celsius: "))

        except ValueError: 
            print("Entrada inválida, favor digitar um número")
            continue

        # Converte para Fahrenheit
        f = ((9/5) * cel) + 32
        f_arredondado = round(f, 2)

        # Exibe os resultados
        print(f"A temperatura em Fahrenheit será: {f}")
        print(f"A temperatura em Fahrenheit arredondada será: {f_arredondado}")
        
        return f, f_arredondado

    # Chamada da função
    cel_para_fah()

## Contribuição

Se você quiser sugerir melhorias, fique à vontade para abrir um Pull Request ou enviar sugestões!

## Autor

Criado por João Pedro de Paula.
