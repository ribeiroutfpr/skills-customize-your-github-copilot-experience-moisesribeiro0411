# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Construa uma API REST para gerenciar tarefas usando FastAPI. Pratique a criação de rotas CRUD, validação de dados com modelos Pydantic e o uso de códigos de status HTTP.

## 📝 Tasks

### 🛠️ Criar os modelos e as rotas da API

#### Descrição
Crie uma aplicação FastAPI para gerenciar tarefas. Cada tarefa deve ter um identificador, um título, uma descrição opcional e um indicador de conclusão. Use armazenamento em memória para manter o foco nas rotas e no comportamento HTTP.

#### Requisitos
O programa concluído deve:

- Definir modelos Pydantic para validar os dados de entrada e representar uma tarefa.
- Implementar `GET /tasks` para listar tarefas e `GET /tasks/{task_id}` para buscar uma tarefa por identificador.
- Implementar `POST /tasks` para criar uma tarefa e retornar o recurso criado com o código de status `201`.
- Implementar `PUT /tasks/{task_id}` para atualizar uma tarefa e `DELETE /tasks/{task_id}` para removê-la.
- Retornar `404 Not Found` quando uma rota receber um identificador que não corresponde a nenhuma tarefa.

### 🛠️ Validar e executar a API

#### Descrição
Execute a aplicação localmente, confira as respostas das rotas e use a documentação interativa do FastAPI para testar as operações.

#### Requisitos
O programa concluído deve:

- Instalar as dependências `fastapi` e `uvicorn`.
- Iniciar a aplicação com `uvicorn main:app --reload`.
- Permitir testar as rotas pela documentação interativa em `/docs`.
- Verificar os códigos de status e os dados de resposta para operações bem-sucedidas e para uma tarefa inexistente.
