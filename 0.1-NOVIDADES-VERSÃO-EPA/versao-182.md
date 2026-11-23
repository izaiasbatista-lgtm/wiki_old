---
title: "Versão 182"
id: 15819
slug: "versao-182"
url: "https://wiki.simeon.com.br/versao-182/"
data: "2024-06-05T11:07:46"
modificado: "2024-09-02T11:45:22"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Versão 182
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Acompanhe os vídeos apresentando as atualizações da Versão 182.** 

**Parte 1**

[https://wiki.simeon.com.br/wp-content/uploads/2024/06/1-video-182.mp4](https://wiki.simeon.com.br/wp-content/uploads/2024/06/1-video-182.mp4)

**Parte 2**

[https://wiki.simeon.com.br/wp-content/uploads/2024/06/2-video-182.mp4](https://wiki.simeon.com.br/wp-content/uploads/2024/06/2-video-182.mp4)

**Release 182.1**

-   **Pessoas- Gestão de Treinamento** 

 **1-** A partir desta versão, introduzimos uma nova funcionalidade para aprimorar a gestão de presenças nos treinamentos. Agora, os participantes poderão assinar a lista de presença utilizando seu login e senha.

-   **Políticas da Qualidade- Documentos**

 **1-** A partir desta versão, introduzimos a possibilidade de definir uma máscara de versão dos documentos diretamente na parametrização geral do sistema. Isso garante que todas as versões criadas sigam o mesmo formato predefinido, promovendo uniformidade:

-   **Máscara de Versão Personalizável:** Agora, é possível definir uma máscara de versão de documentos nas configurações gerais do sistema.
-   **Formato Padronizado:** Todas as versões criadas seguirão automaticamente o formato especificado, assegurando consistência.
-   **Utilização do Padrão “9”:** A máscara deve ser construída utilizando o número “9”, que serve como padrão para os clientes. Isso será destacado na observação do parâmetro para auxiliar os usuários que possam não estar familiarizados com essa convenção.  
    Se a Máscara for definida como 99: versões serão 00, 01, 02, 03…  
    Se a Máscara for definida como 999: versões serão 000, 001, 002, 003…  
    Se a Máscara for definida como 9.9: versões serão 0.0, 0.1, 0.2, 0.3…
    

 **2-** A partir desta versão, introduzimos uma nova funcionalidade na tela de “Alterar Responsável de Documentos”. Agora, os usuários podem selecionar documentos específicos para a substituição do responsável, proporcionando maior controle e precisão no processo.

-   **Seleção Específica de Documentos:** Implementamos uma opção que permite ao usuário selecionar individualmente quais documentos terão o responsável alterado.
-   **Controle e Precisão:** Com essa nova funcionalidade, é possível evitar substituições massivas desnecessárias, garantindo que apenas os documentos desejados tenham seus responsáveis alterados.

 **3-** Agora, é possível filtrar a categoria pela sigla, além do código ou nome da categoria. Essa atualização facilita a busca de documentos específicos por tipo e setor de um hospital, por exemplo.

 **4-** Nesta versão, implementamos uma integração automática entre a criação de novas versões de documentos e o módulo de treinamentos. Agora, ao criar uma nova versão de um documento com a permissão “requerir treinamento” selecionada, o sistema irá proceder com a criação do treinamento correspondente no módulo de treinamentos. **Obs.:** **Essa funcionalidade está disponível apenas para quem possui o modulo de treinamentos.**

-   **Criação Automática de Treinamentos:** Ao criar uma nova versão de um documento com a permissão “requerir treinamento”, o sistema automaticamente criará um treinamento correspondente no módulo de treinamentos.
    
-   **Box “Documentos Aprovados Aguardando Treinamento”:** Na tela inicial, foi adicionada uma box na aba “Analista de Documentos” intitulada “Documentos Aprovados Aguardando Treinamento”. Esta box exibirá os documentos que possuem novas versões aguardando a criação de treinamentos.
    
-   **Visualização de Treinamentos Vinculados aos Documentos:** O analista de documentos poderá visualizar na listagem de treinamentos os treinamentos vinculados aos documentos da Unidade de Engenharia (UEN) dele.
    
-   **Criação de Treinamento ao Editar Documento:** Ao clicar em “editar” e em “criar treinamento” na box “Documentos Aprovados Aguardando Treinamento”, será criado um treinamento com a turma intitulada “TURMA 1”. O título do treinamento será composto pelo nome e versão do documento, incluindo a Unidade Gerencial, o responsável pelo treinamento (elaborador) e a justificativa (descrição do documento).
    
-   **Integração de Informações do Treinamento:** As informações do treinamento, após a sua realização, serão trazidas para a aba de treinamentos do documento, conforme a tela de participantes do treinamento e protótipo.
    

 **5-** Possibilidade de incluir um arquivo ao adicionar um acompanhamento no documento.

**7-** Nesta versão, adicionamos o campo “Classificação de Satisfação” nos relatórios de ouvidoria, permitindo mensurar o índice de satisfação com os retornos das ouvidorias.

**8-** Nesta versão, implementamos uma melhoria significativa na visualização de demandas no sistema. Agora, os usuários têm a capacidade de filtrar as demandas por Unidade de Gestão (UG), permitindo uma organização mais eficiente e um gerenciamento direcionado conforme a responsabilidade de cada UG.

-   **Projetos**

 **1-** Nesta versão, implementamos uma melhoria essencial no termo de encerramento de projetos. Agora, as datas de início e término reais do projeto foram incluídas, proporcionando uma visão abrangente do cronograma do projeto e permitindo uma análise detalhada de seu cumprimento em relação ao planejado.

-   **Portal- Armário Virtual**

**1-** Agora, é possível associar documentos a várias Unidades Gestoras (UGs) simultaneamente.

**2-** Inclusão da Opção “Pessoa Física/Jurídica” no Recurso “Ocultar Colunas” do Relatório de Documentos Vencidos.

-   **Portal- Fornecedores**

**1-** Melhoria na usabilidade do sistema de gerenciamento de fornecedores. Agora, ao editar um fornecedor, a página de edição será aberta em uma nova aba do navegador, preservando os filtros da listagem original.

-   **Portal- Pesquisas**

 **1-** Implementamos a funcionalidade de multiseleção nas colunas “categorias” e “classificação” nos relatórios de respostas de pesquisas, agora, os usuários podem selecionar várias categorias ou classificações simultaneamente, permitindo uma análise mais rica e complexa dos dados.

**Aproveitem as melhorias e nos dê o feedback.**

**Até mais, obrigada.** 

#### **![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)  
**

####  **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!**

---

Fonte: https://wiki.simeon.com.br/versao-182/
