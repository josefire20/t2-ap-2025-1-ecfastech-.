# t2-ap-2025-1-ecfastech-.
while True:
    nome = input("Digite o nome de usuário: ")
    senha = input("Digite a senha: ")

    if senha == nome:
        print("Erro: a senha não pode ser igual ao nome de usuário. Tente novamente.\n")
    else:
        print("Cadastro realizado com sucesso!")
        break
