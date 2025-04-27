# Equipe Hackthoon Codecon

## Equipe

- [**Daniel dos Santos**](https://github.com/danielhinsching) – Função (Desenvolvedor Fullstack) 
- [**Eduardo Montandon**](https://github.com/1montandon) – Função (Desenvolvedor Fullstack) 
- [**Gabriel Lima**](https://github.com/GabrielLima2803) – Função (Desenvolvedor Fullstack)
- [**Luiz Felipe**](https://github.com/LuizNunes06) – Função (Desenvolvedor Fullstack) 
- [**Pedro Henrique**](https://github.com/BlackVSK) – Função (DevOps) 


# **Padrões de Commit**

Os commits devem ser escritos **em inglês** no seguinte formato:  
`<Classificação>:<mensagem de commit><# da issue>`

### **Exemplo**

FEAT: Innital commit #01

O commit semântico possui os seguintes **elementos estruturais (tipos)**, que indicam a intenção ao utilizador(a) do código:

---

### **Classificação de Commit**

- **`feat`**  
  Inclui um **novo recurso** no código.  
  _(Relacionado ao **MINOR** do versionamento semântico)._

- **`fix`**  
  Soluciona um problema (**bug fix**).  
  _(Relacionado ao **PATCH** do versionamento semântico)._

- **`docs`**  
  Indica mudanças na **documentação**, como alterações no README.  
  _(Não inclui modificações em código)._

- **`test`**  
  Modifica ou cria **testes unitários**.  
  _(Não inclui alterações em código)._

- **`build`**  
  Relaciona-se a alterações em **arquivos de build e dependências**.

- **`perf`**  
  Identifica alterações de código relacionadas à **performance**.

- **`style`**  
  Refere-se a **formatações de código** (e.g., semicolons, trailing spaces, lint).  
  _(Não inclui alterações funcionais no código)._

- **`refactor`**  
  Indica **refatorações** que não alteram funcionalidades.  
  _(Exemplo: melhorar o desempenho ou a estrutura do código)._

- **`chore`**  
  Indica **atualizações de tarefas** administrativas ou de build.  
  _(Exemplo: adicionar pacotes no `.gitignore`)._

- **`ci`**  
  Aponta mudanças relacionadas à **integração contínua** (_continuous integration_).

- **`raw`**  
  Refere-se a alterações em **configurações, dados, features ou parâmetros**.

- **`cleanup`**  
  Remoção de **código comentado ou desnecessário**, aprimorando a legibilidade.

- **`remove`**  
  Indica a exclusão de **arquivos, diretórios ou funcionalidades obsoletas**.

---

# **Utilização de Issues**

### **Título da Issue**

O título deve seguir o padrão do commit final gerado pela conclusão da Issue.

Os titulos devem ser escritos **em inglês** no seguinte formato:  
`<Classificação>:<título da Issue>`

### Exemplo:

FEAT: Create sidebar component

### **Resumo**

Apresente brevemente o objetivo daquela tarefa.

## **Descrição**

Descreva o que precisa ser feito ou corrigido, em detalhes de maneira clara.

- A descrição deve ser feita em **inglês**.

## **Informações Adicionais**

- **Assignees** (_responsável pela realização da Issue_)
- **Label** (_legenda relacionada ao responsável da Issue_):
  `FRONTEND` |
  `BACKEND` |
  `DEVOPS` |
  `DOCS` |

- **Priority** (_prioridade para a realização da Issue_):
  `HIGH` | `MEDIUM` |`LOW`

- **Status** (_Fase de desenvolvimento da Issue_):
  `Backlog` | `Ready` |`In progress` | `Done`

---

---

# **Utilização de Pull Requests**

### **Título do Pull Request**

O título deve seguir o padrão do commit principal realizado durante a implementação.

Os títulos devem ser escritos **em inglês** no seguinte formato:  
`<Classificação>:<descrição do Pull Request>`

### **Exemplo:**

### **Resumo**

Apresente uma descrição breve sobre o propósito e impacto do Pull Request.

---

## **Descrição**

Detalhe as alterações realizadas de forma clara e objetiva:

- **Funcionalidades implementadas**
- **Bugs corrigidos**
- **Melhorias de código**
- **Refatorações**

> A descrição deve ser feita em **inglês**.

---

## **Informações Adicionais**

- **Reviewers:** (\_pessoas responsáveis pela revisão das alterações realizas)
- **Assignees:** (_pessoas responsáveis pelas alterações realizadas_)
- **Label:** (_categoria relacionada às mudanças realizadas_):
  - `FRONTEND`
  - `BACKEND`
  - `DEVOPS`
  - `DOCS`

---
