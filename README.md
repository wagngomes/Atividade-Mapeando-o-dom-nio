# Atividade-Mapeando-o-dom-nio

## Entidades
- Produtos ( id, tamanho, cor, estoque mínimo, custo)
- Vendas ( id , produto, quantidade, preço , cliente, data da venda)
- Ordens de compra ( id, produto ,fornecedor, quantidade, preço, data de criação, previsão de entrega)


## Casos de uso
- Rastrear produto individualmente
- Definir quantidades mínimas de estoque por produto
- Receber alertas de estoque baixo de um determinado produto
- Visualizar histórico de vendas
- Visualizar estoque
- Criar e gerenciar ordens de compra

## Não funcionais
- Alertas devem ser enviados por email e no sistema de gerenciamento de estoque
- Ordens de compra são criadas automaticamente, com base nos estoque mínimos definidos e nas tendências de vendas
- Integrar o sistema com os sistemas dos fornecedores parceiros para receber atrualizações
