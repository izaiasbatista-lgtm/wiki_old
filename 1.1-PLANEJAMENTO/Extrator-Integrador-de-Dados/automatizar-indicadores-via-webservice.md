---
title: "Planejamento – Automatizar indicadores via WEBSERVICE"
id: 4479
slug: "automatizar-indicadores-via-webservice"
url: "https://wiki.simeon.com.br/automatizar-indicadores-via-webservice/"
data: "2020-07-29T13:42:23"
modificado: "2022-09-14T10:31:15"
pasta: "1.1-PLANEJAMENTO/Extrator-Integrador-de-Dados"
categorias:
  - "Extrator - Integrador de Dados"
tags:
  - "indicador"
  - "webservice"
---

# Planejamento – Automatizar indicadores via WEBSERVICE
Para automatizar um indicador via webservice insira a URL de acesso ao webservice na tela de configuração do indicador,

na aba **Extrator,** 

campo **Informe a url do webservice que você deseja fazer integração, conforme abaixo:**

**https://endereco\_coleta\_de\_dados?dataInicio=$dataInicio&dataFim=$dataFim**

**endereço\_coleta\_de\_dados**\=endereço do webservice que fornece os dados para o indicador.

**dataInicio=$dataInicio&dataFim=$dataFim**: parâmetro fixo utilizado pelo sistema para importar os dados da etapa definida como padrão no painel de indicadores. As datas serão enviadas no formato yyyy-mm-dd.

                     Exemplo da requisição que chegará ao webservice: https://endereco\_coleta\_de\_dados?dataInicio=2022-09-01&dataFim=2022-09-30

Veja na figura abaixo:

