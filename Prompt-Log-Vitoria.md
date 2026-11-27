## Prompt 1: Product Owner

**Prompt:**
PROMPT 1 — PRODUCT OWNER | iFoome Delivery
Agora iniciaremos a primeira etapa de desenvolvimento do iFoome Delivery.
Antes de realizar qualquer alteração, leia o README.md criado na etapa anterior e analise os arquivos existentes no projeto.
Você deverá assumir a perspectiva de um Product Owner (PO), responsável por compreender o problema, organizar os requisitos, definir prioridades e garantir que o produto não perca seu propósito.
1. Objetivo desta etapa
Transformar o contexto inicial do projeto em uma especificação clara do produto, estabelecendo o que deverá ser desenvolvido nas próximas etapas.
Não desenvolva ainda a interface completa nem implemente as funcionalidades.
2. Requisitos funcionais
Documente os requisitos funcionais do sistema, organizando-os em três grupos.
A. Cardápio digital
O proprietário deverá conseguir:
Visualizar os produtos cadastrados.
Adicionar novos pratos.
Editar informações dos pratos.
Excluir produtos.
Informar nome, descrição, ingredientes e preço.
Adicionar fotografias.
Organizar produtos por categorias.
Marcar produtos como disponíveis ou indisponíveis.
O cardápio deverá apresentar somente os produtos disponíveis aos clientes.
B. Pedidos
O cliente deverá conseguir:
Acessar o cardápio sem realizar cadastro.
Selecionar produtos e quantidades.
Adicionar observações ao pedido.
Visualizar o carrinho e o valor total.
Informar nome e telefone.
Informar endereço quando escolher entrega.
Escolher entre entrega e retirada.
Informar a forma de pagamento.
Finalizar o pedido.
O proprietário deverá conseguir visualizar os pedidos e acompanhar seus respectivos status.
Defina regras claras para evitar pedidos incompletos, valores incorretos ou informações perdidas.
C. Resumo diário
O sistema deverá apresentar:
Quantidade de pedidos recebidos no dia.
Total vendido no dia.
Quantidade de pedidos em andamento.
Histórico simples dos pedidos.
O cálculo do total vendido deverá considerar os pedidos válidos, evitando somar pedidos cancelados.
3. Regras de negócio
Defina regras para o funcionamento do sistema, considerando situações como:
O que acontece quando um produto fica indisponível?
O cliente poderá finalizar um pedido quando o restaurante estiver fechado?
Como será calculada a taxa de entrega?
Como serão tratados os pedidos cancelados?
Em que momento um pedido será considerado uma venda?
O que acontece quando o cliente escolhe retirada no estabelecimento?
Adote soluções simples e coerentes com a realidade de uma pequena marmitaria.
Quando alguma configuração ainda não estiver definida, estabeleça um padrão inicial que possa ser alterado posteriormente pelo proprietário.
4. Fluxos principais
Documente os dois principais caminhos de utilização.
Fluxo do proprietário:
Acessar o sistema → visualizar painel → administrar cardápio → consultar pedidos → atualizar status → acompanhar resumo diário.
Fluxo do cliente:
Acessar cardápio → escolher produtos → adicionar ao carrinho → preencher informações → finalizar pedido → receber confirmação.
5. Priorização
Organize as funcionalidades em:
Essenciais para o MVP.
Importantes, mas que podem ser desenvolvidas depois.
Futuras, fora do escopo inicial.
O MVP deve permanecer concentrado nas quatro funcionalidades centrais definidas no briefing oficial.
A geração de descrições com IA deverá ser considerada complementar.
6. Entregáveis desta etapa
Crie os seguintes documentos:
PRD.md: documento de requisitos do produto.
Regras-de-Negocio.md: regras de funcionamento.
Fluxos-do-Usuario.md: descrição dos caminhos do proprietário e do cliente.
Atualize também o README.md caso alguma informação importante tenha sido detalhada.
Os documentos deverão ser objetivos e servir como referência para os próximos profissionais.
Não invente requisitos complexos nem amplie desnecessariamente o escopo.
7. Personalização opcional
A equipe poderá personalizar alguns aspectos antes da execução:
Nome utilizado para os status dos pedidos.
Categorias iniciais do cardápio.
Formas de pagamento aceitas.
Regras de entrega e retirada.
Indicadores adicionais do painel.
Caso nenhuma personalização seja feita, utilize as definições padrão mais simples e coerentes com o cenário de Seu Raimundo.

8. Encerramento
Nesta etapa, sua responsabilidade é organizar e documentar o produto, não construir a aplicação.
Preserve todos os arquivos existentes e não descarte informações do README.
Ao concluir, apresente um resumo dos requisitos definidos e aguarde o próximo prompt.


**Objetivo:** transformar o contexto do iFoome Delivery em especificação de produto (PRD, regras de negócio e fluxos), no papel de Product Owner.

**Resultado da IA:** (com suas palavras: quais documentos gerou e o que sugeriu de mais complexo)

**Correção:** (o que você mudou: tirou login obrigatório e frete por GPS, manteve pedido sem cadastro e taxa fixa, ajustou o nome do produto)
