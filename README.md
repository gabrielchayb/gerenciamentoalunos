Gerenciador de Alunos

Este projeto é um sistema CRUD (Create, Read, Update, Delete) de gerenciamento de alunos desenvolvido com Django como framework backend e PostgreSQL como banco de dados. O sistema permite que você gerencie informações de alunos, incluindo criação, leitura, atualização e exclusão de dados via API.

Stack Utilizada

	•	Backend: Django 4.2.x
	•	Banco de Dados: PostgreSQL
	•	APIs: Django Rest Framework (DRF)
	•	Servidor de Desenvolvimento: Django’s built-in server

Endpoints da API

As APIs foram desenvolvidas usando Django Rest Framework (DRF) para permitir interações com o sistema de gerenciamento de alunos. Abaixo está um resumo dos principais endpoints e como consumi-los:

Endpoints

	•	GET /api/alunos/ — Retorna a lista de todos os alunos.
	•	POST /api/alunos/ — Cria um novo aluno.
	•	GET /api/alunos/{id}/ — Retorna detalhes de um aluno específico.
	•	PUT /api/alunos/{id}/ — Atualiza os dados de um aluno.
	•	DELETE /api/alunos/{id}/ — Exclui um aluno.

 
