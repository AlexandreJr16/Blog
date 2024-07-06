# Blog em Rails
Este é um projeto iniciante desenvolvido com Ruby on Rails, implementando um CRUD básico para um blog, seguindo a documentação oficial do Rails.

## Funcionalidades
- Create: Criar novos posts no blog.
- Read: Visualizar posts existentes.
- Update: Atualizar posts já publicados.
- Delete: Remover posts do blog.
- 
## Requisitos
Ruby 2.7 ou superior
Rails 6.1.x (ou versão mais recente)
Banco de dados SQLite
Git para controle de versão
## Instalação
1. Clone este repositório para o seu ambiente local:
```bash
git clone https://github.com/seu-usuario/blog-rails.git
```
2. Instale as dependências do projeto:

```bash
cd blog-rails
bundle install
```
3. Crie o banco de dados e execute as migrações:
```bash
rails db:create
rails db:migrate
```
4. Inicie o servidor Rails:
````bash
rails server
````

## Estrutura de Pastas
- app/: Contém os controllers, models, views e assets do projeto.
- config/: Configurações do Rails, incluindo rotas e banco de dados.
- db/: Migrações do banco de dados.
- public/: Arquivos estáticos acessíveis publicamente.
- test/: Testes automatizados (se forem adicionados posteriormente).
- Gemfile, Gemfile.lock: Especificações de gemas (dependências) do Ruby.
