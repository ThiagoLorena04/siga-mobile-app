Gestão de Configuração do Projeto – SIGA Mobile App

Este documento estabelece as diretrizes e práticas para a gestão de configuração do projeto **SIGA Mobile App**, assegurando **rastreamento, controle de versões e colaboração eficiente**.

---

## Objetivos

✔ Garantir a integridade e a rastreabilidade de todos os artefatos do projeto.  
✔ Organizar as versões e revisões de forma estruturada e auditável.  
✔ Promover colaboração entre os membros da equipe e facilitar o acesso ao professor.

---

## 📁 Estrutura de Pastas

---

## Ferramentas Utilizadas

- **GitHub**: repositório central, versionamento e colaboração.
- **LucidChart / Draw.io**: modelagem de diagramas.
- **Figma / Balsamiq**: prototipagem de interface.
- **SCRUM**: metodologia ágil para organização de sprints e tarefas.

-

## Fluxo de Versionamento

- **main**: branch principal e estável.  
- **dev01**: branch para integração de novas funcionalidades.  
- **feature/**: branches para desenvolvimento de recursos específicos, nomeados como `feature/nome-da-feature`.

--

## Padrão de Commits

Adotar **mensagens claras e consistentes**, utilizando prefixos:  
- `feat:` para novas funcionalidades  
- `fix:` para correções de bugs  
- `docs:` para alterações na documentação  
- `style:` ajustes de formatação (espaços, identação, etc.)  
- `refactor:` refatoração de código  
- `test:` criação ou atualização de testes

---

Processo de Revisão

- Todo **merge** na branch `main` deve ser feito por meio de **pull request (PR)**.  
- Revisão de código por ao menos 1 membro antes do merge.  
- Evitar push direto na `main` para manter a integridade e rastreabilidade.
