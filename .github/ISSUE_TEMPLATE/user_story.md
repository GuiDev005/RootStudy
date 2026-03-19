---
about: Criar uma nova história de usuário
labels: user-story
name: User Story
title: USXX - 
---

## Epic

Sistema de Planejamento acadêmico inteligente. 

Permitir que estudantes organizem sua rotina acadêmica por meio da geração automática de cronogramas de estudo, considerando datas de provas, desempenho nas disciplinas e prioridades, com o objetivo de melhorar o rendimento e aumnetar as chances de aprovação.

---------------------------------------------------------------------------------------------------

## História de Usuário

Como estudantes universitários
quero um cronograma automático baseado nas datas das minhas provas e nas matérias com maior risco de reprovação,
para organizar melhor meu tempo e aumentar minha chance de aprovação.

---------------------------------------------------------------------------------------------------
## Critérios de Aceitação em Given / When / Then
Critério 1 - Cadastro de matérias 

Dado que o estudante está no sistema, 
quando ele cadastrar suas matérias 
então o sistema deve salvar e exibir a lista de matérias cadastradas.

Critério 2 - Cadastro de datas das provas 

Dado que o estudante possui as matérias cadastradas
quando ele informar a data das prova de cada matéria, 
então o sistema deve registrar as datas corretamente.

Critério 3 - Indicação de risco de reprovação

Dado que o estudante cadastrou suas matérias
quando ele marcar quais matérias tem risco de reprovar, 
então o sistema deve registrar essas matérias como prioridade. 

Critério 4 - Geração do cronograma 

Dado que o estudante cadastrou as matérias marcadas como maior risco de reprovação, 
quando o cronograma for gerado, 
então o sistema deve criar automaticamnete um plano de estudos. 

Critério 5 - Prioridade no cronograma 

Dado que existem matérias marcadas com risco de reprovação
quando o cronograma for gerado, 
então o sistema deve priorizar mais tempo de estudo para essas matérias. 



