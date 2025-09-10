# Cadastro-Aluno---Atividade-de-BackEnd
Este projeto é uma atividade prática do curso de Análise e Desevolvimento de Sistemas referente ao módulo de Back end.

Projeto em Java que integra Hibernate e a API ViaCEP para consultar CEPs, cadastrar endereços e associar alunos, reforçando práticas de persistência de dados e relacionamentos entre entidades.
_____________________________________________________________________________________________________________________________________________
Requisitos e orientações postadas pela tutora do curso

Requisitos:

* O usuário deve informar um CEP (a forma de captura é livre: Scanner, JOptionPane, interface gráfica etc.).
* O programa deve consultar esse CEP no banco de dados, via Hibernate, se já existe um endereço cadastrado com o CEP informado.
* Se o CEP existir no banco de dados: O sistema deve solicitar o cadastro de um novo aluno associado a esse endereço.
* Se o CEP não existir: O sistema deve consultar a API ViaCEP para recuperar os atributos completos do endereço (logradouro, bairro, cidade, estado, etc.). E com os dados retornados pela API criar um novo registro de endereço no banco de dados, armazenando também a data e hora da gravação.
* Exiba mensagens adequadas ao usuário em cada etapa (CEP encontrado ou não, cliente cadastrado com sucesso etc.).


Objetivos do exercício:
* Reforçar a prática de consultas e persistência de dados usando Hibernate.
* Exercitar relacionamentos entre entidades (Endereco ↔ Cliente).
* Aplicar estruturas condicionais para tratar os dois cenários (CEP já existente ou novo CEP).
