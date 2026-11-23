---
title: "Papéis e Permissões de Unidade Moderadora – Ouvidoria"
id: 16145
slug: "papeis-e-permissoes-de-unidade-moderadora-ouvidoria"
url: "https://wiki.simeon.com.br/papeis-e-permissoes-de-unidade-moderadora-ouvidoria/"
data: "2025-01-14T11:03:03"
modificado: "2025-01-14T11:03:03"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ouvidoria"
categorias:
  - "0- PAPÉIS E PERMISSÕES EPA"
  - "Ouvidoria"
tags:
---

# Papéis e Permissões de Unidade Moderadora – Ouvidoria
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Papéis e Permissões de Unidade Moderadora – Ouvidoria**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/01/img_67865e4d195c3-e1736859515379.png)

**Regras para o campo Unidade Moderadora – Ouvidoria**

As regras se aplicam apenas para quem utiliza **Unidade(s) Moderadora(s)** ativa(s).  
_**Obs.:** Se tiver integração da ouvidoria do seu site para o EPA, e não tem configurado na API de integração_ _o campo Unidade Moderadora. As regras 1, 2 e 3 se aplicam aos registros migrados do site para o EPA.  
Para saber mais sobre a configuração de API de integração acesse **[API de Integração com EPA-Ouvidoria](https://wiki.simeon.com.br/api-de-integracao-com-epa-ouvidoria/)**._

> **Regra 1 ⇒**  Se o usuário não for moderador de nenhuma unidade gerencial e não se comunicar com nenhuma unidade moderadora do sistema, ao incluir um registro de atendimento, o campo Unidade Moderadora estará oculto na página. No entanto, após salvar o registro, ele será gravado sem nenhuma unidade moderadora.
> 
> **Regra 2 ⇒** Se o usuário não for moderador de nenhuma unidade gerencial, mas se comunicar com uma ou mais unidades moderadoras no sistema, ao incluir um registro de atendimento, o campo Unidade Moderadora estará oculto na página.  
> Após salvar o registro, o campo Unidade Moderadora será preenchido automaticamente com a primeira unidade moderadora com a qual o usuário se comunica.
> 
> **Regra 3 ⇒**Se o usuário for moderador de uma ou mais unidades, ao incluir um registro de atendimento, o campo Unidade Moderadora estará disponível na tela, com as opções de unidades moderadoras às quais o usuário logado é moderador. O usuário pode selecionar a unidade moderadora relevante no registro.
> 
> **Regra 4 ⇒** Se o usuário não for moderador de alguma unidade gerencial, mas tiver permissão de Analista de Ouvidoria, ao acessar o menu Política de Qualidade > Ouvidoria > Listar Atendimento.  
> Nos filtros disponíveis na página, o campo Unidade Moderadora estará disponível e com a opção: Sem Unidade Moderadora.  
> Mas o usuário, poderá visualizar apenas os registros que não tem unidade moderadora selecionada.  
> Obs.: Na tela inicial na caixinha de Ouvidoria não vão aparecer os registros sem unidade moderadora para o Analista de Ouvidoria.
> 
> **Regra 5 ⇒** Se o usuário for moderador de alguma unidade gerencial, e não tem permissão de Analista de Ouvidoria, ao acessar o menu  
> Política de Qualidade> Ouvidoria > Listar Atendimento.  
> Nos filtros disponíveis na página o campo Unidade Moderadora estará disponível e com as opções para escolha: A Unidade Moderadora que ele é moderador, e poderá visualizar os registros em que é moderador da unidade.  
> Obs.: Na tela inicial na caixinha de Ouvidoria vão aparecer os registros com moderadora para o usuário moderador.

**Importante:** Quando o registro de atendimento é criado via link externo, o sistema **não considera as regras 1,2 e 3**.  
Ele verifica a unidade gerencial padrão do usuário que foi criado para gerar o link, e seleciona essa unidade como Unidade Moderadora dos registros de atendimento criados.  
Para saber mais sobre a configuração de link externo acesse **[Formulário externo registro de ouvidoria.](https://wiki.simeon.com.br/ouvidoria-formulario-externo-registro-de-ouvidoria/)**

**![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/a38addc0469bb9b9bb45550042634c6d-e1686342600774.jpg)**

**Artigos Relacionados:**

**[Configurar unidade moderadora – Ouvidoria](https://wiki.simeon.com.br/configurar-unidade-moderadora-ouvidoria/)**

**[API de integração do site com EPA – Ouvidoria](https://wiki.simeon.com.br/api-de-integracao-com-epa-ouvidoria/)**

**[Cadastros e Permissões – Permissões em Ouvidoria](https://wiki.simeon.com.br/permissoes-em-ouvidoria/)**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!**

---

Fonte: https://wiki.simeon.com.br/papeis-e-permissoes-de-unidade-moderadora-ouvidoria/
