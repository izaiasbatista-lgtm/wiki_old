---
title: "Versão 190"
id: 16664
slug: "versao-190"
url: "https://wiki.simeon.com.br/versao-190/"
data: "2025-03-21T09:18:47"
modificado: "2025-04-15T06:56:31"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Versão 190
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Confira o vídeo com as atualizações da nova versão e leia abaixo todas as novidades da versão 190.1**

[https://wiki.simeon.com.br/wp-content/uploads/2025/03/190-video.mp4](https://wiki.simeon.com.br/wp-content/uploads/2025/03/190-video.mp4)

**Release 190.1:**

**Portal – Cadastro de Pessoas**

A tela de manutenção de duplicados foi aprimorada para incluir as colunas Matrícula/Número do Cartão, Celular e Origem do Cliente, além das já existentes. Essa melhoria tem como objetivo facilitar a identificação de registros duplicados de forma mais eficiente, permitindo que os usuários visualizem as informações relevantes sem precisar acessar cada cadastro individualmente.

**Portal – Solicitações**

 A regra de exibição de solicitações foi ajustada para listar aquelas em que a Unidade Solicitante ou a Unidade Responsável estejam inativas. Foi adicionado o filtro ‘Solicitações com Unidades Inativas’, que, ao ser selecionado, desativa os filtros de Unidade existentes e exibe apenas as solicitações com unidades inativas. Ao clicar em “Pesquisar”, o sistema permite que o Analista de Solicitações ou o Super usuário altere essas unidades, facilitando a gestão das solicitações de forma mais eficiente.

**Políticas da Qualidade – Ocorrências**

A melhoria implementada permite que a tratativa registrada na ocorrência principal seja automaticamente replicada nos campos “Análise de Causa” e “Plano de Ação” das ocorrências vinculadas. Além disso, ao imprimir uma ocorrência vinculada, as tratativas da ocorrência principal serão incluídas nos relatórios, otimizando o processo e evitando ajustes manuais. Também foi ajustada a regra para que, quando uma ocorrência estiver vinculada a outra, os dados da ocorrência principal prevaleçam sobre os da ocorrência vinculada.

Foi implementado o filtro ‘Ocorrências com Unidades Inativas’ na listagem de ocorrências. Ao ser selecionado, ele bloqueia os filtros de Unidade e exibe apenas as ocorrências com unidades inativas. Após a pesquisa, o Analista de Ocorrências ou o Super Usuário poderá alterar essas unidades diretamente na tela. Essa funcionalidade facilita o rastreamento de ocorrências pendentes e estará visível apenas para usuários autorizados, com a opção desmarcada por padrão.

**Políticas da Qualidade – Ouvidoria**

Na Ouvidoria, foi realizada uma atualização para que o link externo oculte o nome do colaborador responsável pela inclusão ou alteração de um acompanhamento. O nome do colaborador não será exibido ao cliente no link enviado pela Ouvidoria, mas o sistema manterá o registro interno do responsável, acessível apenas para uso interno da empresa. A alteração afeta exclusivamente os acessos externos, garantindo que as visualizações internas do acompanhamento permaneçam inalteradas.

**Projetos**

O aprimoramento realizado permite a geração de um relatório PDF personalizado para a exportação do custo previsto, incluindo a soma total dos valores de previsto, realizado, saldo e % realizado, conforme exibido na tela do EPA. A exportação foi validada para assegurar que os dados correspondam às informações apresentadas na tela. A opção de exportação para Excel permanece inalterada. Apenas usuários com permissões específicas, como Analista de Projetos, Super Usuário, Gestor do Projeto, Gestor EPA e Usuário de Inclusão do Projeto, terão acesso ao formulário de Análise de Custos.

**Portal – Solicitações**

Agora será possível exibir, na tela de informações básicas de solicitações vinculadas ou dependentes, o código, o link e a descrição da solicitação mãe ou de origem. Ao acessar uma solicitação filha ou dependente, o usuário poderá visualizar e acessar diretamente a solicitação mãe por meio do código com link. A descrição completa da solicitação mãe será apresentada em um modal, acionado ao clicar no ícone correspondente. Caso a solicitação esteja vinculada a mais de uma mãe, as informações serão exibidas em formato de lista.

**Políticas da Qualidade – Documentos**

Foi criada a variável {{data\_criacao\_versao}} para uso em documentos, permitindo a inserção automática da informação referente à ‘Data de Criação da Versão’. Essa melhoria proporciona mais agilidade e padronização na geração de documentos.

Foram criadas as variáveis {{nome\_cargo\_revisor}} e {{nome\_cargo\_aprovador}} para uso em documentos, permitindo a inserção automática do nome e do cargo dos Revisores e Aprovadores. Essa melhoria facilita a padronização e garante maior precisão na geração de documentos.

**Portal – Pesquisas e Questionários**

A trilha de auditoria foi aprimorada para registrar de forma mais completa as edições e exclusões de respostas de pesquisas. Agora, cada evento inclui a descrição da pergunta, o nome da pesquisa e seu respectivo código, garantindo maior clareza e rastreabilidade das informações. Essa melhoria reforça a transparência e facilita a identificação precisa das alterações realizadas pelos usuários.

**Planejamento – Planejamento Indicadores**

Foi implementado um novo campo para definir a data limite de inserção e edição da análise de desempenho dos indicadores. A partir dessa data, o sistema bloqueia automaticamente os campos de inclusão e edição da análise crítica na etapa configurada, garantindo maior controle sobre os prazos. Além disso, o responsável será notificado com 5 dias de antecedência, por meio de um alerta na tela principal, contribuindo para uma gestão mais eficiente e evitando atrasos no processo de análise.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/02/img_67ba7b04f0f89.png)

---

Fonte: https://wiki.simeon.com.br/versao-190/
