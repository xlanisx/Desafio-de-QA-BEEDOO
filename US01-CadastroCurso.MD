# Cadastro de Curso

## Objetivo

Permitir que o usuário cadastre um novo curso na aplicação. Após o cadastro, o usuário será redirecionado para a lista de cursos disponíveis.

## Requisitos do Usuário

Como um usuário da aplicação, eu quero:
- Cadastrar um curso
- Ver a lista dos meus cursos disponíveis

## Critérios de Aceitação

### Acesso ao Formulário

- O formulário de cadastro de curso estará disponível ao clicar no menu **"Cadastrar curso"**.

### Campos do Formulário

Os campos obrigatórios do formulário de cadastro de curso são:

1. **Nome do curso**
   - Tipo: Texto
   - Limite de caracteres: 50

2. **Descrição do curso**
   - Tipo: Texto
   - Limite de caracteres: 256

3. **Instrutor**
   - Tipo: Texto
   - Limite de caracteres: 50

4. **URL da imagem de capa**
   - Tipo: Texto
   - Validação: Deve ser uma URL válida

5. **Data de início**
   - Tipo: Data
   - Funcionalidade: Selecione a data via calendário

6. **Data de fim**
   - Tipo: Data
   - Funcionalidade: Selecione a data via calendário
   - Restrição: Não deve ser menor que a **Data de início**

7. **Número de vagas**
   - Tipo: Numérico
   - Limite: Máximo de 1000 vagas

8. **Tipo de curso**
   - Tipo: Seleção
   - Opções: **Presencial**, **Online**

### Validações

- **Nome do curso, Descrição do curso, Instrutor:**
  - Respeitar o limite de caracteres especificado.

- **URL da imagem de capa:**
  - Deve ser uma URL válida.

- **Data de início e Data de fim:**
  - **Data de fim** não pode ser anterior à **Data de início**.

- **Número de vagas:**
  - Deve estar dentro do limite máximo de 1000.

### Mensagens de Erro

- Mensagem padrão para campos obrigatórios não preenchidos: **"O campo é obrigatório"**.

### Finalização do Cadastro

- O cadastro só pode ser finalizado se todos os campos obrigatórios estiverem preenchidos corretamente.
- Após a conclusão bem-sucedida do cadastro, o usuário será redirecionado para a lista de cursos disponíveis.

### Mensagens de Feedback

- **Sucesso:** "Curso cadastrado com sucesso. Você será redirecionado para a lista de cursos."
- **Erro de Validação:** Mensagens específicas para cada tipo de erro (e.g., "URL inválida", "Data de fim não pode ser menor que a data de início").

---

Este documento fornece uma visão geral dos requisitos e critérios de aceitação para o cadastro de cursos na aplicação. Sinta-se à vontade para ajustar conforme necessário.
# Cadastro de Curso

## Objetivo

Permitir que o usuário cadastre um novo curso na aplicação. Após o cadastro, o usuário será redirecionado para a lista de cursos disponíveis.

## Requisitos do Usuário

Como um usuário da aplicação, eu quero:
- Cadastrar um curso
- Ver a lista dos meus cursos disponíveis

## Critérios de Aceitação

### Acesso ao Formulário

- O formulário de cadastro de curso estará disponível ao clicar no menu **"Cadastrar curso"**.

### Campos do Formulário

Os campos obrigatórios do formulário de cadastro de curso são:

1. **Nome do curso**
   - Tipo: Texto
   - Limite de caracteres: 50

2. **Descrição do curso**
   - Tipo: Texto
   - Limite de caracteres: 256

3. **Instrutor**
   - Tipo: Texto
   - Limite de caracteres: 50

4. **URL da imagem de capa**
   - Tipo: Texto
   - Validação: Deve ser uma URL válida

5. **Data de início**
   - Tipo: Data
   - Funcionalidade: Selecione a data via calendário

6. **Data de fim**
   - Tipo: Data
   - Funcionalidade: Selecione a data via calendário
   - Restrição: Não deve ser menor que a **Data de início**

7. **Número de vagas**
   - Tipo: Numérico
   - Limite: Máximo de 1000 vagas

8. **Tipo de curso**
   - Tipo: Seleção
   - Opções: **Presencial**, **Online**

### Validações

- **Nome do curso, Descrição do curso, Instrutor:**
  - Respeitar o limite de caracteres especificado.

- **URL da imagem de capa:**
  - Deve ser uma URL válida.

- **Data de início e Data de fim:**
  - **Data de fim** não pode ser anterior à **Data de início**.

- **Número de vagas:**
  - Deve estar dentro do limite máximo de 1000.

### Mensagens de Erro

- Mensagem padrão para campos obrigatórios não preenchidos: **"O campo é obrigatório"**.

### Finalização do Cadastro

- O cadastro só pode ser finalizado se todos os campos obrigatórios estiverem preenchidos corretamente.
- Após a conclusão bem-sucedida do cadastro, o usuário será redirecionado para a lista de cursos disponíveis.

### Mensagens de Feedback

- **Sucesso:** "Curso cadastrado com sucesso. Você será redirecionado para a lista de cursos."
- **Erro de Validação:** Mensagens específicas para cada tipo de erro (e.g., "URL inválida", "Data de fim não pode ser menor que a data de início").

---

Este documento fornece uma visão geral dos requisitos e critérios de aceitação para o cadastro de cursos na aplicação. Sinta-se à vontade para ajustar conforme necessário.
