---
title: "Planejamento – Parametrizar / Configurar indicador – 1 – Aba Informações Básicas"
id: 17422
slug: "planejamento-parametrizar-configurar-indicador-1-aba-informacoes-basicas-nova-versao"
url: "https://wiki.simeon.com.br/planejamento-parametrizar-configurar-indicador-1-aba-informacoes-basicas-nova-versao/"
data: "2025-05-20T18:33:52"
modificado: "2026-03-02T11:05:45"
pasta: "1.1-PLANEJAMENTO/Configurar-indicador"
categorias:
  - "Configurar indicador"
tags:
  - "configurar"
  - "gráfico"
  - "indicador"
  - "informações básicas"
  - "salvar como"
  - "salvar como indicador"
  - "tipo alimentação"
  - "tipo de gráfico"
  - "unidade de medida"
---

# Planejamento – Parametrizar / Configurar indicador – 1 – Aba Informações Básicas
**![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dceaefbf9.png)**

**Nesse artigo, vamos falar sobre como configurar um indicador no EPA, detalhando os campos disponíveis na tela de edição. Essa etapa é essencial para garantir que os dados de desempenho estejam alinhados aos objetivos estratégicos da instituição. A seguir, apresentamos um guia sobre o preenchimento da aba Informações Básicas e das seções Descrição dos Critérios e Opções, onde são definidos os parâmetros de cálculo, apresentação e alimentação dos resultados.**

Ao acessar a tela de configuração do indicador temos as seguintes opções:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cd81477246.png)

**Preencha os Campos da Aba Informações Básicas Conforme as Orientações a Seguir:**

-   **Planejamento**: O planejamento ao qual o indicador está vinculado.
-   **Ativo:** Quando marcado indica que o indicador/resultado será apresentado no painel e poderá ser utilizado em fórmulas.
-   **Perspectiva**: Campo preenchido automaticamente pelo sistema, conforme o objetivo estratégico selecionado.
-   **Objetivo Estratégico**: Selecione o objetivo, já cadastrado no EPA, ao qual o indicador estará vinculado. Ao defini-lo, o sistema preencherá automaticamente o campo **Perspectiva**, com base na associação existente.
-   **Nome do Indicador**: Informe o título que identifica o indicador.
-   **Unidade Gerencial**: Selecione a unidade gerencial ou o painel ao qual o indicador pertence.
-   **Unidade de Medida**: Defina a unidade utilizada para apresentar o resultado do indicador (exemplos: Reais, Unidade, Percentual, Taxa, Índice, Metro, Quilograma, Hora, Volt, Hertz, Ampere).
-   **Casas Decimais**: Indique o número de casas decimais que devem ser exibidas no painel de indicadores.
-   **Ordem de Apresentação no Painel**: Defina a sequência em que o indicador será apresentado.
-   **Descrição do Indicador**: Insira um texto explicando o conceito ou propósito do indicador.
-   **Como Medir**: Descreva o cálculo a ser realizado para obter o resultado do indicador.
-   **Critérios de Inclusão**: Informe os objetivos e critérios que serão considerados na medição do indicador.
-   **Critérios de Exclusão**: Descreva os itens que não devem ser considerados nos critérios de medição do indicador.

**Na seção “Descrição dos Critérios – Detalhamento do Indicador” estão listadas as configurações dos critérios do indicador, com as seguintes opções:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cda1153124.png)

-   **Descrição do Critério**: Define o título das abas referentes aos critérios previstos para o indicador.
    
-   **Aplicar Alterações dos Critérios para os Subindicadores**: Quando marcado, ao clicar no botão **Salvar**, as alterações nos critérios serão replicadas automaticamente para os indicadores filhos.
    
-   **Código Externo**: Campo utilizado como referência para vincular o indicador à coluna “Código Externo” de uma planilha de importação de resultados.
    

**Na seção “Opções” estão listadas as regras para o cálculo e a apresentação do resultado do indicador. Ao passar o cursor do mouse sobre cada campo, o sistema exibirá a explicação correspondente:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cda7c93e55.png)

**Polaridade**  
  
Define a polaridade a ser considerada no indicador, sendo:

-   **Quanto maior melhor** – Quanto maior o resultado do indicador, maior será o impacto positivo.
    
-   **Quanto menor melhor** – Quanto menor o resultado do indicador, maior será o impacto positivo.
    
-   **Relativo** – O resultado do indicador deverá atingir exatamente o alvo definido para causar impacto positivo. Variações para maior ou menor gerarão impacto negativo.
    

#### Frequência de Alimentação

Define a periodicidade com que os dados do indicador são atualizados. Etapas configuradas como “Não houve registro nessa etapa durante a alimentação” serão omitidas dos gráficos. As frequências disponíveis são:

-   Mensal
    
-   Bimestral
    
-   Trimestral
    
-   Quadrimestral
    
-   Semestral
    
-   Anual
    

#### Tipo de Alimentação

Sinaliza o meio padrão de inclusão de resultados no indicador:  
  
→ **Extrator**: Indicadores automatizados cuja alimentação é feita pelo extrator. Se esta opção estiver selecionada, não permite inclusão manual de valor.  
  
→ **Manual**: Permite incluir valor manualmente.  
  
→ **PHP**: Indicadores automatizados cuja alimentação é feita via PHP. Não permite inclusão manual.  
  
→ **Planilha**: Indicadores alimentados por importação via planilha Excel. Não permite inclusão manual.

