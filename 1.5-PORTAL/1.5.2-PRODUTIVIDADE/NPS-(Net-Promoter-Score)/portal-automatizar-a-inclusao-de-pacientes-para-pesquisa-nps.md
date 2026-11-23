---
title: "Portal – Pesquisa NPS: Automatização na inclusão de clientes"
id: 8190
slug: "portal-automatizar-a-inclusao-de-pacientes-para-pesquisa-nps"
url: "https://wiki.simeon.com.br/portal-automatizar-a-inclusao-de-pacientes-para-pesquisa-nps/"
data: "2021-09-10T09:33:58"
modificado: "2024-10-14T17:26:36"
pasta: "1.5-PORTAL/1.5.2-PRODUTIVIDADE/NPS-(Net-Promoter-Score)"
categorias:
  - "NPS (Net Promoter Score)"
tags:
  - "automatizar clientes campanhas"
  - "campanhas"
  - "NPS"
---

# Portal – Pesquisa NPS: Automatização na inclusão de clientes
![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/img_60f9af23432dd-e1631209450908-213x300.png)

-   -   -   -   -   -   **Nessa versão, o EPA traz uma nova funcionalidade para possibilitar a automatização na inclusão de pacientes/clientes nas Pesquisas NPS.**
                -    
                    -   **A partir da configuração via Extrator, o EPA recebe as informação dos clientes a serem inseridos na campanha, juntamente com a informação da data do último atendimento destes clientes.**
                -    
                    -   **Com isso, no intervalo de tempo determinado, o sistema verifica os atendimentos realizados e inclui os clientes na campanha NPS configurada e dispara e-mails para estes com a pesquisa.**
                -    
                    -   **Essa melhoria, é mais um facilitador na configuração das campanhas do EPA e auxiliará você no controle e gestão das pesquisas NPS disparadas aos seus clientes, agora sendo de forma automática!**

Veja como utilizar essa melhoria!

# CAMPANHAS NPS

**1 –** O primeiro passo é configurar a campanha de NPS. Acesse o caminho **Portal> NPS > Campanhas**, crie ou edite uma campanha para receber os clientes de forma automática, via extrator, e faça as devidas configurações:

1.1. Configure todas as informações padrão de uma campanha NPS, veja em: [Criar uma campanha NPS](https://wiki.simeon.com.br/criar-campanha-nps/);

1.2. Na aba **Visualizar Campanhas,** configure as **datas início e fim** da campanha;

1.3. Configure também qual será a **hora início e fim** em que o EPA deve fazer as verificações de inserção dos participantes e envio das pesquisas a estes;

1.4. E para ativar essa funcionalidade, marque a opção: **Incluir automaticamente na campanha clientes que possuem data do último atendimento no período da campanha.**

1.5 Clique em Salvar

![](https://wiki.simeon.com.br/wp-content/uploads/2024/10/img_670d7b6a99db2.png)

# EXTRATOR WEB

**2 –** Após configurar a campanha de NPS é preciso configurar no extrator a rotina de importar clientes os novos campos.

2.1. Acesse o extrator pelo caminho: **Planejamento> Funcionalidades> Extrator EPA;**

2.2. Edite a página de configuração, para inserir a SQL e demais informações para automatizar este processo, para alimentação dos dados dos clientes;

2.3. No campo Tipo de indicador, selecione **_Clientes_**;

2.4. E na consulta SQL, insira a consulta correspondente (conforme o padrão mostrado na imagem a seguir), adicionando os campos: **questionario\_id**, **campanha\_nps**, **data\_envio\_questionario;**

![](https://wiki.simeon.com.br/wp-content/uploads/2024/10/img_670d7c72c6437.png)

Esta estrutura será usada para criar a SQL de inclusão de cliente.

Em “Verde” estão os campos cruciais para a escolha do NPS ao qual o cliente será inserido. Ressaltamos que esses campos são opcionais para a automatização de indicadores, mas obrigatórios para essa função.

-   **questionario\_id**: Deve conter o código do Questionário usado no NPS;
-   **campanha\_nps**: Deve conter o código da Campanha NPS;
-   **data\_envio\_questionario**: Deve conter o código a Data de envio da campanha.

Em “Azul” estão os principais campos de identificação do cliente, que são obrigatórios para validar a inclusão.

Esses campos são usados para identificar o cliente dentro do sistema e selecioná-lo para inclusão na campanha.

-   **origem**:
    -   Origem do cliente que foi importado para o EPA
    -   **É uma variável obrigatória para não ter uma duplicidade de registros**
-   **codigo**:
    -   Código do cliente dentro do sistema
    -   **É uma variável obrigatória para não ter uma duplicidade de registros**

![](https://wiki.simeon.com.br/wp-content/uploads/2024/10/img_670d7d72e20e4.png)

2.5. Preencha os demais campos necessários nesta página de configuração para o extrator. Para saber a configuração completa a ser feita nos indicadores, acesse: [Extrator-web.](https://wiki.simeon.com.br/extrator-web/)

2.6 Com os **Campos de NPS** e **Campos de Identificação** colhidos, a SQL já pode ser montada e executada no extrator normalmente.

**3 – Processo a ser seguido para essa funcionalidade:**

-   Com a campanha NPS configurada, o sistema fará a verificação via extrator dos clientes que tiveram atendimentos entre a data início e fim configurada na campanha.
-   Essa verificação ocorrerá a cada 5 minutos dentre os horários também configurados na campanha NPS.
-   Entre estas verificações os clientes atendidos neste período serão inseridos automaticamente como participantes na campanha e os e-mails com a pesquisa NPS irão ser enviados para eles.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/img_60f9af23432dd-e1631282333522-213x300.png)

**Observações:**

-   Para evitar que o cliente seja importunado com vários e-mails NPS por vez, o sistema hoje limita o envio de 1 pesquisa NPS por campanha para cada cliente.

-   Recomendamos que seja criada uma campanha por mês (já criar por exemplo, todas as campanhas do ano usando o **salvar como**) para o sistema ir incluindo automaticamente os clientes nas campanhas do mês.

![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)

> **Artigos Relacionados:**
> 
> [Cadastros básicos NPS](https://wiki.simeon.com.br/cadastros-basicos-nps/)
> 
> [NPS – Cadastro de Categorias Campanhas NPS](https://wiki.simeon.com.br/nps-cadastro-de-categorias-campanhas-nps/)
> 
> [Como criar Campanha NPS](https://wiki.simeon.com.br/criar-campanha-nps/)
> 
> [Como criar Questionário NPS](https://wiki.simeon.com.br/criar-questionario-nps/)

#### **Aproveite essa melhoria !**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

#### ![](https://wiki.simeon.com.br/wp-content/uploads/2020/08/logo-epa.png)

---

Fonte: https://wiki.simeon.com.br/portal-automatizar-a-inclusao-de-pacientes-para-pesquisa-nps/
