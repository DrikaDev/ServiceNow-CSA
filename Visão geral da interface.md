## Visão geral da interface da plataforma do usuário do ServiceNow (Xanadu)

## A interface do usuário do ServiceNow possui dois componentes:  

- Banner  
- Quadro de conteúdo

### Banner 
O banner ocupa a parte superior de todas as páginas.  
Ele contém um logotipo, menus de navegação, o título da página no quadro de conteúdo, pesquisa global, ajuda, notificações e um menu do usuário.  

<img width="669" height="141" alt="image" src="https://github.com/user-attachments/assets/06953729-1932-4792-b4b7-f32609f6eec0" />

Use os menus de navegação do banner para acessar aplicativos e módulos (páginas).  
Use o campo Filtro para localizar rapidamente aplicativos ou módulos.  
Nos módulos de treinamento, Aplicativos do Sistema > Studio significa abrir o menu Todos para localizar o aplicativo Aplicativos do Sistema e abrir o módulo 
Studio no quadro de conteúdo, selecionando-o.  

<img width="625" height="655" alt="image" src="https://github.com/user-attachments/assets/9febc7cf-7e2a-42b3-a90f-6e0c0efef79f" />

Selecione o ícone de alfinete no menu de navegação para manter o menu aberto na lateral da tela.  

<img width="988" height="642" alt="image" src="https://github.com/user-attachments/assets/097705b4-5092-4065-b078-80e60810366e" />

O menu Usuário inclui controles relacionados ao usuário.  
Todos os usuários podem visualizar seu Perfil e Preferências, além de sair da sessão.  
O acesso aos controles é restrito com base na função do usuário.  
O usuário administrador visualiza todos os controles, como a possibilidade de se passar por outro usuário ou elevar seus privilégios.  

<img width="427" height="547" alt="image" src="https://github.com/user-attachments/assets/2c743ec9-ddac-4106-8cfc-47e28baf8f13" />

### Quadro de conteúdo
O quadro de conteúdo exibe páginas de conteúdo quando os usuários selecionam módulos nos menus de navegação.  
As páginas no quadro de conteúdo renderizam dados de diversas maneiras.  
Os tipos de página mais básicos são listas e formulários.  

Lista:  
<img width="1270" height="577" alt="image" src="https://github.com/user-attachments/assets/f419178a-d5b8-46e7-9d63-4e156b050706" />

Formulário:  
<img width="1270" height="626" alt="image" src="https://github.com/user-attachments/assets/9d14c9c1-a8f2-414b-836c-400b8ee5cde5" />

## Listas
Uma lista é uma página de conteúdo que exibe zero ou mais registros da mesma tabela.  
A lista é organizada em linhas e colunas.  
Cada linha representa um registro e cada coluna representa um campo desse registro.  
Exemplos de listas são:  
- Pesquisáveis
- Classificáveis
- Editáveis ​​(se as permissões permitirem)  

Você pode aprender mais sobre as opções de pesquisa, classificação e edição na interatividade abaixo.  
<img width="1282" height="329" alt="image" src="https://github.com/user-attachments/assets/567abd36-ea83-4306-bfbb-21ced05abe4e" />

### Filtros
Os filtros determinam quais registros da tabela são exibidos em uma lista.  
Quando um desenvolvedor cria um módulo de lista, as condições de filtro são definidas.  
No exemplo, somente os registros com o valor do campo Ativo igual a verdadeiro aparecem na lista.  
A sintaxe Todos > Ativo = verdadeiro é conhecida como trilha de navegação (breadcrumb).  
<img width="592" height="91" alt="image" src="https://github.com/user-attachments/assets/405bdebe-3d4b-41bc-83d4-fcaeb7471f26" />

Os usuários podem criar ou modificar filtros.  
Saiba mais sobre o processo de modificação de condições usando filtros na interatividade abaixo.  
<img width="1680" height="372" alt="image" src="https://github.com/user-attachments/assets/0f516abc-bd45-49c6-9f25-7a65c0836326" />

