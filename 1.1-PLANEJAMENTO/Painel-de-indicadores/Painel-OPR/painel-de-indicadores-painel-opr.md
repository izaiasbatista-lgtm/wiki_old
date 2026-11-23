---
title: "Planejamento – Painel OPR."
id: 4675
slug: "painel-de-indicadores-painel-opr"
url: "https://wiki.simeon.com.br/painel-de-indicadores-painel-opr/"
data: "2020-08-28T14:42:55"
modificado: "2021-09-10T16:58:40"
pasta: "1.1-PLANEJAMENTO/Painel-de-indicadores/Painel-OPR"
categorias:
  - "Painel OPR"
tags:
  - "Classificação OPR"
  - "OPR"
  - "painel"
  - "Painel OPR"
---

# Planejamento – Painel OPR.
> **Agora  módulo Planejamento conta com o Painel OPR!**
> 
> OPR é uma metodologia, sua Sigla significa Orçamento por resultados. Com ele é possível monitorar a avaliação do desempenho de seus indicadores, com foco nos resultados que são esperados no seu departamento.
> 
> Através do painel OPR você poderá analisar os indicadores que precisam de atenção, os que não alcançaram a meta proposta e planejar a ação a se fazer para chegar a melhores resultados.

A seguir veja como configurar e utiliza-lo:

**1 – Permissões:**

Primeiramente conceda as permissões que são por usuário, a aqueles que terão acesso a configuração do Cadastro Classificação OPR.

**1.1.**  Em permissões Gerais do usuário, abra  a caixa de permissões: Parametrização > Planejamento> e conceda a permissão **Classificação OPR** ao usuário.

Veja a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f50e9b6e14f1.png)

 Outra permissão também é necessária para ter acesso ao Painel OPR.

**1.2.** Ainda em Permissões gerais do usuário, abra a caixa de  permissões: Planejamento> e conceda a permissão **Painel OPR** ao usuário.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f50e96725265.png)

**2 – Configurações:**

**Configurações Classificação do OPR**

Para uso do Painel OPR no EPA, você precisa criar a Classificação do OPR.

Esta classificação é utilizada para agrupar os indicadores a serem analisados e apresentados no Painel, com isso você precisa criar tais classificações com nomes referentes as suas análises.

> No EPA, vá até a tela de Cadastro da classificação do OPR através do caminho: _Configuração> Planejamento> Classificação OPR._

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f50e799cbbdb.png)

Neste ambiente:

**2.1.** Insira o **nome da classificação OPR,**

**2.2.** Selecione como **Ativo** e clique em SALVAR.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f50e8e984fa3.png)

> ![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

_Após salvar você conta com a opção de edição, podendo mudar o Status, nome da classificação e até mesmo excluir uma classificação se a mesma ainda não tiver sido configurada em algum indicador._

**3 – Configuração dos Indicadores para uso no Painel OPR**

Para analisar e apresentar os dados no painel OPR, você precisa configurar os indicadores que deseja obter análise pelo Painel OPR.

**3.1.** Em seu painel de indicadores, escolha um indicador e acesse sua configuração.

Como mostra a imagem a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f521c6592fb6.png)

**3.2.** Após entrar na configuração do indicador, acesse a **aba OPR.**

Configure os itens a seguir:

**3.3.** Escolha uma Classificação para o indicador, no campo de múltipla escolha: **Classificação OPR**,

**3.4.** Insira no campo **Ordem**, uma numeração para representar a ordem que ele vai ser apresentado na listagem do painel  OPR, (1, 2, 3 …),

**3.5.** No campo: **Análise de fatos e dados dos critérios,** você deve selecionar quais critérios deste indicador você deseja que seja analisado através do Painel.

Após esses passos clique em SALVAR.

Veja na imagem a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f521e69b7c18.png)

          Se o indicador que está configurando possuir sub indicadores, a funcionalidade: **Aplicar alterações no indicadores** filhos estará disponível para configuração. Quando selecionado o check, o sistema importa as configurações da aba OPR configuradas no indicador PAI, em todos os indicadores filhos.

**Configure os passos acima nos indicadores que você deseja analisar através do Painel OPR.**

**4 – Acesso ao Painel OPR:**

Acesse o Painel OPR, e veja os indicadores configurados para serem analisado no mesmo.

> _**Clique em** Planejamento > Painel OPR._

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f521ff879c5d.png)

**O Painel OPR conta com a seguinte estrutura:**

**1 – Identificação do Problema – Qual é o problema a ser enfrentado?**

Aqui será listado os indicadores configurados por você, Agrupados pela classificação OPR escolhida.

As informações apresentadas sobre os indicadores aqui são:

**Alvo:** Alvo configurado para o indicador,

**Realizado:** Valor realizado do indicador no mês selecionado,

**Desvio (Realizado – Alvo):** seu cálculo é _(realizado – alvo)_, calculando a diferença do que era previsto com o que foi realizado.

****%desvio:**** cálculo do desvio:_(((realizado – alvo)/alvo)\*100),_ mostrando em percentual o valor do desvio relacionado ao valor previsto e realizado.

**Resul.Hist (Alvo Referência):** é apresentado aqui o valor Alvo referência do mês em questão configurado no indicador.

**%Desvio (Histórico):** cálculo em percentual do Histórico em relação ao realizado e o alvo referência: (((realizado – Alvo Referência) / Realizado) \* 100).

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/img_5f89a16f9caa0.png)

