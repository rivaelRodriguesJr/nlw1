## Lições

### Iniciando
```
- Rota: Endereço completo da requisição
- Recurso: Qual entidade estamos acessando do sistema
```
### Métodos HTTP
```
- GET: Buscar uma ou mais informções do back-end
- POST: Crinar uma nova informação no back-end
- PUT: Atulaizar uma informação existente no back-end
- DELETE: Remover uma informação do back-end
```
### Exemplo de métodos HTTP
```
- POST http://localhost:3333/users = Criar um usuário
- GET http://localhost:3333/users = Listar usuários
- GET http://localhost:3333/users/5 = Buscar dados do usuário com ID 5
```
### Parâmetros de uma requição
```
- Request Param: Parâmetros que vem na própria rota que identificam um recurso
- Query Param: Parâmetnros que vem na própria rota geralmente para filtros, paginação
- Request Body: Parâmetros para criação/atualização de informações
```
### SQL puro vs ORM
```
- SELECT * FROM users WHERE name = 'Diego'
- knex('users').where('name','Diego').select(*)
```
### Usando knex
```
- Migrations = Histórico do banco de dados
- create table points
- create table users
```
