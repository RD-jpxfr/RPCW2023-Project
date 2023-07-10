# API-Server

## Resources

'/resources'

### GET '/'

Devolve todos os recursos ordenados por título, que obdecem a uma query opcional (por tipo, titulo ou por submissor).

### GET '/:rid'

Devolve o recurso com 'id' igual a 'rid'

### POST '/'

Cria um novo recurso

### PUT '/:rid'

Atualiza o tipo, titulo e/ou descrição de um recurso através do 'id'

### PUT '/:rid/review'

Fazer uma review no recurso com 'id' igual a 'rid'

### DELETE '/:rid'

Apaga um recurso através do 'id'

## News

'/news'

### GET '/'

Devolve todas as notícias.

### POST '/'

Cria nova notícia

### PUT '/:id/

Atualiza uma Notícia através do 'id'

### DELETE '/:id'

Apaga uma Notícia através do 'id'

## Comments

'/comments'

### GET '/:id/

Atualiza uma Notícia através do 'id'

### POST '/'

Cria um novo comentário

### DELETE '/:id'

Apaga um comentário através do 'id'

# Auth-Server

# App-Server
