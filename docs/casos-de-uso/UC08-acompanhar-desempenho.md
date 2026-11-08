SAPE
# UC08 — Acompanhar Desempenho

## Objetivo
Permitir que o estudante acompanhe seu desempenho nos simulados realizados.

## Ator principal
Estudante.

## Pré-condições
- O estudante deve estar autenticado.
- Deve existir histórico de simulados ou resultados registrados.

## Fluxo principal
1. O estudante acessa a área de desempenho.
2. O sistema consulta os resultados associados ao estudante.
3. O sistema apresenta o histórico de simulados.
4. O sistema apresenta informações de desempenho.
5. O estudante seleciona um resultado para consultar detalhes.
6. O sistema apresenta as informações disponíveis.

## Fluxos alternativos
- **A1 — Não existem resultados:** o sistema informa que ainda não há simulados realizados.
- **A2 — Falha na consulta:** o sistema informa que não foi possível carregar o histórico.
- **A3 — Acesso não autorizado:** o sistema impede a visualização de resultados pertencentes a outro estudante.

## Pós-condições
O estudante visualiza seu histórico e os resultados disponíveis.

## Requisitos relacionados
RF14, RF15.

## Regras de negócio relacionadas
RN13, RN18.
