SAPE
# UC10 — Gerenciar Professores

## Objetivo
Permitir que administradores ou coordenadores gerenciem os professores participantes do programa de apoio ao ENADE.

## Ator principal
Administrador/Coordenador.

## Pré-condições
- O usuário deve estar autenticado.
- O usuário deve possuir permissão administrativa.

## Fluxo principal
1. O administrador acessa o módulo de professores.
2. O sistema apresenta os professores cadastrados.
3. O administrador seleciona um professor ou inicia um novo cadastro.
4. O sistema apresenta os dados disponíveis.
5. O administrador cadastra ou atualiza as informações.
6. O administrador registra a participação voluntária do professor, conforme confirmação obtida.
7. O sistema valida as informações.
8. O sistema registra a operação.
9. O sistema atualiza a lista de professores participantes.

## Fluxos alternativos
- **A1 — Professor não aceitou participar:** o sistema não o habilita para receber atendimentos.
- **A2 — Dados incompletos:** o sistema solicita o preenchimento das informações obrigatórias.
- **A3 — Professor já cadastrado:** o sistema apresenta o cadastro existente.
- **A4 — Usuário sem permissão:** o sistema impede a operação.

## Pós-condições
O cadastro e a situação de participação do professor são atualizados.

## Requisitos relacionados
RF17, RF18.

## Regras de negócio relacionadas
RN03, RN04, RN17.
