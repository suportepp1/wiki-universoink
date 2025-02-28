# Pedidos

A área de Pedidos exibirá todos os pedidos realizados em sua loja. Como administrador, você poderá **acompanhar** cada pedido e verificar o andamento da produção pela **Universo Ink.** Todas as operações de gestão, como a transferência entre etapas (PRODUÇÃO, CONCLUÍDO, ENTREGUE), serão realizadas pela **Universo Ink** conforme o pedido avança na produção. Eventualmente você poderá utilizar essa área para comunicar algo específico sobre algum pedido para a Universo Ink.

A área de pedidos também possui funcionalidades que tem como objetivo auxiliar o administrador na gestão interna por meio da geração de documentos como **Ticket de Produção** e **Ordem de Serviço** e também por meio de alteração de pedidos em lote.


## Pedidos em Aberto

Nesta área serão classificados os pedidos que ainda estão pendentes de alguma ação por parte do cliente. Pedidos que estão na área de *Pedidos em Aberto* ainda não estão prontos para serem produzidos devido a esta causa.

<div align=center>
<img class="border1" width="30%" src="../_media/pedido.png"/>
</div>

### Incompletos

Os pedidos considerados como **Incompletos** são os pedidos em que o cliente está parado em alguma etapa logo após o carrinho, dentro do checkout. O cliente pode ter parado o processo na etapa de definição de endereço ou na etapa de seleção de meio de pagamento.

### Pendentes

Os pedidos considerados como **Pendentes** são os pedidos que estão aguardando algum tipo de decisão do cliente. São classificados dessa forma quando um pagamento é negado e então o cliente precisa realizar outro pagamento ou alterar o método de pagamento.

### Em Pagamento

Os pedidos considerados como **Em Pagamento** são os pedidos que estão aguardando o pagamento para que sejam processados e então aprovados. Em pedidos pagos com cartão de crédito, por exemplo, o pedido não passa por essa etapa pois assim que o pagamento é realizado , este é processado na hora e considerado como aprovado, diferetemente de um pagamento realizado com boleto, que demora em média 2 dias para ser processado.

> Em pedidos feitos com **transferência bancária** ou **PIX Estático**, o administrador precisa aprovar o pedido manualmente quando estiver no status de **Em pagamento**. Nestes meios de pagamento, o cliente anexa um comprovante que deve ser analisado pelo administrador que realizará este processo de aprovação.

### Abandonados

Os pedidos considerados com **Abandonados** são os pedidos que estão sem receber qualquer tipo de interação do cliente num período de 72 horas. Caso o pedido fique como Incompleto e o cliente não volte para finalizá-lo, o pedido será considerado como abandonado depois desse tempo, por exemplo.


## Pedidos Finalizados

Nesta área serão classificados os pedidos que já estão prontos para produção e envio por parte do administrador. São considerados pedidos já faturados/pagos e passarão por etapas até serem despachados. As etapas são as listadas a seguir:

<div align=center>
<img class="border1" width="30%" src="../_media/pedido2.png"/>
</div>

### Aprovados

São os pedidos que estão prontos para serem produzidos. Pedidos com o status de **Aprovado** já foram pagos/faturados pelos clientes.

### Em Produção

São os pedidos que estão na linha de produção da Universo Ink. 

### Concluídos

São os pedidos que tiveram sua produção finalizada e estão prontos para serem embalados e postados na transportadora pela Universo Ink.

### Entregue

Também chamados de *Despachados*, são os pedidos que já estão sob responsabilidade da transportadora ou já foram entregues ao cliente, logo, é onde se finaliza o processo de gerenciamento do pedido.

?> Pedidos considerados como **Concluídos** ou **Entregues** podem ser retornados para o status de **Em Produção**. Ao realizar isto, é necessário informar um *motivo* que ficará registrado no log de eventos do pedido. Esta operação será realizada também pela **Universo Ink**

### Todos os Pedidos

Aqui são listados todos os pedidos da loja, independentemente de status.