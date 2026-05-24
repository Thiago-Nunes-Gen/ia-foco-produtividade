# Comparação Entre Técnicas de Prompt

Durante o desenvolvimento deste projeto, diferentes técnicas de engenharia de prompts foram testadas no NotebookLM com o objetivo de analisar como pequenas mudanças na estrutura das perguntas influenciam diretamente a qualidade das respostas geradas pela Inteligência Artificial.

Além da construção dos prompts, também foi utilizado o recurso **"Configurar Conversas"** do NotebookLM, permitindo ajustar estilo, profundidade e comportamento das respostas durante os testes.

---

# Configuração Utilizada no NotebookLM

Durante os experimentos, o NotebookLM foi configurado utilizando:

- Modo de conversa: **Padrão**
- Tamanho das respostas: **Padrão**

Essa configuração permitiu observar o comportamento natural da IA sem interferências mais agressivas de personalização, facilitando a comparação entre as diferentes técnicas de prompting utilizadas no projeto.

---

# Técnicas Testadas

## Prompt Simples

O prompt simples demonstrou que perguntas curtas e amplas ainda conseguem gerar respostas úteis, principalmente para introdução de temas.

No entanto, as respostas apresentaram menor direcionamento e pouca personalização, exigindo refinamentos posteriores para atingir análises mais profundas.

---

## Zero-Shot Prompting

O Zero-Shot Prompting apresentou respostas mais organizadas e consistentes apenas com um direcionamento mais claro da solicitação.

Mesmo sem exemplos prévios, a IA conseguiu conectar conceitos relacionados à procrastinação, foco, produtividade e aprendizagem com muito mais coerência.

---

## Few-Shot Prompting

O Few-Shot Prompting mostrou como exemplos prévios ajudam a IA a compreender padrões esperados de resposta.

As respostas ficaram mais objetivas, organizadas e previsíveis, reduzindo ambiguidades e melhorando a clareza das soluções apresentadas.

Ao mesmo tempo, foi possível perceber uma pequena redução na liberdade criativa da IA, que passou a seguir mais rigidamente os padrões fornecidos nos exemplos.

---

## Chain of Thought Prompting

Entre todas as técnicas testadas, o Chain of Thought Prompting apresentou o comportamento mais analítico e aprofundado.

A IA conseguiu estruturar explicações em sequência lógica, desenvolvendo o raciocínio passo a passo e conectando conceitos de maneira muito mais profunda.

Essa técnica demonstrou grande eficiência para temas mais complexos, principalmente quando o objetivo era compreender causas, consequências e relações entre diferentes conceitos.

---

# Principais Percepções Durante os Testes

Ao longo dos experimentos, ficou evidente que a qualidade das respostas depende muito menos da IA "adivinhar" o que o usuário deseja e muito mais da clareza com que o problema é apresentado.

Pequenas mudanças na estrutura dos prompts foram suficientes para alterar:
- profundidade das respostas;
- nível de detalhamento;
- clareza das explicações;
- organização do raciocínio;
- aplicabilidade prática das sugestões.

Outro ponto importante observado foi que a IA tende a responder melhor quando existe:
- contexto;
- direcionamento;
- objetivo claro;
- e organização lógica na solicitação.

Também ficou perceptível que respostas mais longas nem sempre significam respostas melhores. Em alguns casos, prompts mais objetivos produziram conteúdos mais úteis e fáceis de aplicar.

---

# Considerações Finais

Os testes realizados durante o projeto mostraram que a engenharia de prompts vai muito além de simplesmente "fazer perguntas para a IA".

Na prática, construir bons prompts envolve:
- definir contexto;
- organizar objetivos;
- direcionar o raciocínio;
- testar abordagens;
- interpretar resultados;
- e ajustar continuamente a comunicação com a ferramenta.

O uso do NotebookLM como ambiente de estudo também demonstrou como a Inteligência Artificial pode atuar como apoio real à aprendizagem ativa, organização de conhecimento e desenvolvimento de pensamento crítico.

Mais do que acelerar respostas, a IA se mostrou mais valiosa quando utilizada como ferramenta de reflexão, aprofundamento e construção estruturada do aprendizado.

Outro ponto importante é que, durante este projeto, os testes foram realizados utilizando exclusivamente a aba de conversa do NotebookLM, focando principalmente na análise de respostas, comportamento da IA e aplicação das técnicas de engenharia de prompts.

Apesar disso, a plataforma oferece outros recursos avançados dentro da aba "Estúdio", como geração de mapas mentais, apresentações, resumos em áudio, guias de estudo e materiais visuais.

Devido ao potencial dessas funcionalidades, existe a intenção de realizar futuramente um desdobramento deste projeto explorando de forma mais aprofundada os recursos da aba Estúdio, ampliando ainda mais as possibilidades de aprendizagem ativa com Inteligência Artificial.
