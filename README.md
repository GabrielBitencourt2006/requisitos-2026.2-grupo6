[Documento_de_Visao_Sistema_Apoio_ENADE.md](https://github.com/user-attachments/files/34342560/Documento_de_Visao_Sistema_Apoio_ENADE.md)
**SISTEMA DE APOIO AO ENADE**

**DOCUMENTO DE VISÃO**

Projeto de Extensão – Engenharia de Requisitos Aplicada ao Contexto Educacional

**Disciplina: Requisitos e Modelagem de Sistemas**  
Versão 1.0 \| 03 de novembro de 2026  
Equipe: Gabriel Lins (2622664), Gabriel Bitencourt (2520505)  
Instituição: Unifor

# **Controle do documento**

| Campo | Descrição |
| :---- | :---- |
| Nome do produto | Sistema de Apoio ao ENADE |
| Versão / data | 1.0 / 03-11-2026 |
| Situação | Versão inicial para validação com stakeholders |
| Responsável | \[inserir nome da equipe\] |
| Referência | Projeto de Extensão – ENADE: Engenharia de Requisitos Aplicada ao Contexto Educacional |

# **1\. Propósito do documento**

Este Documento de Visão apresenta o problema, os objetivos, o público-alvo, o escopo e os principais benefícios esperados do Sistema de Apoio ao ENADE. Ele estabelece uma compreensão comum do produto e orienta a elicitação, a especificação e a modelagem inicial dos requisitos.

O documento é uma linha de base preliminar. As necessidades aqui descritas deverão ser confirmadas ou ajustadas por entrevistas, questionários e validação com estudantes, professores e coordenações.

# **2\. Contexto e problema**

O ENADE é um componente curricular obrigatório e um indicador relevante da qualidade da educação superior brasileira. No contexto apresentado pelo projeto, estudantes enfrentam dificuldades para se preparar devido à falta de materiais organizados, oportunidades de prática por meio de simulados e feedback que os ajude a compreender seu desempenho.

A preparação pode ficar dispersa entre diferentes fontes, dificultando a identificação de lacunas de aprendizagem e a organização de uma rotina de estudos. Também pode haver dúvidas que não são resolvidas apenas pela consulta ao gabarito ou pela interação em fóruns.

# **3\. Visão do produto**

Oferecer uma plataforma web/mobile de apoio à preparação para o ENADE, reunindo questões de provas anteriores, simulados cronometrados, explicações comentadas, indicadores de desempenho e interação entre estudantes. Como diferencial proposto, a plataforma contará com um assistente conversacional baseado em IA e com a possibilidade de encaminhamento do estudante para atendimento de um professor voluntário previamente selecionado.

A IA será um recurso de apoio ao estudo, não um substituto do professor. O estudante poderá solicitar atendimento humano quando a dúvida exigir acompanhamento pedagógico, quando a resposta da IA não for suficiente ou quando simplesmente preferir conversar com um docente.

# **4\. Objetivos**

## **4.1 Objetivo geral**

Especificar, por meio de práticas de Engenharia de Requisitos, um sistema web/mobile de apoio à preparação dos estudantes para o ENADE, com banco de questões comentadas, simulados, acompanhamento de desempenho e suporte pedagógico.

## **4.2 Objetivos específicos**

* Organizar questões por ano, curso/área de conhecimento e componente (formação geral ou conhecimento específico).  
* Permitir a realização de simulados com controle de tempo.  
* Disponibilizar gabaritos comentados para apoiar a compreensão dos conteúdos.  
* Apresentar estatísticas de desempenho por área de conhecimento.  
* Promover a interação entre usuários por meio de um fórum associado às questões.  
* Disponibilizar um chatbot com IA para orientação e esclarecimento de dúvidas de estudo.  
* Permitir que o estudante solicite atendimento humano de um professor participante.  
* Apoiar a inscrição, seleção e gestão de professores voluntários para o programa de acompanhamento.

# **5\. Stakeholders e público-alvo**

| Stakeholder | Interesse / necessidade | Participação esperada |
| :---- | :---- | :---- |
| Estudante de graduação | Preparar-se para o ENADE, praticar questões, acompanhar evolução e tirar dúvidas. | Usuário principal; utiliza questões, simulados, fórum, IA e atendimento docente. |
| Professor voluntário | Apoiar estudantes e contribuir com a preparação para o exame. | Candidata-se, informa disponibilidade/áreas de domínio e realiza atendimentos após aprovação. |
| Coordenação de curso | Acompanhar a preparação e identificar necessidades dos estudantes. | Consulta indicadores agregados e apoia a mobilização dos participantes. |
| Administrador/gestor do sistema | Manter usuários, conteúdos, permissões e operação da plataforma. | Gerencia cadastros, questões, professores voluntários e parâmetros do sistema. |
| Equipe do projeto | Especificar e modelar uma solução factível. | Realiza elicitação, documentação, validação e modelagem; não implica implementação nesta etapa. |

# **6\. Escopo do produto**

## **6.1 Funcionalidades previstas no escopo-base**

* Banco de questões organizado por ano, curso/área e componente de conhecimento.  
* Simulados cronometrados para prática em condições semelhantes às do exame.  
* Gabarito comentado com explicações das respostas.  
* Estatísticas e visualizações de desempenho por área de conhecimento.  
* Fórum de discussão associado às questões.  
* Cadastro e autenticação de estudantes e administradores.

## **6.2 Funcionalidades diferenciais propostas**

* Chatbot com IA para responder dúvidas relacionadas aos estudos e explicar questões/conceitos.  
* Opção visível para solicitar transferência/encaminhamento para atendimento humano.  
* Cadastro de professores interessados em atuar voluntariamente no apoio ao ENADE.  
* Processo de análise e aprovação dos professores pela administração/coordenação responsável.  
* Gestão de disponibilidade, áreas de conhecimento e solicitações de atendimento docente.  
* Registro do estado do atendimento (solicitado, aguardando, em andamento, concluído ou cancelado).

## **6.3 Fora do escopo desta etapa**

* Implementação e disponibilização de código executável: o projeto é conceitual e voltado à documentação.  
* Correção automática de provas oficiais ou previsão de nota/resultado oficial do ENADE.  
* Substituição de aulas, orientação acadêmica institucional ou atendimento docente regular.  
* Garantia de que respostas geradas por IA sejam infalíveis; respostas devem ser tratadas como apoio e sujeitas a validação.  
* Definição de integração real com sistemas acadêmicos institucionais, caso não seja confirmada pelos stakeholders.

# **7\. Necessidades do usuário**

| ID | Necessidade |
| :---- | :---- |
| NU-01 | Encontrar questões do ENADE organizadas e relacionadas ao seu curso/área. |
| NU-02 | Praticar por meio de simulados com limite de tempo. |
| NU-03 | Entender por que uma alternativa está correta ou incorreta. |
| NU-04 | Visualizar pontos fortes e conteúdos que precisam de reforço. |
| NU-05 | Discutir dúvidas e interpretações com outros estudantes. |
| NU-06 | Receber ajuda imediata para dúvidas de estudo por meio de um assistente de IA. |
| NU-07 | Conseguir atendimento de um professor quando a IA não resolver a dúvida ou quando desejar apoio humano. |
| NU-08 | Como professor, pode-se candidatar voluntariamente e informar áreas de atuação e disponibilidade. |
| NU-09 | Como gestor, selecionar professores e organizar o atendimento aos estudantes. |

# **8\. Benefícios esperados**

* Centralização dos recursos de preparação em um único ambiente.  
* Maior oportunidade de prática e revisão orientada por desempenho.  
* Feedback mais compreensível por meio de questões comentadas.  
* Estímulo à aprendizagem colaborativa.  
* Apoio rápido e contínuo por IA, com possibilidade de escalonamento para um professor.  
* Aproximação entre estudantes, docentes e coordenações em torno da preparação para o ENADE.

# **9\. Premissas, dependências e restrições**

| Tipo | Descrição |
| :---- | :---- |
| Premissa | Estudantes terão acesso a dispositivo com navegador e conexão à internet. |
| Premissa | Haverá questões e gabaritos disponíveis para cadastro, respeitando a origem e os direitos de uso dos materiais. |
| Premissa | Professores poderão aderir voluntariamente, mediante critérios de seleção a serem validados. |
| Dependência | A qualidade e a atualização do conteúdo dependem da curadoria dos materiais e das explicações. |
| Dependência | O chatbot depende de uma base de conhecimento e/ou serviço de IA, cuja solução técnica não está definida nesta fase. |
| Restrição | A atividade atual é de especificação conceitual, sem implementação de código. |
| Restrição | Os requisitos devem ser realistas, factíveis e validados com os stakeholders. |

# **10\. Indicadores de sucesso propostos**

Os indicadores abaixo são sugestões para validação; metas numéricas não foram definidas no material-base.

* Percentual de estudantes que concluem simulados.  
* Frequência de uso das questões comentadas e do chatbot.  
* Tempo de resposta e taxa de resolução percebida das dúvidas pelo chatbot.  
* Quantidade de solicitações encaminhadas a professores e tempo até o primeiro atendimento.  
* Satisfação dos estudantes com os recursos de estudo e com o apoio docente.  
* Evolução do desempenho em simulados ao longo do período de preparação.

# **11\. Pontos que precisam ser validados na elicitação**

* Quais cursos, áreas e períodos acadêmicos serão atendidos inicialmente?  
* Quais filtros e formatos de organização das questões são mais úteis?  
* Como o estudante prefere receber explicações e acompanhar sua evolução?  
* Quais limites e responsabilidades o chatbot deve ter?  
* Em quais situações a solicitação deve ser encaminhada a um professor?  
* Quais critérios serão usados para selecionar professores voluntários?  
* Como serão definidos disponibilidade, horários, quantidade de alunos por professor e canais de atendimento?  
* Quais dados de desempenho poderão ser visualizados por professores e coordenações?

# **12\. Referências e base documental**

Documento elaborado com base no arquivo “Projeto de Extensão – ENADE: Engenharia de Requisitos Aplicada ao Contexto Educacional” fornecido para a atividade e nas issues da Sprint 1 (Milestone M1) apresentadas na imagem enviada. O escopo-base, o público beneficiado e a natureza conceitual do projeto foram preservados. As funcionalidades de IA e acompanhamento docente são propostas adicionais do grupo e deverão ser validadas.
