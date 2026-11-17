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
    
## Relatorio:
O projeto tem como objetivo o desenvolvimento de um sistema voltado para a otimização e o controle do processo de retirada de pedidos realizados online na empresa Translaser.
O sistema abrange desde o cadastro do cliente e a realização da compra até a separação dos produtos no estoque, o controle de status e o processo final de retirada na loja física.
Após efetuada a compra, o sistema identifica o pedido e seus respectivos itens, encaminha os pedidos para a fila de separação no estoque e aguarda a retirada na loja. O sistema também mantém um histórico de alterações de status do pedido, que aplica regras de cancelamento e retorno ao estoque para pedidos não retirados dentro do prazo máximo estipulado pela loja.
