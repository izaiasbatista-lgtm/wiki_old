---
title: "Planejamento – Parametrizar / Configurar indicador – 2 – Aba Configurações Gerais"
id: 2447
slug: "parametrizar-configurar-indicador-2-aba-configuracoes-gerais"
url: "https://wiki.simeon.com.br/parametrizar-configurar-indicador-2-aba-configuracoes-gerais/"
data: "2019-10-28T17:32:38"
modificado: "2021-09-09T11:49:35"
pasta: "1.1-PLANEJAMENTO/Configurar-indicador"
categorias:
  - "Configurar indicador"
tags:
  - "configuração"
  - "configurar"
  - "indicador"
---

# Planejamento – Parametrizar / Configurar indicador – 2 – Aba Configurações Gerais
**  
Faça as configurações necessárias para obter o resultado desejado para o indicador, seguindo as orientações de preenchimento abaixo:**

![](https://wiki.simeon.com.br/wp-content/uploads/2021/09/img_613a1dd9c5d1c.png)

Nesta Aba será definido o comportamento do indicador nas etapas de análises definidas.

-   -   **Etapa:** período de coleta e análise de dados,
-    
    -   **Frequência do indicador:** amplitude de tempo a considerar para computar o resultado do indicador.
-    
    -   **Responsável Análise:** usuário do EPA responsável por inserir análise de desempenho no indicador.
-    
    -   **Responsável Alimentação:** usuário do EPA responsável por verificar/inserir os dados no indicador.
-    
    -   **Indicador Ativo nesta Etapa:** sinaliza se o indicador será visível no painel e impactará no resultado do objetivo estratégico do período.

Na aba **Configurações Gerais** estão relacionados os aspectos que definem o indicador em cada etapa de mensuração.  

**Operações com os dados informados no indicador**:

-   -   **Calcular a soma:**  soma do campo valor de cada item inserido para compor o resultado do indicador. _Campo sinalizado na **imagem 1**_. Ex: (1+3+5+7+9) 
        
    -   **Calcular média aritmética:**  soma do campo valor de cada item inserido para compor o resultado do indicador  dividido pelo total de itens inseridos. _Campo sinalizado na **imagem 1**_ Ex: (1+3+5+7+9)/5
        
    -   **Calcular média ponderada:** soma da multiplicação do campo valor de cada item inserido para compor o resultado do indicador, pelo respectivo número informado no campo peso, dividido pela soma dos pesos de cada item. _Campos sinalizados na **imagem 2**_. Ex: (1x(p5)+3x(p2)+5x(p5)+7x(p3)+9x(p2))/17
        
    -   **Calcular média aritmética do peso:** soma do campo valor de cada item inserido dividido pela soma dos pesos de cada item. _Campos sinalizados na **imagem 2**._ Ex. com base no exemplo do cálculo da média ponderada: (1+3+5+7+9)/17
        
    -     **Executar divisão dos valores no cálculo do resultado. Fator de multiplicação: :**  divisão do valor informados no campo numerador pelo valor informado no campo denominador, de cada item multiplicado por um fator (100,1000, etc). O fator de multiplicação deve ser informado na configuração do indicador. _Campos sinalizados na **imagem 3**_. Ex: (1/2) x 100
        
    -   **Executar divisão dos valores no cálculo do alvo:** Essa opção terá impacto somente no alvo do indicador. Divisão do valor informados no campo numerador pelo valor informado no campo denominador. A inclusão dos resultados para este calculo está disponível somente por planilha ou extrator de dados. Ex: (3/2) x 100
        
    -   **Calcular média da etapa composta:** Essa opção terá impacto no resultado do indicador nas etapas compostas e somente quando a opção Permitir Incluir Valor / Executar Fórmula em Etapa Composta, da aba Informações Básicas, estiver sinalizada. Em uma etapa composta (trimestre, semestre, anual) o resultado apresentado pelo indicador  será a soma das médias de cada etapa dividida pela quantidade de etapas que a compõe. Ex: Etapa trimestral (12+35+20)/3

**Demais configurações:**

-   **Este indicador será alimentado através de fórmula :** Quando marcado não permite a inclusão manual dos resultados diretamente na tela de detalhamento do indicador. E habilita na tela de edição do indicador aba **Formula**, para configurar a formula do calculo do resultado do indicador.  
    _Para saber como configurar a formula no indicador acesse o artigo_ _[Configurar indicador – Fórmulas](https://wiki.simeon.com.br/parametrizar-configurar-indicador-7-criterios/)._

-   **Etapa composta com valor NÃO cumulativo:** Permite informar um valor no indicador quando ele está em uma etapa composta, não somando o valor das etapas para compor o resultado. As etapas compostas irão buscar o último valor do mês.

-   **Apresentar  o último valor lançado:** Quando marcado será mostrado como resultado sempre o último valor lançado no indicador, respeitando data e hora de inclusão.

-   **Indicador Estratégico – Compor o PPR (Plano de Participação nos Resultados):** Quando esta opção for marcada, significa que este indicador nesta etapa irá compor o plano de remuneração.

-   **Considerar o alvo igual a zero quando não existir valor de alvo lançado:** Quando marcado essa opção ao criar um novo indicador, o EPA ajustará os alvos da presente etapa para ‘zero’ e o painel de indicadores não notificará este indicador com ![](https://simeon.sysepa.com.br/epa/figuras/interrogacao.GIF)  (indicador sem alvos configurados).

-   **Peso do indicador:** Peso do indicador no painel que ele é visualizado. O peso é configurado por etapa. Ao disponibilizar um indicador o peso dele influenciará a mensuração dos objetivos estratégicos contidos no painel de indicadores.

-   **Fazer comparação de percentual em relação ao indicador – código:** Permite listar no painel do indicador, o quanto o resultado do indicador representa do resultado do indicador referenciado, na etapa em análise. Utilizar para indicadores de grandezas iguais. Campo sinalizado na **_imagem 4_**.

-   **Alterar também a(s) etapa(s):**  Permite copiar as configurações da etapa selecionada para outras etapas criadas e ativas.

Após executar as configurações desejadas deve-se clicar no botão **SALVAR**.

![](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5db73bfa3c49f.png)

**_Imagem 1_**

![](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5db73d0eccc12.png)

**_Imagem 2_**

![](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5db7407f8af0a.png)

**_Imagem 3_**

![Imagem 4](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5db7491e7bcc6.png)

**_Imagem 4_**

> ![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)
> 
> _**Acesse nossos artigos para saber mais sobre o configuração de indicadores!**_
> 
> [Entendendo o cálculo do Desempenho do Indicador](https://wiki.simeon.com.br/entendendo-o-calculo-do-desempenho-do-indicador/)
> 
> [Parametrizar / Configurar indicador – 8 – Extrator](https://wiki.simeon.com.br/parametrizar-configurar-indicador-8-extrator/)
> 
> [Parametrizar / Configurar indicador – 6 – Critérios](https://wiki.simeon.com.br/parametrizar-configurar-indicador-5-criterios/)
> 
> [Parametrizar / Configurar indicador – 7 – Fórmulas](https://wiki.simeon.com.br/parametrizar-configurar-indicador-7-criterios/)
> 
> [Parametrizar / Configurar indicador – 5 – Disponibilizar Indicador](https://wiki.simeon.com.br/parametrizar-configurar-indicador-5-disponibilizar-indicador/)
> 
> [Parametrizar / Configurar indicador – 4 – Aba Sub indicadores](https://wiki.simeon.com.br/parametrizar-configurar-indicador-4-aba-sub-indicadores/)
> 
> [Parametrizar / Configurar indicador – 3 – Aba Configurar Alvos](https://wiki.simeon.com.br/parametrizar-configurar-indicador-3-aba-configurar-alvos/)
> 
> [Parametrizar / Configurar indicador – 2 – Aba Configurações Gerais](https://wiki.simeon.com.br/parametrizar-configurar-indicador-2-aba-configuracoes-gerais/)
> 
> [Como Incluir indicador](https://wiki.simeon.com.br/incluir-indicador/)
> 
> [Configuração Indicador – Regras de Cálculo Resultado](https://wiki.simeon.com.br/configuracao-indicador-regras-de-calculo-resultado/)

---

Fonte: https://wiki.simeon.com.br/parametrizar-configurar-indicador-2-aba-configuracoes-gerais/
