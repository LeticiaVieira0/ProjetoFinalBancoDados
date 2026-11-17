# Projeto Final Banco Dados

## Integrantes:
* Leticia
* Mi
* Nicole
* Thaissa

## Regras de negócio:

1. Um pedido pertence obrigatoriamente a um único cliente
2. Um pedido possui um ou mais itens, e a quantidade de cada item deve ser maior que zero
3. Todo pedido possui um código único de retirada
4. Os status possíveis de um pedido são: pendente, pronto, retirado ou cancelado
5. Um pedido cancelado não pode ser retirado
6. Quem retira o pedido deve ser o próprio cliente ou uma pessoa autorizada por ele, desde que possua o código de retirada
7. Toda retirada dever ter um funcionário responsável registrado
8. Toda retirada é registrada com data e hora
9. Cada mudança de status no pedido é registrada com data, hora e o funcionário responsável pela alteração
10. Pedidos não retirados em até 20 dias são cancelados e os itens voltam ao estoque
