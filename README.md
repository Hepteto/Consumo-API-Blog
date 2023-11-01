![header](https://64.media.tumblr.com/e972f7e3a1a9610a1cb483d63e5bbb83/ce4527a0e7d43bf5-bb/s2048x3072/87d2c3114110669b94faf1d66a7fb602c18c7fa3.pnj)

# Consumindo a API Blog

Aplicação web criada com Node.js que consome uma API simples RESTful com CRUD. A qual fornece dados JSON de título e texto de um post.

:globe_with_meridians: Site: https://consumo-api-blog.vercel.app/

## Stacks
![Stacks](https://skillicons.dev/icons?i=nodejs,react,vite&perline=3)

## Wireframe
![wireframe](https://64.media.tumblr.com/3e3afc94385ad4403f0c41c09086ad71/c99ce3a2bf27d524-d1/s2048x3072/eb2acf850a74b55151f06d6d84672b2436074536.pnj)

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
