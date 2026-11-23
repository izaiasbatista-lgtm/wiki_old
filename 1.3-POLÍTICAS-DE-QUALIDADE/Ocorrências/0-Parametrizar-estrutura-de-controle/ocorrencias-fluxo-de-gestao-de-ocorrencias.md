---
title: "Ocorrências- Fluxo de Gestão de Ocorrências"
id: 16304
slug: "ocorrencias-fluxo-de-gestao-de-ocorrencias"
url: "https://wiki.simeon.com.br/ocorrencias-fluxo-de-gestao-de-ocorrencias/"
data: "2025-02-23T20:10:29"
modificado: "2025-08-11T08:41:12"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ocorrências/0-Parametrizar-estrutura-de-controle"
categorias:
  - "0- Parametrizar estrutura de controle"
tags:
---

# Ocorrências- Fluxo de Gestão de Ocorrências
![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)

**_  
O módulo de Ocorrências segue um fluxo onde cada fase é uma etapa dentro do processo. O fluxo completo é possível ser visualizado no módulo de ocorrências._**

Nesse artigo vamos entender as funcionalidades de cada etapa desse processo:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/img_629603ee3a9c1.png)

-   **Incluir ocorrência**

Nessa fase é possível preencher os campos para relatar o ocorrido, porém esses campos são editáveis apenas ao incluir ocorrência ou na fase **0-Alterar Descrição / Ação Ocorrência.**

Campos que podem ser editados nessa fase pelo **usuário inclusão e usuário com permissão de Super usuário**:

**Informações Básicas:**

-   Data;
-   Origem;
-   Título da Ocorrência;
-   Unidade Notificadora;
-   Unidade Notificada;
-   Envolveu Paciente/cliente externo? (Caso sim)
-   Prontuário/Código atendimento (Digite no mínimo 5 caracteres);
-   Turno;
-   Nome;
-   faixa etária;
-   Sexo;
-   Contato;
-   Descrição e evidência objetiva encontrada;
-   Ação Imediata:  Descreva a ação imediata que foi realizada;
-   Data da Ação;
-   Evidência:  Anexar arquivo de evidência;
-   Notificado Notivisa;
-   Vigimed;
-   Notificado integrare;

  **Atenção:** 

-   Se o parâmetro _permitir avaliação da ocorrência para o usuário inclusão_? estiver como Sim o usuário inclusão conseguirá visualizar e preencher os campos de avaliação da ocorrência.

-   **1-Avaliar Ocorrência**

Assim que a ocorrência é aberta ela vai para essa fase **1-Avaliar Ocorrência**, onde o Analista de Ocorrências faz a avaliação da ocorrência.

Campos que podem ser editados nessa fase pelo **Analista de Ocorrências**:

**Informações Básicas:**

-   Origem;
-   Título;
-   Unidade Notificadora;
-   Unidade Notificada;
-   Contato.

**Avaliação da Ocorrência:**

-   Tipo de Ocorrência;
-   Severidade/Gravidade (Grau do dano);
-   Processo;
-   Grupo de Risco;
-   Categoria da Ocorrência;
-   Indicador Relacionado;
-   Documento(s) Envolvido(s);
-   Data Prevista Finalização;
-   Requer Análise de Causa e Plano de Ação;
-   Responsável;
-   Comentário do Avaliador.

Caso tenha alguma inconsistência nos dados o Analista de Ocorrências retorna à ocorrência para o usuário inclusão, na fase **0-Alterar Descrição / Ação Ocorrência** para realizar os ajustes. Caso não haja nenhum ajuste a ser realizado, o Analista de Ocorrências, após salvar a avaliação, encaminha a ocorrência para a fase **2-Analisar Causa e Fazer Plano de Ação.**

     **1.1-Alterar Descrição / Ação Ocorrência**

