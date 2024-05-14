# Aplicação de Otimização de Picking

A **logística** tem se destacado como um elemento estratégico nas organizações, devido ao seu papel crucial na criação de uma vantagem competitiva. Isso é alcançado através de entregas rápidas, informações atualizadas sobre o transporte, segurança das cargas, entre outros aspectos.

O processo de **picking**, também conhecido como **order picking**, é a etapa em que os pedidos dos clientes são separados. Nesse processo, os colaboradores selecionam uma variedade de produtos do estoque e os encaminham para a área de expedição, onde serão verificados e preparados para o transporte.

O picking é um dos processos mais importantes em um centro de distribuição, pois é um fator decisivo para a compra e, principalmente, para a fidelização do cliente. Portanto, a separação deve ser meticulosa, rápida e de acordo com o pedido do cliente, para se tornar um diferencial competitivo da empresa.

Nesse contexto, desenvolvi uma aplicação simples, mas eficaz, para otimizar o processo de separação para picking em uma indústria alimentícia. A solução consiste em um **painel de separação**, desenvolvido em Python, integrado a um banco de dados MySQL, que contém dados de um ERP integrado a outra aplicação de checkout/coletor de dados.

O painel de separação é atualizado a cada 30 segundos, exibindo quais pedidos são prioritários para separação. Assim, a equipe de separação tem a informação de qual número de pedido deve ser digitado no coletor para iniciar o processo de separação. Pedidos em separação são exibidos na cor amarela e, quando a separação do pedido é concluída em 100%, o pedido é removido do painel, dando lugar a outro pedido prioritário ainda não separado.

Este projeto é um exemplo de como a tecnologia pode ser aplicada para melhorar a eficiência e a eficácia dos processos logísticos, contribuindo para a satisfação do cliente e o sucesso da empresa.
