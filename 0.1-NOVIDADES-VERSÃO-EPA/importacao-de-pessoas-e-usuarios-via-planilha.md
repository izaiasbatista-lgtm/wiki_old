---
title: "Importação de Pessoas e Usuários via Planilha"
id: 17220
slug: "importacao-de-pessoas-e-usuarios-via-planilha"
url: "https://wiki.simeon.com.br/importacao-de-pessoas-e-usuarios-via-planilha/"
data: "2025-04-28T15:28:28"
modificado: "2025-04-28T15:33:19"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Importação de Pessoas e Usuários via Planilha
**1\. Importar Pessoas:**

O sistema tem a funcionalidade de importar pessoas para cadastro em massa de pessoas e ainda permite já criar um usuário para cada uma das pessoas importadas, facilitando o cadastro e a manutenção dos seus dados caso seja necessário realizar alguma alteração.

**1.1 Escolha a Chave de Validação**

Para importar cadastro de pessoas e/ou usuários através de planilha deve-se acessar a tela de importação:

Parametrização → Portal → Cadastro de Pessoas → Importação de Pessoas

A primeira informação a ser preenchida é a escolha de uma chave de validação (obrigatória), que vai verificar se a pessoa já está ou não cadastrada no sistema. Caso o sistema verifique que a informação definida como chave de validação não está preenchida no sistema, ele realiza o cadastro de pessoa com as informações preenchidas na planilha. Caso o sistema identifique que a informação da chave de validação já está preenchida no sistema, ele atualiza as informações do cadastro de pessoa com as informações preenchidas na planilha, mantendo aquelas informações que permanecem iguais.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc4ef6804b.png)

Figura 1  
   
O sistema oferece quatro opções de chaves:

-   E-mail ou Celular (Indicado para NPS): o sistema verifica se a informação preenchida no campo e-mail ou celular já está cadastrada no sistema. Nessa opção o sistema irá validar apenas uma das informações;

-   Nome e Celular: o sistema verifica se as informações nome e celular já estão cadastradas no sistema. Nessa opção o sistema irá validar as duas informações juntas. Portanto, mesmo que o nome seja igual, por exemplo, se o celular for diferente, o sistema irá considerar pessoas diferentes;

-   Matrícula: o sistema irá verificar a informação preenchida no campo matrícula. Caso o número de matrícula não esteja cadastrado no sistema, ele irá cadastrar a pessoa. Caso já esteja cadastrado o sistema irá atualizar as informações da pessoa;

-   Origem e Código Externo (Indicado para Importação de Pessoas): o sistema verifica se as informações origem e código externo já estão cadastradas no sistema. Nessa opção o sistema irá validar as duas informações juntas. Portanto, mesmo que a origem seja igual, por exemplo, se o código externo for diferente, o sistema irá considerar pessoas diferentes.

OBS: o campo matrícula permite apenas o preenchimento numérico.

**1.2 Layout Disponível**

O sistema oferece um layout para escolha das informações que deseja importar.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc5a2998c3.png)

Figura 2

O usuário pode escolher quantas e quais informações quer importar. A informação definida como chave de validação fica selecionada como obrigatória, assim como o “Nome” que já é padrão do sistema.

Algumas informações precisam ser preenchidas de acordo com a orientação do campo, como as informações destacadas acima (“0” para Pessoa Física, “1” para pessoa jurídica, data de nascimento no formato dd/mm/yyyy, “F” para Feminino, “M” para Masculino etc.).

O sistema irá cadastrar como um parâmetro novo caso tenha alguma informação nova na planilha, como por exemplo o cargo. Caso o cargo listado na planilha seja diferente dos que foram cadastrados anteriormente, ele irá cadastrar como um cargo novo e irá adicionar na listagem.

O sistema também permite já definir um usuário e uma senha para o cadastro de pessoa, realizando assim duas atividades de uma vez só através da importação. Isso substitui a atividade manual de cadastrar pessoas e só depois criar os seus usuários.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc63266f3b.png)

Figura 3

Outra informação que o sistema permite é o do tipo de fornecedor (quando realizada a importação para cadastro de fornecedores) fazendo com que o fornecedor já seja vinculado ao seu tipo correspondente na planilha. Isso também substitui a atividade manual de cadastrar pessoas, cadastrar o tipo de fornecedor e só depois fazer o vínculo entre eles.

OBS: não é permitido aplicar fórmulas no preenchimento da planilha. Caso tenha, o sistema irá identificar um erro nas linhas onde a fórmula foi configurada e o cadastro dessas informações não será realizado.

**1.3 Exemplo de Arquivo**

Ao selecionar as informações que deseja importar o sistema gera um exemplo de arquivo que deve ser seguido na hora do preenchimento:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc663a9e9a.png)

Figura 4

A planilha utilizada na importação deve ser preenchida exatamente nessa mesma ordem pois o sistema irá cadastrar as informações de acordo com as colunas da planilha e do modelo criado. Por exemplo: se no exemplo de arquivo eu tenho o nome sendo a primeira coluna, na planilha, a informação que for preenchida na primeira coluna será levada para o campo nome. Caso no preenchimento as colunas estejam invertidas, o sistema irá cadastrar as informações nos campos errados.

**1.4 Selecione o Arquivo**

Após o preenchimento da planilha, a mesmo deve ser selecionada no botão de selecionar planilha e deve-se ainda selecionar qual a unidade de origem das pessoas importadas:

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc696d8bb3.png)

Figura 5

O sistema ainda permite selecionar o status dos clientes, selecionar um perfil para vincular aos usuários preenchidos na planilha e marcar a opção para alterar senha no primeiro acesso (permitindo o usuário alterar sua senha padrão criada na planilha para uma senha pessoal).  
Ao selecionar essas informações, basta clicar em “Realizar Importação”.

**2\. Visualizar Cadastro de Pessoas**

Para visualizar o cadastro das pessoas importadas na planilha o usuário pode acessar a tela de “Pesquisar” e assim acessar o cadastro da pessoa, ou através do ícone da “Lupa” na parte superior do sistema:

Engrenagem / Portal / Cadastro de Pessoas / Pesquisar

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc72ecf5b2.png)

Figura 6

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc73abf507.png)

Figura 7

**3\. Visualizar Usuário**

Para visualizar o cadastro dos usuários importados na planilha, o usuário pode acessar a tela de “Gerenciar Usuário”:

Parametrização / Usuários / Gerenciar Usuário

![](https://wiki.simeon.com.br/wp-content/uploads/2025/04/img_680fc7dc8e80e.png)

Figura 8

---

Fonte: https://wiki.simeon.com.br/importacao-de-pessoas-e-usuarios-via-planilha/
