## 1. Objetivo dos Testes

Avaliar como diferentes estratégias de engenharia de prompt influenciam:

- Profundidade técnica
- Organização estrutural
- Fundamentação nas fontes
- Capacidade analítica
- Clareza argumentativa

Os testes foram realizados no NotebookLM utilizando como base documentos oficiais do setor financeiro brasileiro.

---

## 2. Critérios de Avaliação

Cada resposta foi analisada segundo os seguintes critérios:

1. Precisão conceitual
2. Referência às fontes fornecidas
3. Estrutura lógica
4. Nível de criticidade
5. Aplicabilidade prática

---

## 3. Teste 1 – Zero-Shot Prompt

### Prompt Utilizado

Explique os principais riscos cibernéticos no setor financeiro brasileiro com base nas fontes fornecidas.

### Resultado Observado

- Resposta descritiva
- Estrutura simples
- Baixa contextualização regulatória
- Referências limitadas às fontes

### Análise

O modelo apresentou visão geral adequada, porém superficial.  
Zero-shot mostrou-se eficiente para introdução ao tema, mas insuficiente para aprofundamento técnico.

---

## 4. Teste 2 – Role Prompting

### Prompt Utilizado

Atue como especialista em segurança da informação no setor financeiro brasileiro e analise os principais riscos cibernéticos, considerando regulamentação, impacto econômico e controles de mitigação.

### Resultado Observado

- Linguagem técnica aprimorada
- Inclusão de aspectos regulatórios
- Melhor articulação entre risco e governança
- Resposta mais estruturada

### Análise

A definição de papel elevou significativamente a qualidade técnica.  
Houve maior profundidade e conexão entre risco, impacto e medidas preventivas.

---

## 5. Teste 3 – Few-Shot Prompt

### Prompt Utilizado

Exemplo de estrutura:
Ataque: definição + vetor de exploração + impacto + medida preventiva.

Explique phishing, ransomware e engenharia social seguindo esse padrão.

### Resultado Observado

- Padronização consistente
- Facilidade de comparação entre ameaças
- Organização didática

### Análise

O uso de exemplo prévio aumentou coerência estrutural.  
Mostrou-se eficaz para produção de material técnico padronizado.

---

## 6. Teste 4 – Chain of Thought

### Prompt Utilizado

Explique passo a passo como ocorre um golpe financeiro digital, desde a engenharia social até o prejuízo final.

### Resultado Observado

- Sequência lógica clara
- Melhor compreensão do fluxo do ataque
- Identificação de pontos de vulnerabilidade

### Análise

A técnica favoreceu entendimento sistêmico e visualização do ciclo do ataque.  
Demonstrou maior valor pedagógico.

---

## 7. Teste 5 – Prompt Comparativo

### Prompt Utilizado

Compare os riscos de segurança do Pix e do Open Finance, destacando diferenças técnicas e regulatórias.

### Resultado Observado

- Estrutura analítica comparativa
- Identificação de riscos específicos
- Maior profundidade crítica

### Análise

Prompts comparativos estimularam pensamento estratégico e maior maturidade analítica.

---

## 8. Síntese dos Resultados

A qualidade das respostas mostrou-se diretamente proporcional ao nível de estruturação do prompt.

Prompts com:
- Definição de papel
- Estrutura prévia
- Solicitação de raciocínio passo a passo
- Comparação explícita

geraram respostas mais completas, técnicas e analíticas.

---

## 9. Conclusão Analítica dos Testes de Prompt

Os experimentos realizados evidenciam que a qualidade das respostas geradas pela IA não depende exclusivamente do modelo utilizado, mas, sobretudo, da estruturação estratégica do prompt.

Os prompts mais elaborados produziram respostas com maior profundidade técnica, organização lógica e contextualização regulatória.

A técnica de Zero-Shot mostrou-se adequada para introdução conceitual, porém limitada. Já abordagens como Role Prompting e Chain of Thought favoreceram maior criticidade, clareza estrutural e integração entre risco, impacto e governança.

Os resultados reforçam que a engenharia de prompt deve ser compreendida como competência metodológica, e não apenas operacional. A formulação adequada da pergunta influencia diretamente o nível de sofisticação do conhecimento produzido.

Conclui-se que a utilização crítica e estruturada da IA Generativa potencializa o aprendizado técnico, desde que acompanhada de curadoria de fontes confiáveis, análise reflexiva e avaliação sistemática das respostas obtidas.
