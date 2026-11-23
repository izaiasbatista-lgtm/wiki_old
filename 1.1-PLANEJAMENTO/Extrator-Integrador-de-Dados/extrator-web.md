---
title: "Planejamento – Extrator Web"
id: 3181
slug: "extrator-web"
url: "https://wiki.simeon.com.br/extrator-web/"
data: "2020-05-12T15:29:02"
modificado: "2024-10-14T12:09:43"
pasta: "1.1-PLANEJAMENTO/Extrator-Integrador-de-Dados"
categorias:
  - "Extrator - Integrador de Dados"
  - "Funcionalidades"
tags:
  - "configurar indicador no extrator"
  - "extrator"
  - "web"
---

# Planejamento – Extrator Web
> ### **Objetivo**: automatizar alvo, resultado de Indicadores e cadastro de Pessoas de qualquer banco de dados, através de uma consulta sql com layout específico. 

#### _Como acessar: menu Planejamento -> Funcionalidades -> Extrator EPA_

### **Como configurar Automatização de Indicadores**

#### **01 – Configurar conexão com Banco de dados de ORIGEM das informações**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/Extrator_conexao.png)

Para criar uma nova conexão, clique em Conexões (sinalizada na Imagem). O EPA abrirá o formulário de conexão.

Em Banco de Dados haverá algumas opções, caso o banco de dados utilizado na sua empresa não esteja nessa listagem será necessário contato com a Simeon para configuração.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/Extrator_conexao_banco-300x159.png)

Será necessário informar todos os dados de conexão: IP, nome do banco, usuário ( poderá ser apenas de leitura ), senha, porta e um nome deverá ser dada a essa conexão. 

#### **02 – Criar Classificações:**

As classificações existem para que possamos classificar, organizar os indicadores por grupos. 

Exemplo: Ocorrências: irei agrupar aqui todos os indicadores do módulo de Ocorrências. 

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/extrator_classificacoes.png)

Para criar, basta clicar no botão + Classificações (sinalizada na Imagem acima). 

#### **03 – Configurar Indicadores**

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/Extrator_indicadores.png)

Para criar a Automatização de Indicadores clique em +Adicionar Indicador (sinalizada na Imagem).

Deverá ser selecionado o Tipo de Indicador ou automatização que deseja, o layout da Consulta SQL, deverá corresponder ao item selecionado. 

