# Ferramentas de BPM — Mapeamento, PDCA e Qualidade

## Metodologias de Representação de Processos

| Notação | Descrição | Quando usar |
|---|---|---|
| **BPMN** (Business Process Model and Notation) | Padrão criado pelo Object Management Group (OMG). Intuitivo, detalhado e aplicável a sistemas/TI. Principal notação do mercado. | Processos de negócio detalhados, especialmente quando integrados a sistemas |
| **Fluxograma** | Conjunto simples e limitado de símbolos (padrão ANSI). Facilita o entendimento rápido. | Processos simples, comunicação com equipes não técnicas |
| **EPC** (Event-driven Process Chain) | Considera eventos como "gatilhos" ou "resultados" de uma etapa. Trabalha com regras AND, OR, XOR. | Modelagem de conjuntos complexos de processos (ecossistema Aris) |
| **UML** (Unified Modeling Language) | Conjunto de notações para descrever requisitos de sistemas de informação. | Implantação de novos sistemas de TI |
| **IDEF** (Integrated Definition Language) | Destaca: entradas, saídas, mecanismos e controles de processo. Padrão americano. | Visão corporativa detalhada com decomposição lógica |
| **Value Stream Mapping** (Mapa de Valor Agregado) | Do Lean Manufacturing. Mostra: tempo de execução, tempo total (incluindo esperas), estoques por etapa e recursos por etapa. | Indústria, análise de eficiência e desperdícios |

---

## Fluxograma — Símbolos Básicos (padrão ANSI)

| Símbolo | Significado |
|---|---|
| Oval / Elipse | Início e Fim do processo |
| Retângulo | Atividade / Tarefa |
| Losango | Decisão / Condição (sim/não) |
| Seta | Fluxo / Sequência |
| Paralelogramo | Entrada ou Saída de dados |
| Cilindro | Banco de dados / arquivo |

**Fases de evolução do fluxograma:**
- **AS-IS**: como o processo funciona hoje
- **TO-BE**: como o processo funcionará após a melhoria
- **MUST-BE**: o padrão definitivo implementado

---

## Ciclo PDCA

O PDCA é a principal ferramenta de gestão da qualidade e melhoria de processos. Aplicado em dois contextos:
- **MASP** — Metodologia de Análise e Solução de Problemas (problemas de rotina)
- **MAMP** — Metodologia de Análise e Melhoria de Processos (otimização contínua)

### As 4 fases

**PLAN (Planejar)**
- Identificar o problema ou oportunidade de melhoria
- Observar e entender o processo atual
- Gerar propostas de solução (técnicas, não apenas "palpites")
- Estabelecer metas e padrões de desempenho almejados
- Estimar recursos: tempo, custo, pessoas, equipamentos

**DO (Executar)**
- Estruturar as ideias em um projeto de melhoria
- Calibrar máquinas e medir variáveis do processo
- Executar **em menor escala** (teste-piloto), para facilitar o controle

**CHECK (Verificar)**
- Analisar todos os resultados obtidos
- Comparar com as metas definidas no Plan
- Identificar e analisar discrepâncias
- Reduzir a variabilidade do processo

**ACT / LEARN (Agir / Aprender)**
- Tomar decisão com base nos controles e resultados
- Disseminar para a organização o que funcionou e o que não funcionou
- Promover o aprendizado organizacional
- Iniciar novo ciclo de melhoria contínua (Kaizen)

> O PDCA pode ser rodado múltiplas vezes para o mesmo processo até atingir a excelência desejada.

---

## As 7 Ferramentas da Qualidade (Ishikawa)

### 1. Diagrama de Causa e Efeito (Ishikawa / Espinha de Peixe)
Representa as possíveis causas que resultam em um efeito indesejado.

**Estrutura:**
- **Cabeça (→)**: o problema ou efeito indesejado
- **Espinhas principais**: categorias de causas. As mais comuns são os 6M:
  - Máquina, Mão de obra, Método, Material, Meio ambiente, Medição
- **Sub-espinhas**: causas potenciais dentro de cada categoria

**Como usar:**
1. Defina o problema (cabeça)
2. Brainstorm das causas em cada categoria
3. Identifique as causas mais prováveis
4. Investigue com dados

