# MateusLopesJardim_Rec_Ag8_DS_I
Pesquisa de Satisfação

# Inicialização dos contadores
excelente = 0
ruim = 0

# Número de entrevistados (troque para 50 depois dos testes)
total_entrevistados = 10  # use 50 na versão final

for i in range(total_entrevistados):
    print(f"\nEntrevistado {i + 1}")
    
    nome = input("Digite o nome: ")
    idade = int(input("Digite a idade: "))
    
    print("Opinião sobre o atendimento:")
    print("1 - EXCELENTE")
    print("2 - BOM")
    print("3 - RUIM")
    
    opiniao = int(input("Digite a opção (1, 2 ou 3): "))
    
    # Estrutura de decisão
    if opiniao == 1:
        excelente += 1
    elif opiniao == 3:
        ruim += 1

# Resultados finais
print("\nResultado da pesquisa:")
print(f"Quantidade de respostas EXCELENTE: {excelente}")
print(f"Quantidade de respostas RUIM: {ruim}")
