# AtividadePDia20

1 - Proposta de Problema:

A saúde é um aspecto crucial para a sociedade, e a gestão eficiente de consultas médicas é essencial para garantir que os pacientes recebam o cuidado adequado no momento certo. O objetivo deste projeto é desenvolver um sistema de gerenciamento de consultas médicas que facilite o agendamento, acompanhamento e gestão de consultas em uma clínica médica. O sistema deve ser interativo, intuitivo e capaz de lidar com diversas funcionalidades necessárias para uma clínica. 

2 - Requisitos Funcionais:

* Cadastro de Pacientes

O sistema deve permitir o cadastro de novos pacientes.
O sistema deve solicitar e armazenar as seguintes informações dos pacientes:
Nome
Data de nascimento
CPF
Endereço
Telefone

* Cadastro de Médicos

O sistema deve permitir o cadastro de novos médicos.
O sistema deve solicitar e armazenar as seguintes informações dos médicos:
Nome
Especialidade
CRM

* Agendamento de Consultas

O sistema deve permitir o agendamento de consultas médicas.
O sistema deve permitir a seleção de um paciente e um médico.
O sistema deve permitir a definição da data e hora da consulta.
O sistema deve verificar e assegurar a disponibilidade do médico no horário selecionado.
O sistema deve armazenar as informações da consulta, incluindo:
Paciente
Médico
Data e hora
Status (Agendada, Cancelada, Concluída)


* O sistema deve permitir que pacientes e médicos visualizem as consultas agendadas.

O sistema deve exibir as consultas em um formato de lista ou calendário.
O sistema deve fornecer detalhes das consultas, como:
Nome do paciente
Nome do médico
Data e hora
Status

* Edição de Consultas

O sistema deve permitir a edição das informações de uma consulta agendada.
O sistema deve permitir a alteração da data e hora da consulta.
O sistema deve permitir a alteração do médico responsável pela consulta.

* Cancelamento de Consultas

O sistema deve permitir que consultas agendadas sejam canceladas.
O sistema deve atualizar o status da consulta para "Cancelada".
O sistema deve manter um histórico de consultas canceladas.

* Notificações e Lembretes

O sistema deve enviar notificações automáticas para pacientes e médicos sobre consultas agendadas.
O sistema deve enviar lembretes por email ou SMS.
O sistema deve permitir a configuração do tempo de antecedência para os lembretes (por exemplo, 1 dia antes, 1 hora antes).

*Relatórios e Estatísticas

O sistema deve gerar relatórios sobre o número de consultas por:
Especialidade
Médico
Período de tempo (diário, semanal, mensal, anual)
O sistema deve fornecer estatísticas de uso, como horários de pico e taxa de cancelamento de consultas.

*Segurança e Confidencialidade

O sistema deve garantir que todos os dados dos pacientes e médicos sejam armazenados de forma segura.
O sistema deve implementar autenticação de usuário para acesso às informações sensíveis.
O sistema deve garantir a confidencialidade dos dados dos pacientes.

*Backup e Recuperação de Dados

O sistema deve realizar backups regulares dos dados armazenados.
O sistema deve fornecer mecanismos para recuperação de dados em caso de falha ou perda de dados.

*Interface de Usuário

O sistema deve ter uma interface de usuário intuitiva e fácil de usar.
O sistema deve apresentar menus e opções de navegação claros.
O sistema deve fornecer feedback adequado ao usuário sobre as ações realizadas (como confirmações de agendamento, edição, e cancelamento de consultas).

3 - Crítica a IA


A IA se mostrou eficaz na identificação dos requisitos funcionais básicos para um Sistema de Gerenciamento de Consultas Médicas, abordando aspectos essenciais como cadastro de pacientes e médicos, agendamento e visualização de consultas, notificações, e segurança de dados. No entanto, há espaço para melhorias, especialmente em termos de especificidade, consideração de funcionalidades avançadas, e detalhes sobre a implementação prática dos requisitos, além disso, a IA se confunde entre os requsitos de usuário, funcionais e não funcionais.

