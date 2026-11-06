# Requisitos Funcionais — SAPE

## 1. Objetivo

Este documento apresenta as funcionalidades que o Sistema de Apoio ao ENADE deverá oferecer aos seus usuários e sistemas externos.

## 2. Requisitos funcionais

### RF01 — Autenticação de usuários
O sistema deverá permitir que os usuários realizem autenticação para acessar as funcionalidades correspondentes ao seu perfil.

### RF02 — Controle de acesso por perfil
O sistema deverá disponibilizar funcionalidades de acordo com o perfil do usuário autenticado: estudante, professor ou administrador/coordenador.

### RF03 — Identificação de estudantes elegíveis
O sistema deverá permitir identificar os estudantes selecionados para o ENADE, utilizando dados institucionais disponibilizados ou, caso a integração não seja viável, uma forma alternativa de cadastro autorizado.

### RF04 — Acesso ao assistente virtual
O sistema deverá disponibilizar um chatbot com Inteligência Artificial para auxiliar os estudantes durante a preparação para o ENADE.

### RF05 — Envio de dúvidas ao assistente
O sistema deverá permitir que o estudante envie perguntas ao chatbot e receba respostas relacionadas à sua preparação para o exame.

### RF06 — Opção de atendimento humano
O sistema deverá disponibilizar ao estudante a opção de solicitar atendimento com um professor humano, inclusive quando estiver utilizando o chatbot.

### RF07 — Registro de solicitação de atendimento
O sistema deverá registrar as solicitações de atendimento humano, incluindo estudante, data, horário, assunto e situação da solicitação.

### RF08 — Encaminhamento de solicitações
O sistema deverá permitir encaminhar as solicitações aos professores voluntários selecionados, considerando a disponibilidade cadastrada.

### RF09 — Atendimento pelo professor
O sistema deverá permitir que o professor visualize as solicitações recebidas e realize o atendimento ao estudante.

### RF10 — Gerenciamento da disponibilidade dos professores
O sistema deverá permitir que professores participantes informem e atualizem sua disponibilidade para atendimento.

### RF11 — Consulta de questões
O sistema deverá permitir que os estudantes consultem questões relacionadas ao ENADE disponibilizadas na plataforma.

### RF12 — Realização de simulados
O sistema deverá permitir que os estudantes realizem simulados compostos por questões disponíveis no sistema.

### RF13 — Registro de respostas
O sistema deverá registrar as respostas fornecidas pelos estudantes durante a realização dos simulados.

### RF14 — Apresentação de resultados
O sistema deverá apresentar o resultado dos simulados realizados pelo estudante.

### RF15 — Acompanhamento de desempenho
O sistema deverá permitir que o estudante consulte seu histórico de simulados e acompanhe seu desempenho.

### RF16 — Gerenciamento de questões
O sistema deverá permitir que usuários autorizados cadastrem, editem, organizem e removam questões da base interna.

### RF17 — Gerenciamento de professores
O sistema deverá permitir que usuários autorizados cadastrem, consultem, atualizem e desativem professores participantes.

### RF18 — Gerenciamento de usuários
O sistema deverá permitir que administradores gerenciem os usuários e seus respectivos perfis de acesso.

### RF19 — Histórico de atendimentos
O sistema deverá manter o histórico das solicitações e dos atendimentos realizados, respeitando as permissões de acesso.

### RF20 — Consulta de informações institucionais
O sistema deverá permitir obter informações institucionais sobre estudantes e professores selecionados por meio de integração autorizada com o UniforOnline ou mecanismo alternativo aprovado.

### RF21 — Obtenção de questões e informações do INEP
O sistema deverá permitir a obtenção de questões e informações oficiais relacionadas ao ENADE por meio de mecanismos disponibilizados e autorizados pelo INEP, quando tecnicamente viável.

### RF22 — Alternativa para integrações indisponíveis
O sistema deverá permitir a inserção e atualização manual de informações e questões por usuários autorizados quando as integrações externas não estiverem disponíveis.

## 3. Observações

- A integração com UniforOnline e INEP é uma funcionalidade planejada e depende de autorização e viabilidade técnica.
- O atendimento humano depende da existência de professores voluntários disponíveis.
- A IA deverá informar suas limitações quando não conseguir responder adequadamente.
- A plataforma não deverá apresentar respostas geradas por IA como posicionamentos oficiais do INEP ou da instituição.
