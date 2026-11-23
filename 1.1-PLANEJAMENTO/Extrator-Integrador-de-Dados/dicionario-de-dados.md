---
title: "Planejamento – Dicionário de dados"
id: 4473
slug: "dicionario-de-dados"
url: "https://wiki.simeon.com.br/dicionario-de-dados/"
data: "2020-07-29T13:21:59"
modificado: "2023-01-06T11:12:13"
pasta: "1.1-PLANEJAMENTO/Extrator-Integrador-de-Dados"
categorias:
  - "Extrator - Integrador de Dados"
tags:
  - "dicionario"
  - "indicador"
---

# Planejamento – Dicionário de dados
Dicionário de Dados

<table style="border-style: solid; width: 1098px;" width="1098"><tbody><tr><td style="width: 196.889px;"><p><b>Campo</b></p></td><td style="width: 196px;"><p><b>Tipo</b></p></td><td style="width: 104.444px;"><p><b>Tamanho</b></p></td><td style="width: 573.778px;"><p><b>Descrição</b></p></td></tr><tr><td style="width: 196.889px;"><p>data</p></td><td style="width: 196px;"><p>DATE (dd/mm/yyyy)</p></td><td style="width: 104.444px;">&nbsp;</td><td style="width: 573.778px;"><p>dia/mês/ano em que do resultado</p></td></tr><tr><td style="width: 196.889px;"><p>valor</p></td><td style="width: 196px;"><p>DOUBLE</p></td><td style="width: 104.444px;">&nbsp;</td><td style="width: 573.778px;"><p>resultado cadastrado</p></td></tr><tr><td style="width: 196.889px;"><p>obs1 a 10</p><p>criterio1 a 10</p></td><td style="width: 196px;"><p>VARCHAR</p></td><td style="width: 104.444px;"><p>200</p></td><td style="width: 573.778px;"><p>identificação nomeada&nbsp; do aspecto/fator a ser observado</p></td></tr><tr><td style="width: 196.889px;"><p>numerador</p></td><td style="width: 196px;"><p>DOUBLE</p></td><td style="width: 104.444px;">&nbsp;</td><td style="width: 573.778px;"><p>valor a ser considerado como numerado em uma divisão</p></td></tr><tr><td style="width: 196.889px;"><p>denominador</p></td><td style="width: 196px;"><p>DOUBLE</p></td><td style="width: 104.444px;">&nbsp;</td><td style="width: 573.778px;"><p>valor a ser considerado como denominador em uma divisão</p></td></tr><tr><td style="width: 196.889px;"><p>usuario</p></td><td style="width: 196px;"><p>INT</p></td><td style="width: 104.444px;"><p>10</p></td><td style="width: 573.778px;"><p>código do usuário responsável pelo valor importado</p></td></tr><tr><td style="width: 196.889px;"><p>codigoexterno</p></td><td style="width: 196px;"><p>VARCHAR</p></td><td style="width: 104.444px;"><p>50</p></td><td style="width: 573.778px;"><p>código do registro de origem no sistema de origem. Este campo é usado em auditorias dos valores.</p></td></tr><tr><td style="width: 196.889px;"><p>campo_filho</p></td><td style="width: 196px;"><p>INT</p></td><td style="width: 104.444px;"><p>10</p></td><td style="width: 573.778px;"><p>código de identificação da origem do dado. Relacionado a códigos de empresas, filiais, equipes, etc. Ver especificação na regra de automatização de cada indicador.</p><p id="RXOZMlF">&nbsp;</p></td></tr></tbody></table>

---

Fonte: https://wiki.simeon.com.br/dicionario-de-dados/
