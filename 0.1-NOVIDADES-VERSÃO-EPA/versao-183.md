---
title: "Versão 183"
id: 15893
slug: "versao-183"
url: "https://wiki.simeon.com.br/versao-183/"
data: "2024-07-15T09:43:17"
modificado: "2024-09-30T09:21:36"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Versão 183
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Acompanhe a release da versão 183.1**

**Release 183.1**

-   **Tela Principal**

**1–** As caixas da tela inicial do EPA agora exibem o nome do responsável pela atividade ao detalhar. Essa funcionalidade foi implementada para que gestores e analistas possam identificar rapidamente qual colaborador é responsável por cada atividade, sem a necessidade de abrir a atividade individualmente.

**2-**No box “Aguardando Assinatura”, ao clicar em **Ações → Detalhes**, agora será exibida uma nova funcionalidade que apresenta informações detalhadas da assinatura, especificamente o signatário e o status da assinatura.

-   **Planejamento- Indicadores**

**1-** Na tela de alimentação de indicadores que torna todos os critérios visíveis desde o início. Esta melhoria visa garantir que os usuários tenham acesso imediato a todos os critérios necessários ao inserir dados. Ao tornar todos os critérios visíveis, evitamos que os usuários cliquem no botão “Salvar” sem preencher todas as informações necessárias. Isso ajuda a garantir que os dados sejam inseridos de forma completa e precisa, promovendo a integridade das informações nos indicadores.

-   **Políticas da Qualidade- Riscos**

**1-** No registro de ocorrência, o sistema puxa automaticamente o risco específico da Unidade Gerencial cadastrado no módulo de riscos, incluindo sua classificação. Os usuários podem alterar o tipo de impacto, se necessário. Para riscos com impacto econômico-financeiro, há opções de grau de impacto com faixas de valores de perda, e é obrigatório preencher os campos de perda real e perda estimada. Para outros riscos, o campo “Grau do Impacto” está disponível para seleção, replicando o cadastro do módulo de riscos. O cálculo do risco proteico é feito com base nos pesos (1 a 5) do grau do impacto. Além disso, na lista de ocorrências registradas, foram incluídos os campos de tipo de risco, valor de perda operacional e unidade gerencial relacionada.

**2-** Implementamos uma nova fase na ouvidoria para validação do parecer, permitindo que, em caso de resposta insatisfatória, o parecer seja retornado ao responsável. Essa funcionalidade possibilita a revisão e correção do parecer pelo responsável, devolvendo-lhe a responsabilidade de execução.

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

Fonte: https://wiki.simeon.com.br/versao-183/