4 - Diagrama de classe

Classe Paciente:

Propriedades: Nome, DataNascimento, CPF, Endereco, Telefone.
Métodos: AgendarConsulta(), CancelarConsulta(), VisualizarHistorico().

Classe Medico:

Propriedades: Nome, Especialidade, CRM, HorariosDisponiveis.
Métodos: Cadastrar(), Atualizar(), Remover(), VisualizarConsultas().

Classe Consulta:

Propriedades: Id, Paciente, Medico, DataHora, Status.
Métodos: Marcar(), Cancelar(), Confirmar().

Classe Notificacao:

Propriedades: Id, Destinatario, Mensagem, DataEnvio.
Métodos: Enviar(), Programar().
Classe Relatorio:

Propriedades: Tipo, Periodo, Dados.
Métodos: Gerar(), Exportar().

5 - Estratégia de Programação com IA

Revisão de Código com IA

Essas foram as informações fornecidas pelo ChatGPT:

A IA pode ajudar a identificar bugs, sugerir melhorias de performance, ou apontar violações de boas práticas de programação.
Como Implementar:

Escrever Código: O estudante desenvolve uma parte ou a totalidade do sistema conforme os requisitos funcionais.
Submeter à IA: O código é submetido a uma ferramenta de revisão de código baseada em IA (como GitHub Copilot, DeepCode, ou Codiga).
Analisar Feedback: O estudante analisa o feedback fornecido pela IA, que pode incluir:
Sugestões de refatoração.
Detecção de possíveis bugs.
Recomendações de melhorias de performance.
Avisos sobre padrões de design inadequados.
Aplicar Melhorias: O estudante implementa as sugestões relevantes e reavalia o código.
Vantagens:

Melhoria da qualidade do código.
Identificação de problemas que podem passar despercebidos.
Aprendizado contínuo de boas práticas de programação.
* Estudo com Auxílio da IA
Descrição:

O estudante utiliza a IA para aprender sobre temas específicos relacionados ao projeto, como gerenciamento de estado, design de interfaces, ou padrões de design. A IA pode fornecer explicações, exemplos de código, e exercícios práticos.
Como Implementar:

Escolher Tema: O estudante escolhe um tema ou conceito que deseja aprofundar.
Consultar IA: Utiliza uma IA (como ChatGPT, OpenAI Codex) para obter explicações detalhadas e exemplos práticos.
Solicitar Exercícios: O estudante pede à IA para criar exercícios práticos sobre o tema escolhido.
Resolver Exercícios: O estudante resolve os exercícios fornecidos pela IA e pode pedir correções e feedback.
Revisar Conceitos: O estudante pode iterar o processo para revisar e solidificar o entendimento dos conceitos.
Vantagens:

Aprendizado direcionado e personalizado.
Prática com feedback imediato.
Exploração de tópicos avançados ou pouco compreendidos.
* Programação por Pares com IA
Descrição:

O estudante utiliza a IA como um parceiro de programação. A IA pode sugerir partes do código, ajudar na resolução de problemas, ou colaborar no design do sistema.
Como Implementar:

Definir Tarefa: O estudante define uma tarefa específica ou uma funcionalidade a ser implementada.
Interagir com IA: Durante a codificação, o estudante alterna entre escrever código e pedir sugestões à IA. Isso pode incluir:
Geração de trechos de código.
Sugestões de algoritmos.
Resolução de erros.
Planejamento de arquitetura.
Revisão Conjunta: O estudante revisa as sugestões da IA e faz ajustes conforme necessário.
Refinamento: O estudante e a IA iteram sobre o código até que a funcionalidade esteja completa e correta.
Vantagens:

Aumento da produtividade.
Redução de bloqueios criativos ou técnicos.
Estímulo ao pensamento crítico e à análise de diferentes abordagens.


