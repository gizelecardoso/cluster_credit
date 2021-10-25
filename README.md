# Projeto Cluster

## Tema: Segmentação de Clientes por Dados de Crédito

<p>Objetivo: Este caso requer o desenvolvimento de uma segmentação de clientes para definir a estratégia de marketing. o
O conjunto de dados de amostra resume o comportamento de uso de cerca de 9.000 titulares de cartões de crédito ativos durante os últimos 6 meses. O arquivo está no nível do cliente com 18 variáveis ​​comportamentais.</p>

<p> Base de Dados da <a href='https://www.kaggle.com/arjunbhasin2013/ccdata'>Kaggle</a></p>

### Variáveis do conjunto de dados

* CUSTID: Identificação do titular do cartão de crédito (categórico)
* BALANCE: Saldo restante na conta para fazer compras (
* BALANCEFREQUENCY: a frequência com que o saldo é atualizado, pontuação entre 0 e 1 (1 = atualizado com frequência, 0 = não atualizado com frequência)
* PURCHASES: Quantidade de compras feitas da conta
* ONEOFFPURCHASES: valor máximo da compra feita de uma vez
* INSTALLMENTSPURCHASES: Valor da compra feita a prazo
* CASHADVANCE: adiantamento em dinheiro dado pelo usuário
* PURCHASESFREQUENCY: a frequência com que as compras estão sendo feitas, pontuação entre 0 e 1 (1 = compra frequente, 0 = compra pouco frequente)
* ONEOFFPURCHASESFREQUENCY: a frequência com que as compras acontecem de uma só vez (1 = compra frequente, 0 = compra não frequente)
* PURCHASESINSTALLMENTSFREQUENCY: Com que frequência as compras parceladas estão sendo feitas (1 = feito com frequência, 0 = não feito com frequência)
* CASHADVANCEFREQUENCY: com que frequência o dinheiro adiantado está sendo pago
* CASHADVANCETRX: Número de transações feitas com "Dinheiro adiantado"
* PURCHASESTRX: Numbe de transações de compra feitas
* CREDITLIMIT: Limite de cartão de crédito para o usuário
* PAYMENTS: Valor do pagamento feito pelo usuário
* MINIMUM_PAYMENTS: Quantidade mínima de pagamentos feitos pelo usuário
* PRCFULLPAYMENT: Porcentagem do pagamento total pago pelo usuário
* TENURE: Posse do serviço de cartão de crédito para o usuário


### Quais variáveis podemos trabalhar no contexto da Clusterização

<p> Variáveis Quantitativas </p>

* BALANCE: Saldo restante na conta para fazer compras
* PURCHASES: Quantidade de compras feitas da conta
* ONEOFFPURCHASES: valor máximo da compra feita de uma vez
* INSTALLMENTSPURCHASES: Valor da compra feita a prazo
* CASHADVANCE: adiantamento em dinheiro dado pelo usuário
* CASHADVANCETRX: Número de transações feitas com "Dinheiro adiantado"
* PURCHASESTRX: Número de transações de compra feitas
* CREDITLIMIT: Limite de cartão de crédito para o usuário
* PAYMENTS: Valor do pagamento feito pelo usuário
* MINIMUM_PAYMENTS: Quantidade mínima de pagamentos feitos pelo usuário
* PRCFULLPAYMENT: Porcentagem do pagamento total pago pelo usuário
* TENURE: Posse do serviço de cartão de crédito para o usuário