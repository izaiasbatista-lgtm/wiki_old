---
title: "Versão 184"
id: 15945
slug: "versao-184"
url: "https://wiki.simeon.com.br/versao-184/"
data: "2024-08-07T10:59:17"
modificado: "2025-03-17T05:56:39"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Versão 184
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Confira os vídeos com as atualizações da nova versão e leia abaixo todas as novidades da versão 184.**

[https://wiki.simeon.com.br/wp-content/uploads/2024/08/parte-1.mp4](https://wiki.simeon.com.br/wp-content/uploads/2024/08/parte-1.mp4)

[https://wiki.simeon.com.br/wp-content/uploads/2024/08/parte-2.mp4](https://wiki.simeon.com.br/wp-content/uploads/2024/08/parte-2.mp4)

-   **Planejamento – Plano de Ação**

 **1–** Agora, o código do plano de ação será exibido na tela de edição, facilitando a identificação e a edição dos detalhes do plano de ação. Isso ajuda a encontrar e gerenciar rapidamente o plano de ação desejado.

 **2**–**** Na tela de “ação”, o sistema agora implementa a mesma regra da listagem de planos de ação: ao pesquisar e selecionar um usuário da lista completa, o sistema atribuirá automaticamente a UG padrão do usuário selecionado como responsável pela ação correspondente. Isso simplifica o processo de atribuição e garante que a responsabilidade seja corretamente associada à unidade gerencial apropriada.

-   **Projetos**

**1–** Implementamos um processo de confirmação antes de excluir um anexo no acompanhamento das tarefas de projetos. Com a nova funcionalidade, ao clicar na lixeira, uma janela de confirmação será exibida, garantindo que a exclusão só ocorra se o usuário confirmar a ação, aumentando a segurança e prevenindo a perda de dados importantes.

**2**–**** Adicionamos uma funcionalidade que permite aos usuários visualizarem a prioridade dos projetos na listagem, utilizando a opção “ocultar colunas”. Isso facilita a visualização e melhora o acompanhamento dos gestores, permitindo que informações cruciais sobre a prioridade dos projetos sejam acessadas de forma rápida e eficiente.

**3**–**** Foi melhorado o gráfico geral de comparação entre custos Planejados e Realizados. Agora, quando o valor Realizado ultrapassar o valor Planejado, o excesso será destacado em vermelho, permitindo uma identificação visual imediata das áreas onde os custos excederam o orçamento planejado.

**4**–**** Foi introduzida uma funcionalidade na Estrutura Analítica de Projetos (EAP) horizontal, permitindo que o usuário selecione se deseja visualizar as horas previstas a faturar. Caso afirmativo, o sistema exibirá o total de horas no título do projeto e o total de horas com a marcação “faturar = sim” para cada fase do projeto. Esta funcionalidade facilitará a apresentação de previsões de faturamento para clientes potenciais, contribuindo para a precisão na elaboração de contratos.

**5**–**** Melhoria na visualização dos valores: Realizado, Previsto e Criticidade nas telas de Edição de Projetos e Listagem de Projetos na aba de Gestão.

**6**–**** Foi adicionada a opção “tipo” no botão “ocultar colunas” na listagem de gestão dos projetos e incluída a informação da “categoria” na aba de gestão de custos dos projetos. Essas melhorias permitem uma visualização mais completa e personalizável das informações, melhorando a eficiência na gestão dos projetos.

-   **Políticas da Qualidade- Riscos**

**1**–**** Foi configurada a funcionalidade de datas automáticas para análise de riscos no sistema, a partir da criação de um campo na tela de parâmetros de risco para definir a frequência segundo a criticidade. A análise de riscos será realizada com base na severidade e probabilidade do risco residual, otimizando o processo de gestão de riscos. A periodicidade será definida conforme as políticas do cliente, garantindo uma gestão mais precisa e eficiente.   
**LEMBRETE: O cálculo automático da data da próxima análise, com base na data de análise anterior, depende do parâmetro “Permitir o usuário informar data de análise maior que a data atual?” da tela de parametrização do sistema.**

**2**–**** Adicionamos um campo de descrição nas severidades do risco nas parametrizações, semelhante ao campo já existente nas probabilidades. Isso permitirá que os usuários forneçam descrições detalhadas para cada nível de severidade do risco, facilitando a compreensão e a gestão dos riscos.

**3-** No registro de ocorrência, o sistema puxa automaticamente o risco específico da Unidade Gerencial cadastrado no módulo de riscos, incluindo sua classificação. Os usuários podem alterar o tipo de impacto, se necessário. Para riscos com impacto econômico-financeiro, há opções de grau de impacto com faixas de valores de perda, e é obrigatório preencher os campos de perda real e perda estimada. Para outros riscos, o campo “Grau do Impacto” está disponível para seleção, replicando o cadastro do módulo de riscos. O cálculo do risco proteico é feito com base nos pesos (1 a 5) do grau do impacto. Além disso, na lista de ocorrências registradas, foram incluídos os campos de tipo de risco, valor de perda operacional e unidade gerencial relacionada.

-   **Políticas da Qualidade- Ouvidoria**

**1**–**** Incluímos no link externo da ouvidoria a possibilidade de os beneficiários consultarem os acompanhamentos dos registros abertos. O campo “acompanhamento” estará disponível para visualização pelos beneficiários, caso esteja marcado como “mostrar no link externo de ouvidoria”. Isso permitirá que os beneficiários acompanhem facilmente o status dos seus registros.

**2-** Implementamos uma nova fase na ouvidoria para validação do parecer, permitindo que, em caso de resposta insatisfatória, o parecer seja retornado ao responsável. Essa funcionalidade possibilita a revisão e correção do parecer pelo responsável, devolvendo-lhe a responsabilidade de execução.

-   **Portal – Fornecedores**

**1**–**** Modificamos o módulo de fornecedores para que, ao gerar relatórios em Excel ou PDF, o processamento ocorra em segundo plano. O usuário será notificado quando o processamento estiver concluído, permitindo que ele continue utilizando o sistema enquanto o relatório é gerado. 

-   **Portal – NPS**

**1**–**** Para facilitar a gestão dos envios e retornos das pesquisas, incluímos uma nova funcionalidade no sistema de relatórios de NPS. Agora, você pode filtrar os relatórios pela “data de envio” das pesquisas. Essa opção permitirá uma análise mais precisa dos períodos em que as pesquisas foram enviadas e respondidas, ajudando a melhorar a gestão e a compreensão dos dados de satisfação dos clientes.

-   **Portal – Gol e Bola Fora**

**1**–**** Criamos um parâmetro no sistema que permite à empresa definir se e-mails serão enviados em caso de inclusão de “gol x bola fora”. Esse parâmetro é configurável, permitindo que a empresa ative ou desative o envio de e-mails conforme sua necessidade. Isso oferece maior flexibilidade e controle sobre as notificações enviadas aos usuários.

-   **Portal – Álbum de Fotos**

**1**–**** Para facilitar a visualização do tamanho máximo permitido para uploads no mural, inserimos um texto informativo que sinaliza qual será o tamanho permitido. Isso ajuda os usuários a entenderem rapidamente as limitações ao fazer upload de fotos e vídeos no mural.

-   **Portal – Usuários**

**1**–**** Ao desativar um usuário, o sistema agora adicionará “.inativo” ao login, por exemplo, “teste.inativo”. Isso facilitará a identificação dos usuários inativados e ajudará a manter a organização e o controle sobre as contas desativadas.

-   **Tela Principal**

**1-** As caixas da tela inicial do EPA agora exibem o nome do responsável pela atividade ao detalhar. Essa funcionalidade foi implementada para que gestores e analistas possam identificar rapidamente qual colaborador é responsável por cada atividade, sem a necessidade de abrir a atividade individualmente.

**2-**No box “Aguardando Assinatura”, ao clicar em **Ações → Detalhes**, agora será exibida uma nova funcionalidade que apresenta informações detalhadas da assinatura, especificamente o signatário e o status da assinatura.

-   **Planejamento- Indicadores**

**1-** Na tela de alimentação de indicadores que torna todos os critérios visíveis desde o início. Esta melhoria visa garantir que os usuários tenham acesso imediato a todos os critérios necessários ao inserir dados. Ao tornar todos os critérios visíveis, evitamos que os usuários cliquem no botão “Salvar” sem preencher todas as informações necessárias. Isso ajuda a garantir que os dados sejam inseridos de forma completa e precisa, promovendo a integridade das informações nos indicadores.

-   **Políticas da Qualidade- Ocorrências**

**1-** Adicionamos a opção de incluir anexos no campo de “informações levantadas durante a investigação de causa”, permitindo a inclusão de vários anexos de uma só vez.

**2-** Agora é possível vincular formulários customizáveis à ferramenta de ocorrências, associados aos títulos de ocorrência/risco. Os campos do formulário serão carregados conforme a seleção do título da ocorrência, permitindo atribuir formulários diferentes a títulos de ocorrência distintos ou o mesmo formulário a mais de um título.

**3-** Desenvolvemos uma funcionalidade no sistema que automatiza a abertura de ocorrências com base nas respostas das pesquisas realizadas. Esta funcionalidade inclui a habilitação de uma flag no cadastro da resposta da pesquisa, permitindo que o sistema identifique automaticamente quando uma ocorrência deve ser gerada. Além disso, o sistema permite a parametrização para definir a origem e o título das ocorrências geradas, e anota na ocorrência o número da pesquisa correspondente. Também registra na resposta da pesquisa o número da ocorrência gerada, garantindo o rastreamento completo do processo.

**4-** Implementamos uma restrição no sistema que impede a conclusão de uma ocorrência mãe se houver planos de ação em aberto em qualquer ocorrência vinculada. Adicionamos um aviso na interface que informa aos usuários sobre a existência de planos de ação pendentes nas ocorrências vinculadas. A conclusão da ocorrência mãe só será possível após a finalização de todos os respectivos planos de ação. 

**5-** Implementamos no sistema a ferramenta “Protocolo de Londres” para análise de causa, que inclui uma orientação detalhada sobre como utilizá-la. Adicionamos um parâmetro para que a organização possa definir se deseja utilizar essa ferramenta ou não.

**6-** Permitimos que usuários com acesso autorizado possam buscar, abrir e visualizar ocorrências na tela de gestão de ocorrências. Além disso, os usuários responsáveis pela execução de um plano de ação podem acessar as ocorrências tanto através da pendência na tela principal quanto na tela de gestão de ocorrências, mesmo após a conclusão do plano de ação ou da ocorrência. 

**7-** Implementamos uma funcionalidade na “Avaliação da Eficácia” que permite o vínculo de prints, imagens e hiperlinks como evidência da avaliação.

-   **Políticas da Qualidade- Documentos**

**1-** A inserção automática de variáveis como código, versão, data, autor e outras informações relevantes nos documentos. Isso assegura a consistência e precisão das informações, além de simplificar o gerenciamento de versões e reduzir a duplicidade de arquivos ao converter automaticamente documentos editáveis para PDF.

-   **Portal- Solicitações**

**1-** Implementamos melhorias significativas na mensagem de erro ao tentar excluir um signatário que recusou a assinatura de um documento. Além disso, atualizamos o comportamento da interface para anexos de solicitações recusadas. Essas mudanças visam proporcionar uma experiência mais clara e informativa para os usuários responsáveis pela configuração da assinatura virtual de solicitações.

**2-** Agora é possível visualizar a data e hora da conclusão de uma solicitação na tela principal, facilitando a análise do tempo de atendimento listado no quadro de solicitações.

**Aproveitem as melhorias e nos dê o feedback.**

**Até mais, obrigada.** 

#### **![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)  
**

####  **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!**

---

Fonte: https://wiki.simeon.com.br/versao-184/
