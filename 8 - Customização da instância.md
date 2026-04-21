## Customização da instância

Na certificação CSA e no dia a dia de um desenvolvedor ServiceNow, "Customização" é um tema sensível.  
Existe um mantra na plataforma: **"Configuration over Customization" (Configuração antes de Customização)**.  

É importante entendermos a diferença entre os dois. Isso demonstra que pensamos na manutenção a longo prazo da instância.  

## 🛠️ Configuração vs. Customização

Para garantir que a plataforma seja sustentável e fácil de atualizar (upgrades), sigo a diretriz de priorizar ferramentas nativas antes de partir para o 
desenvolvimento de código personalizado.  

- Configuração (Low-Code/No-Code): Refere-se ao uso de ferramentas nativas para alterar o comportamento do sistema sem mudar o código base.  
  **Exemplos:** UI Policies, simplificação de formulários, criação de campos, Flow Designer e regras de visibilidade.  
  **Vantagem:** Não quebra durante upgrades de versão (ex: de Washington para a próxima release).  

- Customização (Pro-Code): Envolve a escrita de scripts (JavaScript) ou alterações profundas no core da plataforma para atender requisitos que o
  "out-of-the-box" (OOTB) não suporta.  
  **Exemplos:** Client Scripts complexos, Business Rules avançadas e Script Includes.  
  **Atenção:** Exige testes rigorosos durante cada ciclo de upgrade da ServiceNow.  

### 👉🏻 Abordagem Técnica: 
Buscar sempre a solução OOTB (Out-of-the-box) primeiro.  
Se o requisito de negócio exigir uma customização, ela deve ser devidamente documentada e isolada em **Scoped Applications** para minimizar riscos à 
integridade global da instância.  

### Por que isso é importante para a CSA?
- **Conceito de Upgradeability:** A ServiceNow foca muito em **"Upgradeability"** (capacidade de ser atualizado).  
  Se você customiza demais, o upgrade vira um pesadelo. Colocar isso na documentação mostra que você tem visão estratégica.

- **Uso de Scoped Apps:** Mencionar que você prefere customizar dentro de um "escopo" prova que você sabe proteger a instância de erros globais.  

- **Dica para a Prova CSA:** A prova costuma perguntar quais ferramentas são de configuração (UI Policy, Form Layout) e quais permitem customização
  (Business Rule, Client Script).  

> No projeto **Toy Store** usei um Flow Designer em vez de um Workflow antigo ou um Script pesado:  
"Optei pelo uso de Flow Designer (Configuração) em vez de Business Rules customizadas para facilitar a manutenção e garantir a compatibilidade com futuras 
versões do ServiceNow."  
Isso mostra como sou uma desenvolvedora consciente e moderna!

---

👉🏻 [Clique aqui para voltar ao Readme](https://github.com/DrikaDev/ServiceNow-CSA/blob/main/README.md)📒

---
