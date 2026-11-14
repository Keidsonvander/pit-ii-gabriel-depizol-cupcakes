# Evidências dos Testes e Correções — PIT II

**Aluno:** Gabriel Messias Depizol  
**RGM:** 33627525  
**Projeto:** Aplicativo de vendas online para loja de cupcakes gourmet  
**Data dos testes:** 14/11/2026

## Participantes da avaliação
- André Luiz Carvalho
- Juliana Ferreira Mendes
- Vinicius Almeida Rocha
- Larissa Monteiro Santos
- Bruno César Nogueira

## 1. Mensagem de confirmação do carrinho
**Problema identificado:** a confirmação após adicionar um cupcake apresentava pouco destaque visual.

**Correção aplicada:** foram criadas mensagens visuais distintas para sucesso e erro, com maior contraste e texto mais claro.

**Evidência:** classes `msg ok` e `msg erro` e função `mensagem()` incluídas no arquivo `index.html`.

## 2. Validação dos campos obrigatórios
**Problema identificado:** a versão inicial dependia principalmente da validação padrão do navegador e não informava de forma conjunta quais dados estavam faltando.

**Correção aplicada:** o sistema passou a verificar nome, telefone, endereço, pagamento e entrega, listando os campos que precisam ser preenchidos.

**Evidência:** nova lógica de validação inserida no evento de finalização do formulário.

## 3. Acompanhamento do pedido
**Problema identificado:** a fase atual do pedido não possuía identificação suficientemente clara.

**Correção aplicada:** a etapa “Pedido recebido” passou a ter maior destaque e a indicação “atual”, mantendo visíveis as demais etapas.

**Evidência:** atualização do componente visual de acompanhamento do pedido no `index.html`.

## 4. Responsividade
**Problema identificado:** em telas menores, alguns campos, botões e componentes ficavam muito próximos.

**Correção aplicada:** foram ampliados espaçamentos, áreas de interação e organização dos elementos em smartphones.

**Evidência:** regras adicionais no media query para telas com largura de até 600 pixels.

## 5. Confirmação final
**Problema identificado:** a confirmação apresentava poucas informações após a conclusão do pedido.

**Correção aplicada:** foi criado um resumo contendo número do pedido, cliente, forma de pagamento, modalidade de entrega e status atual.

**Evidência:** novo bloco `confirmacao` incluído na interface.

## Nova verificação
Após as correções, foram revistos os seguintes recursos:
- vitrine virtual;
- carrinho;
- mensagens de retorno;
- validação dos dados;
- seleção do pagamento;
- modalidade de entrega;
- acompanhamento do pedido;
- confirmação final;
- comportamento em telas menores.

O fluxo principal apresentou funcionamento satisfatório após os ajustes.

## Funcionalidades ainda não implementadas
- cadastro e autenticação de usuários;
- pagamento real integrado;
- rastreamento de entrega em tempo real;
- histórico de pedidos;
- área administrativa;
- testes em uma variedade maior de aparelhos e navegadores.
