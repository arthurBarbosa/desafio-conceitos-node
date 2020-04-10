# Back-end com Node.js

Api Rest com um CRUD de Repositorios

## Instalação

- Clonando o repositório
> `git clone https://github.com/arthurBarbosa/desafio-conceitos-node.git`

- Entre no diretório criado e instale as dependências com o Yarn

> `yarn`

- Server API
> `http://localhost:3333`

## Endpoints
> GET `http://localhost:3333/repositories`
> POST `http://localhost:3333/repositories` Parametros { title, url techs, likes:0 }
> PUT `http://localhost:3333/repositories/:id` Parametros { id, title, url techs }
> DELETE `http://localhost:3333/repositories/:id` Parametros { id }
> POST `http://localhost:3333/repositories/:id/likes` Parametros { id }
