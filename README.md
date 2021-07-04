
# Backend EAD TC2

### Rotas

**GET: /api/produtos**

Retorna os produtos cadastrados

----------------

**GET: /api/produtos/baratos**

Remove todos os produto baratos

----------------
**GET: /api/produtos/baratos**

Retorna o produto dado seu ID

 Requer:
  -  "id" - id do produto cadastrado.

----------------
**POST: /api/produtos**

Cadastra um novo produto de acordo com as informações passadas.

Requer:

 - "titulo" - O título do produto. 
 - "preco" - Um número correspondente
   ao preço do produto.
 - "descricao - Uma descrição do produto.

   
----------------
**PUT: /api/produtos/:id**

Atualiza um produto já cadastrado.

Requer:
 -  "id" - id do produto cadastrado.
-   "titulo" - O novo/antigo do produto.
  - "preco" - Um número correspondente ao novo/antigo preço do produto.
-   "descricao - Uma descrição nova/antiga do produto.
   
 ----------------
 **DELETE: /api/produtos/:id**
 
 Deleta um produto cadastrado.
 
 Requer:
  -  "id" - id do produto cadastrado.
