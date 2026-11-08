SAPE
# UC01 — Autenticar Usuário

## Objetivo
Permitir que usuários autorizados acessem o Sistema de Apoio ao ENADE.

## Ator principal
Estudante, Professor voluntário ou Administrador.

## Pré-condições
- O usuário deve possuir cadastro ou estar previamente autorizado.
- O sistema deve estar disponível.

## Fluxo principal
1. O usuário acessa a página de login.
2. O sistema apresenta os campos de autenticação.
3. O usuário informa suas credenciais.
4. O sistema valida as informações.
5. O sistema identifica o perfil do usuário.
6. O sistema disponibiliza as funcionalidades correspondentes ao perfil.

## Fluxos alternativos
- **A1 — Credenciais inválidas:** o sistema informa que os dados estão incorretos e permite nova tentativa.
- **A2 — Usuário não autorizado:** o sistema impede o acesso e informa que o usuário não possui permissão.
- **A3 — Falha no serviço de autenticação:** o sistema informa que não foi possível concluir a autenticação.

## Pós-condições
- O usuário autenticado acessa as funcionalidades autorizadas.
- O acesso fica associado ao perfil correspondente.

## Requisitos relacionados
RF01, RF02.