Para remover uma condição do caminho de navegação, selecione Remover próxima condição (>=) à esquerda da condição que deseja remover.  
Por exemplo, para remover a condição Ativo = verdadeiro, selecione o > entre Todos e Ativo = verdadeiro.  
<img width="511" height="153" alt="image" src="https://github.com/user-attachments/assets/5314b499-d4e8-4f35-9fa3-51ee2a86791c" />

## Formulários
Um formulário é uma página de conteúdo que exibe campos e valores para um único registro de uma tabela de banco de dados.  
Os formulários podem ter um layout de uma coluna, um layout de duas colunas ou uma combinação de ambos.  
Os formulários são abertos a partir de módulos no menu "Todos" ou selecionando o número de um registro em uma lista.  
<img width="992" height="350" alt="image" src="https://github.com/user-attachments/assets/57aa8d98-302d-4ef4-95a9-0a6f0e0c5703" />

### Secções
Os formulários podem conter seções.  
Seções são agrupamentos lógicos de campos.  
Por padrão, as seções são exibidas como abas na parte inferior do formulário.  
O uso de seções evita que os usuários precisem rolar por formulários longos.  
Usando um script, as seções podem ser ocultadas quando não forem necessárias.  
<img width="1241" height="497" alt="image" src="https://github.com/user-attachments/assets/0f99670b-4720-4cc9-a70d-49413b87a5b4" />

### Visualizações
Os formulários podem ter várias visualizações.  
Uma visualização é um layout alternativo para a apresentação dos dados de um registro.  
Diferentes perfis de usuário utilizam visualizações diferentes para ver os dados do mesmo registro.  
O ServiceNow possui uma visualização especial chamada **Visualização de Autoatendimento**.  
Usuários da **Visualização de Autoatendimento** não precisam de uma licença do ServiceNow para visualizar o formulário de um registro.  

O nome da visualização aparece no cabeçalho do formulário.  
Se não houver nome de visualização no cabeçalho do formulário, a visualização será a **Visualização Padrão**.  
<img width="992" height="205" alt="image" src="https://github.com/user-attachments/assets/2c72cccc-65a1-498c-9b64-1d45cae5b5f5" />

Para alterar as visualizações:
1. Abra o menu Ações adicionais e selecione a opção Exibir.
<img width="1680" height="454" alt="image" src="https://github.com/user-attachments/assets/9ad80b4d-69d6-49fe-aa3a-521c6db70f32" />
2. Selecione uma visualização.
<img width="1680" height="357" alt="image" src="https://github.com/user-attachments/assets/80bd19b1-6f65-4c51-b2f6-5bce1c3935bb" />

### Anotações
Alguns formulários contêm anotações.  
As anotações são informações adicionais em um formulário, destinadas a fornecer instruções na tela aos usuários.  
As anotações têm texto escuro sobre fundo colorido.  
Os usuários podem ativar e desativar as anotações individualmente.  
<img width="992" height="193" alt="image" src="https://github.com/user-attachments/assets/2c202f8e-5fa3-488b-b8a2-f0828abe0c8a" />

## Atividade: Navegação, Listas e Formulários

Nesta atividade, vamos praticar:
- Navegação no ServiceNow
- Busca de registros em listas
- Classificação de listas
- Alteração de visualizações de formulários
- Abertura de seções

### Navegação e listas
Nesta seção vamos navegar pela interface do ServiceNow e filtrará uma lista.

1 - Na janela do navegador do ServiceNow, abra o menu Todos e digite Incidente no campo de filtro.  
<img width="483" height="131" alt="image" src="https://github.com/user-attachments/assets/f5c69a57-8688-4c60-b12e-40c09360e2b1" />

2 - Incidente > Open para exibir a lista de todos os registros de incidentes abertos.  
<img width="317" height="270" alt="image" src="https://github.com/user-attachments/assets/c0a6ded2-76e4-4a89-aa98-ec2db36ca0f5" />

