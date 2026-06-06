# Miniguia de Educação Financeira com NotebookLM

> Projeto desenvolvido para o desafio da DIO sobre o uso da Inteligência Artificial como ferramenta de aprendizagem ativa.

## 📌 Sobre o projeto

Este projeto apresenta a construção de um caderno temático no NotebookLM sobre **educação financeira pessoal**, com foco em três assuntos introdutórios:

- organização do orçamento pessoal;
- compreensão dos juros simples e compostos;
- formação de uma reserva de emergência.

A proposta utiliza fontes abertas e confiáveis para criar um miniguia de estudo, registrar testes de prompts e demonstrar como a Inteligência Artificial pode apoiar a leitura, a revisão e a organização do conhecimento.

> **Aviso:** este conteúdo possui finalidade exclusivamente educacional e não representa recomendação individual de investimento.

---

## 🎯 Contexto e objetivos de estudo

A educação financeira ajuda as pessoas a compreenderem melhor como recebem, gastam, economizam e investem seu dinheiro. Apesar de conceitos como orçamento, juros, liquidez e rentabilidade fazerem parte da vida cotidiana, muitas decisões financeiras são tomadas sem planejamento ou sem a compreensão adequada dos custos envolvidos.

O objetivo deste caderno temático é utilizar o NotebookLM para estudar fontes oficiais, comparar conceitos e transformar materiais extensos em conteúdos mais simples e organizados.

### Objetivo geral

Compreender os fundamentos da educação financeira pessoal e desenvolver uma rotina inicial de organização financeira.

### Objetivos específicos

1. Entender a função do orçamento pessoal.
2. Diferenciar receitas, despesas fixas e despesas variáveis.
3. Compreender a diferença entre juros simples e juros compostos.
4. Identificar os efeitos dos juros em investimentos e dívidas.
5. Entender a finalidade de uma reserva de emergência.
6. Aprender conceitos básicos como liquidez, risco, inflação e rentabilidade.
7. Criar prompts reutilizáveis para futuras revisões no NotebookLM.

---

## 📚 Curadoria de fontes

Foram selecionadas cinco fontes abertas, priorizando materiais oficiais e conteúdos introdutórios.

