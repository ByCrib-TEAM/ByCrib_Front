# Projeto E-Commerce - ByCrib

Desenvolvimento de uma loja online para a ByCrib, uma empresa especializada em streetwear e sneakers, oferecendo produtos de diversas marcas nacionais e internacionais. O projeto visa expandir a presença digital da marca, proporcionando uma experiência de compra mais prática e acessível para seus clientes.

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- [Caetano P. Freitas](github.com/caetanopf)
- [João G. L. Martins](github.com/joaoguilherme222)
- [Lucas B. Amaya](github.com/bokorni)
- [Pedro H. Silva](github.com/pedroifc)

Links do projeto:
-   [Documentação (esse documento)](github.com/ByCrib-TEAM/ByCrib_Front?tab=readme-ov-file#bycrib_front)
-   Backend: [Repositório](github.com/ByCrib-TEAM/ByCrib_Back.git) e [Publicação]()
-   Frontend: [Repositório](github.com/ByCrib-TEAM/ByCrib_Front.git) e [Publicação]()

# 1. Desenvolvimento do Projeto

**Loja Online para a ByCrib**

A ByCrib é uma loja física especializada em streetwear e sneakers, localizada em Joinville, SC. Atualmente, as vendas ocorrem apenas presencialmente ou por meio de atendimento no WhatsApp, sem um sistema estruturado de e-commerce. Essa limitação reduz o alcance da loja e dificulta a experiência dos clientes que preferem comprar online.

Nosso projeto consiste no desenvolvimento de um site de e-commerce utilizando Vue.js e tecnologias complementares, permitindo que os clientes realizem compras diretamente pelo site, sem a necessidade de interação prévia com o atendimento. O site contará com um catálogo atualizado de produtos, integração com formas de envio e um sistema administrativo para gerenciamento dos produtos e pedidos.

**Motivo da Escolha**

Optamos por desenvolver uma loja online para a ByCrib porque a ausência de um site próprio impacta diretamente as vendas e a logística da empresa. Criar um sistema completo de e-commerce representa um desafio significativo para nosso aprendizado em desenvolvimento web, envolvendo frontend e backend feitos manualmente (high code).

# 2. Situação Problema

**Introdução**

A ByCrib é uma loja física localizada em Joinville, Santa Catarina, especializada na venda de roupas streetwear e sneakers. A marca já possui um público consolidado, que acompanha as novidades através das redes sociais. No entanto, a ausência de um site próprio limita o crescimento da empresa, tornando o processo de compra dependente do atendimento via WhatsApp ou da visita presencial à loja.

**Situação-Problema**

Atualmente, os clientes da ByCrib enfrentam dificuldades para visualizar o catálogo de produtos de forma prática e organizada. Como a loja não possui um site, as informações sobre os produtos são divulgadas apenas no Instagram ou no WhatsApp, onde as postagens podem se perder rapidamente. Muitos clientes gostariam de consultar o estoque antes de ir até a loja, mas a falta de um sistema adequado torna essa experiência pouco eficiente.

Outro grande problema é a logística de vendas para clientes de outras cidades. Embora a ByCrib receba pedidos de compradores fora de Joinville, todo o processo de cotação de frete e organização dos envios é feito manualmente, o que pode gerar atrasos e dificuldades na gestão das entregas. A falta de integração com transportadoras e cálculo automático de frete torna o envio pouco prático, limitando o potencial de vendas da loja.

**Conclusão**

A criação de uma loja online para a ByCrib resolveria essas questões, permitindo que os clientes tenham acesso a um catálogo atualizado e bem estruturado, além de facilitar o processo de compra. A integração de um sistema de cálculo de frete tornaria os envios mais eficientes, reduzindo o trabalho manual e garantindo mais agilidade na logística. Com essa solução, a ByCrib poderia expandir seu alcance e aumentar suas vendas, tornando-se mais competitiva no mercado.

# 3. Descrição da Proposta

Para solucionar os problemas identificados, desenvolveremos um site de e-commerce para a ByCrib, utilizando Vue.js para o frontend, garantindo um sistema funcional e responsivo, e Django com Python para o backend, além de outras tecnologias complementares. O site permitirá que os clientes realizem compras diretamente, sem precisar recorrer ao WhatsApp, e contará com integração para cálculo automático de frete, gerenciamento de estoque e envio de pedidos.

**Foco de Ação do Software**

O site será uma plataforma completa de e-commerce, permitindo que os clientes visualizem produtos, adicionem itens ao carrinho e finalizem compras diretamente no sistema. Ele também contará com integração de formas de envio para facilitar as entregas para fora da cidade.

**Níveis de Usuário**

O sistema contará com dois níveis de acesso:
- **Clientes**: poderão navegar pelo catálogo, adicionar produtos ao carrinho e realizar compras.
- **Administradores** (gestores da ByCrib): terão acesso a um painel de controle para cadastrar, editar e remover produtos, além de gerenciar pedidos e atualizar informações sobre os envios.

**Funcionalidades do Sistema**

- **Catálogo Virtual**: Página com listagem de produtos, imagens, descrições e preços atualizados.
- **Carrinho de Compras**: Funcionalidade que permite ao cliente selecionar produtos e visualizar o total da compra.
- **Integração com Formas de Envio**: Cálculo automático de frete com base no CEP do cliente e atualizações sobre a entrega de seu pedido.
- **Área Administrativa**: Painel de controle para que os gestores adicionem novos produtos, atualizem preços e gerenciem pedidos.
- **Finalização de Compra**: Sistema para que os clientes concluam a compra com pagamento online.
- **Contato Facilitado**: Links diretos para redes sociais e WhatsApp para suporte adicional.
