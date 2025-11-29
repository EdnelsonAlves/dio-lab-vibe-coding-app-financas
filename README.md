# 💸 App de Organização de Finanças Pessoais com Vibe Coding - Entrega de Projetp

PRD Refinado:
PRD – App de Finanças Pessoais Conversacional (MVP)
1. Visão Geral do Produto

Nome provisório: Assistente Financeiro Conversacional (pode ser ajustado depois).

O produto é um aplicativo de organização de finanças pessoais baseado em conversa (chat), voltado para pessoas iniciantes que desejam controlar seus gastos de forma simples, sem planilhas e sem linguagem técnica.

Em vez de telas cheias de campos, o usuário interage com um “Agente Financeiro”, digitando frases naturais como:

“Gastei 35 reais no mercado hoje”
“Paguei 50 no Uber”
“Quero juntar 500 reais em 3 meses”

O app interpreta essas mensagens, registra os gastos, organiza por categorias, permite criar metas simples e apresenta um resumo do mês de forma clara.

2. Problema & Oportunidade
Problema

Muitas pessoas desistem de organizar as finanças porque:

Apps atuais exigem muita digitação manual e parametrização.

A experiência é técnica e pouco amigável para iniciantes.

Planilhas geram bloqueio e medo em quem não domina finanças.

Oportunidade

Criar uma solução onde:

O controle financeiro começa com uma conversa simples, como falar com um amigo.

O usuário não precisa conhecer termos técnicos nem saber “como montar uma planilha”.

O foco é em registrar gastos rapidamente, enxergar para onde o dinheiro está indo e receber dicas práticas de economia.

3. Objetivos do MVP
Objetivos de Negócio

Validar se um chat financeiro simples é suficiente para engajar iniciantes no controle de gastos.

Identificar se o conceito de “Agente Financeiro” gera percepção de valor e vontade de continuar usando.

Coletar feedback para priorizar futuras evoluções (integrações, recursos avançados, etc.).

Objetivos para o Usuário

Conseguir registrar seus gastos em menos de 15 segundos.

Entender onde está gastando mais naquele mês.

Criar pelo menos uma meta financeira simples e acompanhar o progresso.

Receber dicas de economia em linguagem clara, sem julgamento.

4. Público-Alvo

Pessoas que querem começar a organizar as finanças.

Usuários iniciantes, que:

Não gostam ou não sabem usar planilhas.

Não têm conhecimento prévio em finanças.

Sentem-se perdidos com apps cheios de funcionalidades e gráficos complexos.

Persona simplificada (exemplo):

Ana, 28 anos, trabalha em tempo integral, nunca conseguiu manter uma planilha de gastos por mais de 1 semana. Quer “parar de estourar o cartão” e “começar a sobrar dinheiro no fim do mês”, mas fica perdida em apps complicados. Prefere soluções simples, no estilo conversa.

5. Escopo do MVP
5.1. Funcionalidades Inclusas

Chat com o Agente Financeiro

Registrar gastos em linguagem natural.

Habilitar comandos simples:

“Como está meu mês?”

“Quero criar uma meta.”

“Quanto gastei em alimentação?”

Registro de Gastos via Chat

Entender:

Valor (ex.: 35, 50, 120).

Data (explicitamente ou usar data atual por padrão).

Categoria sugerida (alimentação, transporte, lazer, etc.).

Permitir correção da categoria em seguida.

Classificação Automática de Transações

Regra simples de categorização (palavras-chave + padrão de uso).

Usuário pode ajustar a categoria pelo chat ou na tela de histórico.

Definição e Acompanhamento de Metas Simples

Tipos de metas:

Limite mensal por categoria (ex.: Alimentação até R$ 400).

Meta de economia mensal (ex.: guardar R$ 200).

Objetivo específico (ex.: juntar R$ 500 em 3 meses).

Exibição de progresso (valor atual vs. meta).

Relatório “Meu Mês”

Total gasto no mês.

Gastos por categoria.

