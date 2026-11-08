SAPE
# UC05 — Gerenciar Atendimentos

## Objetivo
Permitir que professores voluntários visualizem e realizem os atendimentos solicitados pelos estudantes.

## Ator principal
Professor voluntário.

## Pré-condições
- O professor deve estar autenticado.
- O professor deve estar selecionado e autorizado a participar do programa.
- O professor deve possuir acesso ao módulo de atendimentos.

## Fluxo principal
1. O professor acessa a área de atendimentos.
2. O sistema apresenta as solicitações encaminhadas.
3. O professor seleciona uma solicitação.
4. O sistema apresenta as informações necessárias para o atendimento.
5. O professor inicia o atendimento.
6. O professor interage com o estudante.
7. O professor finaliza o atendimento.
8. O sistema atualiza a situação da solicitação.
9. O sistema registra o atendimento no histórico.

## Fluxos alternativos
- **A1 — Não existem solicitações:** o sistema informa que não há atendimentos pendentes.
- **A2 — Professor indisponível:** o professor atualiza sua disponibilidade e deixa de receber novas solicitações conforme as regras de distribuição.
- **A3 — Atendimento não concluído:** o professor atualiza a situação da solicitação conforme as opções permitidas.
- **A4 — Solicitação já atendida:** o sistema apresenta o registro existente e impede novo atendimento duplicado.

## Pós-condições
- O atendimento é registrado.
- A situação da solicitação é atualizada.
- O histórico fica disponível conforme as permissões de acesso.

## Requisitos relacionados
RF09, RF10, RF19.

## Regras de negócio relacionadas
RN03, RN04, RN07, RN16.