![](https://wiki.simeon.com.br/wp-content/uploads/2020/07/img_5f21a48963519.png)

O WEBSERVICE deve retornar os dados os campos esperados pelo EPA em XML ou JSON . 

Obs.: Cada dado retornado deve ser identificado seguindo a nomenclatura específica do EPA, veja o exemplo em XML. 

<table style="width: 836px;"><tbody><tr><td style="width: 452.889px;"><p>VARIÁVEIS ESPERADAS PELO EPA</p></td><td style="width: 367.556px;"><p>EXEMPLO DE XML DE ENVIO PARA O EPA</p></td></tr><tr><td style="width: 452.889px;"><p>indicador (obrigatório)</p><p>,codigoExterno</p><p>,data (obrigatório)</p><p>,valor (obrigatório)</p><p>,peso</p><p>,idUsuario</p><p>,idUsuarioExterno</p><p>,numerador</p><p>,denominador</p><p>,idEtapaComposta</p><p>,idCriterio1</p><p>,criterio1 (obrigatório)</p><p>,idCriterio2</p><p>,criterio2</p><p>,idCriterio3</p><p>,criterio3</p><p>,idCriterio4</p><p>,criterio4</p><p>,idCriterio5</p><p>,criterio5</p><p>,idCriterio6</p><p>,criterio6</p><p>,idCriterio7</p><p>,criterio7</p><p>,idCriterio8</p><p>,criterio8</p><p>,idCriterio9</p><p>,criterio9</p><p>,idCriterio10</p><p>,criterio10</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p></td><td style="width: 367.556px;"><p>&lt; indicador&gt;</p><p>&lt;dadosIndicador&gt;</p><p>&lt;indicador&gt;26&lt;/indicador&gt;</p><p>&lt;codigoExterno&gt;0&lt;/codigoExterno&gt;</p><p>&lt;data&gt;2014-01-04&lt;/data&gt;</p><p>&lt;valor&gt;27658&lt;/valor&gt;</p><p>&lt;peso&gt;0&lt;/peso&gt;</p><p>&lt;idUsuario&gt;0&lt;/idUsuario&gt;</p><p>&lt;idUsuarioExterno/&gt;</p><p>&lt;numerador&gt;0&lt;/numerador&gt;</p><p>&lt;denominador&gt;0&lt;/denominador&gt;</p><p>&lt;idEtapaComposta/&gt;</p><p>&lt;idCriterio1/&gt;</p><p>&lt;criterio1&gt;DIVIDA ATV&lt;/criterio1&gt;</p><p>&lt;idCriterio2/&gt;</p><p>&lt;criterio2&gt;MG&lt;/criterio2&gt;</p><p>&lt;idCriterio3/&gt;</p><p>&lt;criterio3&gt;PF&lt;/criterio3&gt;</p><p>&lt;idCriterio4/&gt;</p><p>&lt;criterio4&gt;1&lt;/criterio4&gt;</p><p>&lt;idCriterio5/&gt;</p><p>&lt;criterio5&gt;ZT&lt;/criterio5&gt;</p><p>&lt;idCriterio6/&gt;</p><p>&lt;criterio6/&gt;</p><p>&lt;idCriterio7/&gt;</p><p>&lt;criterio7/&gt;</p><p>&lt;idCriterio8/&gt;</p><p>&lt;criterio8/&gt;</p><p>&lt;idCriterio9/&gt;</p><p>&lt;criterio9/&gt;</p><p>&lt;idCriterio10/&gt;</p><p>&lt;criterio10/&gt;</p><p>&lt;/dadosIndicador&gt;</p><p>&lt;dadosIndicador&gt;</p><p>&lt;indicador&gt;26&lt;/indicador&gt;</p><p>&lt;codigoExterno&gt;0&lt;/codigoExterno&gt;</p><p>&lt;data&gt;2014-01-10&lt;/data&gt;</p><p>&lt;valor&gt;20000&lt;/valor&gt;</p><p>&lt;peso&gt;0&lt;/peso&gt;</p><p>&lt;idUsuario&gt;0&lt;/idUsuario&gt;</p><p>&lt;idUsuarioExterno/&gt;</p><p>&lt;numerador&gt;0&lt;/numerador&gt;</p><p>&lt;denominador&gt;0&lt;/denominador&gt;</p><p>&lt;idEtapaComposta/&gt;</p><p>&lt;idCriterio1/&gt;</p><p>&lt;criterio1&gt;ANUIDADE&lt;/criterio1&gt;</p><p>&lt;idCriterio2/&gt;</p><p>&lt;criterio2&gt;RJ&lt;/criterio2&gt;</p><p>&lt;idCriterio3/&gt;</p><p>&lt;criterio3&gt;PF&lt;/criterio3&gt;</p><p>&lt;idCriterio4/&gt;</p><p>&lt;criterio4&gt;50&lt;/criterio4&gt;</p><p>&lt;idCriterio5/&gt;</p><p>&lt;criterio5&gt;MV&lt;/criterio5&gt;</p><p>&lt;idCriterio6/&gt;</p><p>&lt;criterio6/&gt;</p><p>&lt;idCriterio7/&gt;</p><p>&lt;criterio7/&gt;</p><p>&lt;idCriterio8/&gt;</p><p>&lt;criterio8/&gt;</p><p>&lt;idCriterio9/&gt;</p><p>&lt;criterio9/&gt;</p><p>&lt;idCriterio10/&gt;</p><p>&lt;criterio10/&gt;</p><p>&lt;/dadosIndicador&gt;</p><p>&lt;/indicador&gt;</p></td></tr></tbody></table>

> ![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)
> 
> _**Acesse nossos artigos para saber mais sobre o o extrator e automatização de indicadores!**_
> 
> [Etapas para Automatização de Indicadores](https://wiki.simeon.com.br/etapas-para-automatizacao-de-indicadores/)
> 
> [Extrator Web](https://wiki.simeon.com.br/extrator-web/)
> 
> [Dicionário de dados](https://wiki.simeon.com.br/dicionario-de-dados/)

---

Fonte: https://wiki.simeon.com.br/automatizar-indicadores-via-webservice/