Destaques:

“Sua maior despesa está em [categoria].”

“Você já atingiu X% da meta de alimentação.”

Alertas e Dicas do Agente

Alertas simples:

“Você já usou 80% da sua meta de Lazer.”

Dicas de economia alinhadas ao comportamento observado.

Configurações Básicas

Nome/apelido do usuário.

Preferência de lembretes (sem, diário, alguns dias na semana).

5.2. Fora de Escopo (por enquanto)

Integração com bancos/cartões.

Várias moedas ou contas diferentes.

Funcionalidades de investimento.

Exportação avançada de relatórios (CSV, PDF).

Perfis múltiplos (família, empresa, etc.).

6. Telas do MVP
6.1. Tela de Boas-vindas / Onboarding

Objetivo: apresentar o app rapidamente e coletar 2–3 informações iniciais.

Elementos:

Explicação simples em 2–3 telas:

“Organize suas finanças conversando.”

“Registre gastos pelo chat.”

“Veja onde está gastando mais.”

Perguntas:

Objetivo principal (ex.: “parar de estourar o cartão”, “guardar dinheiro todo mês”, etc.).

Preferência de lembretes (sim/não, frequência).

Botão final: “Começar” → abre o chat.

6.2. Tela Principal – Chat Financeiro

Objetivo: ser o centro da experiência.

Elementos:

Área de mensagens (usuário ↔ Agente).

Campo de texto com placeholder:

“Ex.: ‘Gastei 35 reais no mercado hoje’”

Botões rápidos:

“Ver Meu Mês”

“Ver Metas”

“Registrar gasto rápido” (atalho opcional).

Comportamentos:

Após mensagem do tipo “Gastei X em Y hoje”:

Agente confirma, sugere categoria, pergunta se deseja ajustar.

Para dúvidas do usuário:

“Como está meu mês?” → link ou resposta resumida + botão para abrir tela “Meu Mês”.

6.3. Tela “Meu Mês”

Objetivo: mostrar um resumo rápido e compreensível.

Elementos:

Período (por padrão: mês atual).

Total gasto no mês.

Lista ou gráfico simples com gasto por categoria.

Destaques em texto:

“Você está gastando mais em [categoria].”

Ação: clicar em uma categoria abre o Detalhe da Categoria.

6.4. Tela de Metas

Objetivo: permitir criar e acompanhar metas financeiras simples.

Elementos:

Lista de metas:

Tipo, valor, progresso (ex.: “R$ 300 / R$ 400 – 75%”).

Botão: “Criar nova meta”.

Fluxo de criação:

Escolher tipo de meta.

Informar valor.

Informar prazo (quando fizer sentido).

6.5. Tela de Detalhe de Categoria / Histórico

Objetivo: mostrar os gastos de uma categoria específica.

Elementos:

Cabeçalho com nome da categoria e total gasto.

Lista de transações:

Data – descrição (se tiver) – valor.

Ações:

Editar categoria, valor ou data de uma transação.

6.6. Tela de Configurações

Objetivo: dar ao usuário sensação de controle mínimo.

Elementos:

Nome/apelido.

Preferência de lembretes.

Link simples para termos de uso/privacidade.

7. Requisitos Funcionais (resumo)

RF01 – O sistema deve permitir registrar um gasto via mensagem de texto no chat.

RF02 – O sistema deve extrair automaticamente valor, data e categoria sugerida, quando possível.

RF03 – O sistema deve permitir ao usuário corrigir a categoria de um gasto.

RF04 – O sistema deve permitir criar metas financeiras nos tipos:

limite de categoria,

economia mensal,

objetivo específico.

RF05 – O sistema deve calcular e exibir o progresso das metas.

RF06 – O sistema deve exibir o resumo “Meu Mês” com total gasto e gastos por categoria.

RF07 – O sistema deve enviar mensagens de alerta quando a meta estiver próxima de ser atingida (ex.: ≥ 80%).

RF08 – O sistema deve permitir configurar lembretes de registro de gastos.

