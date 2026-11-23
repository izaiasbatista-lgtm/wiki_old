---
title: "Versão 191"
id: 17188
slug: "versao-191"
url: "https://wiki.simeon.com.br/versao-191/"
data: "2025-04-28T08:50:55"
modificado: "2025-05-20T16:10:45"
pasta: "0.1-NOVIDADES-VERSÃO-EPA"
categorias:
  - "0.1 -NOVIDADES VERSÃO EPA"
tags:
---

# Versão 191
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Confira o vídeo com as atualizações da nova versão e leia abaixo todas as novidades da versão 191.1**

[https://wiki.simeon.com.br/wp-content/uploads/2025/04/191-video-.mp4](https://wiki.simeon.com.br/wp-content/uploads/2025/04/191-video-.mp4)

**Release 191.1:**

### **Portal – Armário Virtual**

Foi adicionada a exibição do nome e do CNPJ na caixa de Documentos Vencidos e Próximos do Vencimento, facilitando a identificação dos fornecedores. No relatório “Gerenciar Vencimento”, a coluna de CNPJ foi incluída e é exibida apenas para pessoas jurídicas. Essa coluna permanece oculta por padrão, podendo ser exibida conforme a necessidade. As melhorias tornam a análise e a gestão documental mais práticas e eficientes.

### **Portal – Fornecedores**

Foi incluída uma nova coluna “Unidade Gerencial” na tabela de Avaliações da aba “Pesquisas” no cadastro de pessoas, permitindo visualizar a unidade selecionada pelo avaliador no momento da resposta. Com essa melhoria, torna-se mais fácil segmentar e analisar os dados das pesquisas por unidade, agilizando o envio de feedbacks direcionados aos fornecedores e fortalecendo a tomada de decisões com base em informações mais precisas e organizadas.

### **Portal- Pesquisas**

Foi adicionada uma nova coluna com o CNPJ do participante na exportação do relatório “Exportar Respostas em Excel”, disponível na tela de resultados da pesquisa. A coluna exibe o CNPJ apenas quando o participante for uma pessoa jurídica, mantendo o campo vazio nos demais casos. Essa melhoria facilita a identificação precisa dos fornecedores nas análises externas, tornando o processo mais ágil e confiável para os gestores de qualidade.  

### **Políticas da Qualidade – Ouvidoria**

Foi inserido um botão de visualização no “Histórico de E-mails” que permite ao usuário visualizar o conteúdo completo do e-mail enviado, diretamente na plataforma. Ao clicar em “Visualizar”, o sistema abre um modal exibindo o corpo da mensagem, e, caso o e-mail possua anexos, apenas os nomes dos arquivos são mostrados, sem links para download. Essa melhoria facilita o acompanhamento das interações com os clientes, sem necessidade de acessar outras telas ou sistemas, tornando o processo mais ágil e centralizado.

Os e-mails enviados pelo módulo de Ouvidoria foram padronizados, com o título alterado para incluir o número do protocolo correto, substituindo a identificação do assunto. A cor da linha azul foi trocada para cinza (#E1E1E1) em todos os e-mails. No e-mail de acompanhamento, foi removida a identificação do usuário e adicionados campos como Cliente, Tipo, Descrição do Atendimento e Acompanhamento, enquanto o campo “Horas” foi excluído, melhorando a clareza e consistência das comunicações.

Agora, a data e hora da resposta ao cliente são inseridas automaticamente no link externo de consulta do protocolo de ouvidoria, assim que a resposta é salva. Isso elimina a necessidade de preenchimento manual dessa informação, garantindo precisão no acompanhamento, independentemente de o e-mail ter sido enviado ou não. A melhoria facilita o processo e assegura que o registro de tempo da resposta esteja sempre atualizado no link externo de consulta.

Foram feitos ajustes na tela de Parecer U.N., incluindo o reposicionamento dos campos “Procedente” e “Improcedente”, e a inclusão do campo obrigatório “Parecer Aprovado?” para melhorar a navegação e a clareza. Também foi alterada a coluna “Fase” na listagem de atendimento para diferenciar melhor os registros “Aguardando parecer” e “Aguardando validação do parecer”. A opção “Agendar Alerta Tela Principal do Analista de Ouvidoria” foi removida, simplificando o processo.

A lógica de exibição da box “Informar a conclusão e finalizar o atendimento” no processo de Ouvidoria foi ajustada para considerar diferentes cenários. O item será exibido se houver parecer aprovado da unidade notificada, ou se houver solicitações e ocorrências concluídas, ou ainda, se o campo “Conclusão da Ouvidoria” estiver preenchido. Esse ajuste visa garantir que a finalização do atendimento aconteça conforme o processo correto.

O fluxo de atendimentos registrados pelo formulário externo de ouvidoria foi ajustado, com a renomeação da fase para “Validar Atendimento” e a criação de uma nova caixa para exibição desses registros na aba “Analista de Ouvidoria”. Os atendimentos sem responsável foram removidos da caixa “Aguardando Parecer”. A partir de agora, ao registrar um atendimento, o responsável pelo parecer será deixado em branco até o analista preencher as informações necessárias, garantindo um processo mais claro e organizado.

Foi implementado um campo de upload de anexos na aba “Conclusão”, dentro da seção “Resposta ao Cliente”, permitindo o envio desses anexos por e-mail ao cliente. Quando anexados, os arquivos são listados no corpo do e-mail, com a possibilidade de download direto. A funcionalidade também inclui uma limitação de 25MB por arquivo e validações de tamanho e formato antes do envio, proporcionando maior agilidade e rastreabilidade no processo de retorno ao cliente.

Agora, todos os registros de ouvidoria terão um número de protocolo gerado automaticamente, seja pelo protocolo ANS ou por um protocolo comum. O sistema garantirá que cada registro tenha um número único, gerado conforme a configuração do cliente, e exibirá essa identificação de maneira clara, proporcionando rastreabilidade e maior segurança no processo.

A nova parametrização foi implementada no sistema EPA, permitindo ao usuário escolher um campo chave obrigatório no formulário externo da Ouvidoria, podendo selecionar entre Matrícula/Número do Cartão, E-mail ou CNPJ/CPF. O campo escolhido será exibido como o primeiro item no formulário e marcado como obrigatório, com um asterisco vermelho.

### **Projetos** 

Foram ajustadas as colunas “Saldo” e “% Realizado” na tabela Horas RH para considerar apenas seus dados, e adicionados totalizadores para “Valor Custo por Hora”, “Horas Previstas” e “Horas Reais”. Dois relatórios personalizados foram criados: um para a tabela Horas RH e outro para a Análise de Custo, ambos em PDF e acessíveis apenas para usuários autorizados. Esses ajustes proporcionam maior precisão nos dados e facilitam a análise de custos, garantindo informações mais claras e eficientes para a tomada de decisões.

A forma de cálculo dos gráficos e tabelas foi padronizada, agora exibindo “Percentual do projeto concluído”, “Percentual de desvio do projeto” e “Percentual de previsão do projeto”. A tabela “Desempenho do Projeto” teve suas colunas renomeadas para “% Previsto”, “% Executado” e “% Desvio”. A padronização das nomenclaturas e ajustes nos gráficos e tabelas garantem as boas práticas de gerenciamento de projetos, facilitando o acompanhamento do desempenho do projeto.

### **Planejamento – Indicadores**

A lógica do ícone de projetos no Painel de Indicadores foi ajustada para exibir no modal apenas os projetos cuja etapa selecionada esteja dentro do intervalo entre a data de início e fim do projeto, e a mensagem exibida ao passar o cursor foi atualizada para refletir essa nova regra. A mudança melhora a precisão das informações apresentadas, tornando a análise mais coerente com o período vigente do projeto.

### **Políticas da Qualidade – Ocorrências**

Foram incluídos os campos “Tipo de Impacto” e “Grau do Impacto” nos filtros da tela de Gestão de Ocorrências, com suporte a seleção múltipla, além da adição da coluna “Grau do Impacto” na listagem de ocorrências (oculta por padrão). Os campos e a coluna são exibidos apenas para clientes com a configuração RN518. Essa melhoria permite filtrar e priorizar ocorrências com maior criticidade de forma mais eficaz.

### **Políticas da Qualidade – Documentos**

Foi solicitada a alteração para que o sistema envie apenas um e-mail diário ao responsável pelo documento, consolidando todas as notificações de documentos em um único envio, em vez de enviar um e-mail por documento. Isso visa melhorar a eficiência e reduzir o número de e-mails enviados ao responsável.  

### **Portal – Reuniões**

Foi implementada a funcionalidade no aplicativo EPA, permitindo que o usuário assine a ata de reunião diretamente no módulo de reuniões. Foi adicionado um botão para assinatura na tela da reunião, e o sistema exige que o usuário forneça login e senha antes de permitir a assinatura. Apenas usuários autorizados podem assinar a ata, garantindo a segurança do processo.

![](https://wiki.simeon.com.br/wp-content/uploads/2025/02/img_67ba7b04f0f89.png)

---

Fonte: https://wiki.simeon.com.br/versao-191/
