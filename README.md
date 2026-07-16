## Instalar Angular
npm install -g @angular/cli
## criar o projeto do site
npx ng new portal
## Entrar na pasta do projeto
cd portal
## Inicializar o servidor angular (modo dev)
npx ng serve
## Criar um novo componente de cabeçalho
npx ng g c header
## Criar um novo componente de rodapé
npx ng g c footer
## Para atualizar as dependências
npx npm install
## Gerar uma build
npx ng build
## Gerar uma build
npx ng build
## instalar o json
npm install -g json-server
npx json-server --watch db.json --port 3000
## Adicionar no arquivo package.json, em scripts
"backend": "json-server --watch db.json --port 3000"