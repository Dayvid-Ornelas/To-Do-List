To Do List 📋

Descrição:

O To Do List é um aplicativo web que permite aos usuários criar e gerenciar suas tarefas diárias. 
O objetivo do aplicativo é fornecer uma ferramenta simples e fácil de usar para ajudar os usuários a se organizar e aumentar sua produtividade.

Funcionalidades:

- O aplicativo permite aos usuários criar novas tarefas e adicioná-las à lista de tarefas.
- O aplicativo permite aos usuários editar e excluir tarefas existentes.
- O aplicativo permite aos usuários marcar tarefas como concluídas.
- O aplicativo inclui uma barra de ferramentas com opções de pesquisa e filtragem.
- O aplicativo armazena os dados localmente no navegador utilizando o LocalStorage, sem precisar de um banco de dados.

Tecnologias utilizadas:

- HTML: utilizado para criar a estrutura do aplicativo.
- CSS: utilizado para estilizar o aplicativo e criar as animações.
- JavaScript: utilizado para criar a lógica do aplicativo e interagir com o usuário.

Arquivos e pastas:

- index.html: arquivo principal do aplicativo que contém a estrutura HTML.
- style.css: arquivo de estilo que contém as regras de estilo para o aplicativo.
- script.js: arquivo de script que contém a lógica do aplicativo.
- imagens/: pasta que contém as imagens utilizadas no aplicativo.

Como usar:

1- Abra o arquivo index.html em um navegador. 

2- Crie uma nova tarefa clicando no botão "Adicionar tarefa". 

3- Edite ou exclua uma tarefa existente clicando nos botões correspondentes. 

4- Marque uma tarefa como concluída clicando no botão "Concluir". 

5- Use a barra de ferramentas para pesquisar ou filtrar as tarefas.

Créditos:

- Dayvid Ornelas: criador do aplicativo.

Armazenamento de dados:

O aplicativo utiliza o LocalStorage para armazenar os dados localmente no navegador. 
Isso é feito na Step01, onde uma nova tarefa é adicionada à lista de tarefas. 
A função saveToDo é chamada aqui para adicionar a nova tarefa à lista e armazená-la no LocalStorage.

Código responsável pelo armazenamento de dados:

Aqui está o trecho de código responsável pelo armazenamento de dados:

![Captura de tela 2024-11-22 151335](https://github.com/user-attachments/assets/e1816c49-c5b2-4d9d-b018-3cd4769bcebc)

O armazenamento de dados é feito automaticamente quando uma nova tarefa é adicionada à lista. 
A função saveToDo é responsável por criar a nova tarefa e adicioná-la à lista, e o LocalStorage é utilizado para armazenar os dados localmente no navegador.
