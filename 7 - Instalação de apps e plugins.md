## 🔌Instalação de apps e plugins

O ServiceNow é uma plataforma modular.  
Para adicionar novas funcionalidades sem a necessidade de desenvolvimento do zero, utilizamos o gerenciamento de aplicações e plugins.  

- Plugins: São componentes de software que ativam recursos específicos dentro da instância (ex: Service Portfolio Management ou Discovery).  
  A maioria dos plugins nativos é ativada via **Plugin Inventory**.  
  Alguns plugins de alta complexidade exigem ativação através do portal de suporte (Now Support).  

- Aplicações (Store Apps): São soluções completas desenvolvidas pela ServiceNow ou parceiros certificados, disponíveis na ServiceNow Store.  
  Elas permitem uma implementação mais rápida de soluções verticais (ex: integrações prontas com Microsoft Teams ou SAP).  

- Application Cross-Scope: Ao instalar ou desenvolver apps, o sistema utiliza o **Scope** para garantir que uma aplicação não interfira nos dados ou
  scripts de outra, garantindo a estabilidade da instância.  

### 👉🏻 Boas Práticas de Implementação: 
Sempre ative e teste plugins primeiramente em instâncias de Desenvolvimento (PDI/DEV).  
Alguns plugins não podem ser desativados após a ativação, por isso a análise de impacto é uma etapa crítica do **SOP (Procedimento Operacional Padrão)**.  

---

👉🏻 [Clique aqui para voltar ao Readme](https://github.com/DrikaDev/ServiceNow-CSA/blob/main/README.md)📒

---