3 - Pesquise todos os registros de incidentes que contenham a palavra "Inativo" no campo "Descrição curta".
  - Altere o valor do campo "Pesquisar" para "Descrição curta".  
  - Digite "*Inativo" no campo "Pesquisar".
  - Pressione a tecla <Enter> no teclado.
  - Examine os registros retornados pela pesquisa.
  - Observe quantos registros foram retornados pela pesquisa.
<img width="612" height="55" alt="image" src="https://github.com/user-attachments/assets/00426d38-5772-4183-aea2-7108ea6a8137" />

4 - Adicione uma condição ao filtro.
  - Abra o Construtor de Condições selecionando o ícone Filtro no cabeçalho da lista.
  - Selecione o botão E na condição Descrição curta.
  - Adicione a nova condição [Categoria] [não é] [Rede].
  - Selecione o botão Executar.
<img width="936" height="286" alt="image" src="https://github.com/user-attachments/assets/9bf0fdbf-5551-4a55-8b1b-aab6859236e4" />
  - Você tem o mesmo número de registros que tinha antes de adicionar a condição de Categoria?
  - Examine o caminho de navegação. Você vê a nova condição no caminho de navegação?

5 - Remova a condição "A descrição curta contém a condição 'Para baixo'" do caminho de navegação selecionando o ícone "Remover próxima condição" (>) para a condição.
<img width="613" height="127" alt="image" src="https://github.com/user-attachments/assets/8fe5312b-a610-4f61-91f1-9de5f7522d97" />

6 - Classifique a lista.
  - Determine por qual coluna a lista está classificada. Procure o indicador de classificação crescente (ícone de seta para cima) ou decrescente (ícone de seta para baixo).
  - Classifique por "Chamador" em ordem decrescente selecionando o cabeçalho da coluna "Chamador". Pode ser necessário selecionar mais de uma vez para obter a ordem de classificação decrescente.
<img width="769" height="154" alt="image" src="https://github.com/user-attachments/assets/1ac95190-8232-473e-b375-f349a7924a31" />

### Formulários

Nesta seção vamos abrir e explorar um formulário.  

1 - Abra qualquer registro de Incidente selecionando o link na coluna Número da Lista de Incidentes.
2 - Examine os campos do formulário e observe o layout de duas colunas.
3 - Role a página para baixo até as seções do formulário e examine a seção Notas. O campo Atividades deve conter pelo menos uma entrada.
4 - Mude para a seção Informações de Resolução (guia). Como você abriu um registro ativo, os campos da seção Informações de Resolução devem estar vazios.
5 - Altere a visualização para a visualização de Autoatendimento.
  - No cabeçalho do formulário, abra o menu Ações adicionais e selecione Exibir > Autoatendimento.
  - Examine o formulário na visualização de Autoatendimento. Ele é igual à visualização Padrão?
  - Procure as seções Notas e Informações de Resolução. Elas fazem parte da visualização de Autoatendimento?
  - Altere a visualização de volta para a visualização Padrão.

---

## Conceitos básicos

• A interface do usuário do ServiceNow é composta por: Banner e Quadro de conteúdo
• Use os menus de navegação no banner para abrir o conteúdo no quadro de conteúdo.
• O menu "Todos" utiliza a estrutura Aplicativo > Módulo para acessar o conteúdo.
• Os módulos em um aplicativo podem ser agrupados por categoria, resultando na estrutura Aplicativo > Categoria > Módulo.
• As listas exibem registros de uma tabela.
• As listas podem ser: Pesquisáveis, Classificáveis, Editáveis ​​(se as permissões permitirem)
• Os filtros exibem um subconjunto dos registros de uma tabela.
• Os formulários são usados ​​para criar e editar registros.
• As visualizações são diferentes layouts dos dados de um registro.

---
