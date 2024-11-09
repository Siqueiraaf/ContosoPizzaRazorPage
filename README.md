
# WebApp Gerenciamento de Estoque de pizzas.


## Funcionalidades
- ### Gerenciamento de Produtos (Pizzas)
**Listar pizzas**: Exibir uma lista de pizzas disponíveis no estoque, incluindo informações como nome, ingredientes, quantidade em estoque e preço.

**Adicionar pizza**: Funcionalidade para criar e adicionar uma nova pizza ao estoque, preenchendo detalhes como nome, ingredientes, preço e quantidade inicial.

**Editar pizza**: Permitir a edição de pizzas existentes para atualizar informações como preço, quantidade em estoque ou alterar os ingredientes.

**Remover pizza**: Capacidade de remover uma pizza do estoque quando ela não for mais relevante para o negócio.

- ### Pesquisa e Filtragem
**Busca de pizzas**: Funcionalidade de busca que permite ao usuário procurar pizzas por nome, ingredientes ou categorias (como vegetariana ou sem glúten).

**Filtragem de pizzas**: Opções de filtragem para visualizar apenas pizzas que atendem a determinados critérios, como pizzas com estoque baixo ou pizzas de determinada faixa de preço.
- ### Controle de Estoque
**Visualizar quantidade de estoque**: Mostrar a quantidade atual de cada pizza no estoque, destacando itens com baixa disponibilidade.

**Atualização de estoque**: Permitir a modificação da quantidade de pizzas em estoque, especialmente após vendas ou recebimento de novas entregas.
Alerta de baixo estoque: Notificações ou avisos automáticos quando o estoque de uma pizza cair abaixo de um limite definido, ajudando a evitar falta de produtos.
- ### Relatórios e Estatísticas
**Relatório de vendas**: Geração de relatórios que mostram a quantidade de pizzas vendidas em determinado período, além de insights sobre os sabores mais vendidos.
**Estatísticas de estoque**: Painel que exibe dados sobre o movimento do estoque, incluindo quantas pizzas foram adicionadas, removidas ou editadas recentemente.
- ### Segurança e Controle de Acesso
**Autenticação de usuários**: Implementar login seguro para que somente usuários autorizados (como gerentes ou funcionários da Contoso Pizza) possam acessar as funcionalidades do WebApp.

**Autorização por função**: Diferenciar permissões de acesso baseadas em funções. Por exemplo, gerentes podem adicionar, editar e remover pizzas, enquanto funcionários podem apenas visualizar o estoque.
- ### Gerenciamento de Fornecedores
**Cadastro de fornecedores**: Permitir o cadastro de fornecedores que fornecem ingredientes ou pizzas congeladas, com dados de contato e histórico de compras.

**Histórico de compras**: Armazenar e exibir o histórico de pedidos feitos a cada fornecedor, facilitando a reabastecimento de ingredientes quando necessário.
- ### Interfaces e Usabilidade
**Interface amigável e responsiva**: Garantir que a interface do usuário seja fácil de navegar e responsiva, adaptando-se a diferentes dispositivos (computadores, tablets e smartphones).

**Feedback visual**: Usar feedback visual, como ícones e cores, para indicar status do estoque, sucesso ou erro ao realizar uma ação (ex: pizza adicionada com sucesso, erro ao atualizar).
- ### Injeção de Dependência e Extensibilidade
**Serviços injetados**: Utilizar injeção de dependência para integrar serviços como bancos de dados, APIs de terceiros ou serviços de notificação. Isso facilita a escalabilidade e a manutenção do WebApp.

- ### Gerenciamento de Categorias e Promoções
**Criar e gerenciar categorias**: Funcionalidade para categorizar pizzas (ex: vegetariana, premium, clássica) e filtrar a exibição de produtos por essas categorias.

**Promoções e descontos**: Opção de criar promoções para determinadas pizzas, como descontos por tempo limitado ou promoções baseadas em quantidade (ex: compre 2, leve 3).
- ### Logs e Auditoria
**Rastreamento de atividades**: Manter um log de todas as operações realizadas no WebApp, como adição, edição e remoção de pizzas. Isso garante transparência e segurança nas ações realizadas.

**Histórico de alterações**: Permitir o rastreamento de alterações feitas no estoque, como aumento ou diminuição da quantidade de pizzas, com a identificação de quem fez a mudança e quando.



## Aprendizados

Nesse estudo Aprendi a desenvolver um Sistema de **WebApp** Gerenciamento de estoque com Razor e ASP.NET Core.

- Entendi quando e por que usar Razor Pages para seu aplicativo ASP.NET Core.
- Examinei um aplicativo ASP.NET Core existente que usa Razor Pages.
- Criei uma Razor Page com suporte para os requisitos de gerenciamento de dados de produto do - aplicativo.
- Usei auxiliares de marca para reduzir a alternância de contexto entre HTML e C#.
- Usei manipuladores de Razor Pages para lidar com solicitações HTTP.

## Referência

 - [AppWeb Multiplataforma](https://learn.microsoft.com/pt-br/training/paths/aspnet-core-web-app/)

## Autores

- [@Siqueiraaf](https://www.github.com/Siqueiraaf)


## Stack utilizada

**Front-end:** Razor

**Back-end:** ASP.NET Core

