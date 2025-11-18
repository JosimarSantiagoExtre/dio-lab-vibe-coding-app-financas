# 💸 App de Finanças Pessoais com Vibe Coding finsnças IA

### 3. Entregando o Desafio na DIO

PRD Refinado no COPILOT WEB:

```Markdown
# PRD – App de Finanças Pessoais com Assistente Financeiro de IA (Design Universal + Linguagem Natural)

Este aplicativo foi pensado para ajudar pessoas a organizar o dinheiro de forma simples e prática.  
Ele permite registrar ganhos e gastos de forma intuitiva, aplicar automaticamente a regra dos 30% sobre qualquer entrada de valor, criar sonhos e metas financeiras, e receber dicas fáceis para começar a investir sem complicação.  
O diferencial é um **assistente financeiro com inteligência artificial**, que conversa em linguagem natural, entende o contexto do usuário e sugere ações personalizadas.

## Objetivo
Ajudar pessoas a cuidar melhor do dinheiro sem complicação.  
O assistente fala de forma clara e natural, mostrando quanto guardar, oferecendo dicas simples e ajudando a planejar sonhos.

## Público
- Pessoas que têm dificuldade em controlar gastos.  
- Quem nunca usou aplicativos de finanças.  
- Quem quer começar a investir de forma descomplicada.  

## Funcionalidades

### Assistente Financeiro com IA
- Conversa em linguagem natural com o usuário.  
- Entende entradas de ganhos e gastos.  
- Sugere guardar 30% de cada entrada automaticamente.  
- Dá dicas personalizadas com base no comportamento financeiro.  
- Responde perguntas simples como:  
  - "Quanto já guardei este mês?"  
  - "Posso gastar mais em lazer?"  

### Sonhos de Investimento
- O usuário escreve seus sonhos, como comprar uma casa ou fazer uma viagem.  
- O assistente responde: "Para realizar esse sonho, você precisa guardar R$ X por mês."  

### Dicas Simples
- Textos curtos e conversacionais.  
- Exemplos:  
  - "Primeiro, guarde para emergências."  
  - "Evite dívidas no cartão, elas crescem rápido."  

### Guardar 30% de Qualquer Entrada
- O usuário informa qualquer valor que entra, seja salário, freela ou presente.  
- O assistente responde naturalmente: "Você recebeu R$ 200, guarde R$ 60 para o futuro."  
- Mostra o progresso com frases simples: "Você já guardou R$ Y este mês."  

### Ganhos e Gastos Intuitivos
- Campos simples para registrar "Ganhos" e "Gastos".  
- O assistente traduz em linguagem natural: "Você gastou R$ 50 em transporte, sobram R$ 150."  
- Visualização intuitiva com frases e gráficos fáceis de entender.  

## Requisitos

### Funcionais
- Cadastro rápido (nome e renda).  
- Criar e editar sonhos.  
- Cálculo automático de 30% sobre qualquer entrada.  
- Registro intuitivo de ganhos e gastos.  
- Dicas curtas em linguagem natural.  
- Assistente de IA integrado para conversas e sugestões.  
- Tela inicial simples com tudo em um só lugar.  

### Não Funcionais
- Design universal (acessível para todos).  
- Linguagem natural e simples.  
- Rápido e seguro.  
- Funciona em Android e iOS.  

## Sucesso
- Quantos usuários criam pelo menos um sonho.  
- Quantos guardam 30% de cada entrada.  
- Quantos registram ganhos e gastos regularmente.  
- Quantos interagem com o assistente de IA.  
- Quantos leem e entendem as dicas sem esforço.  

## Roadmap
- MVP: entradas de valor + cálculo de 30% + sonhos + registro de ganhos e gastos com assistente de IA básico.  
- Versão 2: dicas simples e conversacionais com IA mais personalizada.  
- Versão 3: notificações inteligentes e acessibilidade avançada (voz, contraste, fontes).  

```

Interações com o Loveble:

> crie um app de finanças pessoais de acordo com o seguinte PRD {PRD}

> sim {Gostaria que eu continue para finalizar esses últimos ajustes?}

> quando se falar em ganhos e gastos ao assistente financeiro esse deve colocar os valores no dashboard e perguntar se vai guardar os 30%, se a resposta for sim também colocar no dashboard e for não não colocar
  
> o assistente deve registrar os valores ganhos em total ganhos no dashboard, os valores gastos no total de gastos no dashboard, o economizado não deve ser automatico mas sim perguntar se será guardado esse valor ou não, se positivo deve ser contabilizado em economizado, se não deve ficar em negativo. a meta de economia deve ser em relação ao valor do sonho, o assistente deve contabilizar os sonhos e as transações

