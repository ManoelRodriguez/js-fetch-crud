# Aplicação de Cadastro de Clientes - Petshop
## Descrição do Projeto
Este projeto consiste em uma aplicação web para gerenciar o cadastro de clientes de um petshop. Ele foi desenvolvido com foco em operações CRUD e no uso de uma API mock.

### Funcionalidades:
  
- Cadastro de clientes: Adicionar novos clientes ao sistema.
- Listagem de clientes: Exibir todos os clientes cadastrados.
- Edição de dados: Atualizar as informações de um cliente existente.
- Exclusão de clientes: Remover clientes do sistema.
  
### Tecnologias Utilizadas:
  
- JavaScript: Linguagem principal do projeto.
- Fetch API: Para realizar requisições HTTP (GET, POST, PUT, DELETE).
- Banco de dados mock: Simulação de armazenamento de dados com arquivo db.json.
- Funções assíncronas: Uso de async/await para lidar com requisições de forma eficiente.
  
### Conceitos Aplicados:
  
- CRUD: Implementação completa das operações de criação, leitura, atualização e exclusão de dados.
- Async/Await: Garantia de processamento assíncrono, melhorando a experiência de uso da aplicação.
- Manuseio de DOM: Criação e manipulação dinâmica de elementos HTML para atualização da interface.
  
### Como Rodar o Projeto:

```js
json-server --watch db.json
```
```js
browser-sync start --server --file . --host --port 5000 --startPath admin/telas/lista_cliente.html
```
