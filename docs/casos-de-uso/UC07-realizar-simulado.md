SAPE
# UC07 — Realizar Simulado

## Objetivo
Permitir que o estudante realize um simulado com questões disponíveis na plataforma.

## Ator principal
Estudante.

## Pré-condições
- O estudante deve estar autenticado.
- Deve existir um simulado disponível ou questões suficientes para sua composição.

## Fluxo principal
1. O estudante acessa a área de simulados.
2. O sistema apresenta os simulados disponíveis.
3. O estudante seleciona um simulado.
4. O sistema apresenta as instruções e as questões.
5. O estudante responde às questões.
6. O sistema registra as respostas.
7. O estudante finaliza o simulado.
8. O sistema processa as respostas conforme os critérios cadastrados.
9. O sistema apresenta o resultado.

## Fluxos alternativos
- **A1 — Simulado indisponível:** o sistema informa que não existem simulados disponíveis.
- **A2 — Simulado interrompido:** o sistema aplica a política de salvamento e retomada definida para a plataforma.
- **A3 — Questão não respondida:** o sistema informa a existência de questões sem resposta antes da finalização, conforme a configuração do simulado.
- **A4 — Falha ao salvar respostas:** o sistema informa que não conseguiu registrar as respostas e orienta o estudante sobre a recuperação da atividade.

## Pós-condições
- As respostas ficam registradas.
- O resultado do simulado é disponibilizado quando processado.
- O histórico do estudante é atualizado.

## Requisitos relacionados
RF12, RF13, RF14.

## Regras de negócio relacionadas
RN12, RN13, RN18.
