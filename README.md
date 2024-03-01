# ddd-domain-mapping

## Entities
- Produto
- Estoque
- Movimentacao de Estoque
- Limite Minimo de Estoque
- Alerta
- Historico
- Ordem de Compra
- Fornecedor

## Regras de negocio
- Cada produto deve ter uma identificação única, além de informações detalhadas sobre suas características.
- É necessário ser possivel estabelecer um limite mínimo de estoque para cada produto.
- Devem ser enviados alertas quando a quantidade de um produto atingir ou ficar abaixo do limite mínimo estabelecido.
- Os usuários devem poder acessar dados sobre vendas realizadas, lucro gerado por produto e tendências de estoque ao longo do tempo.
- O sistema deve ser capaz de gerar automaticamente ordens de compra com base nos limites mínimos de estoque e nas tendências de vendas.
- O sistema deve ser integrado aos fornecedores para receber atualizações automáticas sobre prazos de entrega e disponibilidade de produtos.
