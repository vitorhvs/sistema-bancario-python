# Sistema Bancário em Python
Este é um projeto de sistema bancário simples desenvolvido em Python.

*Funcionalidades*
- Criação de conta bancária com saldo inicial opcional
- Depósito de dinheiro na conta
- Saque de dinheiro da conta
- Consulta de saldo da conta

# Como Usar
1 - Clone este repositório:
git clone https://github.com/seu-usuario/sistema-bancario-python.git

2- Navegue até o diretório do projeto:
cd sistema-bancario-python

3 - Execute o arquivo main.py para testar o sistema:
python main.py

4 - Siga as instruções no terminal para criar uma conta, fazer depósitos, saques e consultar o saldo.

-# Exemplo de Uso
from conta_bancaria import ContaBancaria

-# Criando uma conta bancária
conta = ContaBancaria("João", 1000)

-# Realizando algumas operações
conta.consultar_saldo()
conta.deposito(500)
conta.saque(200)
conta.consultar_saldo()


# Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar problemas.

# Licença
Este projeto está licenciado sob a MIT License.
