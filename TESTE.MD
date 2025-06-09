# Plano de Testes do SIGA Mobile App

Este documento detalha a abordagem de testes utilizada no projeto do aplicativo SIGA, contemplando **Requisitos Funcionais (RF)** e **Requisitos Não Funcionais (RNF)**. Para cada requisito, foram definidos 3 casos de teste:

Cada caso de teste contém:
- **Identificação** (ex.: RF0-1-TC01)
- **Objetivo**
- **Dados de Entrada**
- **Procedimento**
- **Resultado Esperado**

---

## Estrutura de Casos de Teste

| Identificação | Objetivo | Dados de Entrada  | Procedimento | Resultado Esperado |
|---------------|----------|-------------------|--------------|---------------------|
| RF0-1-TC01    | Login com credenciais válidas| Usuário: aluno@fatec.com \| Senha: Fatec123 | Inserir as credenciais válidas nos campos de login e senha e clicar no botão "Entrar". | Usuário redirecionado automaticamente à tela principal do aplicativo, exibindo informações acadêmicas. |
| RF0-1-TC02    | Login com senha incorreta | Usuário: aluno@fatec.com \| Senha: incorreta123 | Inserir usuário válido e senha incorreta nos respectivos campos e clicar em "Entrar". | Mensagem de alerta exibida: "Usuário ou senha incorretos. Tente novamente." |
| ... | ... | ... | ... | ... |

---

## Exemplos de Casos de Teste

### 1️⃣ RF0-1-TC01
**Login com credenciais válidas**  
Usuário: aluno@fatec.com \| Senha: Fatec123  
Inserir as credenciais válidas nos campos de login e senha e clicar no botão "Entrar".  
Usuário redirecionado automaticamente à tela principal do aplicativo, exibindo informações acadêmicas.

---

### 2️⃣ RF0-2-TC03
**Consulta em disciplina não cursada**  
Usuário tenta acessar disciplina não matriculada  
Acessar diretamente URL específica da disciplina não matriculada.  
Mensagem informativa exibida: "Você não está matriculado nesta disciplina. Acesso negado."

---

### 3️⃣ RF0-4-TC02
**Solicitação repetida do mesmo documento**  
Usuário tenta solicitar histórico já solicitado  
Selecionar novamente histórico escolar e clicar em "Solicitar".  
Aviso exibido: "Documento já solicitado anteriormente. Acesse sua área de documentos para visualizá-lo."

---

### 4️⃣ RNF-06-TC02
**Queda de desempenho com alta carga**  
Simular 500 acessos simultâneos  
Executar teste de carga com 500 usuários conectados ao mesmo tempo.  
App pode ficar lento mas deve exibir: "Alta demanda detectada, aguarde."

---

** Todos os testes foram organizados para garantir:
. Confiabilidade  
. Usabilidade  
. Segurança e conformidade com normas (ex.: LGPD)  
. Desempenho estável mesmo em situações extremas  

Estes testes fazem parte da garantia de qualidade do projeto e podem ser encontrados em formato CSV/planilha para facilitar a manutenção e expansão. 
--> https://docs.google.com/spreadsheets/d/1BXd5kqMvcqjobqX-hgtsaOsaBiC4lZpdnufS_OgZk0g/edit?usp=sharing
