# Projeto: Caderno Temático com NotebookLM — Clarice Lispector

## Descrição do Projeto

Este repositório documenta um projeto de aprendizagem ativa desenvolvido com o apoio do **NotebookLM** do Google, com foco no estudo de **Clarice Lispector** — sua trajetória, sua obra e as principais características de sua escrita.

A proposta foi utilizar Inteligência Artificial não apenas para resumir conteúdos, mas como ferramenta de **curadoria, síntese, comparação, revisão e organização do conhecimento**, sempre com base em fontes selecionadas previamente.

---

## Objetivos de Estudo

- Compreender quem foi Clarice Lispector e sua relevância para a literatura brasileira
- Identificar as principais características de sua escrita
- Reconhecer temas recorrentes em sua obra
- Transformar leitura e pesquisa em estudo ativo com apoio de IA
- Testar estratégias de prompting para melhorar a qualidade das respostas
- Consolidar o aprendizado em um miniguia de revisão reutilizável

---

## Ferramentas Utilizadas

- [NotebookLM](https://notebooklm.google.com/)
- [GitHub](https://github.com/FelipeSouza90/miniguia-estudos-notebooklm)

## Link do NotebookLM

[Visualizar notebook no NotebookLM](https://notebooklm.google.com/notebook/d95ee3b8-2ec2-4bfc-a57e-f2bd51973fea)

---

## Curadoria de Fontes

As fontes abaixo foram selecionadas para compor a base do notebook. A curadoria buscou equilibrar materiais biográficos, acadêmicos, didáticos e audiovisuais, permitindo uma visão mais ampla da autora.

### Fontes Principais — Texto e PDF

1. [Vida — Clarice Lispector](https://site.claricelispector.ims.com.br/)
2. [Clarice Lispector por Entrelinhas: Um Olhar sobre suas Fontes Biográficas (TCC)](https://www.repositorio.ufal.br/bitstream/123456789/9659/1/Clarice%20Lispector%20por%20entrelinhas%20-%20um%20olhar%20sobre%20suas%20fontes%20biogr%C3%A1ficas.pdf)
3. [Nascimento de Clarice Lispector — FFLCH/USP](https://www.fflch.usp.br/42234)
4. [Toda Matéria — Vida e Obra de Clarice Lispector](https://www.todamateria.com.br/vida-e-obra-de-clarice-lispector/)

### Materiais Complementares

5. [Panorama com Clarice Lispector (YouTube)](https://youtu.be/ohHP1l2EVnU?si=v4eAzStxF2dNYj0x)
6. [Documentário: Clarice Lispector — 100 Anos (YouTube)](https://youtu.be/kw9fUfy5sPk?si=b2JcuI_TQ2OjZ0K2)

---

## Estratégia de Estudo no NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio à aprendizagem, com foco em cinco frentes principais:

- Resumo inicial das fontes
- Comparação entre abordagens biográficas e literárias
- Identificação de padrões e temas recorrentes
- Geração de perguntas para revisão
- Consolidação do conteúdo em um miniguia final

As respostas geradas foram avaliadas com base em três critérios:

- Aderência às fontes fornecidas
- Clareza e utilidade para revisão
- Capacidade de organização do conteúdo

---

## Estratégia de Prompts

Os prompts foram organizados por finalidade, buscando demonstrar uso intencional da ferramenta e refinamento progressivo das interações.

---

### 1. Prompt de Compreensão Inicial

```txt
Faça um panorama estruturado sobre Clarice Lispector com base apenas nas fontes fornecidas, separando 
biografia, principais obras, temas recorrentes e relevância literária.
```

**Objetivo:** Obter uma visão geral do tema e organizar os principais eixos do estudo.

**Resultado observado:** A resposta foi útil como ponto de partida — fez um bom resumo biográfico, citou as principais obras com breves comentários sobre cada uma, e sintetizou os temas mais comuns (existencialismo, solidão, sentido da vida). No entanto, focou mais na importância da obra no meio literário do que no resumo das obras em si. Foram 7 parágrafos separados pelas seções solicitadas. Resposta interessante como introdução, mas ainda ampla para revisão detalhada.

**Aprendizado:** Prompts iniciais mais abrangentes funcionam bem para exploração, mas precisam ser refinados para um estudo mais objetivo.

---

### 2. Prompt de Explicação em Linguagem Simples

```txt
Explique quem foi Clarice Lispector em linguagem simples, como se o leitor nunca tivesse estudado 
literatura brasileira.
```

**Objetivo:** Traduzir o conteúdo para uma linguagem mais acessível e didática.

**Resultado observado:** Nota-se uma mudança na escrita em relação ao primeiro prompt. Ao invés de separar os assuntos por tópicos, a IA produziu um texto corrido, com vocabulário mais simples. Não considero uma mudança significativa, pois a ferramenta já não usava termos muito complexos, mas nota-se a intenção de simplificar o texto.

**Aprendizado:** Pedir adaptação ao nível do leitor melhora a compreensão e a utilidade pedagógica da resposta.

---

### 3. Prompt de Análise Literária

```txt
Liste e explique as principais características da escrita de Clarice Lispector, indicando 
temas recorrentes e padrões observados nas fontes.
```

**Objetivo:** Separar biografia de análise literária e aprofundar o estudo do estilo da autora.

**Resultado observado:** A IA foi mais fundo em um dos aspectos abordados no primeiro prompt, descrevendo de forma mais detalhada como Clarice Lispector de fato escreve. Foi um dos prompts mais úteis do processo — gerou uma resposta mais analítica e organizada, porém mais densa e complexa.

**Aprendizado:** Prompts com foco analítico tendem a produzir material mais valioso do que perguntas muito genéricas. Faz sentido combinar este prompt com o de número 2, caso o leitor tenha dificuldades com textos mais prolixos.

---

### 4. Prompt de Comparação entre Fontes

**Objetivo:** Identificar diferenças de abordagem entre os materiais selecionados.

**Resultado observado:** A resposta ajudou a perceber que algumas fontes priorizam a trajetória de vida (biografia), enquanto outras enfatizam a interpretação das obras em si.

**Aprendizado:** O NotebookLM é especialmente útil para cruzar materiais e destacar pontos em comum e distintos. É também uma boa forma de verificar se as fontes reunidas são de qualidade.

---

### 5. Prompt de Revisão Ativa

```txt
Crie 10 perguntas e respostas para revisão sobre Clarice Lispector com base exclusivamente nas fontes fornecidas.
```

**Objetivo:** Transformar o conteúdo estudado em material de revisão.

**Resultado observado:** Muito útil para fixação do conteúdo e preparação de revisões futuras. A IA dividiu bem os temas nas perguntas.

**Aprendizado:** O valor da IA aumenta quando ela ajuda a converter informação em estudo ativo. Um prompt mais direcionado (ex.: "faça perguntas apenas sobre a biografia") poderia trazer melhor aproveitamento.

---

### 6. Prompt de Controle de Qualidade

```txt
Valide as fontes que foram passadas. Verifique se são confiáveis e de boa qualidade e 
justifique sua resposta.
```

**Objetivo:** Aumentar a confiabilidade das respostas e reduzir extrapolações.

**Resultado observado:** O NotebookLM confirmou que se tratam de fontes confiáveis, destacando a presença de trabalhos acadêmicos de importantes universidades aprovados por banca, instituições culturais de peso e documentos audiovisuais históricos da TV Cultura.

**Aprendizado:** Usar a própria IA para checar as fontes pode ser uma boa estratégia em caso de dúvidas e traz mais confiabilidade nas respostas.

---

## Impedimentos e Dificuldades

### Dificuldades Encontradas

- Respostas iniciais muito amplas
- Repetição de informações biográficas
- Pouca profundidade analítica em prompts muito genéricos
- Necessidade de separar melhor biografia, estilo e temas literários

### Ajustes Realizados

- Refinamento progressivo dos prompts
- Solicitação de respostas em tópicos
- Delimitação mais clara do objetivo de cada pergunta
- Reforço para que as respostas fossem baseadas apenas nas fontes fornecidas

### Lições Aprendidas

- A qualidade da resposta depende fortemente da formulação do prompt
- Curadoria de fontes é parte essencial do resultado
- O NotebookLM funciona melhor como apoio à leitura crítica do que como substituto dela
- Prompts com finalidade clara geram respostas mais úteis e reaproveitáveis

---

## Uso dos Recursos do Estúdio

Além da conversa principal com o notebook, também foram explorados os recursos do **Estúdio do NotebookLM** para apoiar a consolidação do conteúdo.

### Recursos Utilizados

| Recurso | Utilidade |
|---|---|
| Mapa mental | Visualizar relações entre vida, obras, temas e estilo literário |
| Cartões didáticos | Revisão ativa e memorização |
| Guia de estudo / Relatórios | Consolidar o conteúdo em formato mais estruturado |

Os recursos do Estúdio foram importantes porque ajudaram a transformar um conjunto de fontes em materiais de revisão mais acionáveis. Em vez de apenas reunir informação, o processo passou a gerar instrumentos práticos de estudo.

---

## Evidências Visuais

> **Visão geral do caderno temático** — Estrutura do notebook, incluindo fontes reunidas e ambiente de estudo.

> **Exemplo de interação com prompt analítico**

> **Uso dos recursos do Estúdio (mapa mental)**

---

## Miniguia de Estudo

### 1. Quem foi Clarice Lispector

Clarice Lispector foi uma escritora de grande destaque na literatura brasileira do século XX. Nascida na Ucrânia e naturalizada brasileira, construiu uma obra marcada por originalidade, profundidade psicológica e forte densidade reflexiva.

### 2. Principais Características de sua Escrita

- Introspecção
- Subjetividade
- Profundidade psicológica
- Fluxo de consciência
- Reflexão existencial
- Observação do cotidiano
- Foco no universo interior das personagens

### 3. Temas Recorrentes

- Identidade
- Solidão
- Existência
- Autoconhecimento
- Cotidiano
- Condição feminina
- Sentido da vida

### 4. Importância para a Literatura Brasileira

Clarice Lispector é reconhecida por romper com modelos narrativos mais convencionais e por construir uma escrita singular, centrada nas experiências interiores das personagens. Sua obra ampliou as possibilidades da narrativa brasileira e segue influenciando leitores, críticos e escritores.

### 5. Obras de Destaque

- *Perto do Coração Selvagem*
- *Laços de Família*
- *A Paixão Segundo G.H.*
- *A Hora da Estrela*
- *Felicidade Clandestina*

---

## Glossário

| Termo | Definição |
|---|---|
| **Introspecção** | Observação profunda dos próprios pensamentos e sentimentos. |
| **Subjetividade** | Percepção da realidade a partir da experiência individual. |
| **Fluxo de consciência** | Técnica narrativa que busca acompanhar o pensamento da personagem. |
| **Narrativa psicológica** | Narrativa centrada nos conflitos internos das personagens. |
| **Epifania** | Momento de revelação ou percepção intensa. |
| **Existencialismo** | Reflexão sobre existência, identidade e sentido da vida. |

---

## Prompts Reutilizáveis

```txt
Resuma a vida e a obra de Clarice Lispector em tópicos objetivos.
```

```txt
Explique as características da escrita de Clarice Lispector em linguagem simples.
```

```txt
Compare as fontes e destaque semelhanças, diferenças e ênfases de cada uma.
```

```txt
Crie um glossário com os principais conceitos relacionados à obra de Clarice Lispector.
```

```txt
Monte perguntas e respostas para revisão com base exclusivamente nas fontes fornecidas.
```

---

## Considerações Finais

Este projeto mostrou como a Inteligência Artificial pode ser utilizada de forma produtiva no aprendizado quando combinada com curadoria de fontes, objetivos claros e avaliação crítica das respostas. O NotebookLM foi utilizado como ferramenta de apoio para resumos, comparação e revisão, enquanto o GitHub foi utilizado para documentar o processo, registrar os testes realizados e consolidar os resultados obtidos.

Mais do que gerar respostas, o foco deste trabalho foi **estruturar um processo de estudo orientado, rastreável e reutilizável**.

---

## Autor

**Felipe Souza**