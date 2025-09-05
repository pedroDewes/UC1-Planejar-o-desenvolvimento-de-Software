Projeto:
TaskStorm
Responsáveis: Pedro Lima e Vinicius Cardoso

1.Introdução:
Este documento apresenta os requisitos de usuário do sistema TaskStorm e está organizado daseguinte forma: 
a Seção 2 contém uma descrição do propósito do sistema; e a Seção 3 apresenta as listas de requisitos de usuário levantados junto ao cliente.

2.Descrição do Propósito do sistema:
O projeto TaskStorm visa ser uma ferramenta focada na produtividade, tendo seu foco principal para equipes poderem gerenciar tarefas, metas e projetos. 
Através de uma abordagem como Trello, mas com um toque de originalidade da empresa. A plataforma guiará os usuários nos seus planejamentos de tarefas.

3.Requisitos de usuário:
Tomando por base o contexto do sistema, foram identificados os seguintes requisitos de usuário:

Requisitos e Regras de Negócio

Indentificador  Descrição                                                                       Prioridade
RF1            Cadastro e perfil do usuário                                                     Alta
RF1-01         Permitir o cadastro de novos usuários com nome, idade, e-mail e senha.           Alta
RF1-02         Sistema que permite a atribuição de membros nas equipes.                         Alta
RF1-03         Exibir um DashBoard inicial mostrando ao usuário seus projetos, tarefas e metas. Alta
RF1-04         Permitir ao usuário vizualizar e modificar seus dados do perfil.                 Médio

RF2            Planejamento de projetos,tarefas e subtarefas.                                   Alta
RF2-01         Criar projetos, tarefas e subtarefas.                                            Alta
RF2-02         Notificar o usuário ao ultrapassar o prazo proposto.                             Média
RF2-03         Permitir ao usuário estipule um prazo para suas tarefas e projetos.              Baixa
RF2-04         Sistema de comentários que possibilita ao usuário comentar sobre equipes
               , projetos usuário.
RF2-05         Método de checklist para projetos já concluidos.                                 Média
RF2-06         Painel com gráficos de desempenho e um recurso de alerta de atrasos.             Alta

RF1           Regra da Usabilidade e Experiência do Usuário:
 
RF1-01        A interface do usuário deve ser moderna e ter modo escuro.                       Alta
RF1-02        A plataforma deve rodar em mobile, e ter integração com Slack e google calendar. Alta
RF1-03        A plataforma deve ser fácil de rodar de navegar, com fluxos claros e mínimos
               cliques para realizar as principais ações.

RNF2            Regra para Responsáveis por porjetos e tarefas                                              Alta
RNF2-01        Todo projeto criado pela equipe deve apresentar um owner.                        Alta
RNF2-02        Tarefas que não tem responsáveis devem ser invisíveis.                           Alta

RNF3           Sistema de incentivo ao usuário                                                  Alta
RNF3-01        Mascote virtual que incentive usuário com frases que parabenizam                 Média
               ao finalizar a tarefa.
RNF3-02        Sistema que ao concluir uma tarefa ou uma meta, o mascote dará ao                Baixa
               usuário um emblema.
RNF3-03        O usuário poderá por em seus perfil os emblemas colecionados                     Baixa

RNF4           Segurança                                                                        Alta  
RNF4-01        Implementar autenticação robusta para acesso ao aplicativo (e.g., senhas         Alta
               forte autenticação de dois fatores opcional).           
RNF4-02        Proteger contra acessos não autorizados e vazamento de dados.                    Alta
RNF4-03        Os dados do usuário, como suas informações de cadastro devem ser
               criptografados e armazenados de forma segura.
RNF4-04        Assegurar a conformidade com as leis de proteção de dados (e.g., LGPD no Brasil) Alta

RNF5           Compatibilidade
RNF5-01        
               
