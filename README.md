# Template RAILS 8 + Vue 3 ⏱️

Template fácil para um app Rails com:

- 💎 Ruby on Rails 8
- ⚡ Vite.js + Vue 3

## Inicialização rápida

- Tenha o Ruby 3.2.2 instalado
- Instale as gems: `bundle install`
- Tenha o Node 20 instalado
- Instale os pacotes NPM com yarn `yarn install`
- Crie o `.env` com `cp .env.example .env` (não é necessário alterar a não ser que queira alguma customização)
- Faça a build do docker: `docker compose up -d`
- Inicie o banco: `rails db:create` e `rails db:migrate`

```bash
# Inicia tanto o servidor Rails quanto o servidor Vite.js de uma vez
bin/dev

# Caso encontre o erro de:
# /usr/bin/env: ‘ruby\r’: No such file or directory
# /usr/bin/env: use -[v]S to pass options in shebang lines
# Formate os arquivos e rode o binário novamente:
dos2unix bin/*
bin/dev
```

O sistema estará disponível em: [http://localhost:3000](http://localhost:3000)

## Estrutura do projeto

Padrão do Rails.
Você pode achar os arquivos do Vue em `app\frontend`.
Arquivo base do VUE: `app\frontend\entrypoints\application.js`

## Stack Tecnológica

- **Ruby:** 3.2.2
- **Rails:** 8
- **Database:** PostgreSQL
- **Frontend:** Vue 3 gerenciado pelo Vite
