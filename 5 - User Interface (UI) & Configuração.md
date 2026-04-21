## User Interface (UI) & Configuração

A interface é o ponto de entrada para usuários e administradores.  
A personalização garante que a plataforma atenda à identidade visual e às necessidades operacionais da empresa.

* **Branding & Personalização:** Alteração de logotipos, cores corporativas e banners globais através de **System Properties**.  
* **Listas e Formulários:**
    * **Listas:** Exibição de registros com suporte a filtros complexos e personalização de colunas.
    * **Formulários:** Visualização de registros individuais. 
* **Ferramentas:** Diferença entre o **Form Designer** (interface drag-and-drop) e o **Form Layout** (interface de lista de campos).
* **Plugins:** Extensões de software que adicionam funcionalidades específicas à instância. Devem ser ativados conforme a necessidade de negócio.

---

## 2. Gestão de Dados (O "Coração" da Plataforma)

A base de dados do ServiceNow é o que sustenta todas as aplicações e fluxos de trabalho.

* **Tabelas e Campos:**
    * **Tabelas do Sistema:** Nativas da plataforma (ex: `sys_user`).
    * **Tabelas Customizadas:** Criadas pelo desenvolvedor (prefixo `u_`).
    * **Tabelas Estendidas:** Tabelas que herdam campos de uma tabela pai (ex: `Incident` estende `Task`).
* **Dicionário de Dados:** Repositório central que define as propriedades, regras e tipos de cada campo no sistema.
* **Import Sets & Transform Maps:**
    * **Import Sets:** Ferramenta para importar dados de fontes externas (Excel, XML, JDBC).
    * **Transform Map:** Define a relação entre os campos de origem e os campos de destino no ServiceNow.
    * **Coalesce:** Campo chave utilizado para evitar a criação de registros duplicados durante a importação (atualiza se já existir).
* **CMDB (Configuration Management Database):** Base de dados que armazena os **Configuration Items (CIs)** e rastreia as relações complexas entre eles (ex: qual servidor sustenta qual aplicação).

---

## 3. Automação e Lógica de Negócio

Define como o sistema se comporta e automatiza processos para reduzir o trabalho manual.

* **UI Policies vs. Data Policies:**
    * **UI Policy:** Executada no **Client-side** (navegador). Controla visibilidade, obrigatoriedade e leitura de campos na interface.
    * **Data Policy:** Executada no **Server-side**. Garante a integridade dos dados independente da entrada (mesmo via importação ou Web Services).
* **Business Rules:** Scripts do lado do servidor executados quando um registro é exibido, inserido, atualizado ou deletado.
* **Client Scripts:** JavaScript executado no navegador do usuário para interações em tempo real (ex: alertas ou preenchimento automático).
* **Flow Designer:** Interface low-code para criação de fluxos de automação. Composto por **Triggers** (gatilhos) e **Actions** (ações).

---

## 4. Self-Service e Suporte

Focado na experiência do usuário final e na democratização do conhecimento.

* **Service Catalog:** Portal para solicitação de serviços e produtos.
    * **Catalog Items:** O item que o usuário solicita.
    * **Variables:** Perguntas feitas no formulário de solicitação.
    * **Record Producers:** Formulários que, ao serem enviados, criam registros em tabelas específicas (ex: criar um Incidente a partir do Portal).
* **Knowledge Management:** Gestão de artigos de ajuda. Segue o ciclo: **Criação** -> **Revisão** -> **Publicação** -> **Aposentadoria**.

---

## 5. Governança e Desenvolvimento

Garante que o desenvolvimento seja seguro, organizado e auditável.

* **Update Sets:** Grupos de alterações de configuração que podem ser movidos entre instâncias (DEV > TEST > PROD). 
    * *Nota:* Capturam configurações (regras, campos), mas **não** capturam dados transacionais (incidentes, usuários novos).
* **User & Access:**
    * **Usuários:** Contas individuais.
    * **Grupos:** Conjuntos de usuários (ex: Service Desk).
    * **Roles (Papéis):** Permissões atribuídas a grupos. *Best Practice:* Usuário > Grupo > Role.
* **ACL (Access Control Lists):** Regras de segurança que definem permissões de acesso (CRUD - Create, Read, Update, Delete) em nível de tabela ou campo.

---

## 📋 Tabela de Comparação Rápida

| Funcionalidade | Onde Roda? | Principal Objetivo |
| :--- | :--- | :--- |
| **Client Script** | Browser (Cliente) | Interação imediata com o usuário no formulário. |
| **Business Rule** | Servidor | Lógica de banco de dados e processamento de dados. |
| **UI Policy** | Browser (Cliente) | Dinâmica visual e interativa do formulário. |
| **Update Set** | Entre Instâncias | Migração de desenvolvimento e configurações. |

---

👉🏻 [Clique aqui para voltar ao Readme](https://github.com/DrikaDev/ServiceNow-CSA/blob/main/README.md)📒

---
