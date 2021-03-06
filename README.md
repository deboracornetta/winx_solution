# Parceiro Magalu

Em 2020 muitas pessoas foram atingidas pela pandemia de Covid-19. A impossibilidade de se sair de casa trouxe impactos sociais, psicológicos e, claro, econômicos. Lojistas tiveram uma enorme queda em vendas e rendimentos, e frente a esse desafio, precisavam de uma solução.

É nesse contexto que surge o **Parceiro Magalu**, projeto do time Clube das Winx, participantes do Luiza Code. Essa plataforma permite que um lojista se cadastre e crie sua própria lojinha que será totalmente integrada ao sistema da Magazine Luiza.

Dessa forma, além de o lojista poder diminuir o impacto causado pela quarentena; o catálogo do site da Magalu também se expande, o que beneficia os clientes. Além disso, com vários negócios locais participando dessa iniciativa, o sistema de compras e entregas pode ser otimizado, diminuindo o preço de fretes e o tempo de entrega e beneficiando os pequenos negócios locais.

## Como funciona?

**É bem simples!**

Primeiro você acessa o site e, caso já possua um cadastro, já pode entrar.

![Página de login](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/01.png)

Caso precise se cadastrar, precisaremos de alguns de seus dados primeiro...

![Página de cadastro de usuário](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/02.png)

... e depois de detalhes da sua loja!
![Página de cadastro de loja](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/03.png)

Por fim, na página principal, você poderá ter uma visão geral de sua loja com pontos importantes destacados!

![Homepage](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/04.png)

Mas não se preocupe, caso queira ver mais detalhes, temos páginas para isso também, como a página de pedidos:

![Página de pedidos](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/05.png)

A página de estoque:

![Página de estoque](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/06.png)

A página de notificações:

![Página de notificações](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/07.png)

E a página de controle da loja:

![Página de controle da loja](https://raw.githubusercontent.com/lindiner/winx_solution/main/screenshots/08.png)

Viu só como é fácil? Ainda assim, se por algum motivo algo não estiver claro, você pode conversar através de um chat com a própria Magalu! Ela adora ajudar e estará sempre disponível!

### A especificação do projeto está apresentada abaixo

```Uma solução aberta para outros vendedores colocarem seus produtos a venda
em nossa plataforma.

Discutindo os requisitos para o MVP, o pessoal de produto considerou:

Requisitos Obrigatórios:

- O desenvolvimento deve ser via API REST (sugestão de frameworks: Django, Flask, aiohttp);
- A representação dos dados (cadastrar/visualizar produto) o formato de dados é preferencialmente JSON
- Na solução, deve ser possível:
    - Cadastrar um produto;
    - Atualizar um produto;
    - Consultar um produto;
    - Inativar um produto (observação: não é necessário apagar produto e sim inativar);

- Um produto deve ter os seguintes campos:
    - Título;
    - Preço;
    - Código do produto;
    - Identificador do vendedor (seller);
    - Quantidade em estoque;

Requisitos não obrigatórios:

- Criação de testes unitários para a solução;
- Implementação de Continuous Integration (Sugestão se for fazer, utilizem o github =) );
- Versionamento do código (git);
- Autenticação na API por seller (cada seller teria uma "chave" de acesso)```
