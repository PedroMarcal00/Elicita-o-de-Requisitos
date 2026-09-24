# Atividade — Sua vez de elicitar
---

## Processo 1 — Registro de pedidos (vendedor)

### Requisito 1
**O sistema deve permitir que o vendedor registre um pedido informando o cliente, os produtos e as quantidades, tanto em atendimento por telefone quanto presencial.**

- **Fonte 1.** Entrevista com o vendedor. Fonte humana, nível operacional, classe de usuário vendedor.
- **Fonte 2.** Formulários e anotações de pedido usados hoje pela equipe de vendas. Fonte não humana, categoria documentação.

### Requisito 2
**O sistema deve verificar o saldo em estoque no momento do pedido e alertar o vendedor quando a quantidade solicitada for maior que a disponível.**

- **Fonte 1.** Reunião com o gerente de logística. Fonte humana, nível tático.
- **Fonte 2.** Planilha de controle de estoque em uso atualmente. Fonte não humana, categoria sistema legado.

### Requisito 3
**O sistema deve gerar um comprovante do pedido (com itens, valores e forma de pagamento) e emitir o documento fiscal exigido para a venda.**

- **Fonte 1.** Legislação fiscal sobre emissão de nota fiscal. Fonte não humana, categoria norma.
- **Fonte 2.** Entrevista com clientes que compram por telefone, para saber que confirmação esperam receber. Fonte humana, nível externo.

---

## Processo 2 — Cadastro e remoção de produtos (administrador)

### Requisito 4
**O sistema deve permitir que o administrador cadastre um produto informando código, nome, descrição, categoria e preço.**

- **Fonte 1.** Entrevista com o administrador. Fonte humana, nível operacional, classe de usuário administrador.
- **Fonte 2.** Catálogo de produtos e tabela de preços atuais da empresa. Fonte não humana, categoria documentação.

### Requisito 5
**O sistema não deve permitir a exclusão definitiva de um produto que tenha pedidos ou movimentações de estoque registrados; nesse caso, deve apenas inativá-lo.**

- **Fonte 1.** Entrevista com o gerente comercial, sobre o que fazer com produtos que saem de linha. Fonte humana, nível tático.
- **Fonte 2.** Legislação fiscal sobre a guarda de registros e documentos de venda. Fonte não humana, categoria norma.

### Requisito 6
**O sistema deve restringir o cadastro e a remoção de produtos ao perfil de administrador, registrando quem fez cada alteração e quando.**

- **Fonte 1.** Conversa com o diretor da empresa sobre quem deve ter autoridade sobre o catálogo. Fonte humana, nível estratégico.
- **Fonte 2.** Política interna de acesso e segurança da informação da empresa. Fonte não humana, categoria documentação.

---

## Processo 3 — Controle de estoque (time de estoque)

### Requisito 7
**O sistema deve permitir que o estoquista registre a saída de produtos, subtraindo a quantidade do saldo disponível.**

- **Fonte 1.** Entrevista com o estoquista. Fonte humana, nível operacional, classe de usuário estoquista.
- **Fonte 2.** Planilha de controle de estoque em uso atualmente, para entender como as baixas são feitas hoje. Fonte não humana, categoria sistema legado.

### Requisito 8
**O sistema deve permitir que o estoquista registre a entrada de mercadorias, informando produto, quantidade, data e fornecedor.**

- **Fonte 1.** Notas fiscais de compra e romaneios de entrega dos fornecedores. Fonte não humana, categoria documentação.
- **Fonte 2.** Entrevista com o fornecedor sobre como as entregas são feitas e documentadas. Fonte humana, nível externo.

### Requisito 9
**O sistema deve alertar a equipe quando o saldo de um produto ficar abaixo do estoque mínimo e emitir relatório das movimentações de entrada e saída por período.**

- **Fonte 1.** Reunião com o gerente de logística, para definir estoque mínimo e relatórios necessários. Fonte humana, nível tático.
- **Fonte 2.** Análise de sistemas de controle de estoque de outras empresas do mercado (benchmarking). Fonte não humana, categoria concorrência.
