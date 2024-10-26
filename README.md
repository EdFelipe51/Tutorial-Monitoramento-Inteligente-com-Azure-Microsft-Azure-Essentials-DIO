# Tutorial-Monitoramento-Inteligente-com-Azure-Microsft-Azure-Essentials-DIO

1 - Assistente do Azure
    Seu guia personalizado e gratuito de melhores práticas do Azure. O Assistente do Azure oferece recomendações               acionáveis para ajudar você a otimizar seus recursos do Azure quanto à confiabilidade, segurança, excelência               operacional, desempenho e custo.

2 - Otimize suas implantações com recomendações personalizadas do Azure
    O consultor fornece práticas recomendadas relevantes para ajudá-lo a melhorar a confiabilidade, segurança, e               desempenho, alcançar excelência operacional, e reduzir custos. Configure o consultor para segmentar assinaturas            específicas e grupos de recursos, para se concentrar em otimizações críticas. Acesse o Assistente por meio do portal       do Azure, do Interface de Linha de Comando (CLI) do Azure, ou a API do Assistente. Ou configure alertas para ser           notificado automaticamente sobre novas recomendações.

3 - Otimize suas implantações com recomendações personalizadas do Azure
    O consultor fornece práticas recomendadas relevantes para ajudá-lo a melhorar a confiabilidade, segurança, e               desempenho, alcançar excelência operacional, e reduzir custos. Configure o consultor para segmentar assinaturas            específicas e grupos de recursos, para se concentrar em otimizações críticas. Acesse o Assistente por meio do portal       do Azure, do Interface de Linha de Comando (CLI) do Azure, ou a API do Assistente. Ou configure alertas para ser           notificado automaticamente sobre novas recomendações.

4 - Avalie se suas cargas de trabalho seguem bem as melhores práticas
    Veja se suas cargas de trabalho estão seguindo as melhores práticas do Azure, avalie quanto você ganha corrigindo          problemas e priorize as recomendações com maior impacto que você pode seguir para otimizar suas implantações com a         pontuação do Assistente do Azure. A pontuação do Assistente permite que você aproveite ao máximo seu investimento no       Azure usando um painel centralizado para monitorar, trabalhar e acompanhar o progresso para otimizar o custo, a            segurança, a confiabilidade, a excelência operacional e o desempenho dos recursos do Azure.

5 - O Assistente do Azure é gratuito
    O Assistente do Azure está disponível sem custo adicional. No entanto, observe que algumas recomendações podem             incorrer em custos de atualização. Por exemplo, habilitar o backup da máquina virtual pode incorrer em encargos para       os backups. O Assistente tem como objetivo ajudar a encontrar as eficiências de custo da nuvem enquanto segue as           melhores práticas do Azure.

    O painel do Assistente exibe recomendações personalizadas para todas as assinaturas. As recomendações são divididas em     cinco categorias:

        A - Confiabilidade: para garantir e melhorar a continuidade de seus aplicativos comercialmente críticos. Para                  obter mais informações, confira as Recomendações de confiabilidade do Assistente.

        B - Segurança: para detectar ameaças e vulnerabilidades que podem levar a possíveis violações de segurança. Para               obter mais informações, confira as Recomendações de segurança do Assistente.

        C - Desempenho: para melhorar a velocidade dos aplicativos. Para obter mais informações, confira as Recomendações              de desempenho do Assistente.

        D - Custo: para otimizar e reduzir o gasto geral do Azure. Para obter mais informações, confira as Recomendações               de custo do Assistente.

        E - Excelência operacional: para ajudar você a obter eficiência de processos e fluxos de trabalho, capacidade de               gerenciamento de recursos e melhores práticas de implantação. Para obter mais informações, confira as                      Recomendações de excelência operacional do Assistente.
  
6 - As ferramentas de monitoramento do Azure permitem acompanhar o desempenho, a integridade e a operação de recursos,         aplicativos e agentes de máquinas virtuais do Azure. Algumas das ferramentas de monitoramento do Azure são: 

        Azure Monitor: Coleta métricas, logs e dados de desempenho e os armazena em um banco de dados de séries temporais.                        O Azure Monitor pode monitorar recursos no Azure, em outras nuvens ou localmente. 

        Azure Monitor Metrics: Uma ferramenta de monitoramento do Azure. 

        Azure Monitor Logs: Uma ferramenta de monitoramento do Azure. 
        
        Azure Sentinel: Fornece análise de segurança inteligente e inteligência contra ameaças. 

        Applications Manager: Uma ferramenta de monitoramento do Azure que ajuda a monitorar o desempenho de serviço do                                  ambiente em nuvem. 

        PRTG: Monitora o status das máquinas virtuais Azure, exibindo o uso de CPU, assim como os créditos de CPU usados e               restantes. 
        
Para obter dados do Azure Monitor em outras ferramentas, é possível usar a API REST para métricas ou a API REST ou as bibliotecas de cliente associadas para logs. 

