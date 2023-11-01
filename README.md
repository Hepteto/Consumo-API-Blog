![header](https://64.media.tumblr.com/12ca7b73fa2efe7c430d911d4e62f487/84f40d067667fc17-a3/s2048x3072/1072e90413b907041d1e75a5dd4170c41b0db5f4.pnj)

# Consumindo a API Blog

Aplicação web criada com Node.js que consome uma API simples RESTful com CRUD. A qual fornece dados JSON de título e texto de um post.

:globe_with_meridians: Site: https://consumo-api-blog.vercel.app/
<br />
:globe_with_meridians: Documentação da API: https://app.swaggerhub.com/apis-docs/HEPTETOOFICIAL/BLOG_HEPTETO/1.0#/

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
