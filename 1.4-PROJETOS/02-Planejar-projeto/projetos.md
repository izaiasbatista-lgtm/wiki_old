---
title: "Projetos – Configuração para tarefas dependentes (T-I)"
id: 8038
slug: "projetos"
url: "https://wiki.simeon.com.br/projetos/"
data: "2021-08-13T09:58:57"
modificado: "2024-09-18T16:34:50"
pasta: "1.4-PROJETOS/02-Planejar-projeto"
categorias:
  - "02- Planejar projeto"
tags:
  - "projetos"
  - "tarefas com predecessoras"
  - "tarefas de projeto"
---

# Projetos – Configuração para tarefas dependentes (T-I)
![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/img_60f9af23432dd-213x300.png)

Nessa versão, uma das funcionalidades das tarefas no módulo de projetos ganhou uma nova configuração!

-   -   -   -   -   -   -   -   **A funcionalidade (T-I , término e início) usada para informar ao sistema quando uma tarefa possui dependência para ser iniciada, conta agora com uma funcionalidade que ajusta datas e informa ao projeto no EPA para não contabilizar atraso em atividades** **dependentes****, isso quando sua tarefa predecessora estiver com data de conclusão em atraso.**
                    -    
                        -   -   **Com isso, o sistema ao detectar atraso na tarefa que é predecessora no projeto, ajustará a data da tarefa sucessora para o próximo dia e assim a tarefa sucessora não é contabilizada com atraso.**
                    -    
                        -   -   **Essa melhoria traz uma melhor gestão sobre a finalização das tarefas que possuem dependência e suas datas proposta no projeto!**

Veja como utilizar essa melhoria!

⇒ Primeiramente você deverá selecionar a configuração que ativa essa funcionalidade, vá até a página: 

**Aba Iniciação**\> **Informações básicas**\> _Selecione o check:_ **_Ativar reprogramação automática das atividades que utilizam predecessora T-I (termino-início) – quando a predecessora estiver atrasada._**

Veja:

![](https://wiki.simeon.com.br/wp-content/uploads/2021/08/img_611fa5c02c229.png)

**1 – Em Projetos> Gestão de Projetos:** acesse e edite o projeto que você deseja configurar para que o EPA  “Reprograme automaticamente as datas das  atividades/tarefas que utilizam como predecessora T-I (termino-início), quando a tarefa predecessora estiver atrasada.

**2 –** Após ativar a configuração, as tarefas do projeto que utilizam a configuração de (T-I) término inicio, irão obedecer o ajuste de atualização das datas das tarefas sucessoras, para que elas não sejam classificadas como atrasadas quando a atividade predecessora estiver com das datas em atraso.

Veja um exemplo:

-   -   -   Na ilustração abaixo, a tarefa _**24104 – Alinhar escopo da base de conhecimento,**_ não foi concluída e está **atrasada**, segundo a data planejada…

-   -   -   A tarefa **24220 – Propor padrão de escrita/conteúdo**, possui a configuração T-I, predecessora da tarefa acima: 24104. O EPA alterou a data início da presente tarefa (24220) para o próximo dia, para que ela não seja classificada e apresentada como atrasada.

Veja: 

![](https://wiki.simeon.com.br/wp-content/uploads/2021/08/img_611fa7381032f.png)

![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/img_60f9af23432dd-e1629464574925-213x300.png)

> **Observação**:
> 
> -   -   Ao utilizar essa funcionalidade, você precisará estar ciente que a _**data final**_ do projeto poderá sofrer alteração, pois houve reprogramação/atualização de datas das tarefas de projeto, caso ocorra o cenário citado acima.
> -    
>     -   Caso não selecione esta configuração para ajuste de datas de tarefas dependentes, as tarefas de projeto seguirão o fluxo normal,  já utilizado em versões anteriores.

**Importante:**  Na configuração da tarefa **Predecessora** tem algumas siglas que referem ao tipo de **dependência** entre duas tarefas.

![](https://wiki.simeon.com.br/wp-content/uploads/2024/09/img_66eb218f671e2.png)

Aqui está o significado de cada combinação:

1.  **T-T (Término a Término)**: A tarefa sucessora só pode terminar quando a tarefa predecessora terminar. Ou seja, o término de uma tarefa depende do término de outra.
    
    -   Exemplo: A revisão final de um relatório (tarefa sucessora) só pode terminar quando a escrita do relatório (tarefa predecessora) terminar.
2.  **I-I (Início a Início)**: A tarefa sucessora só pode começar quando a tarefa predecessora começar. Elas precisam iniciar juntas ou a sucessora iniciar após a predecessora.
    
    -   Exemplo: A tarefa de teste (sucessora) pode começar apenas quando o desenvolvimento do software (predecessora) começar.
3.  **T-I (Término a Início)**: A tarefa sucessora só pode começar quando a tarefa predecessora terminar. Esta é a dependência mais comum em cronogramas de projetos.
    
    -   Exemplo: A tarefa de iniciar o marketing (sucessora) só pode começar após o término da criação do produto (predecessora).
4.  **I-T (Início a Término)**: A tarefa sucessora só pode terminar quando a tarefa predecessora começar. Esse tipo de dependência é menos comum.
    
    -   Exemplo: A tarefa de suporte ao cliente (sucessora) só pode terminar quando a nova equipe de suporte começar a trabalhar (predecessora).

![](https://wiki.simeon.com.br/wp-content/uploads/2021/07/istockphoto-921459570-612x612-1-e1626985188707-167x300.jpg)

> **Artigos Relacionados:**
> 
> [Projetos – Definir horário para execução das tarefas de projeto no EPA](https://wiki.simeon.com.br/projetos-campos-hora-inicio-e-hora-fim-inserido-nas-tarefas-de-projeto/)
> 
> [Projetos – Classificação das tarefas de projeto.](https://wiki.simeon.com.br/projetos-classificacao-das-tarefas-de-projeto/)
> 
> [Projetos – Box para acompanhar Tarefas que eu preciso gerenciar](https://wiki.simeon.com.br/projetos-box-para-acompanhar-tarefas-que-eu-preciso-gerenciar/)
> 
> [Projetos – Detalhes informações de Tarefas de Projetos](https://wiki.simeon.com.br/projetos-detalhes-informacoes-de-tarefas-de-projetos/)

#### **Aproveite essa melhoria !**

#### **Qualquer dúvida ou sugestão para aprimoramento, estamos a disposição!**

#### ![](https://wiki.simeon.com.br/wp-content/uploads/2020/08/logo-epa.png)

---

Fonte: https://wiki.simeon.com.br/projetos/
