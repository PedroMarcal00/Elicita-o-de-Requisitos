# User Stories – Aplicativo de Delivery de Comida

Como PO do aplicativo, foram levantadas três necessidades vagas que foram transformadas em User Stories com critérios de aceite no formato *Dado / Quando / Então*.

---

## 1. Acompanhamento do pedido após a compra

**Necessidade:** O usuário precisa acompanhar o pedido depois de fazer a compra.

**User Story:**
> Como cliente, quero receber um aviso por mensagem para saber quando o pedido saiu para entrega.

**Prioridade (MoSCoW):** `Should`

**Critérios de Aceite:**

1. **Dado** que fiz o pedido, **quando** fiz o pagamento, **então** posso visualizar o andamento do pedido.
2. **Dado** que o entregador saiu com o pedido, **quando** isso ocorre, **então** recebo um aviso por notificação.
3. **Dado** que o pagamento foi finalizado, **quando** o cliente clicou no botão confirmar, **então** o pedido foi para a cozinha.

---

## 2. Aviso de indisponibilidade de item do cardápio

**Necessidade:** O restaurante precisa avisar quando um item do cardápio fica indisponível.

**User Story:**
> Como cliente, quero receber um aviso para saber se o produto está indisponível.

**Prioridade (MoSCoW):** `Must`

**Critérios de Aceite:**

1. **Dado** que não há mais o produto, **quando** o cliente tenta solicitá-lo, **então** o sistema não deixa avançar.
2. **Dado** que o produto está em falta, **quando** o cozinheiro verificou o estoque, **então** o cardápio é atualizado pelo gerente.
3. **Dado** que o produto fique indisponível, **quando** o cliente ainda está finalizando o pedido, **então** o sistema bloqueia a operação e explica o motivo.

---

## 3. Reporte de problema durante a entrega

**Necessidade:** O entregador precisa reportar um problema durante a entrega.

**User Story:**
> Como entregador, quero poder reportar um problema para o cliente e o fornecedor.

**Prioridade (MoSCoW):** `Could`

**Critérios de Aceite:**

1. **Dado** que o pedido seja cancelado, **quando** o pedido esteja em rota, **então** o entregador recebe um aviso por notificação.
2. **Dado** que um problema tenha sido reportado pelo entregador, **quando** o registro for salvo com sucesso, **então** o sistema deve notificar simultaneamente o cliente e o fornecedor, informando o tipo de problema e o horário em que ocorreu.
3. **Dado** que um problema tenha sido reportado, **quando** o cliente ou fornecedor acessar o pedido, **então** deve ser possível visualizar o status da ocorrência.
