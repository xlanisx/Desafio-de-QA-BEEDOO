# DESAFIO QA BEEDOO

## User Stories e Casos de Teste

### Decisões Tomadas para Criar as User Stories

Ao criar as user stories, seguimos um processo de análise detalhada do módulo de curso disponível no site Creative Sherbet. As principais decisões e considerações foram:

1. *Identificação das Funcionalidades Principais*:
   - Analisamos o site para identificar as funcionalidades principais que um usuário precisaria acessar. Isso incluiu login, navegação para o módulo de curso, inscrição em cursos e acesso ao conteúdo do curso.

2. *Mapeamento das Jornadas do Usuário*:
   - Mapeamos as possíveis jornadas do usuário, desde o acesso inicial ao site até a conclusão de um curso. Esse mapeamento ajudou a garantir que todas as etapas críticas fossem cobertas pelas user stories.

3. *Consideração de Cenários de Sucesso e Falha*:
   - Para cada funcionalidade, consideramos cenários de sucesso (onde tudo funciona como esperado) e cenários de falha (onde ocorrem erros ou problemas). Isso garantiu que os testes fossem abrangentes e cobrissem diferentes situações.

4. *Simplificação e Clareza*:
   - Nos concentramos em criar user stories que fossem simples e claras, para que pudessem ser facilmente compreendidas por todas as partes interessadas. Evitamos detalhes técnicos e focamos na perspectiva do usuário.

### User Stories e Casos de Teste

#### User Story 1: Acesso ao módulo de curso
*User Story:*
Como usuário, quero acessar o módulo de curso para visualizar o conteúdo disponível.

*Casos de Teste:*

*Cenário 1: Acesso bem-sucedido ao módulo de curso*
```gherkin
Given que o usuário está na página inicial
When ele clica no link "Módulo de Curso"
Then ele deve ser redirecionado para a página do módulo de curso
And a página do módulo de curso deve ser exibida corretamente

Cenário 2: Página não encontrada


Given que o usuário está na página inicial
When ele clica em um link inválido
Then ele deve ver uma mensagem de erro "Página não encontrada"

User Story 2: Login no sistema
User Story:
Como usuário, quero fazer login no sistema para acessar meus cursos.

Casos de Teste:

Cenário 1: Login com sucesso

Given que o usuário está na página de login
And ele tem uma conta registrada
When ele insere seu email e senha corretos
And clica no botão "Login"
Then ele deve ser redirecionado para a página do painel de cursos
And uma mensagem de boas-vindas deve ser exibida

Cenário 2: Login com falha (credenciais incorretas)

gherkin
Copiar código
Given que o usuário está na página de login
And ele tem uma conta registrada
When ele insere um email ou senha incorretos
And clica no botão "Login"
Then ele deve ver uma mensagem de erro "Email ou senha incorretos"
