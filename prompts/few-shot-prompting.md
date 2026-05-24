# Few-Shot Prompting

## Conceito

Few-Shot Prompting é uma técnica de engenharia de prompts em que exemplos são fornecidos antes da solicitação principal.

Esses exemplos ajudam a Inteligência Artificial a identificar padrões de resposta, contexto e estrutura esperada, tornando o resultado mais consistente e direcionado.

---

# Exemplo Utilizado

```txt
Exemplo 1:
Pessoa com dificuldade de foco → Técnica Pomodoro

Exemplo 2:
Pessoa com excesso de distrações → Bloqueio de notificações

Agora sugira soluções para uma pessoa que procrastina durante os estudos.
```

---

# Características

- Uso de exemplos prévios
- Melhor direcionamento
- Respostas mais consistentes
- Maior contextualização
- Estrutura mais previsível

---

# Resposta Obtida no NotebookLM

> Pessoa que procrastina durante os estudos = Regra dos Dois Minutos / Mapa do Dia / Dispositivos de Compromisso
>
> Abaixo estão as soluções práticas para quem procrastina nos estudos, fundamentadas nos mecanismos de formação de hábitos e motivação:
>
> Aplicar a Regra dos Dois Minutos:
>
> Reduza a atividade de estudar para uma ação muito simples que leve menos de dois minutos para ser iniciada. Em vez de se forçar a "estudar por três horas", defina como meta apenas "abrir minhas anotações". O objetivo é parar de focar no resultado final e dominar o hábito de dar o pontapé inicial, pois depois que você começa, torna-se muito mais fácil continuar.
>
> Desmembrar Tarefas e criar um Mapa do Dia:
>
> A procrastinação frequentemente surge da "paralisia decisória" diante de tarefas assustadoras. Para evitar que seu cérebro emocional sinta medo da carga de estudos, divida o conteúdo em blocos de 30 a 60 minutos.
>
> Em seguida, anote essas tarefas em um papel criando uma sequência lógica de execução com horários definidos, o que elimina a incerteza do que fazer a seguir e previne o esgotamento.
>
> Agir com a Regra dos 3 Segundos do Samurai:
>
> Assim que lembrar ou chegar a hora de estudar, aja no tempo máximo de cinco batimentos cardíacos. Se você pensar demais antes de abrir os livros, seu cérebro automaticamente começará a racionalizar o processo e inventará desculpas para permanecer na zona de conforto.
>
> Criar Dispositivos de Compromisso e Contratos de Hábito:
>
> Adote medidas no presente que dificultem ou punam a procrastinação no futuro. Você pode firmar um contrato com um amigo ou familiar, declarando sua meta de estudo e definindo um custo imediato caso falhe.
>
> Fazer um Empacotamento de Tentações:
>
> Combine a obrigação dos estudos com uma atividade que lhe dê prazer. Crie uma regra pessoal onde você só tem permissão para fazer algo prazeroso após concluir o que precisava ser feito.

---

# Resultado Observado

A resposta gerada pelo NotebookLM apresentou um comportamento muito mais direcionado e objetivo em comparação às técnicas anteriores.

Os exemplos fornecidos no prompt ajudaram a IA a compreender rapidamente o padrão esperado de resposta, fazendo com que as sugestões fossem apresentadas de maneira mais prática, organizada e consistente.

Outro ponto percebido foi a tendência da IA em seguir exatamente a estrutura demonstrada nos exemplos iniciais, mantendo coerência no formato das soluções apresentadas.

---

# Pontos Positivos

- Resposta mais objetiva
- Melhor direcionamento das sugestões
- Estrutura consistente
- Maior clareza na organização das ideias
- Sugestões práticas e aplicáveis
- Boa adaptação ao padrão apresentado nos exemplos
- Redução de respostas excessivamente amplas

---

# Limitações

- Menor liberdade criativa da IA
- Tendência a seguir rigidamente o padrão fornecido
- Possibilidade de respostas mais previsíveis
- Dependência da qualidade dos exemplos utilizados

---

# Análise Crítica

O Few-Shot Prompting demonstrou um comportamento bastante interessante durante os testes realizados no NotebookLM.

Diferente do Zero-Shot, onde a IA precisava interpretar sozinha o formato ideal da resposta, aqui os exemplos funcionaram como um guia claro de raciocínio e estrutura.

Isso fez com que a resposta se tornasse mais prática, direta e alinhada com o objetivo esperado, reduzindo respostas muito amplas ou excessivamente teóricas.

Outro ponto importante foi a capacidade da IA de replicar o padrão apresentado nos exemplos iniciais sem perder coerência entre as sugestões geradas. A resposta ficou mais organizada, previsível e fácil de aplicar no contexto dos estudos e produtividade.

Ao mesmo tempo, também ficou perceptível que a IA passou a trabalhar com menos liberdade criativa. Em alguns momentos, ela priorizou seguir a estrutura apresentada em vez de explorar novas possibilidades ou conexões mais profundas entre os conceitos.

Isso mostrou que a qualidade dos exemplos fornecidos influencia diretamente o resultado final. Exemplos mal estruturados podem limitar ou direcionar incorretamente a resposta da IA.

Ainda assim, o Few-Shot Prompting demonstrou ser extremamente eficiente para cenários onde se busca padronização, clareza e respostas mais orientadas para aplicação prática.

---

# Conclusão

O experimento mostrou que o Few-Shot Prompting melhora significativamente a consistência e o direcionamento das respostas geradas pela IA.

Ao receber exemplos prévios, a IA consegue identificar padrões de estrutura e contexto com muito mais facilidade, produzindo respostas mais organizadas, objetivas e alinhadas ao resultado esperado.

Na prática, a técnica se mostrou especialmente útil para tarefas que exigem clareza, padronização e aplicações mais diretas, reduzindo ambiguidades e melhorando a qualidade das respostas obtidas.
