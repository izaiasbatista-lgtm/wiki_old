---
title: "API de Integração com EPA-Ouvidoria"
id: 2824
slug: "api-de-integracao-com-epa-ouvidoria"
url: "https://wiki.simeon.com.br/api-de-integracao-com-epa-ouvidoria/"
data: "2020-01-13T11:42:11"
modificado: "2025-06-24T17:31:08"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Ouvidoria"
categorias:
  - "Ouvidoria"
tags:
  - "API"
  - "integração"
  - "moderadora"
  - "ouvidoria"
  - "site"
---

# API de Integração com EPA-Ouvidoria
O EPA está preparado para receber um POST de uma URL a ser gravado como um novo registro de atendimento na ferramenta de ouvidoria.  
Abaixo segue a descrição da estrutura da string de envio e de retorno.

**STRING DE ENVIO**

**\-URL**\=URL do EPA

**\-Método**\=POST

**\-Parâmetros:**

 **token:** string,

**opcao:** string,

**atendimento:** objeto \[nome:string, telefone:string, email:string, descricao:string, assunto:string, unidade:string, tipo:string, UnidadeModeradora:string\]

**PARÂMETROS A SEREM MANTIDOS COMO OBRIGATÓRIOS:**

**token:** Solicitar à equipe de desenvolvimento da Simeon. É um código único para cada cliente.

**opção:** “RegistrarAtendimento“

**assunto:** Código do assunto existente no cliente criado especificamente para identificar os registros inseridos pela API

**tipo:** Código do tipo de atendimento existente no cliente

**unidade:** “Ouvidoria”

**_Exemplo em JSON_**

JSON:

{ “token”: “XXXXXXXXX”,

   “opcao”:”RegistrarAtendimento”,

   “atendimento”: { “nome”: “XXXXXX”,  “telefone” : “XXXXX”, “email” : “XXX@XXXX”, “descrição” : “XXXXXXX”, assunto:”XXX”, unidade:”Ouvidoria”, tipo:”XXXX”, UnidadeModeradora:”Ouvidoria”}

}

**_Exemplo de implementação em JavaScript_**

<head>

<script src=”https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js”>  
</script>

</head>

<body>

<script>

$(document).ready(function(){  
$.ajax({url: ‘https://cliente.sysepa.com.br/epa/srvepa.php’,

type: “POST”,  
method: “POST”,  
dataType: “json”,

data: {token: “55fff11739632fec4f630748e1c”,  
opcao: “RegistrarAtendimento”,  
atendimento: {  
nome: “nometeste”,  
telefone: “88441234”,  
email: “teste@hotmail.com”,  
descricao: “conteudo da mensagem”,  
assunto: “2”,  
tipo: “5”,  
unidade: “Ouvidoria”  
UnidadeModeradora: “Ouvidoria”

}  
}}).done(function(response){

console.log(response); // json com o retorno, inclusive codigo gerado pelo sistema

}).fail(function(response){

console.log(response);

})

})

</script>

</body>

**STRING DE RETORNO**

Sucesso:{“Atendimento:99999”,”Atendimento registrado com sucesso!”, conteudo(nome, telefone, email, descricao)}

_Sendo:_

**_Atendimento:_** _código do atendimento registrado no EPA;_

**_conteúdo_****_:_** _nome, telefone, email e_ _descrição__: conteúdo dos campos digitado no site._

Falha:

{“statusCode:9”,mensagem de erro}

_Falhas previstas:_

_1: Nome não informado_

_2: Telefone não informado._

_3: Email não informado._

_4: Não foi possível registrar no banco de dados._

Importante:  O parâmetro **“Definir o campo chave que será utilizado no formulário externo da Ouvidoria”** é responsável por determinar qual campo será utilizado pelo EPA para localizar o cadastro da pessoa e vincular o registro de atendimento.

Na requisição enviada para o EPA, deve estar presente a informação correspondente ao campo selecionado neste parâmetro. As opções disponíveis são:

-   **“Matrícula/Número do Cartão”**: a requisição deve conter o campo `matricula`.
    
-   **“CNPJ/CPF”**: a requisição deve conter o campo `cpf_cnpj`.
    
-   **“E-mail”**: a requisição deve conter o campo `email`.
    
    ![](https://wiki.simeon.com.br/wp-content/uploads/2025/06/img_6841a61ec4abb.png)

---

Fonte: https://wiki.simeon.com.br/api-de-integracao-com-epa-ouvidoria/
