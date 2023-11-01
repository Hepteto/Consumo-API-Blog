![header](https://64.media.tumblr.com/4ec081bc9cdae094930958977a1e93be/8e8c89988f3cf4b7-80/s640x960/3867dbd30a0338e10d97d36cad08a802c9b2f6b4.pnj)

# Consumindo a API Blog

Aplicação web criada com Node.js que consome uma API simples RESTful com CRUD. A qual fornece dados JSON de título e texto de um post.

:globe_with_meridians: Site: https://consumo-api-blog.vercel.app/

## Stacks
![Stacks](https://skillicons.dev/icons?i=nodejs,react,vite&perline=3)


## API
:globe_with_meridians: Repo GitHub: https://github.com/Hepteto/API-Blog

- `POST /posts`
Cria uma nova postagem no blog com base nos dados fornecidos no corpo da solicitação.

- `GET /posts`
Retorna uma lista de todas as postagens no blog.
    
- `GET /posts/{id}`
Retorna os detalhes de uma postagem específica com base no `id`.

- `PATCH /posts/{id}`
Atualiza uma postagem existente com base no `id` com os dados fornecidos no corpo da solicitação.

- `DELETE /posts/{id}`
Exclui uma postagem existente com base no `id`.
