#Deploy RENDER

https://fqm-socialnet.onrender.com


## Proyecto Final Red Social
El proyecto lo hemos estado desarrollando durante las clases, deberan entregar 2 enlaces, su repositorio y su app desplegada
 
 
 # by: florencio quelca


# Red Social API

### Url base: http://localhost:9000/api/v1

- /auth

  - /login -> Login con las credenciales del usuario para autenticar

- /posts

  - /me -> Mis propias publicaciones
  - /user/:id -> Publicaciones de usuarios en particular
  - /:id -> Una publicación en especifico
  - /:id/comments -> Los comentarios de una publicación en especifico
  - /:id/likes -> Los likes de una publicación en especifico

- /users
  - /me -> Mi informacion de usuario
  - /:id -> Un usuario en especifico
  - /:id/follow

example ecommerce: /product/:id/add-to-cart

- /follows

  - /:id

- /followers
  - /:id

### Controllers Posts

- [x] findAllPosts
- [x] findPostById
- [x] createPost
- [x] updatePost
- [x] removePost

### Services Posts
- [ ] getAllPosts
- [ ] getPostById
- [ ] postNewPost 
- [ ] patchPost
- [ ] deletePost


###deploy in RENDER

npm install && npm start

npm star

configurar variables de entorno
@dpj hasta el  /
