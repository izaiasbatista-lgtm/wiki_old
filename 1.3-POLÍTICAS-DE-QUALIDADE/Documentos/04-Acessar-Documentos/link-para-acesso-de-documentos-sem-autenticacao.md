---
title: "Documentos – Criar link para acesso de Documentos sem autenticação"
id: 15448
slug: "link-para-acesso-de-documentos-sem-autenticacao"
url: "https://wiki.simeon.com.br/link-para-acesso-de-documentos-sem-autenticacao/"
data: "2024-01-05T11:50:24"
modificado: "2024-01-05T16:48:11"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Documentos/04-Acessar-Documentos"
categorias:
  - "04 -Acessar Documentos"
  - "Documentos"
tags:
  - "integracao documentos"
  - "link acesso externo documentos"
  - "link documentos"
  - "Token de integração"
---

# Documentos – Criar link para acesso de Documentos sem autenticação
![](https://wiki.simeon.com.br/wp-content/uploads/2023/07/img_64a7fca1dd9eb.png)  
No EPA é possível configurar para que os colaboradores possam acessar documentos através de um link de integração, sem a necessidade de login e senha. Esse link pode ser incorporado a um site ou intranet, permitindo que os colaboradores acessem os documentos diretamente, sem a necessidade de um usuário e senha específicos.  
Veja como  é fácil configurar:

_**1\. Criar um usuário genérico.**_

Para cadastrar usuário clique ![](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5d94b2623f099.png) **→  Usuários → Gerenciar Usuários**, e clique no botão ![](https://wiki.simeon.com.br/wp-content/uploads/2019/10/img_5d950cfdbc054.png)  para incluir um novo usuário.  
É necessário para cadastrar usuário que já tenha um cadastro de pessoa para ter um vínculo.  
Será aberta uma tela para pesquisar o nome da pessoa, informe o **nome (1)** e clique em pesquisar, abaixo será listado os nomes que contem a palavra digitada ou traz somente o nome que pesquisou se digitar o nome completo. Selecione o **nome desejado (2)** e clique no botão próxima etapa.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_659808e46e397.png)

 Na próxima tela vamos começar a configurar o cadastro do usuário, informe o **Login(3)** que o usuário vai utilizar para acessar o EPA,  selecione o **componente de desempenho(4)**, a **unidade gerencial padrão (5)** esses dados que vão definir a estrutura da unidade gerencial do usuário que vamos configurar mais a frente. 

Assim que clicar no botão salvar serão habilitadas as abas abaixo, para fazer a configuração conforme o cargo ou o departamento do usuário.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_65980883b3b05.png)

**2.** _**Permissões Gerais  
**_  
No cadastro do usuário na aba Permissões Gerais acesse o menu **Politicas da Qualidade → Documentos** e marque a permissão ****Quando Acessar o EPA direcionar para Lista Mestra.****

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597f7a22900c.png)

 **3.** _**Unidades Gerenciais**_

No cadastro do usuário na aba Unidades Gerenciais selecione na **coluna C** as unidades que o usuário pode se comunicar.  
Essa configuração tem impacto na visão dos documentos que serão disponibilizados, então marque apenas as unidades que estão os documentos que esse usuário pode acessar.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597f88f0f8b6.png)

**4.**  _**Documentos da Qualidade**_

No cadastro do usuário na aba Documentos da Qualidade, selecione apenas os documentos que serão disponibilizados para os colaboradores acessarem através do link.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597f94ae3701.png)

_**5.  _Gerar o link de integração para o site_**_

Após finalizar a configuração do usuário, acesse a aba Integrações e copie o código do campo **Token de integração.**  

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597fc1f01a03.png)

Acesse o módulo de documentos.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597fc7689bc9.png)

Quando carregar a página, copie a URL. No meu exemplo, a URL é _https://atendimento.sysepa.com.br/epa/ge\_doc.php._

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597fcb10389e.png)

Na URL que copiou, após **_ge\_doc.php_**, adicione **_?token=_** e inclua o código do token de integração que copiou do usuário que cadastrou.  
A URL deve ficar dessa forma: **_link da pagina de documentos + ?token= + código do token de integração_**   
Exemplo: _https://atendimento.sysepa.com.br/epa/ge\_doc.php?token=32f06e4a0b33e01b62171001b14f_  
Esse link pode ser incorporado a um site ou intranet, permitindo que os colaboradores acessem os documentos diretamente, sem a necessidade de um usuário e senha específicos.  
O processo de inclusão desse link no site fica sob responsabilidade do cliente ou da equipe responsável pelo gerenciamento do seu site/intranet.

Quando o colaborador clicar no site, ele será direcionado para o link e vai visualizar a tela de Gestão de Documentos e os documentos que foram configurados para serem acessados.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/01/img_6597ffa89e2ef.png)

Também é possível configurar para que o acesso desse usuário, assim o link só poderá ser acessado dentro da empresa.  
Para configurar acesse o artigo [**Bloquear Acesso externo.**](https://wiki.simeon.com.br/usuario-bloquear-acesso-externo/)

**![](https://wiki.simeon.com.br/wp-content/uploads/2022/05/a38addc0469bb9b9bb45550042634c6d-e1684323914567.jpg)**

**Acesse nossos artigos para saber mais sobre Documentos no EPA!  
**

[Papéis e permissões – Documentos](https://wiki.simeon.com.br/papeis-e-permissoes-documentos-2/)

[QR code para acesso aos documentos](https://wiki.simeon.com.br/gestao-de-documentos-qr-code-para-acesso-aos-documentos/)

####  **Qualquer dúvida ou sugestão para aprimoramento, estamos à disposição!  ![](https://wiki.simeon.com.br/wp-content/uploads/2022/02/img_62191d147280f.png)**

---

Fonte: https://wiki.simeon.com.br/link-para-acesso-de-documentos-sem-autenticacao/