RF09 – O sistema deve armazenar e listar o histórico de transações por categoria e por período.

8. Requisitos Não Funcionais (resumo)

RNF01 – Usabilidade: linguagem simples, sem termos técnicos; fluxo com poucas etapas.

RNF02 – Desempenho: respostas do agente em poucos segundos (quando online).

RNF03 – Segurança: dados financeiros básicos armazenados com segurança (mínimo: autenticação padrão da plataforma).

RNF04 – Acessibilidade: textos legíveis, contraste adequado, botões em tamanho confortável.

9. Tom de Voz do Agente Financeiro

Amigável, educativo e encorajador.

Sem tom de julgamento (“você gasta demais”) – preferir:

“Percebo que seus gastos em [categoria] estão altos, quer definir uma meta para isso?”

Linguagem simples, frases curtas.

Explicar conceitos quando necessário:

Ex.: “Meta é um objetivo que você quer alcançar, como gastar até R$ 400 em alimentação no mês.”

10. Métricas de Sucesso do MVP

% de usuários que:

Registram ao menos 3 gastos no primeiro dia.

Criam pelo menos 1 meta.

Retornam ao app após 7 dias.

Feedback qualitativo:

Usuários respondendo “sim” à pergunta:

“O app te ajudou a entender melhor para onde seu dinheiro está indo?”

NPS simples:

“Você recomendaria este app para alguém que não gosta de planilhas?” (0 a 10).

11. Estratégia de Validação (resumo)

Entrevistas iniciais com 5–10 usuários do público-alvo para entender hábitos e reações à ideia de “chat financeiro”.

Protótipo clicável com o fluxo: onboarding → chat → Meu Mês → Metas.

Beta fechado com 20–50 usuários por 7 a 14 dias:

Acompanhar uso real,

Coletar feedback por questionário curto.



### APP No Lovable
https://converse-fin.lovable.app

### APP No Lovable - Telas
<img width="1495" height="621" alt="image" src="https://github.com/user-attachments/assets/f07618af-ad3a-4eb4-b43f-98dbcd1e496d" />
<img width="481" height="509" alt="image" src="https://github.com/user-attachments/assets/8ec0dbdc-a1fb-48f7-a1f6-2551e84f5aa2" />
<img width="1057" height="714" alt="image" src="https://github.com/user-attachments/assets/2ba18464-73b2-48d9-a8e8-39f2d7e57d35" />
<img width="1002" height="619" alt="image" src="https://github.com/user-attachments/assets/c69dfce5-6f23-41cf-9979-fa846e6ddab7" />



###1. Resumo do que o meu App de Finanças Pessoais faz


Meu app ajuda pessoas iniciantes a organizarem suas finanças por meio de conversa, em vez de planilhas ou formulários.
O usuário fala com um “Agente Financeiro” em um chat, dizendo coisas como:

“Gastei 35 reais no mercado hoje”

O app entende o valor, a data e a categoria, registra o gasto, permite criar metas simples (como limite por categoria ou juntar um valor em X meses) e mostra um resumo do mês com onde a pessoa está gastando mais e se está perto de estourar algum limite.

2. Reflexão sobre o processo

O que funcionou bem?

A ideia de usar chat em vez de planilhas para deixar tudo mais leve para iniciantes.

Usar a IA para estruturar o MVP (telas, fluxo e prioridades), deixando a ideia mais clara e organizada.

O que não funcionou como o esperado?

No início, fiz pedidos muito amplos e recebi respostas genéricas demais.

Algumas sugestões da IA eram complexas para um MVP e precisaram ser simplificadas.

O que aprendi sobre conversar com IAs?

Quanto mais contexto e detalhes eu dou, melhor fica a resposta.

É importante ser específico no pedido (o que eu quero, para quem, com qual tom).

Trabalhar com IA é um processo iterativo: peço, ajusto, aprofundo. Funciona melhor como uma parceria do que como uma resposta “única e final”.

