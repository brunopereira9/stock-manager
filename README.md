# stock-manager

## Back-End
#### Getting Started

Clone o repositório e caso seja necessário altere a porta do servidor no arquivo Properties\launchSettings.json

`git clone https://github.com/brunopereira9/back-stock-manager.git`

#### Configure a StringConection em appsettings

`"Server=localhost\\SQLEXPRESS;Database=Stock_Manager;Trusted_Connection=True;"`

### Migrations
#### Instale dotnet ef
`dotnet tool install --global dotnet-ef`

#### Migration Init
`dotnet ef database update`

#### Start

`dotnet run`

### Porta Padrão
#### Https
`https://localhost:7003`
#### Http
`http://localhost:5217`

### Verifique o front-end no repositório abaixo

`https://github.com/brunopereira9/front-stock-manager.git`

## Front-End
### Getting Started

Clone o repositório e altere a porta do servidor no arquivo .env

`git clone https://github.com/brunopereira9/front-stock-manager.git`

### Start

`npm start`

#### Verifique o back-end no repositório abaixo

`https://github.com/brunopereira9/back-stock-manager.git`