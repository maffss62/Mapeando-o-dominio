# Mapeando-o-dominio


Entidades de domínio
Produto

Atributos: ID único, nome, tamanho, cor, quantidade atual, quantidade mínima de estoque, preço, histórico de movimentação.
Estoque

Atributos: Lista de produtos, níveis de estoque, status de alertas.
Venda

Atributos: ID da venda, data, produto(s) vendido(s), quantidade, preço total, lucro.
Ordem de Compra

Atributos: ID da ordem, produto(s) a serem adquiridos, quantidade, fornecedor, status da ordem, prazo de entrega.
Fornecedor

Atributos: Nome, contato, informações de entrega, histórico de pedidos.
Usuário do Sistema

Atributos: Nome, e-mail, preferências de alerta (e-mail, notificação no sistema).
Casos de uso (ações)
Gerenciar Produtos

Criar, editar ou excluir produtos.
Adicionar atributos como tamanho e cor.
Rastrear movimentações de estoque por produto.
Definir Quantidade Mínima de Estoque

Configurar limites mínimos por produto.
Atualizar configurações de estoque mínimo.
Receber Alertas de Estoque Baixo

Enviar notificações por e-mail.
Exibir alertas no sistema.
Visualizar Histórico de Vendas

Consultar vendas realizadas por período.
Visualizar lucro gerado por produto.
Analisar os produtos mais vendidos por período.
Gerenciar Tendências de Estoque

Exibir relatórios de movimentações e níveis de estoque ao longo do tempo.
Identificar tendências para decisões de compra.
Gerenciar Ordens de Compra

Criar ordens de compra com base no estoque mínimo e vendas.
Acompanhar o status das ordens.
Atualizar manualmente ou automaticamente o status de entrega.
Integrar com Fornecedores

Receber atualizações automáticas de prazos de entrega.
Consultar informações sobre fornecedores e históricos de pedidos.
Configurar Preferências de Alertas

Escolher método de recebimento de alertas (e-mail, sistema).
Personalizar as notificações.
