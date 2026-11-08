SAPE
# UC06 — Consultar Questões

## Objetivo
Permitir que o estudante consulte questões relacionadas ao ENADE disponíveis na plataforma.

## Ator principal
Estudante.

## Pré-condições
- O estudante deve estar autenticado.
- A base de questões deve possuir conteúdo disponível.

## Fluxo principal
1. O estudante acessa a área de questões.
2. O sistema apresenta as opções de consulta.
3. O estudante seleciona os filtros disponíveis.
4. O sistema pesquisa as questões cadastradas.
5. O sistema apresenta os resultados.
6. O estudante seleciona uma questão.
7. O sistema apresenta o enunciado e as informações disponíveis.

## Fluxos alternativos
- **A1 — Nenhuma questão encontrada:** o sistema informa que não existem questões correspondentes aos filtros.
- **A2 — Falha na consulta:** o sistema informa que não foi possível carregar as questões.
- **A3 — Conteúdo externo indisponível:** o sistema apresenta as questões internas disponíveis, sem depender de acesso em tempo real ao INEP.

## Pós-condições
O estudante consulta as questões disponíveis na plataforma.

## Requisitos relacionados
RF11.

## Regras de negócio relacionadas
RN09, RN10, RN11, RN15.
