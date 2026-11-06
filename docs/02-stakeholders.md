# Identificação de Stakeholders

## 1. Objetivo

Identificar os principais envolvidos no Sistema de Apoio ao ENADE, suas responsabilidades, interesses e influência sobre o desenvolvimento e a utilização da solução.

## 2. Stakeholders identificados

| ID | Stakeholder | Tipo | Interesse |
|---|---|---|---|
| ST01 | Estudantes selecionados para o ENADE | Usuário direto | Preparar-se para o exame e esclarecer dúvidas. |
| ST02 | Professores voluntários | Usuário direto | Auxiliar estudantes e acompanhar solicitações. |
| ST03 | Coordenadores acadêmicos | Gestão | Acompanhar a preparação e organizar a participação dos professores. |
| ST04 | Administradores do sistema | Gestão técnica | Gerenciar usuários, permissões e conteúdos. |
| ST05 | Instituição de ensino | Institucional | Apoiar os estudantes e melhorar a organização da preparação. |
| ST06 | UniforOnline | Sistema externo | Disponibilizar informações institucionais, se houver integração autorizada. |
| ST07 | INEP | Órgão/sistema externo | Fonte de questões e informações oficiais do ENADE. |
| ST08 | Serviço de Inteligência Artificial | Serviço tecnológico | Processar perguntas e gerar respostas para os estudantes. |

## 3. Descrição dos stakeholders

### ST01 — Estudantes

São os principais usuários da plataforma. Precisam acessar materiais de preparação, consultar questões, realizar simulados e obter suporte para dúvidas.

**Necessidades:**
- Acesso simples e seguro.
- Respostas para dúvidas.
- Opção de atendimento humano.
- Acesso a questões e simulados.
- Visualização do próprio desempenho.

### ST02 — Professores voluntários

São professores selecionados pela instituição que aceitam participar voluntariamente do acompanhamento dos estudantes.

**Necessidades:**
- Acesso às solicitações de atendimento.
- Visualização das dúvidas encaminhadas.
- Organização dos atendimentos.
- Atualização de disponibilidade.
- Histórico de atendimentos realizados.

### ST03 — Coordenadores acadêmicos

Responsáveis por organizar a participação acadêmica no projeto e acompanhar a atuação dos professores.

**Necessidades:**
- Visualizar professores participantes.
- Acompanhar solicitações e atendimentos.
- Identificar necessidades dos estudantes.
- Acompanhar indicadores gerais, conforme permissões.

### ST04 — Administradores do sistema

Responsáveis pela administração técnica e operacional da plataforma.

**Necessidades:**
- Gerenciar contas e permissões.
- Gerenciar questões e conteúdos.
- Configurar parâmetros do sistema.
- Monitorar funcionamento e integrações.

### ST05 — Instituição de ensino

É a organização responsável pelo contexto acadêmico em que o sistema será utilizado.

**Interesses:**
- Apoiar os estudantes selecionados.
- Organizar o acompanhamento para o ENADE.
- Facilitar a atuação dos professores voluntários.
- Garantir uso adequado das informações institucionais.

### ST06 — UniforOnline

Sistema institucional externo considerado como fonte de dados sobre estudantes e professores selecionados.

**Dependências:**
- Autorização institucional.
- Disponibilidade de acesso técnico.
- Definição dos dados que poderão ser compartilhados.
- Regras de segurança e privacidade.

### ST07 — INEP

Órgão externo responsável pelas informações oficiais relacionadas ao ENADE.

**Dependências:**
- Disponibilidade de conteúdo.
- Condições de acesso e utilização.
- Existência de interface ou mecanismo autorizado de obtenção de dados.

### ST08 — Serviço de Inteligência Artificial

Serviço tecnológico utilizado para interpretar perguntas e gerar respostas.

**Responsabilidades esperadas:**
- Processar perguntas dos estudantes.
- Gerar respostas contextualizadas.
- Auxiliar na explicação de questões.
- Sinalizar limitações quando não tiver segurança para responder.

A IA não deverá substituir a opção de atendimento humano.

## 4. Priorização dos stakeholders

| Stakeholder | Interesse | Influência | Prioridade |
|---|---|---|---|
| Estudantes | Alto | Alto | Muito alta |
| Professores voluntários | Alto | Alto | Muito alta |
| Coordenadores | Alto | Alto | Alta |
| Administradores | Alto | Alto | Alta |
| Instituição | Alto | Alto | Muito alta |
| UniforOnline | Médio/alto | Alto | Alta |
| INEP | Médio/alto | Alto | Alta |
| Serviço de IA | Alto | Médio/alto | Alta |

## 5. Considerações

Os stakeholders externos não são usuários necessariamente autenticados na plataforma. INEP e UniforOnline são tratados como sistemas externos participantes de integrações planejadas, não como funcionalidades internas.
