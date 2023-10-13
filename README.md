## Introdução

Visando inovar e oferecer soluções cada vez mais alinhadas às necessidades de clientes, será desenvolvido um novo produto voltado para finanças pessoais.
Este produto tem como objetivo auxiliar os clientes no controle e gestão de seus gastos, permitindo uma visão mais clara e estratégica de suas finanças.

## Desafio

No projeto de finanças pessoais, a base de dados inclui informações dos clientes, bem como seu histórico bancário e transações de cartão de crédito.

O desafio é **desenvolver uma solução para agrupar clientes baseado nos seus perfis de gastos**.
Para atingir esse objetivo, serão executados os seguintes passos:

1. Realizar uma análise exploratória profunda dos dados para entender as características e padrões de gastos dos clientes.
2. Criar uma nova feature que identifique se as transações se referem a gastos fixos ou variáveis.
3. Utilizar técnicas de clustering para segmentar os clientes em diferentes perfis de gastos.
4. Com base na análise exploratória, etiquetar cada cluster identificado com padrões de gastos quanto à quantidade, natureza (fixo/variado) e categoria da compra (como alimentação, saúde, lazer, etc.).
5. Responder às seguintes perguntas:
   - Quais os perfis de clientes que mais gastam proporcionalmente em gastos fixos?
   - Quais as categorias de compra que mais impactam nos perfis de gasto?
   - Quais são os perfis centrais (ou típicos) de cada cluster?

### Sobre os dados

Os dados estão disponíveis na pasta `data` e comportam informações de pessoas, contas e transações.
Sendo que a base de transações possui registros detalhados de transações bancárias e de cartão de crédito.
As bases se relacionam por meio de identificadores. 

Todos os dados disponibilizados são fictícios.