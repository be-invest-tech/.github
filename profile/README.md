# **Tecnologia InvestSmart XP | Be.Smart**
![alt text](logo-invest.png)
---

Olá, este é o github do setor de tecnologia da InvestSmart e Be.smart. Aqui serão centralizados os códigos do time de desenvolvimento e dados.

## Boas Práticas e padrões
Aqui estão algumas regras de padronização para manter a organização dos repositórios do time. É muito importante seguir os padrões de nomenclatura definidos aqui para manter os repositórios organizados para todos no time.

### Nome dos repositórios
Os repositórios devem ser nomeados seguindo o padrão:
  - Todo o nome deve estar em letras minúsculas
  - Palavras devem ser separadas com - (hífen)
  - Pense sempre em criar padrões de nomenclatura para grupos de código (Exemplo: todos os repositórios de pipelines de dados começam com o nome pipeline-xxxxx). Isto facilita a busca de repositórios por sufixos.

### Commits
Ao fazer um commit devemos seguir um padrão para manter as mudanças e alterações de código claras. Este padrão também é conhecido como commits semânticos.

#### **Estrutura dos commits:**
{*Tipo do commit*}{*Escopo do commit*}:{*Descrição da alteração*}

  - **Tipos de commit**:
    #### $\textcolor{red}{\textsf{OBRIGATÓRIO}}$ 
    - *feat* - Tratam adições de novas funcionalidades ou de quaisquer outras novas implementações e alterações de funcionalidade ao código.
    - *docs* - Inclusão ou alteração somente de arquivos de documentação.
    - *fix* - Essencialmente definem o tratamento de correções de bugs.
    - *refactor* - Tipo utilizado em quaisquer mudanças que sejam executados no código, porém não alterem a funcionalidade final da tarefa impactada.
    - *test* - Adicionando testes ausentes ou corrigindo testes existentes nos processos de testes automatizados (TDD)

    *Ex* - feat: acrescenta o sistema de login e autenticação

  - **Escopo do commit**:
    #### $\textcolor{orange}{\textsf{OPCIONAL}}$ 
    O escopo é opcional. É uma forma de indicar em qual contexto foi modificado. Exemplo ao realizar uma mudança no login do sistema.
      
      *Ex* - feat(login): altera a caixa de texto

  - **Descrição**:
    #### $\textcolor{red}{\textsf{OBRIGATÓRIO}}$ 
    Trata-se da breve descrição da modificação feita naquele commit. Sempre em letras minúsculas, menos quando necessário para nomear uma classe, por exemplo.
---
