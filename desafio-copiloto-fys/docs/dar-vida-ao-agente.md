# Como Dar Vida ao Copiloto Comercial FYS

## Introdução

Até este ponto, construímos toda a inteligência do nosso Copiloto Comercial FYS através de:

* Base de conhecimento;
* Regras de negócio;
* Argumentos comerciais;
* Prompt especializado.

Agora vamos transformar esse material em um agente funcional utilizando plataformas de Inteligência Artificial.

Mesmo que você nunca tenha criado um agente antes, siga os passos abaixo.

---

## Antes de Começar

Caso ainda não tenha preparado os arquivos localmente:

➡️ [Preparando o Ambiente](preparando-o-ambiente.md)

---

# Opção 1 - Cursor AI (Recomendado)

O Cursor é uma ferramenta baseada em Inteligência Artificial que permite criar agentes utilizando arquivos como contexto.

## Passo 1 - Instalar o Cursor

Acesse:

https://cursor.com

Baixe a versão compatível com seu sistema operacional e realize a instalação.

---

## Passo 2 - Abrir o Projeto

Abra o Cursor.

Clique em:

```text
File → Open Folder
```

Selecione a pasta:

```text
desafio-copiloto-fys
```

Você deverá visualizar:

```text
knowledge/
prompts/
examples/
docs/
README.md
```

na barra lateral esquerda.

---

## Passo 3 - Abrir o Chat

No canto direito do Cursor existe um ícone de chat.

Clique nele para abrir o assistente.

---

## Passo 4 - Configurar o Agente

Copie e envie a seguinte instrução:

```text
Leia todos os arquivos da pasta knowledge e o arquivo prompts/agente-priorizacao-padarias.md.

Utilize essas informações como base de conhecimento permanente para esta conversa.

A partir de agora você será o Copiloto Comercial FYS.
```

Aguarde alguns segundos para o Cursor processar os arquivos.

---

## Passo 5 - Realizar o Primeiro Teste

Cole:

```text
Padaria Bom Pão

Cidade: Campinas

Fluxo de clientes: Alto

Venda de refrigerantes individuais: Sim

Possui geladeira para bebidas: Sim

Movimento no horário do almoço: Alto
```

O agente deverá gerar:

* Diagnóstico
* Potencial Comercial
* Prioridade
* Argumento Comercial
* Próxima Ação Recomendada

---

# Opção 2 - Claude Projects

O Claude permite criar projetos com conhecimento persistente.

## Passo 1

Acesse Claude.

Crie um novo Project.

---

## Passo 2

Faça upload dos arquivos da pasta:

```text
knowledge/
```

---

## Passo 3

Copie o conteúdo do arquivo:

```text
prompts/agente-priorizacao-padarias.md
```

e cole nas instruções do projeto.

---

## Passo 4

Salve o projeto.

---

## Passo 5

Teste utilizando uma padaria fictícia.

Exemplo:

```text
Padaria Central

Cidade: São Paulo

Fluxo: Alto

Vende bebidas individuais: Sim
```

---

# Opção 3 - ChatGPT (GPT Personalizado)

## Passo 1

Acesse:

Explorar GPTs → Criar GPT

---

## Passo 2

No campo "Instruções", copie o conteúdo de:

```text
prompts/agente-priorizacao-padarias.md
```

---

## Passo 3

Na seção "Conhecimento", envie os arquivos:

```text
knowledge/
```

---

## Passo 4

Salve o GPT.

---

## Passo 5

Inicie uma conversa e forneça dados de uma padaria para análise.

---

# Opção 4 - Antigravity

## Passo 1

Criar um novo agente.

Nome:

```text
Copiloto Comercial FYS
```

---

## Passo 2

Localize o campo:

```text
System Prompt
```

Cole o conteúdo de:

```text
prompts/agente-priorizacao-padarias.md
```

---

## Passo 3

Adicione todos os arquivos da pasta:

```text
knowledge/
```

na área de Base de Conhecimento.

---

## Passo 4

Salvar e publicar o agente.

---

# Exemplo Completo de Uso

Entrada:

```text
Padaria Pão Quente

Cidade: São Paulo

Fluxo de clientes: Alto

Venda refrigerantes individuais: Sim

Espaço para exposição: Médio

Movimento almoço: Alto

Público predominante: Trabalhadores e estudantes
```

Saída esperada:

```text
Potencial Comercial: 9/10

Prioridade: Estratégica

Pontos Fortes:
- Alto fluxo diário
- Consumo individual compatível
- Público alinhado ao perfil da marca

Argumento Comercial:
A FYS complementa o portfólio da padaria com opções alinhadas às tendências de consumo, oferecendo produtos com menos açúcar e o respaldo do Grupo Heineken.

Próxima Ação:
Agendar visita comercial e propor teste inicial do portfólio.
```

---

# Conclusão

Este projeto foi estruturado para demonstrar como uma base de conhecimento bem organizada, combinada com Engenharia de Prompt, pode transformar um desafio real de vendas em uma solução prática utilizando Inteligência Artificial.

---

## Entenda Como a Solução Funciona

➡️ [Fluxo da Solução](fluxo-solucao.md)
