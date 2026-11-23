---
title: "Como testar conexão AD"
id: 6373
slug: "como-testar-conexao-ad"
url: "https://wiki.simeon.com.br/como-testar-conexao-ad/"
data: "2021-04-14T10:40:22"
modificado: "2026-01-07T10:17:52"
pasta: "1.6-CONFIGURAÇÕES/Cadastrar-Usuário-e-Perfil-de-Usuário"
categorias:
  - "Cadastrar Usuário e Perfil de Usuário"
  - "Suporte"
tags:
  - "conexão"
  - "Configurações AD"
  - "testar conexão AD"
---

# Como testar conexão AD
![](https://wiki.simeon.com.br/wp-content/uploads/2022/06/Imagens-Engracado-PNG-e-Vetor_-com-Fundo-Transparente-Para-Download-Gratis-_-Pngtree-removebg-preview-1-164x300.png)O EPA permite integração com o Active Directory (AD). O AD é uma ferramenta da Microsoft, utilizada para o gerenciamento de usuários de rede.  
Quando integrado com o EPA, os usuários cadastrados no AD são importados automaticamente para o EPA, e esses usuários conseguem acessar o EPA com a mesma senha do AD.  
Além disso, se na parametrização do sistema o parâmetro **_Vincular o código do perfil informado no parâmetro na importação do AD. Informe o código do perfil_** estiver configurado, os usuários importados do AD para o EPA recebem automaticamente as permissões de acordo com o perfil de usuário informado nesse parâmetro.Para saber mais entre em contato com a equipe de Suporte**_.  
_**

**1 –** Para testar conexão do EPA com AD, primeiro faça o login no EPA e acesse o menu **Engrenagem > Usuários > Configurações AD**. 

![](https://wiki.simeon.com.br/wp-content/uploads/2025/12/img_694e795f29935.png)

  
  

**2 –** Caso o usuário não tenha permissão para acessar essa tela, acesse o menu **Parametrização > Usuários**. No cadastro do usuário, marque a permissão **Configurações AD**.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/12/img_694e7991d16f8.png)

**Importante:** Essa tela contém informações importantes relacionadas à configuração de conexão com o Active Directory (AD). O acesso deve ser restrito apenas a administradores do sistema. Qualquer alteração indevida nessas configurações pode impactar diretamente a conexão do EPA com o AD e comprometer o funcionamento da autenticação.

  
**3 –** Na tela de Configurações AD clique no botão **Testar Configuração**.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/12/img_694e7a13696e8.png)

Se aparecer a mensagem: **Conexão realizada com Sucesso**, indica que o EPA conseguiu se conectar ao Active Directory e está apto a sincronizar os dados dos usuários.  
Caso o cliente identifique divergências entre os dados do AD e do EPA, como login, senha ou e-mail, deve ser aberta uma solicitação de incidente para que a equipe técnica possa realizar a verificação.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/12/img_694e7fa9c9d2f.png)

  
  
  
  
Se aparecer alguma mensagem de erro em vermelho, quer dizer que o EPA não esta conseguindo se conectar com o AD, e isso pode afetar a sincronização dos dados dos usuários e também a autenticação de login dos usuários no EPA.  
Neste caso é necessário que o cliente verifique com a equipe de TI, para que eles possam verificar a configuração da tela Configurar AD e validar se as credenciais configuradas nessa tela continuam corretas.  
  
Exemplos de mensagens de erro que podem aparecer:  
  

![](https://wiki.simeon.com.br/wp-content/uploads/2025/12/img_694e7fc7cd5e9.png)

 

  
  
  
  

**Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!** 

#### **![](https://wiki.simeon.com.br/wp-content/uploads/2025/09/img_68da8df21910a.png)**

---

Fonte: https://wiki.simeon.com.br/como-testar-conexao-ad/