Para mostrar as cores da coluna: **abs (realizado-alvo)** → **vermelho** ou **verde:** O EPA verifica a **_polaridade do indicador_** 

Se a polaridade for “Quanto MENOS melhor”: E o resultado do indicador for menor ou igual ao alvo o resultado do abs fica verde, se for maior fica vermelho.

Se a polaridade for “Quanto MAIS melhor” ou “Relativo”: E o resultado do indicador for maior ou igual ao alvo o resultado do abs fica verde, se for menor fica vermelho.

**2 – Análise de Fatos e Dados**

Aqui será listado os críterios e os resultados que precisam ser analisados dos indicadores configurados. O sistema faz o cálculo para identificar os critérios que não atingiram a meta, e apresenta os 10 que tiveram o maior desvio.

Aqui também também é realizado o cálculo mostrando o resultado em percentual do desvio do critério, dentre o alvo e realizado:

**%abs (desvio):** cálculo do desvio: _(((realizado – alvo)/alvo)\*100),_ mostrando em percentual o valor do desvio relacionado ao valor Alvo e realizado.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/img_5f89a1877adb9.png)

Para mostrar as cores da coluna: **%abs (Desvio) →** **vermelho** ou **verde:** O EPA verifica a **_polaridade do indicador_** e o valor do: **%abs(Desvio)**, e faz a comparação:

Se a polaridade for “Quanto MENOS melhor”: abs\_desvio < 0 -> verde. (MENOR QUE 0) abs\_desvio >= 0 -> vermelho. (MAIOR OU IGUAL)

Se a polaridade for “Quanto MAIS melhor” ou “Relativo”: abs\_desvio >= 0 -> verde. (MAIOR OU IGUAL A 0) abs\_desvio < 0 -> vermelho. (MENOR QUE 0)

**3 – Plano de ação – Qual é a intervenção (ação) a ser realizada para atingir o resultado?**

Diante dos resultados apresentados na análise, você pode criar a ação de decisão com iniciativas a serem trabalhadas para alcançar o resultado desejado.

Você pode escolher um Indicador e seu critério e criar um plano de ação e  direcionar a ação a ser realizada.

Você poderá criar uma ação a partir do critério:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f52385f5cba0.png)

Outra forma de criar os Planos de ação é inserindo os dados diretamente no ambiente 3 do painel,  preencha os campos:  Indicador, Critério, Causa, Ação, Quando, Como, Quem, Onde, Qtd. Custo, Impacto, disponiveis para ele.

Veja a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f523121858c0.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2020/06/img_5eecbdba05736.png)

**_Observações:_**

**_\-> Você poderá editar as informações do plano de ação diretamente do Painel. É só clicar nos campos, eles são editáveis._**

**_\-> O Plano de ação_ _n__o_ _painel, também conta com filtro para pesquisar os planos por Data inicio e Data Fim e Status._**

**4 – Acompanhamento:**

O Painel também conta com um ambiente para você inserir acompanhamentos, a partir de um indicador escolhido. Nele é permitido inserir anexos e enviar Emails a usuários registrados no EPA.

Para inserir um acompanhamento, preencha os campos e clique em SALVAR,

**4.1.** Escolha o indicador que você deseja registrar um acompanhamento,

**4.2.** Selecione a data do registro do acompanhamento,

**4.3.** Escreva o acompanhamento,

**4.4.** Se necessário insira anexos,

**4.5.** Escolha e selecione os usuários que você deseja notificar com email a respeito deste acompanhamento.

Salve as informações.

Abaixo a lista será apresentada, com os acompanhamentos já registrados no painel OPR.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f5232ea01c34.png)

**Opções do Painel OPR**

**5 – Impressão do Relatório:**

O Painel OPR, contem a opção de exportar um Relatório PDF com todas as informações que estão sendo apresentadas nele.

Para esse Documento, clique no botão Imprimir!

Veja a Seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f5233b76ed9b.png)

**6 – Filtro Painel OPR**

Na parte superior do Painel, você pode selecionar e filtrar as informações a serem apresentadas no painel, por **Unidade Gerencial, Etapa e colaborador.**

Estes filtros seguem a estrutura e permissões de visualização do Painel de Indicadores.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/09/img_5f5234205df5c.png)

**8 – Facilitadores do Painel OPR:**

**8.1.** Na listagem dos indicadores apresentados em: **1 – Identificação do Problema – Qual é o problema a ser enfrentado?,**   os indicadores listados possuem um link de acesso que poderá te encaminhar para a tela de detalhamento do indicador em questão.

Veja na imagem a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/img_5f771f717d546.png)

**8.2.** Na listagem dos planos de ação já incluídos no Painel OPR, apresentados em: **3 – Planos de Ação – Qual é a intervenção (ação) a ser realizada para atingir o resultado?,**   você poderá também excluir um plano de ação criado.

Veja na imagem a seguir:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/10/img_5f7720b93f738.png)

**Qualquer Dúvida estamos a disposição!**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/08/logo-epa.png)

**Referência:** PAULO, Governo de São. **METODOLOGIA OpR**: uma forma de elaborar programas com foco nos resultados. Uma forma de elaborar programas com foco nos resultados. 2019. Disponível em: http://www.ppa.sp.gov.br/ppa2023/OrcamentoOPR. Acesso em: 28 ago. 2020.

---

Fonte: https://wiki.simeon.com.br/painel-de-indicadores-painel-opr/
