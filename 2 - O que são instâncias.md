## Instâncias

São ambientes separados para desenvolvimento, teste e produção. Isso ajuda a evitar impactos nos usuários em produção durante alterações.

## Gerenciamento de Instâncias e Ciclo de Vida (SDLC)

O desenvolvimento no ServiceNow é realizado através de instâncias isoladas para garantir a integridade dos dados e a continuidade do negócio.  

O fluxo padrão seguido neste projeto foi:  

- Desenvolvimento (DEV): Ambiente destinado à criação de novas funcionalidades, configurações de regras de negócio e automações (Flow Designer).  
  É onde as Update Sets são geradas.

- Teste/Homologação (TEST/QA): Espaço para validação das soluções por analistas de qualidade e usuários finais (UAT - User Acceptance Testing).
  O objetivo é garantir que os requisitos técnicos e funcionais foram atendidos sem bugs.

- Produção (PROD): O ambiente "vivo", onde os usuários finais operam.  
  Alterações só são movidas para cá após aprovação rigorosa nos ambientes anteriores.  

### 👉🏻 Boas Práticas Aplicadas: 
Este isolamento previne que erros de script ou configurações incompletas afetem a operação real da empresa, permitindo uma governança de TI eficiente e segura.  
Trabalhe sempre respeitando o fluxo de instâncias para garantir que qualquer erro seja capturado em DEV ou TEST, nunca chegando ao usuário final em PROD.  

---

👉🏻 [Clique aqui para voltar ao Readme](https://github.com/DrikaDev/ServiceNow-CSA/blob/main/README.md)📒

---
