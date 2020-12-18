# Especificações do projeto

### Requisitos não funcionais
* O gerenciador de tarefas será criado com a utilização de uma API em PHP nativo. O consumo da API se dará através da tecnologia curl.
* O código será gerado com intuito de rodar apenas em computadores.

### Resquisitos funcionais
1. O usuário pode cadastrar uma tarefa.
2. O usuário pode editar uma tarefa.
3. O usuário pode excluir uma tarefa.
4. O usuário pode cadastrar o tempo necessário para realizar uma tarefa.
5. O usuário pode cadastrar a descrição de uma tarefa.
6. O usuário pode editar a descrição de uma tarefa.
7. O usuário pode inserir um tempo que foi dedicado na tarefa (apenas quando tiver preenchido a opção do requisito 4).
8. O usuário pode zerar o tempo dedicado em uma tarefa.
9. O usuário pode visualizar o progresso de uma tarefa.
10. O usuário pode cadastrar informações dentro de uma tarefa (ideias, sites para pesquisar...)
11. O usuário pode cadastrar uma lista de to-do (check box list) dentro da tarefa.
12. O usuário pode excluir a lista de to-do quando utilizar o recurso do requisito onze.
13. O usuário pode ver o progresso da lista de to-do quando utilizar o recurso do requisito onze.
14. O usuário poderá optar entre os temas light e dark mode.
15. O usuário poderá realizar seu cadastro no sistema.

### Tecnologias a serem utilizadas
* PHP
* MySQL
* HTML
* CSS
* JavaScript
* Ajax
* Jquery
* Curl
* Padrão de arquitetura MVC
* Scrum

### Entidades necessárias para desenvolvimento do BD
1. task       - a entidade principal, as outras terão foreing key com a primary key desta.
2. task_topic - cada informação que o usuário inserir dentro de uma tarefa.
3. todo_item  - a lista de to do que pode ter dentro da tarefa.
4. user       - informações de login.