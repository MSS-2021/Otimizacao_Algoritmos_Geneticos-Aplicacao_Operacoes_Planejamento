# Otimização por Algoritmos Genéticos: Aplicação no planejamento das operações de carregamento de linhas flexíveis

Aluno: Marcos Sidnei Silva

Matrícula: 211.101.157

Orientadora: Ana Carolina Alves Abreu

## Resumo

A solução proposta neste trabalho consiste na aplicação de algoritmos genéticos na otimização dos custos das operações de carregamento de linhas flexíveis em uma empresa de grande porte, que atua no seguimento de óleo e gás.

O planejamento das operações de carregamento realizado atualmente tem como objetivo principal distribuir a demanda de carregamento entre os diferentes complexos portuários disponíveis, priorizando o nivelamento da utilização da capacidade dos recursos (berços de atracação de embarcações), sendo o aspecto custo considerado apenas nos casos nos quais existe a possibilidade de realizar estas operações diretamente nos fornecedores. Apesar de se tratar de uma atividade secundária, os serviços de logística de base envolvem valores representativos, desta forma, identificou-se a oportunidade de acrescentar ao planejamento critérios que objetivam a otimização dos custos, tanto relacionados ao suprimento dos bens (referente a entrega nas bases de carregamento contratadas por disponibilidade ou carregamento diretamente nos fornecedores) quanto ao deslocamento das embarcações até os locais de aplicação das linhas, sem deixar de considerar, é claro, a necessidade de atendimento as restrições de capacidade de carregamento nos diferentes complexos portuários.

O modelo de otimização em algoritmos genéticos foi implementado em Python, utilizando a biblioteca deap. O modelo recebe como dados de entrada informações particulares dos projetos, como por exemplo, o tipo de linha flexível, quantidade (em unidades), o local de aplicação, o tipo de operação de carregamento que será realizada, a data prevista e a identificação do contrato de fornecimento da linha. Ademais, são utilizadas informações referentes as condições de fornecimento prevista em cada contrato, bem como informações referentes as distâncias entre os locais de carregamento e os locais de aplicação. Conforme já informado anteriormente, a função objetivo busca minimizar o custo total para atendimento a demanda planejada, considerando como restrição a capacidade mensal dos complexos portuários próprios e de fornecedores.
