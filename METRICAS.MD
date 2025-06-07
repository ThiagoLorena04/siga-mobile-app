# MÉTRICAS.md – Métricas do Projeto SIGA Mobile App

Este documento apresenta o cálculo estimado de Pontos de Função do sistema e as métricas que serão adotadas para monitorar o progresso e a qualidade do desenvolvimento do aplicativo **SIGA**.

---

## Visão Geral do Sistema

O **SIGA** tem como objetivo oferecer aos alunos(as) uma plataforma mobile integrada e acessível para consulta de informações acadêmicas essenciais, incluindo:

- Visualização de notas e histórico escolar
- Gerenciamento de faltas e presença
- Consulta de disciplinas matriculadas e horários
- Avisos e mensagens importantes

O sistema prioriza **usabilidade, acessibilidade** e **integração com o SIGA** oficial, garantindo que as informações estejam atualizadas e organizadas.

---

## Cálculo de Pontos de Função (PF)

O cálculo dos Pontos de Função foi baseado na identificação das principais funcionalidades do app e na classificação de complexidade. Utilizamos como ferramenta de apoio uma **planilha de Pontos de Função**, que segue a seguinte estrutura:

| Tipo de Funcionalidade | Quantidade | Complexidade (Média) | PF por Item | Total PF |
|--------------------------|------------|----------------------|-------------|----------|
| Entradas Externas (EE)   | 4          | Média                | 4           | 16       |
| Saídas Externas (SE)     | 4          | Média                | 5           | 20       |
| Consultas Externas (CE)  | 3          | Média                | 4           | 12       |
| Arq Lógicos Internos (ALI) | 2        | Média                | 7           | 14       |
| Arq de Interface Externa (AIE) | 1    | Baixa              | 5           | 5        |
| **Total Geral**          | -          | -                    | -           | **67 PF**|

 Descrição resumida
- **Entradas Externas (EE):** formulários de login, atualização de dados, solicitações de documentos, envio de mensagens.  
- **Saídas Externas (SE):** relatórios de notas, boletim, faltas e avisos.  
- **Consultas Externas (CE):** visualização de disciplinas e horários.  
- **ALI:** dados acadêmicos internos do app (cache local, histórico de notas).  
- **AIE:** integração do app com o SIGA oficial (banco de dados externo).

O valor **67 PF** é uma estimativa que reflete o escopo atual do projeto e pode sofrer ajustes conforme o refinamento dos requisitos.

---

## Métricas para Acompanhamento do Desenvolvimento

Para garantir que o projeto atinja seus objetivos com qualidade e dentro do prazo, adotaremos as seguintes métricas de acompanhamento:

### 1 - Métricas de Progresso
- **% de Funcionalidades Concluídas**: rastreia o avanço em relação ao backlog definido.
- **Velocidade da Equipe (Story Points/Sprint)**: mensura a capacidade de entrega em cada sprint.
- **Número de Commits por Sprint**: monitora a atividade de versionamento e colaboração.

### 2 - Métricas de Qualidade
- **Taxa de Bugs Encontrados por Sprint**: avalia a estabilidade e a confiabilidade do app.
- **Taxa de Reabertura de Tarefas**: identifica possíveis falhas no desenvolvimento ou no entendimento dos requisitos.

### 3 - Métricas de Produtividade
- **Horas Gastas por Funcionalidade Entregue**: ajuda a ajustar as estimativas e identificar gargalos.
- **Índice de Retrabalho**: mede a eficiência do processo de desenvolvimento e revisão.

---

## Ferramentas de Apoio

- **Planilha de Pontos de Função (Excel/Google Sheets)**: para facilitar o cálculo e ajustes futuros.  
- **GitHub**: repositório central para versionamento e rastreabilidade.  
- **Jira / Trello / Monday**: ferramentas para gestão ágil de tarefas, sprints e métricas.  

---

 **Importante:**  
Essas métricas e o cálculo dos Pontos de Função não apenas atendem aos requisitos acadêmicos, mas também simulam um processo de **desenvolvimento profissional e sustentável**, alinhado com as melhores práticas de Engenharia de Software e gestão de produto digital.

---