#### Tipo de Gráfico Padrão

Permite parametrizar o gráfico padrão para apresentação dos critérios do indicador. As opções disponíveis são:

-   Horizontal
    
-   Vertical
    
-   Linha
    

#### **Visibilidade e Organização:**

-   **Ocultar Indicador do Painel de Origem**  
      
    → O indicador não será exibido no painel principal. Útil para ocultar agrupadores ou indicadores de uso interno.
    
-   **Não computar valor dos subindicadores (Filhos)**  
      
    → O valor do indicador principal será independente dos seus subindicadores. Serve apenas como agrupador lógico.
    

#### **Alertas e Aprovações:**

-   **Emitir alerta por e-mail para o Gestor/Responsável Análise**  
      
    → Envia e-mail 10 dias antes do fim da etapa, alertando sobre possível mau desempenho.
    
-   **Aguardando aprovação do Gestor/Responsável Análise**  
      
    → Mostra solicitação de aprovação no painel do responsável, ideal para controle de alterações e validações.
    

#### **Gestão de Metas (Alvos) e Resultados:**

-   **Não Atualizar Alvo Etapa Composta**  
      
    → Permite definir um alvo manual para etapas compostas, ignorando a soma das metas das etapas filhas.
    
-   **Atualizar o ALVO da etapa conforme o ALVO da última etapa com alvo configurado**  
      
    → Atualiza automaticamente o alvo da etapa com base no último valor configurado nas etapas anteriores.
    
-   **Atualizar o RESULTADO da etapa conforme o RESULTADO da última etapa com valor**  
      
    → Atualiza automaticamente o resultado da etapa com base no valor da última etapa com resultado.
    
-   **Permitir Incluir Valor / Executar Fórmula em Etapa Composta**  
      
    → Quando essa opção está marcada, o EPA deixa de considerar os valores dos meses que compõem a etapa composta para o cálculo do resultado.  
    Com isso, o sistema permite que o usuário insira manualmente o valor diretamente na etapa composta.  
    Caso exista uma fórmula configurada na aba Fórmula, o indicador passará a utilizar essa fórmula para calcular o resultado da etapa composta. **Obs.:** Essa opção não se aplica à fórmula de critérios.
    

#### **Visualização:**

-   **Mostrar gráfico de evolução no detalhamento do painel**  
      
    → Permite ativar/desativar o gráfico de **Evolução dos Últimos 3 Anos** no detalhamento do indicador, personalizando a visualização.
    

Caso queria criar um novo indicador, copiando a mesma configuração de outro indicador clique no botão **Salvar Como.**

**Veja:** 

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cf3ce7602d.png)

Na aba que será carregada teremos as seguintes opções:

-   **1) Marque a opção _“Manter o Nome”_**  
      
    → Se o **nome do novo indicador** for **idêntico** ao nome do indicador atual.
    
-   **(2) Informe um novo nome no campo _“Nome”_**  
      
    → Se o **nome do novo indicador** for **diferente**, digite o novo nome desejado.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cf4442b39e.png)

-   **No campo _Objetivo Estratégico_**, selecione o objetivo estratégico do novo indicador.
    
-   **Caso o indicador pertença a uma unidade gerencial diferente da unidade do indicador de origem, marque a opção _“Alterar Unidade?”_**  
      
    → Isso habilitará os campos para selecionar:
    
    -   O **componente de desempenho**
        
    -   A **unidade da nova gerência**
        
-   Após preencher, clique em **_Salvar_** para concluir a configuração.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_682cf5182247f.png)

Pronto! Agora a tela será atualizada na visão de edição do novo indicador criado.

**Artigos Relacionados:**

[Entendendo o cálculo do Desempenho do Indicador](https://wiki.simeon.com.br/entendendo-o-calculo-do-desempenho-do-indicador/)

[Parametrizar / Configurar indicador – 8 – Extrator](https://wiki.simeon.com.br/parametrizar-configurar-indicador-8-extrator/)

[Parametrizar / Configurar indicador – 7 – Fórmulas](https://wiki.simeon.com.br/parametrizar-configurar-indicador-7-criterios/)

[Parametrizar / Configurar indicador – 6 – Critérios](https://wiki.simeon.com.br/parametrizar-configurar-indicador-5-criterios/)

[Parametrizar / Configurar indicador – 5 – Disponibilizar Indicador](https://wiki.simeon.com.br/parametrizar-configurar-indicador-5-disponibilizar-indicador/)

[Parametrizar / Configurar indicador – 4 – Aba Sub indicadores](https://wiki.simeon.com.br/parametrizar-configurar-indicador-4-aba-sub-indicadores/)

[Parametrizar / Configurar indicador – 3 – Aba Configurar Alvos](https://wiki.simeon.com.br/parametrizar-configurar-indicador-3-aba-configurar-alvos/)

[Parametrizar / Configurar indicador – 2 – Aba Configurações Gerais](https://wiki.simeon.com.br/parametrizar-configurar-indicador-2-aba-configuracoes-gerais/)

[Como Incluir indicador](https://wiki.simeon.com.br/incluir-indicador/)

[Configuração Indicador – Regras de Cálculo Resultado](https://wiki.simeon.com.br/configuracao-indicador-regras-de-calculo-resultado/)

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dcb3f0f6b.png)

---

Fonte: https://wiki.simeon.com.br/planejamento-parametrizar-configurar-indicador-1-aba-informacoes-basicas-nova-versao/