> quando for falado em gastos para o assistente esse deve registrar em gastos nas transações e no total gastos do dashboard, deve ter um registro no dashboard de total em caixa contabilizando o total de ganhos subtraindo o total de gastos, o assistente deve perguntar sobre o desejo de economizar os 30% se a resposta for positiva ele deve contabilizar em economizado e se for negativa ele deve subtrair do economizado.

>  preciso que tenha um botão onde se possa ser feita alterações nos valores contidos no dashboard.
preciso que o assistente sempre que for informado que teve algum ganho de valores se gostaria de guardar 30%.
preciso que o assistente sempre que for informado que se quer guardar 30% do valor faça o preenchimento no dashboard, tanto do valor ganho quanto do valor guardado.
preciso que o assistente sempre que for informado que não se quer guardar os 30% responda o porque é importante ter uma reserva de emergencia.
preciso que o assistente sempre que for informado que se quer guardar 30% de dicas do como pode ser investido este valor.
preciso que o assistente sempre que for informado de um sonho pergunte o valor do sonho e coloque as informações na aba sonho.
preciso que sempre que se diga que gastou o valor do economizado seja subtraido o valor no dashboard.
preciso que o assistente fique fixo no dashboard.
preciso que tenha um botão em transações onde se possa ter acesso ao extrato do periodo selecionado.
preciso que todos os valores sejam atualizados em tempo real.

> preciso que em cada caixa tenha um botão de editar valores no dashboard, preciso que os valores na caixa economizado possam ser subtraidos e atualizados. preciso que o assistente fique aberto na parte inferior do dashboard e não em uma outra aba.

Resultado Final no Lovable: https://dinheiro-amigo-ia.lovable.app/dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0c2a9e28-c31a-432b-b172-1dca5ad5fa15" />

## Principais Funcionalidades do FinançasIA
### Assistente Financeiro com IA
Conversa em Linguagem Natural: Interage de forma humana, entendendo o contexto dos ganhos e gastos.

Sugestão Personalizada: Oferece dicas e ações com base no comportamento financeiro do usuário.

Respostas Imediatas: Responde a consultas simples (ex: "Quanto já guardei este mês?", "Posso gastar mais em lazer?").

### Metas e Sonhos de Investimento
Criação de Sonhos: Permite registrar objetivos financeiros de longo prazo (ex: casa, viagem).

Cálculo de Metas: A IA calcula e informa o valor necessário para guardar mensalmente.

Monitoramento de Progresso: Exibe o progresso em relação à "Meta de Economia (Total dos Sonhos)" no Dashboard.

### Regra de Economia Automática (30%)
Cálculo Automático: Aplica a regra de guardar 30% de qualquer valor de entrada (salário, freela, etc.).

Feedback Simples: Informa o valor sugerido para guardar em linguagem fácil ("Você recebeu R$ 200, guarde R$ 60...").

Registro Visível: Exibe o total já "Economizado" no Dashboard.

### Gestão Intuitiva de Ganhos e Gastos
Registro Simplificado: Campos claros para registrar "Ganhos" e "Gastos".

Tradução em Frases: O assistente traduz os registros para linguagem natural ("Você gastou R$ 50, sobram R$ 150.").

Dashboard Centralizado: Tela inicial simples com indicadores chave: Ganhos, Gastos, Economizado, Sonhos Ativos e Total em Caixa.

### Dicas Simples de Educação Financeira
Conteúdo Conversacional: Textos curtos e diretos para descomplicar a vida financeira (ex: "Guarde primeiro para emergências.").

## reflexão sobre o processo 
### O que funcionou bem?  
A interação com o copilot foi bem satisfatória, eu resolvi criar o PRD do zero apenas com uma ideia simples e fui refinando colocando mais informações, o que foi bem legal.

### O que não funcionou como o esperado?
Quando foi levado o PRD para o Lovable deu bastante problema, tanto que não consegui fazer a IA do assistente fazer as atualizações direito nos valores, também não consegui que os valores no quesito Economizado fossem retirados, nem por IA e nem manualmente, a IA do app também não coloca os valores muito certos, as vezes entendendo como sonhos, as vezes colocando valor duplicado. Todavia no fim ela perguntava sobre a previsão de economia e porque de ser uma boa. 

### O que aprendeu sobre conversar com IAs?
Aprendi que quanto mais imputs você der mais facil a interação e o entendimento da IA. Todavia tem dias que é meio dificil e a IA não entende, Você não entende, ninguém entende e é isso.


## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
