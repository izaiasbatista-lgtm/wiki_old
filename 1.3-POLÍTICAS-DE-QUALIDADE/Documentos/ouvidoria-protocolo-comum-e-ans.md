---
title: "Ouvidoria – Protocolo Comum e ANS"
id: 17254
slug: "ouvidoria-protocolo-comum-e-ans"
url: "https://wiki.simeon.com.br/ouvidoria-protocolo-comum-e-ans/"
data: "2025-05-02T15:13:27"
modificado: "2026-07-29T09:23:28"
pasta: "1.3-POLÍTICAS-DE-QUALIDADE/Documentos"
categorias:
  - "Documentos"
tags:
  - "ANS"
  - "ouvidoria"
  - "protocolo"
  - "Protocolo ANS"
---

# Ouvidoria – Protocolo Comum e ANS
**![](https://wiki.simeon.com.br/wp-content/uploads/2023/05/depositphotos_38689733-stock-photo-giraffe.webp)**

**Neste artigo, vamos falar sobre uma nova funcionalidade no módulo de Ouvidoria. Essa funcionalidade tem como objetivo garantir que todos os registros possuam um número de protocolo único, independentemente da utilização do padrão ANS (Agência Nacional de Saúde). Essa melhoria promove maior rastreabilidade dos registros e mais segurança no compartilhamento de informações, ao evitar a exposição de IDs internos para usuários externos.**

### Geração do Protocolo

-   Se você possui a configuração do protocolo ANS ativa, o sistema seguirá exatamente a mesma regra já utilizada. Para saber como configurar o protocolo ANS acesse **[Ouvidoria: Código padrão ANS para registros de atendimento externo.](https://wiki.simeon.com.br/8668-2/)**
    
-   Para quem não utilizam o protocolo ANS, será gerado automaticamente um número de protocolo do tipo _comum_, utilizando a mesma lógica de hash atualmente aplicada em ocorrências.
    
-   Esse protocolo comum é exclusivo para cada registro e seguirá o mesmo padrão de segurança e integridade.
    

O campo será exibido na tela de **Registro de Atendimento**, localizada em: **Políticas de Qualidade → Ouvidoria → Listar Atendimento → Registro de Atendimento.**

**Veja:**

![](https://wiki.simeon.com.br/wp-content/uploads/2025/05/img_6814f3f5c979b.png)

Na tela do **Registro de Atendimento**, o número de protocolo será exibido em local de destaque, próximo às informações principais do registro. Para facilitar a compreensão dos usuários, os protocolos serão apresentados com nomenclaturas distintas:

-   **Protocolo ANS**: segue o padrão regulatório atual.
    
-   **Protocolo Comum**: gerado automaticamente pelo sistema para demais casos.
    

![](https://wiki.simeon.com.br/wp-content/uploads/2025/03/img_67c87b79c4bf5.png)

---

Fonte: https://wiki.simeon.com.br/ouvidoria-protocolo-comum-e-ans/