Quando o Analista de Ocorrências avalia a ocorrência e identifica que tem inconsistência nos dados, ele pode voltar a ocorrência para a fase **0-Alterar Descrição / Ação Ocorrência** para que o usuário que incluiu a ocorrência revise e faça os ajustes necessários.

Quando a ocorrência é encaminhada para essa fase o EPA mantém os dados que já foram preenchidos anteriormente, e o usuário inclusão pode ajustar os campos que foram preenchidos no momento da inclusão da ocorrência:

**Informações Básicas:**

-   Data;
-   Origem;
-   Título da Ocorrência;
-   Unidade Notificadora;
-   Unidade Notificada;
-   Envolveu Paciente/cliente externo? (Caso sim)
-   Prontuário/Código atendimento (Digite no mínimo 5 caracteres);
-   Turno;
-   Nome;
-   faixa etária;
-   Sexo;
-   Contato;
-   Descrição e evidência objetiva encontrada;
-   Ação Imediata:  Descreva a ação imediata que foi realizada;
-   Data da Ação;
-   Evidência:  Anexar arquivo de evidência;
-   Notificado Notivisa;
-   Vigimed;
-   Notificado integrare.

Os campos podem ser editados nessa fase apenas pelo **usuário inclusão** e **usuário com permissão** **Analista de Ocorrências.**

Após alterações realizadas serem salvas, a ocorrência volta para a fase de **1-Avaliar Ocorrência** novamente.

-   **2-Analisar Causa e Fazer Plano de Ação** 

Após o Analista de Ocorrências validar a ocorrência, ela é encaminhada para a fase **2-Analisar Causa e Fazer Plano de Ação.** Nessa fase apenas o responsável da ocorrência pode fazer análise de causa e incluir o plano de ação.

O EPA permite a utilização de 2 metodologias para Análise de Causa:  **Espinha de Peixe** e os **5 Porquês.**

Após realizar a análise de causa será feita a inclusão do plano de ação, podendo criar um novo plano ou vincular um plano já existente.

Após a criação do plano de ação a ocorrência é encaminhada para a fase **3-Validar a Análise da Causa e/ou Plano de Ação** para que a equipe da qualidade valide a análise.

**Atenção:**

-   O botão para incluir o plano de ação só será habilitado, quando o campo “Inserir as informações levantadas durante a investigação da causa”, na análise de causa, estiver preenchido;
-   Somente o responsável e o usuário inclusão conseguem excluir um plano de ação. Após encaminhado para a fase de **3-Validar a Análise da Causa e/ou Plano de Ação,** o mesmo não pode ser excluído;
-   Apenas nessa fase é possível incluir plano de ação e tarefas.

Campos que podem ser editados nessa fase pelo **usuário responsável da ocorrência:** os campos da aba análise de causa conforme a metodologia utilizada (**Espinha de Peixe** ou **5 Porquês).**  E no plano de ação os campos:

1.  O Que (what) – Tipo da ação, Título e status;
2.  Como (how);
3.  Quando (when) – Data Início Prevista e Data Fim Prevista;
4.  Quem (who) – Responsável;
5.  Quanto Custa (how much) – Valor Previsto e Valor Real;
6.  Porque (why) – Selecionar as causas que deseja tratar e consequências;
7.  Onde (where).

Após salvar a inclusão do plano de ação, a ocorrência deve ser encaminhada para a fase de **Validar a Análise da Causa e/ou Plano de Ação,** ou pode voltar a mesma para a fase de **1-Avaliar Ocorrência.**

-   **3-Validar a Análise da Causa e/ou Plano de Ação** 

Nessa fase o Analista de Ocorrências será notificado que existe uma ocorrência para validar.  Ele deverá verificar, se a Análise de Causa e Plano de Ação estão conforme o processo definido e encaminhar a Ocorrência para a fase **4-Gerenciar o Plano de ação**.

Caso seja identificado que a Análise de Causa e/ou Plano de Ação precise de revisão, o analista deve encaminhar novamente para a fase **2.1-Fazer Revisão Conforme Orientação.**