<table style="border-collapse: collapse; width: 100%;" border="1"><tbody><tr><td style="width: 20.2811%; text-align: center;"><strong>Tipo</strong></td><td style="width: 46.3855%; text-align: center;"><strong>SQL</strong></td><td style="width: 33.3333%; text-align: center;"><strong>Campos Opcionais</strong></td></tr><tr><td style="width: 20.2811%; text-align: center;"><strong>Indicador</strong></td><td style="width: 46.3855%;">SELECT<br>campo as data,<br>campo as valor,<br>campo as obs1,<br>campo as obs2,<br>campo as obs3,<br>campo as obs4,<br>campo as obs5,<br>campo as obs6,<br>campo as obs7,<br>campo as obs8,<br>campo as obs9,<br>campo as obs10,<br>campo as usuario,<br>campo as codigoexterno<br>FROM ???????<br>WHERE ???????<br>data &gt;= ‘$datainicio’ and data&lt;= ‘$datafim’</td><td style="width: 33.3333%;"><p>campo_filho,&nbsp; (quando existe subindicador)</p><p>peso, (quando o indicador utilizar média ponderada)</p><p>numerador,&nbsp; denominador ( quando o indicador tiver a configuração de “<span title="" data-original-title="Será executado o calculo da soma do valor numerador pela soma do valor denominador . soma(numerador)/soma(denominador)* Fator de multiplicação. Ex. Indicador de ROB  (Margem Bruta/Faturamento) e FOB)">Executar divisão dos valores no cálculo do resultado</span>. Fator de multiplicação” em suas configurações gerais )</p><p>&nbsp;</p><p>etapa_composta (permitir importar valores específicos para a etapa composta)</p></td></tr><tr><td style="width: 20.2811%;">Alvo</td><td style="width: 46.3855%;">SELECT<br>0 as alvoTipo ( 0 valor normal , 1 alvo referência , n de acordo com a tabela alvo_tipo)<br>,0 as usuario (informar zero quando não existir usuário)<br>,data<br>, campo as ncriterio_1&nbsp;<br>,campo as ncriterio_2<br>, campo as ncriterio_3<br>, campo as ncriterio_4<br>, campo as ncriterio_5<br>, campo as ncriterio_6<br>, campo as ncriterio_7<br>, campo as ncriterio_8<br>,campo as ncriterio_9<br>,campo as ncriterio_10<br>,campo as valor<br>FROM ???????<br>WHERE ???????<br>data &gt;= ‘$datainicio’ and data&lt;= ‘$datafim’</td><td style="width: 33.3333%;"><p>campo_filho,</p><p>peso,</p><p>etapa (Quando informado, o sistema irá ignorar o campo data).</p></td></tr><tr><td style="width: 20.2811%;">Clientes</td><td style="width: 46.3855%;"><p>SELECT<br>campo as nome, campo as fantasia<br>,campo as tipo ( 0= pessoa fisica , 1= pessoa juridica )<br>,campo as endereco<br>,campo as bairro<br>,campo as cidade<br>,campo as uf<br>,campo as cep<br>,campo as cpf<br>,campo as email<br>,campo as nascimento<br>,campo as matricula<br>,campo as origem<br>,campo as codigo<br>,campo as data_cadastro<br>,campo as telefone<br>,campo as celular<br>,campo as empresa</p><p>,campo as codigo_protocolo</p><div><div>,campo as questionario_id</div><div>,campo as campanha_nps</div><div>,campo as data_envio_questionario<p></p><p><span style="font-family: inherit; font-size: inherit;">,id_externo_unidade</span></p></div></div><p>,campo as data_atendimento_importacao<br>FROM ???????<br>WHERE ???????<br>data_cadastro &gt;= ‘$datainicio’</p></td><td style="width: 33.3333%;"><p>&nbsp;</p><p>,campo as origem <span style="color: #ff0000;"><span style="color: #000000;">(</span>É uma variável obrigatória para não ter uma duplicidade de registros<span style="color: #000000;">)</span></span><br>,campo as codigo&nbsp;<span style="color: #ff0000;"><span style="color: #000000;">(</span>É uma variável obrigatória para não ter uma duplicidade de registros<span style="color: #000000;">)</span></span></p><p>&nbsp;</p><p>,campo as telefone ( Se refere ao campo no cadastro da pessoa <strong>Telefone 1</strong>)</p><p>&nbsp;</p><p>Os campos: <strong>questionario_id</strong>, <strong>campanha_nps</strong>, <strong>data_envio_questionario</strong>; são opcionais, mas são obrigatórios caso queira incluir um cliente como participante em uma <strong>Campanha NPS</strong>.</p></td></tr></tbody></table>

-   Informe um nome para essa automatização do indicador, informe o código do indicador no EPA,  selecione a conexão que já deverá ter sido criada no passo 1, informe o horário que deverá sincronizar e tecle enter, informe o formato de data do banco de dados de origem, a classificação. 

-   Informe a Qtde Mês Retroativo, ex. o sistema sempre pega o mês atual, porém se quiser importar automaticamente, os últimos 2 meses, basta informar 2 nesse campo. 

-   Executar Mês a Mês: essa opção é utilizada quando temos apenas uma data final no critério da consulta. Ex. Inadimplência, pegar tudo que está em aberto até o final do mês independente da data de origem do débito. 

-   Clique em **Salvar**. 

**Observação**:

Para os campos na configuração de clientes o: _**“codigo\_protocolo” e “id\_externo\_unidade”**_, ambos são de tipo número inteiros, e não são obrigatórios. Para conseguir adicionar um cliente com origem com unidade gerencial tem que adicionar estes dois campos. 

#### **04 – Atualizar Indicador**

Independente do horário configurado, o usuário com permissão poderá no Extrator EPA, poderá executar atualização de algum indicador manualmente. Para isso, ele deverá informar o período e clicar no botão de atualizar do indicador em questão, conforme sinalizado na imagem abaixo:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/Extrator_executar.png)

#### **05 – Monitoramento do Extrator**

Existe a opção de Log, onde poderão ser acompanhas as últimas execuções realizadas pelo Extrator.

![](https://wiki.simeon.com.br/wp-content/uploads/2020/05/Extrator_log.png)

> ![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)
> 
> _**Acesse nossos artigos para saber mais sobre o o extrator e automatização de indicadores!**_
> 
> [Etapas para Automatização de Indicadores](https://wiki.simeon.com.br/etapas-para-automatizacao-de-indicadores/)
> 
> [Automatizar indicadores via WEBSERVICE](https://wiki.simeon.com.br/automatizar-indicadores-via-webservice/)
> 
> [Dicionário de dados](https://wiki.simeon.com.br/dicionario-de-dados/)

---

Fonte: https://wiki.simeon.com.br/extrator-web/
