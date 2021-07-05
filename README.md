Informações gerais gerada automaticamente
# Detran

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.12.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
# Detran
# Detran

--Informamações para executar
Lista de bibliotecas e/ou frameworks utilizados
DotNet Core 2.2
bibliotecas do dotnet core
Microsoft.EntityFrameworkCore 5.0.7
Microsoft.EntityFrameworkCore.SqlServer 5.0.7
Microsoft.EntityFrameworkCore.Abstractions
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.Relationa

Angular 11
bibliotecas do Angular

ngx-toastr
animations
angular material
ngx-mask

Explicação de como rodar a ferramenta em ambiente de desenvolvimento
API

Executar o comando
dotnet restore – Restaura as dependências e as ferramentas de um projeto.

Executar package manager console os seguintes comandos para criar o banco de dados
Add-Migration StartMigration
e em seguida
Update-Database

Explicação de como rodar o front
Na pasta raiz executar o comando npm install – Restaura as dependências e as ferramentas de um projeto.

Ao executar a API e o Front é necessario realizar um cadastro de usuario (Esta aberto para cadastro apenas para testes)
Preencha os campos e cadastre o usuario e a senha
O usuario de autenticação será o e-mail cadastrado e a senha deverá conter ao meno 1 caracter especial, 1 letra maiuscula, 1 letra minuscula e no minimo 8 caracteres

Na dashboard consta os acessos aos registros Veiculo e Condutor, o registro de compra/venda não consegui terminar em tempo.

Com exceção ao cadastrado de usuario e login todos os metodos exigem autenticação com token valido.
