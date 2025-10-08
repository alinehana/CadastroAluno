# CadastroAluno
Hibernate Project
Implemente uma funcionalidade no sistema que permita gerenciar o cadastro de endereços de alunos a partir de um CEP informado pelo usuário.

Requisitos:

O usuário deve informar um CEP (a forma de captura é livre: Scanner, JOptionPane, interface gráfica etc.).
O programa deve consultar esse CEP no banco de dados, via Hibernate, se já existe um endereço cadastrado com o CEP informado.
Se o CEP existir no banco de dados: O sistema deve solicitar o cadastro de um novo aluno associado a esse endereço.
Se o CEP não existir: O sistema deve consultar a API ViaCEP para recuperar os atributos completos do endereço (logradouro, bairro, cidade, estado, etc.). E com os dados retornados pela API criar um novo registro de endereço no banco de dados, armazenando também a data e hora da gravação.
Exiba mensagens adequadas ao usuário em cada etapa (CEP encontrado ou não, cliente cadastrado com sucesso etc.).


Objetivos do exercício:
Reforçar a prática de consultas e persistência de dados usando Hibernate.
Exercitar relacionamentos entre entidades (Endereco ↔ Cliente).
Aplicar estruturas condicionais para tratar os dois cenários (CEP já existente ou novo CEP).
