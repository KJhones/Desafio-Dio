Sistema Bancário Otimizado com Python

Este projeto consiste na criação de um Sistema Bancário desenvolvido durante a jornada no DIO Campus Expert. O objetivo foi evoluir um código procedural simples para uma estrutura baseada em funções, aplicando conceitos de modularização e boas práticas de desenvolvimento em Python.

O sistema permite gerenciar operações básicas como depósitos, saques e extratos, além de cadastrar novos usuários e contas correntes de forma organizada.

Funcionalidades
Depósito: Permite adicionar valores ao saldo, validando apenas entradas positivas.

Saque: Implementa limites de valor por saque (R$ 500,00), limite diário de transações e verificação de saldo insuficiente.

Extrato: Exibe todas as movimentações realizadas e o saldo atual formatado.

Gerenciamento de Usuários: Cadastro de clientes com validação de CPF (único).

Gerenciamento de Contas: Vinculação de contas correntes (sequenciais) a usuários cadastrados.

Tecnologias e Conceitos Aplicados
Linguagem: Python 3.

Modularização: Separação da lógica de negócio em funções específicas para cada operação.

Estruturas de Dados: Uso de listas e dicionários para armazenamento temporário em memória.

Clean Code: Variáveis com nomes autoexplicativos e funções com responsabilidade única.

Desafios de Implementação
O maior desafio deste projeto foi a transição do código linear para o uso de argumentos nomeados (keyword only) e posicionais (positional only) nas funções, conforme exigido pelo desafio técnico para garantir a segurança e clareza das chamadas.
