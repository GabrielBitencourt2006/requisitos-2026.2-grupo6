# UC11 — Sincronizar Dados Institucionais

## Objetivo
Permitir a obtenção de informações institucionais sobre estudantes e professores selecionados para o ENADE e, quando autorizado e tecnicamente viável, obter questões e informações oficiais relacionadas ao exame.

## Ator principal
Administrador/Coordenador.

## Sistemas externos envolvidos
- UniforOnline.
- INEP.

## Pré-condições
- O administrador deve estar autenticado e autorizado.
- Deve existir mecanismo de integração ou acesso autorizado aos dados externos.
- As condições de uso e compartilhamento dos dados devem estar definidas.

## Fluxo principal
1. O administrador acessa o módulo de integrações.
2. O sistema apresenta as integrações disponíveis.
3. O administrador seleciona a integração desejada.
4. O sistema verifica as condições de conexão.
5. O sistema solicita os dados disponíveis ao sistema externo.
6. O sistema recebe as informações.
7. O sistema valida os dados recebidos.
8. O sistema registra ou atualiza as informações autorizadas.
9. O sistema apresenta o resultado da operação.

## Fluxos alternativos
- **A1 — UniforOnline indisponível:** o sistema informa a falha e permite utilizar os mecanismos alternativos de cadastro autorizados.
- **A2 — INEP indisponível:** o sistema informa a indisponibilidade e mantém disponíveis as questões já cadastradas.
- **A3 — Integração não autorizada:** o sistema não realiza a operação e informa a necessidade de autorização.
- **A4 — Dados inválidos ou incompletos:** o sistema rejeita os dados inconsistentes e registra a ocorrência.
- **A5 — Integração ainda não implementada:** o sistema informa que a funcionalidade depende de configuração e viabilidade técnica.

## Pós-condições
- Quando a integração estiver disponível e autorizada, os dados recebidos serão atualizados conforme as regras estabelecidas.
- Quando a integração não estiver disponível, os dados internos permanecerão acessíveis.
- A operação será registrada para fins de acompanhamento.

## Requisitos relacionados
RF03, RF20, RF21, RF22.

## Regras de negócio relacionadas
RN09, RN10, RN14, RN15.
