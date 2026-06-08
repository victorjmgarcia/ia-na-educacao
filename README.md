# IA Generativa na Educação — guia de boas práticas e pesquisa aplicada

Projeto que une duas coisas: um guia prático sobre uso responsável de inteligência artificial generativa na educação, e uma pesquisa aplicada para medir se esse guia realmente funcionava na prática. Em vez de só escrever o material e entregar, apliquei com educadores reais, coletei dados antes e depois, e analisei o resultado.

Foi meu trabalho de conclusão do curso de Gestão da Tecnologia da Informação (Uninter), mas o que interessa aqui é o método: levantar uma hipótese, coletar dados estruturados, medir o efeito e interpretar os números.

## O problema

Professores estão usando IA generativa (ChatGPT, Claude, Gemini) sem necessariamente conhecer os riscos: vazamento de dados de alunos, alucinações apresentadas como fato, vieses, problemas de acessibilidade e direitos autorais. A pergunta do projeto foi: um guia bem estruturado consegue, de forma mensurável, melhorar o conhecimento desses educadores sobre uso responsável de IA?

## Como foi feito

Apliquei o material com 5 educadores de diferentes níveis de ensino (fundamental, médio, educação especial, superior e técnico), usando uma metodologia de pré-teste e pós-teste:

1. **Pré-teste** — questionário inicial medindo conhecimento sobre LGPD, prompts, alucinações, viés e direitos autorais.
2. **Leitura do guia** — os participantes estudaram o material.
3. **Pós-teste** — reaplicação do mesmo questionário para medir a variação.
4. **Análise** — consolidação dos resultados, comparação antes/depois e leitura qualitativa dos comentários.

A coleta foi feita em Google Forms, de forma anonimizada — coerente com o próprio tema do guia (proteção de dados):

- [Formulário do pré-teste](https://docs.google.com/forms/d/e/1FAIpQLScASCAb8hNBD3yTHiRiYY4fqreenVHSzbq_sV72tQY_Uv3exw/viewform)
- [Formulário do pós-teste](https://docs.google.com/forms/d/e/1FAIpQLSd0aaxMzFXWPBf4Q2Zj6DBUtHfLSxsaF88a5chYhPmZuux6-g/viewform)
  
## Resultados

| Métrica | Pré-teste | Pós-teste | Variação |
|---|---|---|---|
| Acerto no teste de conhecimento | 48% (média 2,4/5) | 100% (média 5/5) | +52 pontos percentuais |
| Satisfação (escala 1–5) | 4,0 | 4,8 | +0,8 |

A mediana de acerto saiu de 2/5 para 5/5, e 80% dos participantes deram nota máxima de satisfação no pós-teste. Com amostra pequena (n=5, seleção por conveniência), o resultado não tem pretensão de generalização estatística — é uma validação inicial qualitativa, e isso está declarado abertamente no trabalho como limitação.

## A parte de governança e análise

Além da pesquisa com os educadores, o projeto inclui dois instrumentos que mostram o lado mais analítico e estruturado:

**Matriz de Conformidade** — um checklist que avalia o guia contra quatro frameworks (LGPD, WCAG 2.2, UNESCO e NIST AI RMF), atribuindo nota de 0 a 4 por critério. Foram 12 critérios avaliados, com média 3,92/4. Serve como uma auditoria objetiva do material.

**Tabela Comparativa Multi-IA** — comparação das respostas de ChatGPT, Claude e Grok para os mesmos prompts (checklist LGPD, rubrica de avaliação, roteiro anti-alucinação), registrando qual modelo foi escolhido para cada caso e a justificativa técnica da decisão. É uma forma de documentar decisões com critério, não no "achismo".

## O que esse projeto demonstra

- Coleta estruturada de dados (Google Forms) com cuidado de anonimização
- Metodologia pré-teste/pós-teste para medir efeito
- Análise quantitativa (médias, medianas, variação) e qualitativa
- Avaliação por critérios contra frameworks (matriz de conformidade pontuada)
- Documentação de decisões com justificativa
- Consciência de LGPD e uso ético de dados aplicada na prática

## Arquivos do repositório

- `Atividades_Extensionista_Trabalho_Final.pdf` — o trabalho completo, com metodologia, dados e análise
- `Guia-IA-na-Educacao.pdf` — o material aplicado com os educadores
- `README.md` — este arquivo

## Ferramentas

Google Forms (coleta), Google Docs e Canva (produção do material), e comparação entre modelos de IA generativa (ChatGPT, Claude, Grok).