Após o plano de ação ser criado os campos abaixo só podem ser editados pelo **Analista de Ocorrências** ou **super usuário:** 

1.  O Que (what) – Tipo da ação e Título;
2.  Quando (when) – Data Início Prevista e Data Fim Prevista;
3.  Quem (who) – Responsável;
4.  Como (how);
5.  Porque (why) – Causas e Consequências _**(Campo não editável nessa fase)**_;
6.  Quanto Custa (how much) – Valor Previsto e Valor Real;
7.  Onde (where).

Campos que podem ser editados pelo responsável do plano: incluir acompanhamento.

**OBS**: nessa fase ainda é permitido encaminhar a ocorrência para a fase **1-Avaliar Ocorrência.**

-   **3.1-Fazer Revisão Conforme Orientação**

Quando a ocorrência é encaminhada para a fase **3-Validar a Análise da Causa e/ou Plano de Ação** e o Analista de Ocorrências identifica algo que precisa ser corrigido na análise ou no plano de ação, ele encaminha a ocorrência para a fase **2.1-Fazer Revisão Conforme Orientação** com as devidas orientações. O responsável recebe a ocorrência, faz as correções e encaminha novamente para **3-Validar a Análise da Causa e/ou Plano de Ação.**

Campos que podem ser editados pelo **responsável do plano** de ação nessa fase:

-   Os campos da aba análise de causa conforme a metodologia utilizada **Espinha de Peixe** ou **5 Porquês.** 

 E no plano de ação:

1.  O Que (what) – Tipo da ação, Título e status;
2.  Quando (when) – Data Início Prevista e Data Fim Prevista;
3.  Quem (who) – Responsável;
4.  Como (how);
5.  Porque (why) – Selecionar as causas que deseja tratar e consequências;
6.  Quanto Custa (how much) – Valor Previsto e Valor Real;
7.  Onde (where).

Permite ainda incluir um acompanhamento no plano de ação, criar um novo plano de ação e/ou vincular um plano já existente.

-   **4-Gerenciar Plano de Ação**

Nessa fase o responsável pelo plano de ação poderá acessar a ocorrência e editar a ação de sua responsabilidade. Informar na ação quando realizar algo em prol da entrega, registrar o trabalho realizado como acompanhamento e concluir o plano de ação.

Quando o responsável pela ocorrência ao verificar que o plano de ação foi concluído, deverá encaminhar a ocorrência para **5-Validar Execução Ação(ões).**

 Campos abaixo só podem ser editados pelo **Analista de Ocorrências** ou **super usuário:**

1.  O Que (what) – Tipo da ação, Título e Status;
2.  Quando (when) – Data Início Prevista e Data Fim Prevista;
3.  Quem (who) – Responsável;
4.  Como (how);
5.  Porque (why) – Causas e Consequências _**(Campo não editável nessa fase)**_;
6.  Quanto Custa (how much) – Valor Previsto e Valor Real;
7.  Onde (where).

Campos que podem ser editados pelo responsável do plano:

8.  Encerramento da Ação: Data Início Real, Data Fim Real, Justificativa da Conclusão, incluir acompanhamento e anexar arquivo no acompanhamento e ainda incluir tarefas no plano de ação

**Atenção**:

-   O sistema permitirá atualizar os campos de encerramento da Ação apenas na fase **4-Gerenciar plano de ação**.

-   **5-Validar Execução Ação(ões)**

Nessa fase o analista vai verificar se as ações foram concluídas e se as evidências fornecidas para a conclusão são suficientes. Caso não seja suficiente o analista deve editar o plano de ação clicar em **Reabrir e encaminhar para revisão** e encaminhar a ocorrência para a fase **6-Revisar Execução Ação(ões).**

