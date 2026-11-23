---
title: "Riscos- Cálculo da Mitigação do Controle Interno"
id: 18626
slug: "riscos-calculo-da-mitigacao-do-controle-interno"
url: "https://wiki.simeon.com.br/riscos-calculo-da-mitigacao-do-controle-interno/"
data: "2025-10-29T16:39:48"
modificado: "2025-12-16T14:46:54"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Risco/07-Controle-Interno"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
  - "07 Controle Interno"
  - "Versão 194"
tags:
---

# Riscos- Cálculo da Mitigação do Controle Interno
**![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dceaefbf9.png)**

**Neste artigo, vamos demonstrar na prática como utilizar o Controle Interno dentro de um Risco, entendendo como ele influencia diretamente na análise e nos cálculos de mitigação. A partir de um exemplo real, você verá como o EPA aplica os valores definidos no controle interno para ajustar os fatores da análise de risco automaticamente.**

> **Observação:** Para ter acesso à parametrização do Controle Interno, é necessário que, nos **Parâmetros do Sistema**, a opção **“Deseja incluir Controle(s) Interno(s) na Gestão de Riscos?”** esteja configurada como **“Sim”**.
> 
> ![](https://wiki.simeon.com.br/wp-content/uploads/2025/11/img_690b41e58061f.png)

Na seção **“Análises do Risco”** _(Políticas de Qualidade > Riscos > Gestão de Riscos > Escolha um risco.)_, ao clicar em **“+Análise”**, será exibido o modal de **“Nova Análise”**.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_69025a9da9214.png)

Após preencher os dados da análise, o **EPA** ajustará automaticamente os valores conforme as **mitigações** aplicáveis à **unidade gerencial** vinculada ao controle interno.

#### Exemplo prático do cálculo

Suponha que o controle interno tenha sido configurado para **mitigar o fator “Probabilidade”** com um valor de **45%**.  
  
Durante a análise, o usuário informa a **Probabilidade = 4**.  
  
O EPA aplicará o percentual de mitigação sobre esse valor, utilizando a seguinte lógica:

**4 x 0,45 = 1,8**

Como o sistema sempre **arredonda automaticamente** para o valor mais próximo definido nos **Parâmetros do Risco**, o resultado final será:

**Probabilidade ajustada = 2**

Dessa forma, o EPA garante que o impacto do controle interno seja refletido diretamente nos fatores da análise, proporcionando uma **avaliação mais realista e consistente do risco mitigado**.

Quando possuir mais de um controle interno para o mesmo fator e mesma unidade gerencial, o sistema deve utilizar a fórmula 1 – \[ (1 – C1) (1 – C2) … (1-Cn) \] para calcular o valor total que será mitigado

Nesse modelo: O controle com maior eficácia atua primeiro, reduzindo parte do risco. Os demais controles atuam sobre o risco residual (o que sobra). O resultado é um percentual total de mitigação mais fiel à realidade do processo.

Importante: O percentual final de mitigação calculado será aplicado diretamente nos Fatores Mitigados do risco, reduzindo sua probabilidade e/ou impacto conforme parametrização.

**Exemplo prático:**

Controle 1: eficácia 80%  
Controle 2: eficácia 50%

Cálculo: Controle 1 reduz o risco em 80% → sobra 20%  
Controle 2 atua sobre os 20% restantes → 50% de 20% = 10% 

Mitigação total = 80% + 10% = 90%

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_6902607e5ac79.png)

O valor da mitigação será ajustado **somente** se a **avaliação da auditoria** do controle interno (localizada em: **_Políticas da Qualidade → Risco → Gestão de Risco → Auditorias de Controle Interno_**) estiver **sem valor** ou **eficiente**. Caso a auditoria esteja marcada como **ineficiente**, **nenhum ajuste de mitigação será aplicado** na análise.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_69026c589f3d1.png)

Após o cálculo, o valor ajustado da mitigação será automaticamente refletido na **Matriz de Riscos** (**_Políticas da Qualidade → Risco → Gestão de Risco → Matriz de Riscos_**), atualizando os fatores de probabilidade, impacto ou outros que foram definidos para serem mitigados

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_69026c6e3391e.png)

Neste artigo, vimos como o **Controle Interno** atua diretamente dentro do **Risco**, desde o momento do seu cadastro até o impacto real nos valores da **análise de risco**. O EPA realiza automaticamente o cálculo da **mitigação** com base nas classificações configuradas, ajustando os fatores definidos (como probabilidade, impacto, entre outros).

**Quer aprender a fazer uma auditoria no controle interno? [Clique aqui](https://wiki.simeon.com.br/riscos-auditorias-de-controle-interno/)**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/10/img_68e2dcb3f0f6b.png)

---

Fonte: https://wiki.simeon.com.br/riscos-calculo-da-mitigacao-do-controle-interno/
