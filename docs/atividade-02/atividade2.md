# Diagnóstico de Qualidade – Startup Local Eats

> Disciplina: Qualidade de Software  
> Aula 3 – Papéis, Responsabilidades e Práticas de QA  
> Equipe: Garotos do QA  
> Integrantes: Eric Bauer, Derek Bezerra, João Pedro Silva e Felipe Noguez

---

# 1. Diagnóstico da Situação Atual

## 1.1 Papéis atuais identificados

Liste quais papéis vocês acreditam que existem atualmente na startup.

- CEO
- Desenvolvedores
- Tech Lead
- Designer/Marketing

---

## 1.2 Quem é responsável pela qualidade hoje?

Descreva como vocês acreditam que a qualidade está sendo tratada atualmente.

> Resposta: Em uma startup com essas funções, a qualidade geralmente está atrelada aos desenvolvedores, com o desenvolvimento de testes e boas práticas na hora do código, deixando boa parte da qualidade fora de código de lado. Como acompanhamento de histórias de usuário, testes pós produção, etc. Aleém disso, acredito que o CEO tenha um papel importante de olhar por fora, como uma visão do cliente.

---

## 1.3 Problemas identificados

Liste os principais problemas relacionados à falta de organização da qualidade.

- Falta de clareza com quem é responsável pela qualidade (deve se ter uma opinião além da produção)
- Problemas aparecerão tanto em produção, como pós produção.
- Falta de acompanhamento inicial por um QA, pode causar problemas enormes no futuro do projeto.

---

## 1.4 Impactos desses problemas

Explique quais são as consequências desses problemas para o sistema e para os usuários.

> Resposta: Erros na hora do uso, reclamações para o cliente, problemas de carga, falta de coesão no projeto, entre outros...

---

## 1.5 A qualidade é responsabilidade de quem?

Explique se a qualidade deve ser responsabilidade de uma pessoa ou de toda a equipe.

> Resposta: A qualidade deve ter alguém responsável por todo o projeto. Mas todos integrantes devem estar cientes de usar as melhores práticas para produção, para evitar ao máximo falhas e bugs.

---

# 2. Papéis da Equipe Propostos

Definam quais papéis deveriam existir na equipe da Local Eats.

---

## 2.1 Lista de papéis

- Equipe de qualidade - com representante
- Equipe de desenvolvedores 
- SM
- Product Owner

---

## 2.2 Descrição dos papéis

Preencha a tabela abaixo:

| Papel | Responsabilidades principais | Relação com a qualidade |
| QA |Acompanhamento direto do desenvolvimento do produto junto com o cliente|Esclarecer ao máximo o produto para os desenvolvedores e acompanhar 100% do tempo|
| Product Owner | Conexão direta com o cliente | Manter o projeto alinhado com o que foi pedido inicialmente, e esclarecer atualizações e/ou mudanças |
| SM | Como um TECH LEAD, deve comandar a equipe de desenvolvedores e o restante da equipe com reuniões periódicas para alinhar todos em uma página| Manter o projeto alinhado para todos os setores do projeto |
| Equipe de desenvolvedores | Codificar o projeto e manter atualizações | Usar sempre as melhores práticas, e de acordo com o que for solicitado, usar testes unitários no código. |

---

# 3. Práticas de QA Sugeridas

Sugira práticas que a startup pode adotar para melhorar a qualidade.



---

## 3.1 Lista de práticas

- Acompanhamento do QA junto com o Product Owner para esclarecimento do projeto aos demais.
- Utilizar testes unitários no código. (desenvolvedores)
- QA atuar também no código, com testes de API.
- Liberar versão beta para amigos próximos, pois nem toda falha conseguimos identificar em produção.
---



# 4. Anúncios de Contratação

A startup decidiu contratar novos profissionais. Crie anúncios de vagas.

> Mínimo: 2 vagas

---

## 4.1 Vaga 1 – Quality Assurance

### Descrição da vaga
> Estamos em busca de um(a) Quality Assurance (QA) para garantir a qualidade do nosso produto desde as etapas iniciais de desenvolvimento até a entrega final ao usuário. Esse profissional atuará de forma próxima ao time de desenvolvimento e produto, assegurando que requisitos sejam bem definidos, testados e validados continuamente.

### Responsabilidades
- Planejar, criar e executar cenários de teste (manuais e automatizados)
- Validar histórias de usuário junto ao Product Owner
- Identificar, documentar e acompanhar bugs até sua resolução
- Realizar testes funcionais, regressivos e exploratórios

### Requisitos obrigatórios
- Experiência com testes manuais (funcionais e exploratórios)
- Noção de APIs (REST) e testes com ferramentas como Postman ou Insomnia
- Conhecimento em fundamentos de teste de software
- Entendimento básico de metodologias ágeis (Scrum/Kanban)

### Requisitos desejáveis
- Experiência com automação de testes (ex: Cypress, Playwright, Selenium)
- Experiência com testes de performance ou carga

### Certificações desejáveis
- ISTQB CTFL

---

## 4.2 Vaga 2 – Desenvolvedor com foco em Qualidade

### Descrição da vaga
> Procuramos um(a) Desenvolvedor(a) com forte mentalidade de qualidade, que não apenas implemente funcionalidades, mas também garanta a confiabilidade, testabilidade e sustentabilidade do código. O profissional atuará diretamente no desenvolvimento e na criação de testes automatizados.

### Responsabilidades
- Desenvolver novas funcionalidades com foco em qualidade e performance
- Trabalhar em conjunto com QA para garantir cobertura de testes
- Revisar código (code review) com foco em boas práticas
- Escrever e manter testes unitários e de integração

### Requisitos obrigatórios
- Experiência com desenvolvimento (ex: JavaScript, TypeScript, Python ou similar)
- Conhecimento em testes unitários (ex: Jest, Mocha, PyTest)
- Entendimento de boas práticas (Clean Code, SOLID)
- Noção de integração contínua (CI/CD)

### Requisitos desejáveis
- Experiência com TDD (Test Driven Development)
- Conhecimento em testes de integração e end-to-end


### Certificações desejáveis
- 

---

# 5. Conclusão da Equipe

Descreva brevemente:

- O que a equipe aprendeu com a atividade: A equipe entendeu melhor a importância da qualidade no projeto, principalmente em startup. Também vimos que não é só uma pessoa responsável, mas sim todo mundo envolvido no desenvolvimento.

- Principais dificuldades encontradas: A maior dificuldade foi definir quem cuida da qualidade, já que em startup as funções se misturam. Também foi difícil separar o papel do QA e dos desenvolvedores.

- Principais melhorias propostas para a startup: Inserir um QA desde o início, usar mais testes (unitários e API) e melhorar o alinhamento entre Product Owner, QA e desenvolvedores, para evitar erros em produção.