7 - Azure Health

    Introdução
    Abrir Resource Health para um recurso:
    Entre no portal do Azure.
    Procure o recurso.
    No menu de recursos no painel esquerdo, selecione Resource Health.
    Na grade de histórico de integridade, você pode baixar um PDF ou clicar no botão RCA "Compartilhar/Gerenciar".

    O Azure Resource Health ajuda você a diagnosticar e receber suporte para os problemas de serviço que afetam os seus        recursos do Azure. Ele gera relatórios sobre a integridade atual e passada dos seus recursos.

    O Status do Azure gera relatórios sobre problemas de serviço que afetam um amplo conjunto de clientes do Azure. O          Resource Health oferece um painel personalizado da integridade dos seus recursos. Ele mostra todas as vezes que os         seus recursos ficaram indisponíveis devido a problemas de serviço do Azure. Com esses dados, é simples identificar se      um SLA foi violado.

    7.1 - Definição de recurso e avaliação de integridade:

          O Resource Health se baseia em sinais de diferentes serviços do Azure para avaliar se um recurso está íntegro.             Se um recurso não estiver íntegro, o Resource Health analisará informações adicionais para determinar a origem             do problema. Ele também informa as ações que a Microsoft está realizando para corrigir o problema e identifica o           que você pode fazer para resolvê-lo.

          Para mais informações sobre como a integridade é avaliada, confira a lista de tipos de recursos e verificações             de integridade do Azure Resource Health.

    7.2 - Status da integridade Azure Health
          
          A integridade de um recurso é exibida como um dos estados a seguir:

              7.2.1 - Disponível:
              
                      Disponível significa que não há eventos detectados que afetem a integridade do recurso. Quando o                           recurso se recuperou do tempo de inatividade não planejado durante as últimas 24 horas, você verá                          uma notificação “Recentemente resolvidos”.
 
              7.2.2 - Indisponível:
              
                      Indisponível significa que o serviço detectou uma plataforma em andamento ou um evento não                                 relacionado à plataforma que afeta a integridade do recurso.


             7.2.3 - Eventos de plataforma: 

                     Os eventos da plataforma são disparados por vários componentes da infraestrutura do Azure. Eles                            incluem ações agendadas (por exemplo, manutenção planejada) e incidentes inesperados (por exemplo,                         uma reinicialização não planejada do host ou um hardware de host degradado cuja falha está prevista                        para depois de uma janela de tempo especificada).

                     O Resource Health apresenta detalhes adicionais sobre o evento e o processo de recuperação. Ele                            também permite que você entre em contato com o Suporte da Microsoft mesmo que não tenha um contrato                        de suporte ativo.

            7.2.4 - Eventos de não plataforma:

                    Os eventos não relacionados à plataforma são acionados por ações do usuário. Alguns exemplos são parar                     uma máquina virtual ou alcançar o número máximo de conexões do Cache do Azure para Redis.
                    Status *Indisponível* de uma máquina virtual devido a um evento não relacionado à plataforma

            7.2.5 - Desconhecido:
            
                    Desconhecido significa que o Resource Health não recebe informações sobre o recurso há mais de dez                         minutos. Isso geralmente ocorre quando as máquinas virtuais foram desalocadas. Embora esse status não                      seja uma indicação definitiva do estado do recurso, ele pode ser um ponto de dados importante para a                       solução de problemas.

                    Se o recurso estiver em execução conforme o esperado, o status do recurso mudará para Disponível após                      alguns minutos.

                    Se você tiver problemas com o recurso, o status da integridade Desconhecido poderá significar que um                       evento da plataforma está afetando o recurso.

            7.2.6 - Degradado:

                    Degradado significa que o seu recurso detectou uma perda de desempenho, embora ele ainda esteja                            disponível para uso.

                    Os diferentes recursos têm seus próprios critérios para informar que estão degradados.

                    Status Degradado de uma máquina virtual

                    Para Conjuntos de Dimensionamento de Máquinas Virtuais, visite a página O estado de integridade do                         recurso é "Degradado" no Conjunto de Dimensionamento de Máquinas Virtuais do Azure para obter mais                         informações.

            7.2.7 - Integridade sem suporte:
                    
                    A mensagem Sem suporte para integridade ou RP não tem informações sobre o recurso ou você não tem                          acesso de leitura/gravação para esse recurso significa que seu recurso não tem suporte para as                             métricas de integridade.

                    Para saber quais recursos dão suporte a métricas de integridade, consulte a página Tipos de recursos                       com suporte.

            7.2.8 - Eventos de integridade de recursos enviados para o log de atividades
                    
                    Um evento de integridade do recurso é registrado no log de atividades quando:

                    Uma anotação, por exemplo, "ResourceDegraded" ou "AccountClientThrottling", é enviada para um recurso.
                    Um recurso transitório para ou de Não Íntegro.
                    Um recurso estava Não íntegro por mais de 15 minutos.
                   
                    As seguintes transições de integridade de recursos não são registradas no log de atividades:

                    Uma transição para o estado Desconhecido.
                    
                    Uma transição do estado Desconhecido se:
                            Esta for a primeira transição.
                            Se o estado anterior ao Desconhecido for o mesmo que o novo estado após a transição. (Por                                  exemplo, se o recurso passou de Íntegro para Desconhecido e depois voltou para Íntegro).
                            Para recursos de computação: VMs que fazem a transição de Íntegro para Não íntegro e depois                                voltam para Íntegro, quando o tempo Não íntegro for menor que 35 segundos.

            7.2.9 - Informações do histórico:

                    Você pode acessar até 30 dias de histórico na seção Histórico de integridade do Resource Health no                         portal do Azure.

            7.3.1 - Informações de causa raiz
                    Se o Azure tiver mais informações sobre a causa raiz de uma indisponibilidade iniciada pela                                plataforma, essas informações poderão ser postadas na integridade de recursos até 72 horas após a                          indisponibilidade inicial. Essas informações estão disponíveis somente para máquinas virtuais no                           momento.

                    
            
