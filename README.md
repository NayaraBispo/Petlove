# Petlove - Análise de Dados

# O problema

A equipe de assinaturas tem como objetivo reduzir a perda de assinantes. O termo "Churn" é ultilizado para referenciar a perda de qualquer usuário que assinou o serviço de assinatura da Petlove e o cancelou em algum momento após a contratação.

Para resolução do problema será considerado alguns questionamentos, tais como:
* Quais fatores influenciaram no cancelamento dos assinantes?
* Em qual período existiu uma maior quantidade de cancelamento de assinatura?
* A localidade tem relação com o aumento de cancelamento das assinaturas?


# Recursos

Neste projeto, foram utilizadas a linguagem de programação Python, as bibliotecas Pandas e Matplotlib.


# Sobre a amostra

A amostra contém dados dos clientes que realizaram a assinatura na PetLove no período de 19 de fevereiro de 2016 a 18 de fevereiro de 2021.


**Descrição das colunas da amostra:**

Column - Description

* id - Identificação do cliente
* created_at - Data de criação da assinatura
* updated_at - Data da última modificação da assinatura
* deleted_at - Data de cancelamento da assinatura
* name_hash - Nome do usuário (criptografado)
* email_hash - Email (criptografado)
* address_hash - Endereço (criptografado)
* birth_date - Data de aniversário do cliente
* status - Status da assinatura
* version - Versão da assinatura
* city - Cidade do cliente
* state - Estado do cliente
* neighborhood - Bairro do cliente
* last_date_purchase - Data do último pedido que ocorreu pela assinatura
* average_ticket - Média de gasto por pedido
* items_quantity - Média de itens na assinatura
* all_revenue - Total de receita realizado pelo cliente
* all_orders - Total de pedidos realizado pelo cliente
* recency - Tempo desde a última compra do cliente
* marketing_source - Canal de marketing que converteu a assinatura
