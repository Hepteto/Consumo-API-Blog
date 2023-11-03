![header](https://64.media.tumblr.com/e972f7e3a1a9610a1cb483d63e5bbb83/ce4527a0e7d43bf5-bb/s2048x3072/87d2c3114110669b94faf1d66a7fb602c18c7fa3.pnj)

# Consumindo a API Blog

Aplicação web criada com Node.js que consome uma API simples RESTful com CRUD. A qual fornece dados JSON de título e texto de um post.

:globe_with_meridians: Site: https://consumo-api-blog.vercel.app/

## Stacks
![Stacks](https://skillicons.dev/icons?i=nodejs,react,vite,vercel&perline=4)

## Wireframe
![wireframe](https://64.media.tumblr.com/fdcfbb625e10e7c6e08e2f972b9f5c9c/b228ba4571478b61-de/s2048x3072/d63b357a56d1ac9448d3170598291e86a369f2de.jpg)

## API
:globe_with_meridians: Repo GitHub: https://github.com/Hepteto/API-Blog

![CRUD API](https://64.media.tumblr.com/02b45bc24ac59348628a9ac7f59ac731/d6a66cbb62fdd41d-6a/s2048x3072/f547062af7b7c1ea6cc0e384eb42d4a5480e51d3.jpg)

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