---

### 2. Histograma
Gráfico de barras que mostra a **distribuição da variação** de dados em um processo.

Permite analisar:
- Distribuição dos dados
- Valores médios e desvio padrão
- Comparações com padrões
- Comparações entre itens estratificados

**Termos:**
- **Classes**: cada barra (ex: faixa de dias)
- **Amplitude**: intervalo entre limites de uma classe
- **Frequência**: número de observações em uma classe

---

### 3. Diagrama de Pareto
Baseado na regra 80/20: **20% das causas geram 80% dos efeitos**.

**Como interpretar:**
- Ordene os problemas por frequência (do maior para o menor)
- Trace a linha de porcentagem acumulada
- Identifique os "poucos e vitais" (causas que somam ~80% do impacto)
- Concentre esforços nessas causas

**Classificação:**
- **Pouco vitais**: pequeno número de problemas, mas grande impacto
- **Muito triviais**: grande número de problemas, mas pequenas perdas

---

### 4. Fluxograma de Processos
(Ver seção de metodologias acima)

---

### 5. Carta / Gráfico de Controle
Verifica se um processo está dentro dos **limites de variação estabelecidos**.

**Elementos:**
- **LSC** — Limite Superior de Controle
- **LM** — Linha Média (linha central)
- **LIC** — Limite Inferior de Controle

Se os dados saem dos limites, o processo está **fora de controle** — ação corretiva necessária.

---

### 6. Diagrama de Dispersão
Verifica o **grau de correlação entre duas variáveis**.

**Tipos de correlação:**
- **Positiva (A)**: quando uma variável aumenta, a outra também aumenta
- **Negativa (C)**: quando uma aumenta, a outra diminui
- **Nula / Neutra (B)**: as variáveis não se influenciam

---

### 7. Folha de Verificação
Planilha simples para **avaliar e controlar problemas ou ações** em um período.

**Estrutura básica:**

| Tipo de problema | Seg | Ter | Qua | Qui | Sex | Total |
|---|---|---|---|---|---|---|
| Problema A | IIIII | III | II | IIII | IIIII | 19 |
| Problema B | III | I | IIII | II | III | 13 |

Permite identificar: quais problemas são mais frequentes e em quais dias/turnos.

---

## Outras Ferramentas Importantes

### Amostragem Estatística
Utilizada no processo de inspeção. O tamanho da amostra depende de:
- Intervalo de confiança desejado
- Recursos financeiros disponíveis
- Maturidade da equipe
- Grau de exigência dos clientes

### Inspeção (NBR 5425:1985)
Verifica se produto/resultado está de acordo com as especificações. Funções:
1. Separar produtos aceitáveis dos não aceitáveis
2. Avaliar grau de conformidade com requisitos
3. Apontar deficiências às partes interessadas
4. Assegurar que requisitos de qualidade foram atendidos

### Revisão de Solicitações de Mudança
Controle de desvios em relação ao planejado. Toda alteração aprovada deve ser refletida nos documentos do projeto e constantemente revisada.

---

## 5W2H — Plano de Ação

Ferramenta para elaboração de planos de ação, definindo responsabilidades, métodos, prazos, objetivos e recursos.

| Pergunta | O que responde |
|---|---|
| **What** (O quê?) | Tarefas que devem ser realizadas |
| **Who** (Quem?) | Responsáveis pelas tarefas |
| **When** (Quando?) | Cronograma / prazos |
| **Where** (Onde?) | Local de execução |
| **Why** (Por quê?) | Razão / justificativa |
| **How** (Como?) | Melhor maneira de executar |
| **How much** (Quanto?) | Custo estimado |

**Exemplo de tabela 5W2H:**

| O quê | Quem | Quando | Onde | Por quê | Como | Quanto |
|---|---|---|---|---|---|---|
| Realizar testes de protótipo | João B. (Depto. Manufatura) | Até 10/nov/xx | Lab. de testes SP | Alto índice de quebras | Comparação de dados e consultoria | R$ 100.000 |

---

## Gráfico de Execução
Permite avaliação de **histórico, evolução e variação** de atividades ao longo do tempo.
Útil para análise de tendências e tomada de decisão baseada em performance histórica.
