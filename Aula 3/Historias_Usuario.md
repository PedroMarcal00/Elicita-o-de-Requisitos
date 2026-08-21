# Histórias de Usuário

## História 1

**Como** cliente, **quero** avaliar o pedido depois da entrega, **para** ajudar outros clientes a escolherem melhor.

**Critérios de Aceitação:**

- **Dado** que o pedido foi entregue, **quando** o cliente abre o app, **então** aparece a opção de avaliar o pedido.
- **Dado** que o cliente avalia com nota e comentário, **quando** confirma o envio, **então** a avaliação aparece no perfil do restaurante.

**Requisitos Não Funcionais (RNF):**

1. O usuário só pode avaliar apenas uma vez o pedido. `[SEGURANÇA]`
2. A avaliação aparece no perfil do restaurante em até 3 segundos. `[EFIC. DESEMPENHO]`
3. A notificação de avaliação aparece em até 5 segundos após a confirmação do pedido entregue. `[EFIC. DESEMPENHO]`

---

## História 2

**Como** cliente, **quero** salvar um cartão de pagamento, **para** não digitar os dados a cada compra.

**Critérios de Aceitação:**

- **Dado** que o cliente cadastra um cartão válido, **quando** confirma o cadastro, **então** o cartão fica disponível para escolha no checkout.
- **Dado** que o cliente tem um cartão salvo, **quando** faz um novo pedido, **então** pode selecionar esse cartão sem redigitar os dados.

**Requisitos Não Funcionais (RNF):**

1. Os dados do cartão são criptografados. `[SEGURANÇA]`
2. Os dados salvos do cartão ficam visíveis após login do usuário. `[SEGURANÇA]`
3. Um novo pedido é feito em apenas 5 cliques. `[USABILIDADE]`

---

## História 3

**Como** dono de restaurante, **quero** ver um resumo diário de vendas, **para** acompanhar o desempenho do dia.

**Critérios de Aceitação:**

- **Dado** que o dia comercial termina, **quando** o restaurante abre o painel de vendas, **então** vê o total de pedidos e o faturamento do dia.
- **Dado** que o restaurante seleciona um período diferente, **quando** aplica o filtro, **então** o resumo é recalculado para aquele período.

**Requisitos Não Funcionais (RNF):**

1. O tempo do recálculo do resumo leva 2 segundos. `[EFIC. DESEMPENHO]`
2. O usuário pode gerar um resumo em 3 cliques. `[USABILIDADE]`
3. É gerado um resumo do dia no horário selecionado pelo usuário. `[EFIC. DESEMPENHO]`
