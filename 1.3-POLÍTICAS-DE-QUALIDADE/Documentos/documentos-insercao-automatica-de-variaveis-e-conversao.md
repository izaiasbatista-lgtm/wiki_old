---
title: "Documentos – Inserção Automática de Variáveis e Conversão em PDF"
id: 16364
slug: "documentos-insercao-automatica-de-variaveis-e-conversao"
url: "https://wiki.simeon.com.br/documentos-insercao-automatica-de-variaveis-e-conversao/"
data: "2025-02-25T12:00:33"
modificado: "2025-11-26T16:47:32"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Documentos"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
  - "Documentos"
tags:
  - "conversão arquivo PDF"
  - "Converter Download do Documento em PDF"
  - "converter pdf"
  - "variáveis"
  - "variavel"
---

# Documentos – Inserção Automática de Variáveis e Conversão em PDF
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**A gestão eficiente de documentos é essencial para garantir a precisão das informações. Para otimizar esse processo, fizemos a implementação de funcionalidades que permitem a inserção automática de variáveis nos documentos, além de um processo de conversão automática de arquivos editáveis para PDF.**

**As melhorias podem ser encontradas ao acessar: Políticas da Qualidade → Documentos → Gestão de Documentos**. Ao adicionar um novo documento e preencher as informações básicas, a tela exibirá as seguintes opções:

![](https://wiki.simeon.com.br/wp-content/plugins/image-elevator/assets/admin/img/circle-preloader.gif)

## **Inserção automática de variáveis**

Variáveis como código, versão, data, autor e outras informações relevantes são automaticamente inseridas nos documentos conforme a escolha do usuário, garantindo maior consistência e precisão. Além disso, o processo de conversão automática de arquivos editáveis para PDF está disponível, eliminando a duplicidade de arquivos e facilitando o controle das versões. Para maior flexibilidade, oferecemos a opção de selecionar o formato de leitura de um documento, seja em PDF ou editável, permitindo que formulários e outros documentos que necessitam de edição sejam mantidos em formatos apropriados.

## **Conversão do Documento escolhido**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/02/img_67bdd8c8135fd.png)

-   Se o **usuário** marcar “Sim”, o documento será convertido automaticamente.
-   Se o **usuário** marcar “Não”, aparecerá um campo de input para anexar o PDF manualmente.
-   Caso o **usuário** insira um documento com uma extensão não permitida e marque “Sim”, uma mensagem de erro será exibida.

Além disso, documentos com as extensões permitidas serão automaticamente convertidos em PDF para visualização, caso a opção _“Converter Download automaticamente em PDF”_ esteja marcada como “Sim”. Para arquivos com extensões não permitidas, o **usuário** deverá anexar o arquivo em PDF para visualização, já que o sistema não realizará a conversão automaticamente.

## **Utilização das variáveis**

Segue a lista das opções das variáveis dos documentos:

<table class="table table-striped" bgcolor=""><tbody><tr bgcolor=""><td>{{categoria}}</td><td>Categoria</td></tr><tr bgcolor=""><td>{{unidade_gerencial}}</td><td>Unidade Gerencial</td></tr><tr bgcolor=""><td>{{codigo}}</td><td>Código</td></tr><tr bgcolor=""><td>{{titulo}}</td><td>Título</td></tr><tr bgcolor=""><td>{{elaborador}}</td><td>Elaborador</td></tr><tr bgcolor=""><td>{{gestor}}</td><td>Gestor do Documento</td></tr><tr bgcolor=""><td>{{responsavel}}</td><td>Responsável pelo Documento</td></tr><tr bgcolor=""><td>{{data_criacao}}</td><td>Data da Criação do Documento</td></tr><tr bgcolor=""><td>{{data_validade}}</td><td>Data de Validade</td></tr><tr bgcolor=""><td>{{versao}}</td><td>Número da versão</td></tr><tr bgcolor=""><td>{{revisor}}</td><td>Nome do(s) Revisor(es)</td></tr><tr bgcolor=""><td>{{data_revisao}}</td><td>Data da Revisão</td></tr><tr bgcolor=""><td>{{aprovador}}</td><td>Nome do(s) Aprovador(es)</td></tr><tr bgcolor=""><td>{{data_aprovacao}}</td><td>Data da Aprovação</td></tr><tr bgcolor=""><td>{{data_criacao_versao}}</td><td>Data Criação da Versão</td></tr><tr bgcolor=""><td>{{nome_cargo_resivor}}</td><td>Nome e Cargo do(s) Revisor(es)</td></tr><tr bgcolor=""><td>{{nome_cargo_aprovador}}</td><td>Nome e Cargo do(s) Aprovadores(es)</td></tr></tbody></table>

Para utilizar essas variáveis, basta copiar o código correspondente e inseri-lo no documento desejado. O sistema se encarregará de preencher as informações automaticamente.

**Limitações da Conversão de Arquivos para PDF**

O EPA utiliza um serviço externo para converter arquivos em PDF. Esse serviço possui  algumas limitações, portanto alguns elementos do arquivo original podem não ser convertidos corretamente.

Componentes que podem não aparecer ou não manter o formato original:  
• Caixas de seleção, botões e listas suspensas  
• Formas e desenhos, como blocos, setas, ícones e SmartArt  
• Macros e códigos internos  
• Objetos conectados a fontes externas, como tabelas dinâmicas ou vínculos externos  
• Elementos interativos ou com validações avançadas  
• Conteúdos posicionados fora da área de impressão  
• Impressões configuradas com múltiplas áreas ou escalas específicas  
• Fontes não disponíveis na ferramenta de conversão, que podem ser substituídas  
• Arquivos protegidos por senha ou com restrições de edição

![](https://wiki.simeon.com.br/wp-content/uploads/2025/02/img_67bdd36f041f0.png)

---

Fonte: https://wiki.simeon.com.br/documentos-insercao-automatica-de-variaveis-e-conversao/
