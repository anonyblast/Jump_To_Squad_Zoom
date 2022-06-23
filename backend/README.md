# Passo a Passo

>Crie uma pasta
```sh
mkdir nome-da-pasta
```
> Acesse a pasta que você acabou de criar
```sh
cd nome-da-pasta
```

> Clone este repositório
```sh
git clone https://github.com/anonyblast/Jump_To_Squad_Zoom.git
```

> Instale as dependências
```sh
npm install
```

#### MUDE AS INFORMAÇÕES NO ARQUIVO src/config/config.json

> Execute a aplicação em modo de desenvolvimento. Esse comando irá inicializar o banco de dados MySQL com dados fakes
```sh
npm run jump
```
#### OU
>Execute apenas a aplicação sem inicializar o banco
```sh
npm start
```

#### O servidor iniciará na porta:3300 - acesse <http://localhost:3300>

> Para facilitar em qualquer um dos casos de execução, aparecerão alertas representando as ações