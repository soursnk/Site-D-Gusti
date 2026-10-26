# D'Gusti Café e Lanches - Redesign do Site

Redesign do site da **D'Gusti Café e Lanches**, estabelecimento localizado em Vitória da Conquista, Bahia. O projeto tem como objetivo desenvolver uma experiência digital própria para a marca, com um cardápio organizado, navegação intuitiva e um fluxo simplificado de pedidos.

Além de atender às necessidades do estabelecimento, este projeto representa uma oportunidade prática de aprendizado em desenvolvimento web e fará parte do meu portfólio profissional.

## Objetivos

- Desenvolver uma identidade visual própria, moderna e acolhedora.
- Melhorar a organização e a navegação do cardápio digital.
- Facilitar a seleção de produtos e a montagem do carrinho.
- Permitir pedidos para entrega ou retirada no estabelecimento.
- Implementar o cálculo da taxa de entrega.
- Disponibilizar pagamento presencial com cartão.
- Desenvolver um fluxo de envio, recebimento e confirmação de pedidos.
- Garantir uma experiência responsiva em celulares, tablets e computadores.

## Identidade visual

A proposta visual combina elementos artesanais e acolhedores com uma interface moderna, organizada e funcional, preservando o nome e a logo existentes da marca.

### Paleta de cores

 Cor - Código - Aplicação 
 Verde principal - `#267447` - Botões e destaques 
 Verde suave - `#EAF2E7` - Fundos secundários 
 Creme - `#FFF8ED` - Fundo principal 
 Terracota - `#C8753D` - Detalhes e elementos secundários 
 Marrom-escuro - `#302D28` - Textos, títulos e ícones 

### Tipografia

- **Lora:** títulos e elementos que transmitem tradição e personalidade.
- **Nunito Sans:** textos, descrições, preços, botões e informações dos pedidos.

## Tecnologias

### Frontend — primeira etapa

- **HTML5:** estruturação das páginas e dos conteúdos.
- **CSS3:** estilização, identidade visual e responsividade.
- **JavaScript:** interações, carrinho de compras e funcionalidades do pedido.
- **Git e GitHub:** versionamento e documentação da evolução do projeto.

### Backend e banco de dados — etapas posteriores

- **Node.js:** execução de JavaScript no servidor.
- **Express:** desenvolvimento da API para comunicação entre frontend e backend.
- **PostgreSQL:** armazenamento de produtos, categorias, pedidos e informações relacionadas.

## Funcionalidades planejadas

### 1. Página inicial e cardápio

- Apresentação da marca.
- Produtos em destaque.
- Navegação por categorias.
- Listagem de produtos com imagens, descrições e preços.
- Informações sobre funcionamento, entrega e retirada.
- Cabeçalho com acesso ao carrinho e rodapé com informações da loja.

O cardápio utilizará um formato híbrido, combinando produtos em destaque com imagens maiores e listas mais compactas nas demais categorias.

### 2. Carrinho de compras

- Adição de produtos.
- Alteração das quantidades.
- Remoção de itens.
- Cálculo do subtotal e do valor total.

### 3. Finalização do pedido

- Identificação do cliente por nome e WhatsApp.
- Escolha entre entrega e retirada.
- Informações de endereço para pedidos com entrega.
- Cálculo da taxa de entrega.
- Seleção de pagamento presencial com cartão.
- Revisão dos itens e envio do pedido.

### 4. Acompanhamento do pedido

- Identificação do pedido.
- Resumo dos produtos e valores.
- Exibição do status do pedido, como aguardando confirmação, aceito ou recusado.

### 5. Funcionalidades futuras

- Área administrativa para gerenciamento de produtos e pedidos.
- Integração com o WhatsApp.
- Melhorias no gerenciamento da operação do estabelecimento.

> **Observação:** as funcionalidades serão implementadas progressivamente. O fluxo de recebimento e confirmação dos pedidos ainda será definido, e a integração com o WhatsApp está prevista para uma etapa posterior.

## Planejamento do banco de dados

A modelagem inicial do banco de dados PostgreSQL deverá contemplar as seguintes entidades:

| Entidade | Finalidade |
|---|---|
| Categorias | Organizar os produtos do cardápio |
| Produtos | Armazenar nome, descrição, preço, categoria e disponibilidade |
| Pedidos | Registrar data, status, valor total e dados necessários do cliente |
| Itens do pedido | Registrar produtos, quantidades e preços no momento da compra |

A estrutura poderá ser ampliada para contemplar adicionais, regras de entrega e outras necessidades identificadas durante o desenvolvimento.

## Responsividade

O desenvolvimento seguirá a abordagem **mobile-first**, priorizando a experiência em dispositivos móveis antes da adaptação para telas maiores.

Serão utilizados recursos do CSS, como Flexbox, Grid e media queries, para ajustar a organização dos elementos conforme a largura da tela.

O site será acessível diretamente pelo navegador, sem necessidade de instalação de aplicativo.

## Sobre o projeto

Este projeto é desenvolvido com foco no aprendizado prático de desenvolvimento web, na aplicação de boas práticas de organização de código e na construção de uma solução que considere as necessidades reais de um negócio local.

A proposta é evoluir gradualmente, desde a interface inicial até a implementação de um sistema completo de pedidos.

**Status:** Em desenvolvimento 🚧

**Localização do estabelecimento:** Vitória da Conquista — Bahia, Brasil.

**Área:** Desenvolvimento Web | Frontend | Backend | Banco de Dados
