# Documentação do Projeto — PIT II

## Identificação
**Aluno:** Gabriel Messias Depizol  
**RGM:** 33627525  
**Projeto:** Aplicativo de vendas online para loja de cupcakes gourmet

## 1. Continuidade da PIT I
A PIT II dá continuidade ao projeto de intervenção desenvolvido anteriormente para uma loja de cupcakes gourmet.

Na PIT I, o foco foi levantar corretamente os requisitos e organizar as histórias de usuário do sistema, considerando a necessidade de criar uma solução mais segura para a vitrine virtual, cadastro, carrinho, pedido eletrônico, pagamento e entrega.

## 2. Objetivo
Transformar a especificação inicial desenvolvida na PIT I em uma solução funcional e testável, mantendo coerência com os requisitos, histórias de usuário, critérios de aceitação, regras de negócio e backlog priorizado.

## 3. Metodologia utilizada
A organização do projeto segue práticas ágeis da Engenharia de Software, com foco em:
- elicitação e organização de requisitos;
- histórias de usuário;
- critérios de aceitação;
- regras de negócio;
- backlog priorizado;
- desenvolvimento incremental.

## 4. Principais perfis envolvidos
- Cliente;
- Administrador da loja;
- Entregador.

## 5. Fluxo principal da solução
1. acesso à vitrine virtual;
2. visualização dos produtos;
3. inclusão de cupcakes no carrinho;
4. preenchimento dos dados do cliente;
5. escolha da forma de pagamento;
6. definição da entrega;
7. confirmação do pedido;
8. acompanhamento do status.

## 6. Requisitos Funcionais
**RF01:** Exibir a vitrine virtual de cupcakes.  
**RF02:** Exibir nome, descrição e preço dos produtos.  
**RF03:** Permitir adicionar produtos ao carrinho.  
**RF04:** Atualizar quantidade e valor total do pedido.  
**RF05:** Permitir informar os dados do cliente.  
**RF06:** Permitir selecionar uma forma de pagamento.  
**RF07:** Permitir escolher a modalidade de entrega.  
**RF08:** Permitir finalizar o pedido eletrônico.  
**RF09:** Exibir confirmação após a finalização.  
**RF10:** Exibir o acompanhamento simplificado do pedido.

## 7. Requisitos Não Funcionais
- interface simples e organizada;
- boa legibilidade;
- layout responsivo;
- navegação intuitiva;
- validação de dados obrigatórios;
- retorno visual após ações importantes;
- organização do código e da documentação.

## 8. Histórias de Usuário
- Como cliente, quero visualizar os cupcakes disponíveis para escolher os produtos desejados.
- Como cliente, quero adicionar cupcakes ao carrinho para montar meu pedido.
- Como cliente, quero escolher uma forma de pagamento para concluir a compra.
- Como cliente, quero definir a forma de entrega para receber ou retirar o pedido.
- Como cliente, quero acompanhar o status para saber em qual etapa o pedido se encontra.

## 9. Critérios de Aceitação
- o catálogo deve apresentar os produtos disponíveis;
- o carrinho deve atualizar quantidade e valor total;
- os dados obrigatórios devem ser validados;
- a finalização deve apresentar confirmação;
- o status deve indicar a situação atual do pedido;
- a interface deve se adaptar a telas menores.

## 10. Regras de Negócio
- não permitir finalizar o pedido sem produtos no carrinho;
- exigir os dados necessários para concluir a compra;
- permitir apenas as formas de pagamento disponibilizadas;
- registrar uma modalidade de entrega;
- gerar identificação para o pedido finalizado.

## 11. Backlog Priorizado
### Alta prioridade
- vitrine de produtos;
- carrinho;
- dados do cliente;
- pedido eletrônico;
- pagamento;
- entrega.

### Média prioridade
- acompanhamento do pedido;
- confirmação detalhada;
- responsividade.

### Evoluções futuras
- autenticação;
- integração real com pagamentos;
- rastreamento em tempo real;
- histórico de pedidos;
- área administrativa.

## 12. Relação com a PIT I
Na PIT I, as necessidades da loja foram transformadas em requisitos claros, histórias de usuário e backlog priorizado. A PIT II utiliza essa especificação como base para a implementação da solução.

## 13. Controle de versão
O código-fonte, a documentação e as correções realizadas após os testes serão mantidos neste repositório GitHub.
