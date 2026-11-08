SAPE
# UC09 — Gerenciar Questões

## Objetivo
Permitir que administradores gerenciem a base de questões utilizada na preparação para o ENADE.

## Ator principal
Administrador.

## Pré-condições
- O administrador deve estar autenticado.
- O administrador deve possuir permissão para gerenciar questões.

## Fluxo principal
1. O administrador acessa o módulo de questões.
2. O sistema apresenta as opções de gerenciamento.
3. O administrador seleciona a opção de cadastro, edição ou remoção.
4. O sistema apresenta o formulário correspondente.
5. O administrador informa ou altera os dados da questão.
6. O sistema valida as informações.
7. O sistema registra a operação.
8. O sistema apresenta a confirmação da operação.

## Fluxos alternativos
- **A1 — Dados inválidos:** o sistema informa os campos que precisam ser corrigidos.
- **A2 — Questão duplicada:** o sistema informa a possível duplicidade.
- **A3 — Usuário sem permissão:** o sistema impede a operação.
- **A4 — Questões externas indisponíveis:** o administrador poderá utilizar o cadastro manual autorizado.

## Pós-condições
A base interna de questões é atualizada.

## Requisitos relacionados
RF16, RF22.

## Regras de negócio relacionadas
RN09, RN10, RN11, RN15.
