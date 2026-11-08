SAPE
# Catálogo de Casos de Uso — Sistema de Apoio ao ENADE

## 1. Objetivo

Apresentar os casos de uso previstos para descrever as interações entre os usuários, os sistemas externos e o Sistema de Apoio ao ENADE.

## 2. Atores

| Ator | Descrição |
|---|---|
| Estudante | Usuário que utiliza a plataforma para estudar e se preparar para o ENADE. |
| Professor voluntário | Professor selecionado que realiza atendimentos aos estudantes. |
| Administrador/Coordenador | Responsável pela administração e gestão da plataforma. |
| UniforOnline | Sistema externo previsto como fonte de dados institucionais. |
| INEP | Fonte externa prevista para questões e informações oficiais. |
| Serviço de IA | Serviço tecnológico que processa perguntas e gera respostas para o chatbot. |

**Observação:** o serviço de IA é tratado como sistema externo de apoio quando fornecido por uma plataforma de terceiros. Caso a IA seja implementada internamente, sua representação arquitetural poderá ser diferente.

## 3. Catálogo

| ID | Caso de uso | Ator principal |
|---|---|---|
| UC01 | Autenticar usuário | Estudante, Professor, Administrador |
| UC02 | Acessar assistente virtual | Estudante |
| UC03 | Resolver dúvidas com IA | Estudante |
| UC04 | Solicitar atendimento humano | Estudante |
| UC05 | Gerenciar atendimentos | Professor voluntário |
| UC06 | Consultar questões | Estudante |
| UC07 | Realizar simulado | Estudante |
| UC08 | Acompanhar desempenho | Estudante |
| UC09 | Gerenciar questões | Administrador |
| UC10 | Gerenciar professores | Administrador/Coordenador |
| UC11 | Sincronizar dados institucionais | Administrador/Coordenador |

## 4. Relação com os requisitos

| Caso de uso | Requisitos relacionados |
|---|---|
| UC01 | RF01, RF02 |
| UC02 | RF04 |
| UC03 | RF05, RF04 |
| UC04 | RF06, RF07, RF08 |
| UC05 | RF09, RF10, RF19 |
| UC06 | RF11 |
| UC07 | RF12, RF13, RF14 |
| UC08 | RF15 |
| UC09 | RF16, RF22 |
| UC10 | RF17, RF18 |
| UC11 | RF03, RF20, RF21, RF22 |

## 5. Observações

Os casos de uso descrevem o comportamento esperado do sistema. As integrações com UniforOnline e INEP dependem de autorização e viabilidade técnica. A especificação não pressupõe que essas integrações estejam implementadas.
