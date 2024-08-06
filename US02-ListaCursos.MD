# Lista de Cursos

## Objetivo

Permitir que o usuário acesse a lista de cursos disponíveis na aplicação para visualizar os cursos cadastrados.

## Requisitos do Usuário

Como um usuário da aplicação, eu quero:
- Acessar a lista de cursos.
- Ver os cursos disponíveis em um formato organizado e fácil de usar.

## Critérios de Aceitação

### Acesso à Lista de Cursos

- O usuário deve acessar a lista de cursos ao clicar no menu **"Listar Cursos"**.

### Visualização da Lista de Cursos

- **Sem Cursos Cadastrados:**
  - Se não houver cursos cadastrados, exibir uma tela padrão vazia com o texto: **"Não existem cursos cadastrados"**.

- **Com Cursos Cadastrados:**
  - Exibir os cursos em formato de **cards** com um tamanho padrão.
  - Cada card deve incluir um botão **"Excluir curso"**.
  - Ao clicar em **"Excluir curso"**, o usuário deve ver a mensagem: **"Curso excluído com sucesso"**.

### Funcionalidades Adicionais

- **Ordenação dos Cursos:**
  - Os cursos devem ser ordenados por **data de criação** por padrão.
  - O usuário deve ter a opção de ordenar os cursos por **data de criação** ou **ordem alfabética**.

- **Edição de Cursos:**
  - Não é permitido editar cursos diretamente a partir da lista.

## Comportamento Esperado

1. **Acesso à Lista:**
   - O usuário clica em **"Listar Cursos"** no menu.

2. **Tela Sem Cursos:**
   - Se não houver cursos cadastrados, a tela deve exibir: **"Não existem cursos cadastrados"**.

3. **Tela Com Cursos:**
   - Se houver cursos cadastrados, eles devem ser exibidos como cards.
   - Cada card deve ter um botão **"Excluir curso"**.
   - Ao clicar no botão **"Excluir curso"**, o curso é removido e uma mensagem de sucesso é exibida.

4. **Ordenação:**
   - A lista de cursos deve ser inicialmente ordenada por **data de criação**.
   - O usuário pode selecionar a ordenação por **data de criação** ou **ordem alfabética** através de uma opção de filtragem.


