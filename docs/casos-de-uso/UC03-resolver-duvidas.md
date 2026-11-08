SAPE
# UC03 — Resolver Dúvidas com IA

## Objetivo
Permitir que o estudante envie dúvidas ao assistente virtual e receba respostas relacionadas ao ENADE.

## Ator principal
Estudante.

## Ator secundário
Serviço de IA.

## Pré-condições
- O estudante deve estar autenticado.
- O assistente virtual deve estar disponível.

## Fluxo principal
1. O estudante acessa o assistente virtual.
2. O estudante digita sua dúvida.
3. O estudante envia a mensagem.
4. O sistema encaminha a pergunta ao serviço de IA.
5. O serviço de IA processa a pergunta.
6. O sistema apresenta a resposta ao estudante.
7. O estudante pode continuar a conversa ou solicitar atendimento humano.

## Fluxos alternativos
- **A1 — Pergunta não compreendida:** o sistema informa que não conseguiu interpretar a pergunta e solicita que o estudante reformule.
- **A2 — Ausência de resposta confiável:** o assistente informa sua limitação e recomenda atendimento humano.
- **A3 — Serviço indisponível:** o sistema informa a indisponibilidade e permite que o estudante tente novamente.
- **A4 — Solicitação de professor:** o estudante segue para o UC04.

## Pós-condições
A interação fica disponível durante a sessão, respeitando as políticas de armazenamento e privacidade definidas para o sistema.

## Requisitos relacionados
RF04, RF05.
