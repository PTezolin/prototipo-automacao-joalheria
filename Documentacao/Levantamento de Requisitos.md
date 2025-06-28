# Levantamento de Requisitos

O levantamento de requisitos foi conduzido com base na observação das rotinas da joalheria e em conversas diretas com os funcionários envolvidos nas etapas de registro e acompanhamento de consertos. A partir dessa análise, foi possível identificar um conjunto de necessidades fundamentais que norteiam o desenvolvimento do sistema proposto, visando substituir os processos manuais por uma solução digital mais eficiente, segura e adaptada à realidade da empresa.
<br><br>


## Necessidades do Sistema

As necessidades do sistema correspondem a requisitos iniciais identificados durante a análise do contexto da joalheria, abrangendo tanto aspectos funcionais quanto não funcionais de forma ampla. Esses elementos serviram como base para o delineamento das funcionalidades, restrições e expectativas relacionadas ao desempenho e à usabilidade da solução, orientando as etapas subsequentes do desenvolvimento.

|        | Necessidades do Sistema                                                   |
|--------|---------------------------------------------------------------------------|
| NE01   | Substituir registros manuais por sistema digital.                        |
| NE02   | Executar o sistema em ambiente online.                                   |
| NE03   | Disponibilizar o sistema para uso em dispositivos móveis no futuro.      |
| NE04   | Desenvolver uma interface otimizada, intuitiva e funcional.              |
| NE05   | Permitir operações de consulta, edição e exclusão.                       |
| NE06   | Vincular cada reparo a um número de ordem único.                         |
| NE07   | Permitir que um cliente tenha múltiplos reparos simultâneos.             |
| NE08   | Classificar reparos por categoria e subcategoria.                        |
| NE09   | Implementar controle de status dos reparos em tempo real.                |
| NE10   | Implementar busca instantânea e eficiente.                               |
| NE11   | Ativar alertas automáticos de prazos e pendências.                       |
| NE12   | Definir um prazo mínimo operacional para os consertos.                   |
| NE13   | Permitir o anexo de fotos aos registros de consertos.                    |
| NE14   | Gerar comprovantes físicos e digitais com envio por WhatsApp.            |
| NE15   | Armazenar o histórico completo de reparos.                               |
| NE16   | Integrar um canal de comunicação interna entre setores.                  |
| NE17   | Estabelecer padrões mínimos de desempenho.                               |
| NE18   | Gerar relatórios automáticos e analíticos.                               |

<br>

## Requisitos Funcionais

Os requisitos funcionais definem as funcionalidades que o sistema deve ser capaz de executar para atender às necessidades operacionais da joalheria. Eles representam as ações essenciais relacionadas ao cadastro, controle, comunicação, processamento e apresentação das informações no ambiente digital.

|        | Requisitos Funcionais                                                     |
|--------|---------------------------------------------------------------------------|
| RF01   | Permitir o cadastro de novos reparos.                                     |
| RF02   | Definir campos obrigatórios no cadastro do reparo.                        |
| RF03   | Gerar número de ordem único para cada reparo.                             |
| RF04   | Classificar reparos por tipo (joia ou relógio) e subcategoria.            |
| RF05   | Permitir o anexo de fotos nos registros dos reparos.                      |
| RF06   | Informar dados detalhados da peça no cadastro.                            |
| RF07   | Permitir que um cliente tenha múltiplos reparos simultâneos.             |
| RF08   | Manter o histórico completo de reparos cadastrados.                       |
| RF09   | Implementar controle e visualização do status dos reparos.                |
| RF10   | Apresentar um painel de status geral dos serviços em andamento.          |
| RF11   | Implementar busca rápida com filtros e palavras-chave.                    |
| RF12   | Disponibilizar operações de consulta, edição e exclusão (CRUD).           |
| RF13   | Gerar e emitir comprovantes de entrada e retirada dos reparos.           |
| RF14   | Enviar notificações automáticas de prazos, pendências e atrasos.         |
| RF15   | Gerar relatórios gerenciais e analíticos sobre os serviços.              |
| RF16   | Executar o sistema em ambiente de forma online.                           |
| RF17   | Enviar mensagens via WhatsApp.                                            |
| RF18   | Permitir a visualização da imagem que foi anexada ao reparo.             |
| RF19   | Validar o número de telefone.                                             |
| RF20   | Validar se o usuário informou o valor corretamente.                       |

<br>

## Regras de Negócio

As regras de negócio representam diretrizes específicas definidas com base nas práticas da joalheria e nas necessidades operacionais identificadas. Diferentemente dos requisitos funcionais, essas regras delimitam comportamentos obrigatórios do sistema, assegurando conformidade com os procedimentos internos, a padronização do fluxo de trabalho e a integridade dos registros.

|        | Regras de Negócio                                                         |
|--------|---------------------------------------------------------------------------|
| RN01   | Reparo deve ter tipo e subcategoria definidos.                            |
| RN02   | Cada reparo recebe um número de ordem único.                              |
| RN03   | O sistema deve permitir buscar os dados do cliente.                       |
| RN04   | Alguns dados no cadastro são obrigatórios.                                |
| RN05   | Todo reparo deve estar vinculado a um cliente.                            |
| RN06   | O recebimento do item deve ser presencial.                                |
| RN07   | Prazo mínimo para conserto é de 7 dias úteis.                             |
| RN08   | Histórico inalterável e disponível apenas para visualização.             |
| RN09   | Emitir comprovantes de entrada e retirada é obrigatório.                  |
| RN10   | Exibir consertos com entrega nos próximos dias.                           |

<br>

## Requisitos Não Funcionais

Os requisitos não funcionais especificam atributos de qualidade e características técnicas que o sistema deve apresentar para garantir desempenho, usabilidade, escalabilidade e compatibilidade. Embora não estejam diretamente relacionados às funcionalidades, esses requisitos exercem papel fundamental na experiência do usuário e na eficiência da solução proposta.

|        | Requisitos Não Funcionais                                                 |
|--------|---------------------------------------------------------------------------|
| RNF01  | O sistema deve possuir uma interface simples, com no máximo 12 campos no formulário. |
| RNF02  | O sistema deve ser executado de forma on-line.                            |
| RNF03  | O sistema deve processar buscas em pouco tempo.                           |
| RNF04  | O sistema deve armazenar registros de reparos, incluindo fotos.           |
| RNF05  | O sistema deve ser acessível.                                             |
| RNF06  | O sistema deve suportar muitos reparos por ano sem perda de desempenho.  |
| RNF07  | O sistema deve ser compatível com navegadores.                            |

