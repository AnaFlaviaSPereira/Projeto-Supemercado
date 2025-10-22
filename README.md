### **Estudo de Caso: Sistema de Vendas para um Supermercado**

**Descrição do Problema**

Os proprietários de um supermercado precisam de um sistema que viabilize o
armazenamento de informações sobre seus produtos, colaboradores e clientes para que
no momento em que ocorram as vendas todas as informações possam ser guardadas em
uma base de dados segura, para que estes dados sirvam de insumos para realização de
futuras vendas que possam fidelizar os clientes que costumam realizar compras neste
supermercado.


1. **Requisitos do analisar**

- Realizar o levantamento de requisitos apresentando pelo menos 10 questões que
faria para que a base de dados possa ser criada;
 a) Evidenciar as perguntas
 b) Simular as respostas do cliente

2. **Modelar Banco de Dados**

- Através do levantamento de requisitos realizado, o aluno deve criar as modelagens
para que o banco de dados com todas as suas tabelas possam ser efetivamente
criadas;
 a) Modelo conceitual
 b) Modelo lógico
 c) Modelo físico (com código compatível para execução no MySQL)

**Solução**

**Perguntas para levantamento de requisitos**

1. Quais informações dos usuários devem ser armazenadas?

Resposta: precisamos armazenar:nome, e-mail, telefone, endereço e cpf.

2. Queremos programa de fidelidade/acúmulo de pontos?

Resposta: Sim, identificaremos o acúmulo de pontos por compra através do CPF do cliente.

3. Que informações precisamos sobre os produtos?

Resposta: Para cada produto precisaremos de: código, nome, categoria, preço de venda, estoque e fornecedor.

4. Uma venda pode ter vários itens? Como as vendas são registradas?

Resposta: Sim, cada venda pode ter vários itens. São registradas por clientes, colaboradores, preço unitário.

5. Como será o cadastro dos colaboradores?

Resposta: Cargo, nome, cpf, usuário e senha.

6. É necessário identificar controle de estoque?

Resposta: Sim, pois é necessário identificar quando um item está em falta.

7. É necessário controlar fornecedores? De quais informações iremos precisar?

Resposta: Sim. Nome, CNPJ, contato, telefone, produtos fornecidos e condições de pagamento.

8. Como realizar devoluções e estornos?

Resposta: O processo para realizar o estorno/devolução estão vinculadas à venda original com motivo, itens devolvidos, quem autorizou e ajuste de estoque.

9. Quais informações são necessárias num relátorio?

Resposta: Vendas por período, principais produtos, ticket médio, clientes por frequência, itens com estoque baixo, margem por produto, vendas por colaborador.

10. Quais requisitos necessários para integração com sistemas fiscais / emissão de cupom eletrônico?

Resposta: Integração com emissão de nota/ cupom fiscal eletrônico (número do documento, chave, série).

**Modelo Conceitual**

![Image](https://github.com/user-attachments/assets/59d83746-dac0-4c92-9982-1ba95e006142)

**Modelo Lógico**

![Image](https://github.com/user-attachments/assets/45e92e52-2550-4283-a8e7-cbe49d26676d)