Caso não tenha correção, o Analista de Ocorrências deve alterar o status da ocorrência para concluído, no campo de encerrar a ocorrência, e pode ainda descrever um comentário para conclusão, e agendar eficácia, caso seja pertinente, preenchendo os campos abaixo:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/img_62960522ede98.png)

Atenção, para reabrir a ocorrência tem que:

-   Estar na fase **5-Validar Execução Ação(ões)** e não pode ter tarefa (se existir tem que tratar na tarefa);
-   Ser responsável da Ocorrência, ou responsável da ação ou Analista de Ocorrências.

Campos que podem ser editados nessa fase pelo **Analista de Ocorrências**, na aba encerrar ocorrência:

-   Status da Ocorrência;
-   Comentário para Conclusão da Ocorrência;
-   Agendar Eficácia;
-   Avaliador da Eficácia;
-   Justificativa para a Avaliação da Eficácia.

-   **6-Revisar Execução Ação(ões)**

Após a Reabertura de Plano de Ação/Tarefa a ocorrência volta para o responsável do plano de ação, e o plano volta para o status em andamento para que seja revisado.

Campos que podem ser editados nessa fase pelo **Analista de Ocorrências,** no plano de ação:

1.  O Que (what) – Tipo da ação e Título;
2.  Quando (when) – Data Início Prevista e Data Fim Prevista;
3.  Quem (who) – Responsável;
4.  Como (how);
5.  Porque (why) – Causas e Consequências _**(Campo não editável nessa fase)**_;
6.  Quanto Custa (how much) – Valor Previsto e Valor Real;
7.  Onde (where).

Campos que podem ser editados pelo **responsável do plano:**

8.  Encerramento da Ação: Data Início Real, Data Fim Real, Justificativa da Conclusão, incluir acompanhamento e anexar arquivo no acompanhamento e ainda incluir tarefas no plano de ação.

Após a revisão da execução da ação(ões), a ocorrência deve ser encaminhada para a fase **5-Validar Execução Ação(ões)** novamente.

-   **Avaliar de Eficácia do plano de ação**

        Na ocorrência o Analista de Ocorrências vai acessar a aba ação imediata e clicar no botão **Avaliação da eficácia**, sinalizando se o plano de ação foi eficaz ou não e informando a sua avaliação da eficácia.

Campos que podem ser editados nessa fase pelo **Analista de Ocorrências**, no plano de ação:

-   Agendar Eficácia;
-   Avaliador da Eficácia;
-   Justificativa para a Avaliação da Eficácia;
-   Considerar Plano de ação Eficaz? (Sim ou Não);
-   Avaliação da Eficácia.

**Importante:**

Ao encaminhar ocorrência, o Analista de Ocorrências tem a opção de fazer encaminhamentos de correções ou pontos de melhoria na ocorrência fora do fluxo proposto, podendo selecionar qualquer fase, conforme abaixo:

![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/img_629606480d57d.png)  
  **Artigos Relacionados:**

  [Incluir ocorrência](https://wiki.simeon.com.br/incluir-ocorrencia/)

  [Analisar causa e fazer plano de ação](https://wiki.simeon.com.br/analisar-causa-e-fazer-plano-de-acao/)

  [Gerenciar plano de ação](https://wiki.simeon.com.br/gerenciar-plano-de-acao/)  

  [Gerenciar plano de ação- Informar o que foi realizado na ação e concluir plano de ação](https://wiki.simeon.com.br/informar-o-que-foi-realizado-na-acao-e-concluir-plano-de-acao/?preview_id=392&preview_nonce=041f3c98cd&_thumbnail_id=-1&preview=true)

[Registrar o resultado da verificação de eficácia](https://wiki.simeon.com.br/registrar-o-resultado-da-verificacao-de-eficacia/)

![](https://wiki.simeon.com.br/wp-content/uploads/2025/02/img_67bb823fd3e85.png)

---

Fonte: https://wiki.simeon.com.br/ocorrencias-fluxo-de-gestao-de-ocorrencias/
