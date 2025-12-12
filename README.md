Análise Exploratória de Dados — Pós-Venda e Custo Invisível
 Contexto do Projeto

Este projeto simula o cenário de uma indústria de bens duráveis que enfrenta problemas no pós-venda, envolvendo assistência técnica, reclamações no Reclame Aqui e impacto na recompra de clientes.

Apesar do crescimento nas vendas, a empresa percebe queda na satisfação do cliente e perda de valor ao longo do tempo. O desafio central é entender onde o pós-venda está falhando, quais fatores realmente explicam a insatisfação e quanto isso custa financeiramente.

 Objetivo

Utilizar Análise Exploratória de Dados (EDA) para:

Identificar padrões de problemas no pós-venda

Avaliar o impacto de chamados, reaberturas e reclamações públicas

Medir o efeito do pós-venda na recompra de clientes

Estimar o custo invisível gerado após a venda

Simular o impacto financeiro de melhorias no processo

 Estrutura dos Dados

O dataset sintético contém aproximadamente 3.000 registros, com informações sobre:

Cliente e produto

Linha de produto (Econômica, Premium, Branca)

Canal de venda

Chamados de assistência técnica

Tempo de resolução e reaberturas

Reclamações no Reclame Aqui

Nota da reclamação

Recompra em até 6 meses e valor associado

Os dados foram projetados para refletir situações reais, incluindo valores nulos que representam eventos não ocorridos (ex.: clientes que não reclamaram).

 Principais Perguntas de Negócio

Produtos mais vendidos são os que mais geram problemas?

Reabrir chamados piora a avaliação do cliente?

Tempo de resolução elevado gera mais reclamações públicas?

Reclamar no Reclame Aqui reduz a recompra?

O canal de venda influencia a taxa de reclamação?

Qual linha de produto gera maior custo invisível de pós-venda?

 Principais Análises e Insights
- Pós-Venda não é explicado por volume

Produtos mais vendidos não são necessariamente os que apresentam maior taxa proporcional de problemas.

- Reabertura e tempo não explicam sozinhos a insatisfação

Reabertura de chamados não reduz automaticamente a nota no Reclame Aqui

Tempo de resolução, inclusive acima de 30 dias, não é o principal gatilho de reclamações

- Reclamação pública impacta fidelização

Clientes que reclamam no Reclame Aqui apresentam menor taxa de recompra, evidenciando impacto direto no valor do cliente ao longo do tempo.

- Canal de venda não é o vilão

Não foi identificada associação estatisticamente significativa entre canal de venda e taxa de reclamação.

 Índice de Custo Invisível do Pós-Venda

Foi criado um índice composto para avaliar o impacto do pós-venda por linha de produto, considerando:

Taxa de chamados

Tempo médio de resolução

Taxa de reabertura

Taxa de recompra (invertida)

 Ranking de Custo Invisível

Linha Econômica — maior custo invisível

Linha Premium — custo elevado por complexidade de resolução

Linha Branca — melhor equilíbrio entre volume, custo e retorno

 Demonstrativo Financeiro

Foi simulada uma melhoria conservadora no pós-venda, incluindo:

Redução de chamados e reaberturas

Redução do tempo médio de resolução

Pequeno aumento na taxa de recompra

 Impacto estimado (6 meses):

Economia de custos: ~R$ 75 mil

Receita incremental: ~R$ 195 mil

Ganho total: ~R$ 270 mil

 O maior ganho vem da recuperação de receita, não apenas da redução de custos.

 Conclusão

O projeto demonstra que o maior problema do pós-venda não está no tempo ou no canal, mas na qualidade da experiência e na eficiência da resolução.

O pós-venda, quando mal gerido, gera um custo invisível relevante.
Quando bem estruturado, torna-se um motor de fidelização e crescimento financeiro.

 Tecnologias Utilizadas

Python

Pandas

Matplotlib

Análise Exploratória de Dados (EDA)
