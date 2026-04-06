[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IDEzcQ6G)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23380564)
# :checkered_flag: NOME DO PROJETO

**Nelsa Variedades Online**.

Sistema web desenvolvido como vitrine digital para a loja Nelsa Variedades. A plataforma permite que clientes visualizem itens disponíveis, realizem compras ou encomendas e acompanhem a disponibilidade de estoque em tempo real.

## :technologist: Membros da equipe

569533 Rogério Girão de Castro

596042 Raul Camurça Rabelo de Almeida

## :bulb: Objetivo Geral
Desenvolver um sistema web para a Nelsa Variedades que funcione como uma vitrine digital integrada ao controle de estoque, permitindo a visualização, compra e encomenda de produtos pelos clientes, além de possibilitar a gestão eficiente dos itens e usuários por meio de diferentes níveis de acesso, contribuindo para a organização, digitalização e aumento do alcance de pequenos comércios locais.

## :eyes: Público-Alvo
Pequenos empreendedores e clientes de comércios locais.

## :star2: Impacto Esperado
Espera-se que o sistema proporcione maior praticidade, organização e acessibilidade tanto para os clientes quanto para os responsáveis pela loja.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

A aplicação possui os seguintes tipos de usuários:
- Usuário não logado (visitante): pode acessar a vitrine da loja, visualizar os produtos, preços e disponibilidade em estoque.
- Cliente (usuário logado): além das funcionalidades do visitante, pode realizar compras ou encomendas de produtos.
- Vendedor: responsável por gerenciar os produtos e pedidos, podendo adicionar, editar ou remover itens e atualizar o estoque.
- Administrador: possui acesso total ao sistema, podendo gerenciar produtos, pedidos e usuários (criar, editar e remover contas).

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

A aplicação terá como principal objetivo servir como vitrine digital e sistema de gestão para a loja, oferecendo as seguintes funcionalidades:

**Funcionalidades acessíveis a todos os usuários:**
- Visualização dos produtos disponíveis
- Consulta de preços e descrição dos itens
- Verificação da disponibilidade em estoque
- Navegação pela vitrine da loja

**Funcionalidades para usuários logados (Cliente)**
- Realizar compras ou encomendas de produtos
- Visualizar pedidos realizados

**Funcionalidades restritas (Vendedor)**
- Cadastrar novos produtos
- Editar informações de produtos (preço, descrição, quantidade)
- Remover produtos
- Atualizar status de estoque (disponível/esgotado)
- Gerenciar pedidos dos clientes

**Funcionalidades restritas (Administrador)**
- Todas as funções do vendedor
- Gerenciamento de usuários (criar, editar e remover contas)
- Controle total do sistema

## :spiral_calendar: Entidades ou tabelas do sistema

**Entidades do sistema:**
- Usuário: armazena os dados dos usuários do sistema (nome, email, senha, tipo de usuário, cliente, funcionário ou administrador).
- Produto: contém as informações dos produtos da loja (nome, descrição, preço, quantidade em estoque, status de disponibilidade).
- Pedido: registra as compras ou encomendas realizadas pelos clientes (data, status, valor total, usuário responsável).
- Item do Pedido: representa os produtos incluídos em cada pedido, relacionando produto e pedido (quantidade, preço unitário).
- Categoria: organiza os produtos por tipo (ex: roupas, acessórios, utilidades).


----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.

**Backend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Entidade 1 | X |  X  |  | X |
| Entidade 2 | X |    |  X | X |
| Entidade 3 | X |    |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
