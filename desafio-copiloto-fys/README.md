# Copiloto Comercial FYS - Priorização Inteligente de Padarias

## Sobre o Projeto

Este projeto foi desenvolvido como solução para o desafio "Copiloto de Vendas com IA para Atendimento ao Cliente", proposto pela DIO em parceria com a FYS, marca de refrigerantes do Grupo Heineken.

A solução busca utilizar Inteligência Artificial para apoiar a identificação, priorização e ativação de padarias com maior potencial de venda da marca FYS, reduzindo a dependência da força de vendas tradicional.

---

## Navegação Rápida

### Documentação Principal

- 📖 [Preparando o Ambiente](docs/preparando-o-ambiente.md)
- 🤖 [Como Dar Vida ao Agente](docs/dar-vida-ao-agente.md)
- 🔄 [Fluxo da Solução](docs/fluxo-solucao.md)

### Base de Conhecimento

- 🧃 [Marca FYS](knowledge/marca-fys.md)
- 🎯 [Desafio Comercial](knowledge/desafio-comercial.md)
- 📦 [Portfólio](knowledge/portfolio.md)
- 💬 [Argumentos de Venda](knowledge/argumentos-venda.md)

### Configuração do Agente

- ⚙️ [Prompt Principal](prompts/agente-priorizacao-padarias.md)

### Exemplos

- 📝 [Simulações](examples/simulacoes.md)

---

## Problema de Negócio

Durante a mentoria da FYS, foi apresentado um desafio real enfrentado pela marca:

* O mercado de padarias possui grande relevância para a categoria de refrigerantes.
* Existem milhares de padarias com potencial comercial.
* A equipe de vendas costuma priorizar estabelecimentos com maior volume de vendas de cerveja.
* Muitas padarias acabam recebendo pouca atenção comercial.
* Como consequência, a presença da FYS nesse canal ainda é limitada.

O desafio consiste em encontrar uma forma mais inteligente de identificar quais padarias devem ser priorizadas para ações comerciais.

---

## Objetivo da Solução

Criar um Copiloto Comercial baseado em Inteligência Artificial capaz de:

* Analisar informações sobre uma padaria;
* Identificar o potencial de venda para a marca FYS;
* Priorizar oportunidades comerciais;
* Sugerir argumentos de venda personalizados;
* Recomendar a próxima ação comercial.

---

## Usuário Principal

A solução foi pensada para:

* Representantes comerciais;
* Equipes de Trade Marketing;
* Supervisores de vendas;
* Analistas comerciais.

---

## Como Funciona

O usuário informa características da padaria, como:

* Localização;
* Fluxo de clientes;
* Presença de refrigerantes concorrentes;
* Estrutura do estabelecimento;
* Perfil de consumo.

A Inteligência Artificial analisa essas informações e retorna:

* Nível de potencial da oportunidade;
* Prioridade comercial;
* Motivos da classificação;
* Argumentos de venda recomendados;
* Próxima ação sugerida.

---

## Exemplo de Utilização

### Entrada

Padaria Central

Cidade: São Paulo

Fluxo de clientes: Alto

Venda de refrigerantes individuais: Sim

Possui geladeira exclusiva para bebidas: Não

Movimento no horário do almoço: Alto

### Saída

Potencial Comercial: 9/10

Prioridade: Alta

Motivos:

* Alto fluxo de consumidores;
* Forte aderência ao consumo individual;
* Localização estratégica.

Argumento Comercial:

A FYS oferece opções com menos açúcar e está alinhada às novas tendências de consumo, além de possuir a qualidade associada ao Grupo Heineken.

Próxima Ação:

Agendar visita comercial e propor ativação inicial da marca.

---

## Base de Conhecimento Utilizada

A solução utiliza informações obtidas a partir da mentoria da FYS e conteúdos relacionados à marca:

* Posicionamento da FYS;
* Portfólio de produtos;
* Diferenciais competitivos;
* Desafios comerciais apresentados;
* Características do mercado de padarias.

---

## Estrutura do Projeto

```text
knowledge/
├── marca-fys.md
├── desafio-comercial.md
├── portfolio.md
└── argumentos-venda.md

prompts/
└── agente-priorizacao-padarias.md

examples/
└── simulacoes.md

docs/
└── fluxo-solucao.md
```

## Benefícios Esperados

* Melhor aproveitamento das oportunidades comerciais;
* Maior eficiência na prospecção;
* Apoio à tomada de decisão;
* Escalabilidade da operação comercial;
* Maior presença da marca FYS no canal padarias.

---

## Melhorias Futuras

* Integração com CRM;
* Integração com geolocalização;
* Dashboard de oportunidades;
* Lead Scoring automatizado;
* Sugestão automática de roteiros de visita;
* Integração com agentes de IA para atendimento comercial.

---

## Tecnologias e Conceitos Aplicados

* Inteligência Artificial Generativa
* Engenharia de Prompt
* Base de Conhecimento
* Atendimento Consultivo
* Priorização Comercial
* IA Aplicada a Vendas

---

## Aplicação Prática

Embora este projeto tenha sido desenvolvido como uma solução conceitual para o desafio da DIO, sua estrutura foi organizada para permitir implementação prática em plataformas modernas de Inteligência Artificial.

A combinação entre:

* Base de conhecimento;
* Prompt especializado;
* Simulações de uso;
* Regras de decisão comercial;

permite que o Copiloto Comercial FYS seja utilizado em ferramentas como Cursor, Claude Projects, ChatGPT Custom GPTs, Antigravity e outras plataformas compatíveis com agentes de IA.

Para um guia completo de implementação e execução do agente, consulte:

📄 **docs/dar-vida-ao-agente.md**

---

## Autor

Projeto desenvolvido como atividade prática do Bootcamp DIO + FYS + Heineken, explorando o uso de Inteligência Artificial para resolver desafios reais de vendas e atendimento.
