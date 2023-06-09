# Sistema_Intermediario_bancario
Sistema com aperfeiçoamento de dicionário
# Criando um dicionário de informações de um usuário
usuario = {
    "nome": "João",
    "idade": 30,
    "email": "joao@example.com",
    "cidade": "São Paulo"
}

# Acessando e exibindo os valores do dicionário
print("Nome:", usuario["nome"])
print("Idade:", usuario["idade"])
print("Email:", usuario["email"])
print("Cidade:", usuario["cidade"])

# Modificando o valor de uma chave no dicionário
usuario["idade"] = 31

# Adicionando uma nova chave e valor ao dicionário
usuario["telefone"] = "(11) 98765-4321"

# Exibindo o dicionário completo após as modificações
print(usuario)