| Nº | Fonte | Instituição | Formato | Motivo da escolha |
|---|---|---|---|---|
| 1 | [Caderno de Educação Financeira — Gestão de Finanças Pessoais](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) | Banco Central do Brasil | PDF | Apresenta orçamento, planejamento, consumo, crédito, poupança e investimentos. |
| 2 | [Orçamento Pessoal](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Folhetos_Serie_II_Financas_Pessoais/folder_serie_II_orcamento_pessoal.pdf) | Banco Central do Brasil | PDF | Material curto e prático para iniciar o controle das receitas e despesas. |
| 3 | [Glossário Simplificado de Termos Financeiros](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Informacoes_gerais/glossario_cidadania_financeira.pdf) | Banco Central do Brasil | PDF | Reúne definições acessíveis de conceitos financeiros importantes. |
| 4 | [Juros Simples e Compostos: impactos no cenário financeiro](https://www.gov.br/investidor/pt-br/penso-logo-invisto/juros-simples-e-compostos-um-estudo-detalhado-sobre-seus-impactos-no-cenario-financeiro) | Portal do Investidor / Governo Federal | Texto | Explica a importância dos juros em dívidas e na construção de patrimônio. |
| 5 | [Tesouro Selic](https://www.tesourodireto.com.br/produtos/titulos/selic) | Tesouro Direto | Texto | Apresenta um exemplo de produto associado à reserva de emergência, com foco em segurança e liquidez. |

### Critérios utilizados na curadoria

- fontes gratuitas e abertas;
- linguagem adequada para iniciantes;
- preferência por instituições oficiais;
- relação direta com o tema escolhido;
- presença de conceitos que podem ser comparados entre as fontes.

---

## 🧠 Organização do caderno no NotebookLM

O caderno temático foi planejado com a seguinte estrutura:

1. **Fontes:** upload dos três PDFs e inclusão dos dois textos disponíveis na internet.
2. **Objetivos:** definição das perguntas que deveriam ser respondidas ao final do estudo.
3. **Consultas iniciais:** perguntas gerais para identificar os principais tópicos das fontes.
4. **Consultas específicas:** perguntas comparativas e aplicação dos conceitos em exemplos.
5. **Validação:** conferência das referências indicadas pelo NotebookLM.
6. **Consolidação:** elaboração deste miniguia, do glossário e da biblioteca de prompts.

---

## 🧪 Engenharia de prompts e “cicatrizes”

Esta seção registra o raciocínio por trás dos prompts, as limitações encontradas e as melhorias aplicadas.

### Teste 1 — Resumo geral

**Prompt inicial**

> Resuma as fontes sobre educação financeira.

**Resultado observado**

O comando é amplo e tende a produzir uma resposta genérica, misturando orçamento, crédito, juros e investimentos sem indicar uma ordem de estudo.

**Cicatriz identificada**

Faltaram público-alvo, formato, limite de tópicos e exigência de referências.

**Prompt melhorado**

> Usando somente as fontes adicionadas ao caderno, produza um resumo introdutório sobre educação financeira para uma pessoa sem conhecimento prévio. Organize a resposta em quatro partes: orçamento pessoal, controle de despesas, juros e reserva de emergência. Em cada parte, apresente a ideia principal, um exemplo cotidiano e as fontes utilizadas.

**Melhoria obtida**

A resposta tende a ficar mais organizada, didática e fácil de conferir nas fontes.

---

### Teste 2 — Comparação de juros

**Prompt inicial**

> Qual é a diferença entre juros simples e compostos?

**Resultado observado**

A explicação conceitual pode ser correta, porém insuficiente para visualizar o impacto financeiro.

**Cicatriz identificada**

O prompt não exigia um exemplo com valores iguais nem solicitava comparação entre os resultados.

**Prompt melhorado**

> Explique a diferença entre juros simples e juros compostos utilizando o mesmo capital inicial, a mesma taxa e o mesmo período. Apresente uma tabela comparativa, explique o cálculo em linguagem simples e informe em quais situações cada tipo de juro pode aparecer.

**Melhoria obtida**

O exemplo numérico torna a diferença mais clara e ajuda a relacionar o conceito com dívidas e investimentos.

---

### Teste 3 — Criação de um plano financeiro

**Prompt inicial**

> Crie um plano para organizar minhas finanças.

**Resultado observado**

A resposta pode trazer recomendações genéricas, sem conexão direta com as fontes do caderno.

**Cicatriz identificada**

Faltaram dados do cenário, prazo, objetivo e regra para não inventar informações.

**Prompt melhorado**

> Com base exclusivamente nas fontes do caderno, crie um plano financeiro inicial de 30 dias para uma pessoa que recebe R$ 3.000 por mês, possui despesas essenciais de R$ 1.800, despesas variáveis de R$ 800 e deseja começar uma reserva de emergência. Não indique produtos específicos como recomendação. Apresente ações semanais, metas mensuráveis e alertas sobre limitações do plano.

**Melhoria obtida**

O plano se torna mais aplicável, mensurável e alinhado ao objetivo de aprendizagem.

---

### Teste 4 — Glossário

**Prompt inicial**

> Faça um glossário financeiro.

**Resultado observado**

A IA pode selecionar termos demais ou trazer conceitos que não aparecem nas fontes.

**Cicatriz identificada**

Não havia limite de termos nem exigência de linguagem acessível.

**Prompt melhorado**

> Selecione 12 conceitos essenciais presentes nas fontes para uma pessoa iniciante em educação financeira. Para cada conceito, apresente: definição em linguagem simples, exemplo cotidiano e fonte de referência. Não inclua termos que não estejam presentes nos materiais.

**Melhoria obtida**

O glossário fica mais objetivo, verificável e adequado ao nível introdutório.

---

## 📝 Registro resumido das respostas e referências

> As respostas abaixo representam uma consolidação de estudo baseada nas fontes selecionadas. Ao reproduzir o projeto no NotebookLM, recomenda-se salvar também as respostas reais e as referências exibidas pela ferramenta.

| Pergunta estratégica | Síntese da resposta | Fontes principais |
|---|---|---|
| Por que elaborar um orçamento pessoal? | O orçamento permite visualizar receitas e despesas, identificar hábitos de consumo, definir prioridades, preparar-se para imprevistos e planejar objetivos. | Caderno de Educação Financeira; Orçamento Pessoal |
| Como iniciar o controle financeiro? | O primeiro passo é registrar todas as entradas e saídas, separar despesas por categorias e comparar o total gasto com a renda disponível. | Orçamento Pessoal; Caderno de Educação Financeira |
| Qual é a diferença entre juros simples e compostos? | Nos juros simples, a taxa incide sobre o capital inicial. Nos compostos, os juros acumulados passam a fazer parte da base dos cálculos seguintes. | Portal do Investidor |
| Por que os juros compostos merecem atenção? | Eles podem favorecer a acumulação de patrimônio ao longo do tempo, mas também podem acelerar o crescimento de dívidas. | Portal do Investidor |
| O que observar em uma reserva de emergência? | A reserva deve priorizar disponibilidade do dinheiro, segurança e compatibilidade com necessidades imprevistas. | Caderno de Educação Financeira; Tesouro Selic; Glossário |
| O que é liquidez? | É a capacidade de transformar um ativo ou investimento em dinheiro disponível. | Glossário Simplificado de Termos Financeiros |

---

# 📖 Miniguia de estudo

## 1. Orçamento pessoal

O orçamento pessoal é uma ferramenta de planejamento utilizada para organizar as receitas, as despesas e os objetivos financeiros. Ele ajuda a responder perguntas básicas: quanto dinheiro entra, quanto sai, onde está sendo gasto e quanto pode ser reservado para o futuro.

Um orçamento não deve ser visto apenas como uma forma de cortar gastos. Ele também permite definir prioridades, planejar compras, reduzir desperdícios e preparar-se para situações inesperadas.

### Passos iniciais

1. Registrar todas as receitas do mês.
2. Registrar todas as despesas, inclusive pequenos gastos.
3. Separar as despesas em categorias.
4. Comparar receitas e despesas.
5. Identificar gastos que podem ser reduzidos.
6. Definir uma meta realista de economia.
7. Revisar o orçamento todos os meses.

### Exemplo de orçamento mensal

| Categoria | Valor |
|---|---:|
| Receita mensal | R$ 3.000 |
| Despesas essenciais | R$ 1.800 |
| Despesas variáveis | R$ 800 |
| Valor disponível para objetivos | R$ 400 |

Nesse exemplo, a pessoa possui um saldo positivo de R$ 400. Esse valor pode ser direcionado para objetivos financeiros, como a criação de uma reserva de emergência.

---

## 2. Receitas e despesas

### Receitas

São os valores recebidos, como salário, comissões, prestação de serviços, benefícios ou rendimentos.

### Despesas fixas

São gastos recorrentes que costumam ter pouca variação, como aluguel, mensalidade e prestação.

### Despesas variáveis

São gastos que mudam de valor conforme o consumo, como alimentação fora de casa, lazer, transporte e compras não essenciais.

### Despesas imprevistas

São gastos que não estavam programados, como reparos, problemas de saúde ou perda de renda. A reserva de emergência ajuda a lidar com essas situações.

---

## 3. Juros simples e juros compostos

Os juros representam o custo do dinheiro ao longo do tempo. Eles podem aparecer quando alguém contrata crédito, atrasa um pagamento ou realiza um investimento.

### Juros simples

Nos juros simples, a taxa incide sempre sobre o valor inicial.

**Exemplo:** capital de R$ 1.000, taxa de 1% ao mês e prazo de 12 meses.

- Juros mensais: R$ 10
- Juros totais: R$ 120
- Montante final: R$ 1.120

### Juros compostos

Nos juros compostos, os juros de cada período são incorporados ao saldo. Por isso, os cálculos seguintes incidem sobre um valor acumulado.

Utilizando o mesmo exemplo:

- Capital inicial: R$ 1.000
- Taxa: 1% ao mês
- Prazo: 12 meses
- Montante aproximado: R$ 1.126,83

A diferença parece pequena nesse exemplo, mas cresce conforme o prazo, a taxa e o valor aumentam.

### Aplicação prática

- Em investimentos, os juros compostos podem contribuir para o crescimento do patrimônio.
- Em dívidas, podem aumentar rapidamente o saldo devedor.
- Antes de contratar crédito, é importante observar taxas, encargos e o Custo Efetivo Total.

---

## 4. Reserva de emergência

A reserva de emergência é um valor guardado para cobrir despesas inesperadas ou períodos de redução de renda. Sua finalidade é evitar que a pessoa dependa imediatamente de empréstimos, cheque especial ou crédito rotativo em uma situação urgente.

### Características importantes

- **Disponibilidade:** o dinheiro deve poder ser acessado quando necessário.
- **Segurança:** o objetivo principal é proteção, e não a busca do maior retorno possível.
- **Liquidez:** deve ser possível transformar o valor investido em dinheiro com facilidade.
- **Planejamento:** a reserva deve ser construída gradualmente, respeitando o orçamento.

Não existe um valor único adequado para todas as pessoas. O tamanho da reserva depende das despesas mensais, da estabilidade da renda e das responsabilidades individuais.

### Exemplo de construção gradual

Uma pessoa que consegue reservar R$ 400 por mês pode iniciar da seguinte forma:

| Período | Total acumulado, sem considerar rendimentos |
|---|---:|
| 1 mês | R$ 400 |
| 3 meses | R$ 1.200 |
| 6 meses | R$ 2.400 |
| 12 meses | R$ 4.800 |

O mais importante no início é criar consistência e revisar a meta conforme a realidade financeira mudar.

---

## 5. Roteiro prático de 30 dias

### Semana 1 — Diagnóstico

- registrar todas as receitas;
- anotar todos os gastos;
- identificar dívidas e pagamentos recorrentes;
- separar despesas essenciais e não essenciais.

### Semana 2 — Organização

- criar categorias de gastos;
- identificar desperdícios;
- definir limites para despesas variáveis;
- estabelecer uma meta inicial de economia.

### Semana 3 — Execução

- reduzir gastos escolhidos;
- transferir o valor da meta para uma reserva separada;
- evitar novas dívidas desnecessárias;
- acompanhar o orçamento durante a semana.

### Semana 4 — Revisão

- comparar o planejamento com os gastos reais;
- identificar dificuldades;
- ajustar limites e metas;
- preparar o orçamento do mês seguinte.

---

## 📘 Glossário de conceitos

| Conceito | Definição simples |
|---|---|
| **Receita** | Dinheiro recebido em determinado período. |
| **Despesa** | Valor gasto para adquirir produtos, serviços ou cumprir obrigações. |
| **Orçamento pessoal** | Organização das receitas, despesas e objetivos financeiros. |
| **Saldo positivo** | Situação em que as receitas são maiores do que as despesas. |
| **Juros** | Valor pago ou recebido pelo uso do dinheiro ao longo do tempo. |
| **Juros simples** | Juros calculados sempre sobre o valor inicial. |
| **Juros compostos** | Juros calculados sobre o valor acumulado, incluindo juros anteriores. |
| **Custo Efetivo Total — CET** | Percentual que reúne os custos e encargos de uma operação de crédito. |
| **Liquidez** | Facilidade de transformar um ativo ou investimento em dinheiro disponível. |
| **Rentabilidade** | Percentual que representa o retorno de um investimento. |
| **Risco** | Possibilidade de obter resultado diferente do esperado ou sofrer perdas. |
| **Inflação** | Aumento contínuo e generalizado dos preços de bens e serviços. |
| **Poupança ou economia** | Parte da renda que não é gasta e é guardada para uso futuro. |
| **Reserva de emergência** | Valor separado para cobrir despesas inesperadas ou períodos de redução da renda. |

---

## ♻️ Biblioteca de prompts reutilizáveis

### Prompt para resumo estruturado

> Usando somente as fontes deste caderno, resuma o tema **[INSERIR TEMA]** para uma pessoa iniciante. Organize a resposta em definição, importância, exemplo prático, erros comuns e referências utilizadas.

### Prompt para comparação

> Compare **[CONCEITO A]** e **[CONCEITO B]** com base nas fontes. Apresente semelhanças, diferenças, exemplos cotidianos e uma tabela final. Informe as referências de cada afirmação importante.

### Prompt para revisão rápida

> Crie uma revisão de cinco minutos sobre **[TEMA]**, destacando os cinco conceitos mais importantes, três erros comuns e três perguntas de autoavaliação.

### Prompt para perguntas de estudo

> Crie dez perguntas progressivas sobre **[TEMA]**, começando pelo nível básico e avançando para aplicações práticas. Depois, apresente um gabarito comentado baseado nas fontes.

### Prompt para identificar divergências

> Analise como as fontes explicam **[TEMA]**. Identifique diferenças de enfoque, pontos complementares e possíveis limitações. Não apresente informações externas ao caderno.

### Prompt para criar plano prático

> Com base somente nas fontes, crie um plano de **[NÚMERO]** dias para alcançar o objetivo **[OBJETIVO]**. Apresente ações semanais, indicadores de acompanhamento, riscos e limitações.

### Prompt para verificar compreensão

> Faça uma simulação de entrevista sobre **[TEMA]**. Apresente uma pergunta por vez, avalie minha resposta e explique o que precisa ser melhorado com base nas fontes.

### Prompt para glossário

> Selecione os principais conceitos relacionados a **[TEMA]** presentes nas fontes. Para cada conceito, apresente definição simples, exemplo cotidiano e referência.

### Prompt para checagem de resposta

> Revise a resposta anterior e identifique quais afirmações estão diretamente apoiadas pelas fontes, quais são inferências e quais precisam de confirmação adicional.

### Prompt contra respostas genéricas

> Responda utilizando exclusivamente as fontes deste caderno. Evite recomendações genéricas, não invente dados e indique claramente quando as fontes não forem suficientes para responder.

---

## ✅ Principais aprendizados

O uso do NotebookLM pode tornar o estudo mais ativo quando a ferramenta é utilizada para formular perguntas, comparar fontes e validar referências. A qualidade das respostas depende diretamente da qualidade das fontes e da clareza dos prompts utilizados.

Durante o projeto, ficou evidente que prompts genéricos produzem respostas superficiais. Quando são adicionados público-alvo, objetivo, formato esperado, restrições e exigência de referências, as respostas se tornam mais úteis e verificáveis.

Também foi possível compreender que a educação financeira começa pela organização do orçamento. Antes de buscar produtos financeiros ou retornos, é necessário conhecer a própria realidade, controlar despesas, compreender juros e definir objetivos possíveis.

---

## 🚧 Limitações do projeto

- O material possui caráter introdutório.
- Os exemplos numéricos foram simplificados para facilitar a aprendizagem.
- A situação financeira de cada pessoa exige análise individual.
- Produtos financeiros, regras, taxas e condições podem mudar.
- As respostas geradas por IA devem ser conferidas nas fontes originais.
- O NotebookLM pode interpretar ou resumir uma fonte de maneira incompleta.

---

## 🔄 Possíveis melhorias futuras

- adicionar capturas de tela do caderno no NotebookLM;
- incluir as respostas completas geradas pela ferramenta;
- criar um arquivo separado com exercícios resolvidos;
- desenvolver uma planilha simples de orçamento mensal;
- ampliar o estudo para crédito, endividamento e investimentos;
- adicionar um quiz de revisão;
- registrar novas variações de prompts e seus resultados.

---

## 📁 Estrutura sugerida do repositório

```text
miniguia-educacao-financeira-notebooklm/
├── README.md
├── assets/
│   ├── notebooklm-fontes.png
│   ├── notebooklm-resumo.png
│   └── notebooklm-prompts.png
├── prompts/
│   └── prompts-testados.md
└── fontes/
    └── fontes-utilizadas.md
```

---

## 🛠️ Tecnologias e ferramentas utilizadas

- NotebookLM
- GitHub
- Markdown
- Fontes abertas do Banco Central do Brasil
- Portal do Investidor
- Tesouro Direto

---

## 👤 Autor

Desenvolvido por Matheus Barcelli como parte de um desafio de projeto da DIO.

---

## 📄 Licença

Este projeto pode ser utilizado para fins educacionais. Consulte também as condições de uso e as licenças das fontes originais.
