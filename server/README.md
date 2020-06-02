## Lições

### Iniciando
```bash
- Rota: Endereço completo da requisição
- Recurso: Qual entidade estamos acessando do sistema
```
### Métodos HTTP
```bash
- GET: Buscar uma ou mais informções do back-end
- POST: Crinar uma nova informação no back-end
- PUT: Atulaizar uma informação existente no back-end
- DELETE: Remover uma informação do back-end
```
### Exemplo de métodos HTTP
```bash
- POST http://localhost:3333/users = Criar um usuário
- GET http://localhost:3333/users = Listar usuários
- GET http://localhost:3333/users/5 = Buscar dados do usuário com ID 5
```
### Parâmetros de uma requição
```bash
- Request Param: Parâmetros que vem na própria rota que identificam um recurso
- Query Param: Parâmetnros que vem na própria rota geralmente para filtros, paginação
- Request Body: Parâmetros para criação/atualização de informações
```
### SQL puro vs ORM
```bash
- SELECT * FROM users WHERE name = 'Diego'
- knex('users').where('name','Diego').select(*)
```
