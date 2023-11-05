# SistemaGerenciadorTarefasDotnet
Sistema Gerenciador de Tarefas construído durante as aulas ministradas pela Digital Innovation One.

## Contexto
Construir um sistema gerenciador de tarefas, onde poderá cadastrar uma lista de tarefas que permitirá organizar melhor a sua rotina.
Essa lista de tarefas precisa ter um CRUD, ou seja, deverá permitir a você obter os registros, criar, salvar e deletar esses registros.
A aplicação deverá ser do tipo Web API ou MVC, fique a vontade para implementar a solução que achar mais adequado.
A sua classe principal, a classe de tarefa, deve ser a seguinte:
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/4dfe7de8-e37e-459f-b08e-9d60b6d18b9d)

OBS: Não esqueça de gerar a sua migration para atualização no banco de dados.

## Métodos esperados
É esperado que você crie o seus métodos conforme a seguir:

## Swagger
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/5e801c95-4bbf-4c86-b6f5-ffc421901f72)

## Endpoints

Verbo	Endpoint	Parâmetro	Body
GET	/Tarefa/{id}	id	N/A
PUT	/Tarefa/{id}	id	Schema Tarefa
DELETE	/Tarefa/{id}	id	N/A
GET	/Tarefa/ObterTodos	N/A	N/A
GET	/Tarefa/ObterPorTitulo	titulo	N/A
GET	/Tarefa/ObterPorData	data	N/A
GET	/Tarefa/ObterPorStatus	status	N/A
POST	/Tarefa	N/A	Schema Tarefa

Esse é o schema (model) de Tarefa, utilizado para passar para os métodos que exigirem
{
  "id": 0,
  "titulo": "string",
  "descricao": "string",
  "data": "2022-06-08T01:31:07.056Z",
  "status": "Pendente"
}

# RESOLUÇÃO
## TODOS OS ENDPOINTS
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/99edced8-5ab9-4c66-82b7-00b05aafa178)

## CRIANDO UMA TAREFA
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/e84f1218-2e82-42d4-9e63-f3164e9d82dc)


## OBTENDO LISTA TODAS AS TAREFAS
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/86088725-a516-4a80-8a67-43e53679ce69)

## OBTER TAREFA POR ID
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/ed7f2157-d333-47d4-9dd7-174f8c0f099a)

## OBTER TAREFAS POR TITULO
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/2ab455c9-338e-4dc1-a742-e5b99a07bf1e)

## OBTER TAREFAS POR DATA
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/1127ce10-771b-4c91-8af7-3720fe0ece48)

## ATUALIZAR TAREFA
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/b0b1747e-e0e1-4f09-9eb6-75c0310d6e1e)
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/8a8e7867-3a67-49db-886a-6c36a6b8ecf1)

## DELETAR TAREFA
![image](https://github.com/Lucasgyn94/SistemaGerenciadorTarefasDotnet/assets/91031320/7b366397-9fec-4356-9bea-9a1bd0032c75)
