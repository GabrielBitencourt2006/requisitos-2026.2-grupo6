SAPE
# UC04 — Solicitar Atendimento Humano

## Objetivo
Permitir que o estudante solicite atendimento com um professor voluntário quando desejar orientação humana.

## Ator principal
Estudante.

## Ator secundário
Professor voluntário.

## Pré-condições
- O estudante deve estar autenticado.
- O estudante deve possuir acesso ao sistema.

## Fluxo principal
1. O estudante seleciona a opção de atendimento humano.
2. O sistema apresenta um formulário para descrever a dúvida ou o assunto.
3. O estudante informa os dados solicitados.
4. O estudante confirma a solicitação.
5. O sistema registra a solicitação.
6. O sistema verifica os professores disponíveis.
7. O sistema encaminha a solicitação conforme os critérios de distribuição definidos.
8. O sistema informa ao estudante que a solicitação foi registrada.
9. O professor recebe ou visualiza a solicitação.

## Fluxos alternativos
- **A1 — Não existem professores disponíveis:** o sistema informa a indisponibilidade e mantém a solicitação registrada para atendimento posterior, conforme a política definida.
- **A2 — Dados obrigatórios não preenchidos:** o sistema solicita o preenchimento das informações necessárias.
- **A3 — Falha no encaminhamento:** o sistema mantém o registro da solicitação e informa que o encaminhamento não foi concluído.
- **A4 — Solicitação cancelada:** o estudante cancela a solicitação antes do início do atendimento, desde que permitido pelas regras do sistema.

## Pós-condições
- A solicitação fica registrada.
- A situação da solicitação é atualizada.
- O estudante consegue consultar o estado do pedido.

## Requisitos relacionados
RF06, RF07, RF08.

## Regras de negócio relacionadas
RN03, RN04, RN05, RN06, RN07.
