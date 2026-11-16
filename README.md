
# Testes Automatizados de API REST com Postman

## Sobre o projeto

Projeto acadêmico desenvolvido durante meus estudos em Sistemas de Informação, com foco em Qualidade de Software (QA) e testes de APIs REST.

A coleção utiliza o Postman para realizar requisições HTTP à API pública JSONPlaceholder e validar automaticamente as respostas.

## Tecnologias utilizadas

- Postman
- JavaScript (scripts de teste)
- API REST
- HTTP
- JSON
- JSONPlaceholder

## Cenários de teste

### 1. GET - Post existente
- Verificação do status HTTP 200.
- Validação do formato JSON.
- Verificação dos campos obrigatórios.

### 2. GET - Post inexistente
- Verificação do status HTTP 404.

### 3. GET - Filtrar posts por usuário
- Validação do status HTTP 200.
- Verificação de resposta em formato de array.
- Conferência dos IDs dos usuários.

### 4. POST - Criar post simulado
- Verificação do status HTTP 201.
- Validação dos dados retornados.

### 5. GET - Comentários de um post
- Verificação do status HTTP 200.
- Validação da estrutura da resposta.
- Conferência da associação dos comentários ao post.

## Como executar

1. Instale o Postman.
2. Baixe o arquivo `.postman_collection.json` deste repositório.
3. Abra o Postman.
4. Clique em Import.
5. Selecione o arquivo JSON.
6. Abra a coleção importada.
7. Utilize o Collection Runner para executar os testes.
8. Confira os resultados das validações.

## Objetivo

Desenvolver conhecimentos práticos em testes de APIs, validação de respostas HTTP, automação de testes e identificação de possíveis falhas.

## Observações

A API JSONPlaceholder é pública e utilizada para testes e prototipação.

As operações POST são simuladas e não persistem os dados permanentemente.

## Autor

Projeto acadêmico desenvolvido por Felipe Talassi Honora Filho, estudante de Sistemas de Informação da Faculdade Impacta de Tecnologia.
