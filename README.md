Pré-requisitos para rodar o projeto localmente:
Antes de começar, certifique-se de ter instalado em seu sistema:

Node.js e npm: Necessários para executar e gerenciar dependências do projeto.
Angular CLI: Você pode instalá-lo globalmente usando o comando: npm install -g @angular/cli
Configuração do projeto:
Clone este repositório para o seu sistema local:

git clone git@github.com:seu-usuario/angular-todo-list.git.
Navegue até o diretório do projeto:

cd todo-list-angular
Instale as dependências:

npm install
Inicie o servidor:

ng serve

Estrutura do projeto
src/app/app.component.html: Template HTML principal.

src/app/app-routing.module.ts: Define as rotas da aplicação.

src/app/layout: Contém os componentes gerais da aplicação.

src/app/todo: Contém os componentes relacionados à funcionalidade principal da lista de tarefas.

src/app/shared/services: Contém os serviços que gerenciam a lógica de negócios.

src/app/shared/models: Define as estruturas de dados utilizadas na aplicação.

#Funcionalidades#
- Criar tarefas;
- Concluir Tarefas;
- Apagar tarefa(s);
