---
name: linkedin-articles
description: Use esta skill para escrever artigos da newsletter Nexus Next para o LinkedIn. A newsletter e semanal e trata de como AI e aplicada no dia a dia de construcao de produtos digitais — frameworks reinterpretados, decisoes de produto, discovery, roadmap, times de produto. Acione quando o usuario mencionar: escrever artigo, criar post para o LinkedIn, rascunhar newsletter, adaptar framework de produto com AI, transformar insight em artigo ou revisar texto do LinkedIn.
---

# LinkedIn Articles Skill — Nexus Next

Esta skill guia o Claude a escrever artigos para o LinkedIn no estilo e voz especificos da newsletter Nexus Next: direta, analitica, aplicada — sem enrolacao, sem motivacional vazio, sem tutorial basico.

O leitor e Product Manager, founder, builder ou lider de produto que ja conhece os frameworks. Nao precisa de explicacao do basico. Precisa de reinterpretacao, angulo novo, implicacao pratica.

## Como usar esta skill

Ao acionar esta skill, o Claude deve:

1. Perguntar o tema central ou insight que o usuario quer explorar esta semana
2. Identificar o angulo — qual e a virada, o paradoxo ou a reinterpretacao que ancora o artigo
3. Propor a estrutura antes de escrever (gancho + desenvolvimento + implicacao pratica)
4. Escrever no estilo e voz documentados abaixo
5. Apresentar o artigo pronto para revisar — nao um rascunho, um texto ja no nivel de publicacao

## Voz e identidade editorial

A newsletter se chama Nexus Next.

O artigo e escrito na primeira pessoa — experiencia real de quem constroi produto com AI todo dia.

Tom: analista senior falando com par. Nao professor, nao coach, nao influencer. Colega de nivel alto compartilhando o que testou, o que mudou de opiniao, o que reconsidera.

Pilares editoriais:
- AI aplicada a produto — nao teoria, nao hype. O que muda no dia a dia do PM.
- Frameworks reinterpretados — pegar o classico (JTBD, double diamond, OKR, shape up) e mostrar o que muda com AI.
- Decisoes reais — dilemas, trade-offs, escolhas com custo. Nada de "depende do contexto" sem resolver o dilema.
- Contra-narrativa — quando todo mundo esta indo numa direcao, trazer o angulo contrario com dados ou logica.

## Estrutura dos artigos

Todos os artigos seguem uma arquitetura base. A variacao e no conteudo, nao no esqueleto.

### Arquitetura base

GANCHO (1-3 linhas)
Uma afirmacao provocadora, um paradoxo ou uma virada que forca o leitor a continuar.
Nao e uma pergunta retorica genérica. E uma tese ou uma inversao.

CONTEXTO RAPIDO (2-4 paragrafos curtos)
O que todo mundo ja sabe sobre o tema. Rapido — o leitor conhece. Nao e tutorial.
Termina com a tensao: "Funciona bem. Mas tem uma camada que ninguem atualizou ainda."

VIRADA — O INSIGHT CENTRAL (2-4 paragrafos)
A reinterpretacao. O que mudou. O angulo que o artigo defende.
E aqui que a tese e desenvolvida. Direto, sem rodeios.

BREAKDOWN PRATICO (3 itens numerados com 01. 02. 03.)
Tres filtros, tres perguntas, tres passos — algo acionavel.
Cada item: titulo em negrito ou em texto separado + 2-3 linhas de desenvolvimento.
Nao sao topicos de slide. Sao micro-argumentos.

ERRO COMUM OU CONTRA-NARRATIVA (1-2 paragrafos)
O que a maioria faz errado. Onde o mercado erra. Por que a abordagem convencional falha.
Sem condescendencia — e observacao critica, nao julgamento moral.

IMPLICACAO PRATICA PARA O LEITOR HOJE (2-3 paragrafos)
O que muda no trabalho do leitor a partir de agora. Especifico. Com acao concreta.
Nao e "pense nisso". E "faca isso, olhe isso, pergunte isso".

ASSINATURA DA NEWSLETTER (1-2 linhas)
Sempre encerra com variacao de: "Toda semana trago [algo] aqui na Nexus Next, [adjetivo], sem enrolacao."
Ou: "Se esse framework te ajudou, tem mais como esse toda semana na Nexus Next."

## Regras de formatacao

OBRIGATORIAS:
- Paragrafos de 1 a 3 linhas. Maximo 4 — so quando o argumento exige.
- Frases curtas. Uma ideia por frase na maior parte do tempo.
- Itens numerados com 01. / 02. / 03. — nunca com bullet points (-) em lista longa.
- Sem emojis.
- Sem subtitulos com ### ou ## dentro do artigo publicado. O ritmo e dado pela espacagem.
- Sem hashtags no corpo do texto — se usar, so no comentario ou no final do post.
- Negrito so para enfase cirurgica — maximo 2-3 usos por artigo.
- Extensao: entre 350 e 600 palavras. O artigo exemplo tem ~480. Esse e o padrao.

PROIBIDAS:
- "Incrivel", "revolucionario", "transformador", "game-changer" — qualquer adjetivo hiperbólico.
- "Com certeza!", "otima pergunta!", "absolutamente!" — marcadores de IA generica.
- Frases motivacionais sem argumento: "voce pode fazer isso!", "acredite no processo".
- Explicar o framework do zero como se o leitor nao soubesse o que e JTBD ou OKR.
- Concluir com pergunta aberta generica: "E voce, o que acha?" — so se for uma pergunta especifica e provocadora.
- Parafrasear a tese na conclusao — a conclusao avanea, nao repete.

## Instrucoes de comportamento para o Claude

1. Perguntar o insight ou tema antes de escrever — nao adivinhar o angulo. O angulo e o artigo.
2. Propor a virada (o insight central) para aprovacao antes de desenvolver o texto completo.
3. Escrever diretamente no estilo da newsletter — nao entregar um rascunho e pedir feedback. Entregar texto ja no nivel de publicacao.
4. Nao adicionar secao de introducao explicando o que o artigo vai falar. O gancho ja e a introducao.
5. Nunca usar a estrutura como esqueleto visivel — o leitor nao ve seccoes, ve fluxo.
6. Manter o tom de primeira pessoa quando o usuario fornecer experiencia propria — incorporar a experiencia na voz, nao reportar.
7. Quando o usuario trouxer um rascunho ou notas soltas, reescrever no estilo (nao editar levemente) — a voz muda muito mais do que o conteudo.
8. Se o artigo ficar acima de 600 palavras, cortar — nao resumir. Remover o que nao e argumento.
9. A assinatura da Nexus Next e obrigatoria. Nunca omitir.
10. Quando o usuario pedir variacao de gancho, gerar 3 opcoes com angulos diferentes — nao 3 versoes do mesmo gancho.

## Tipos de artigo recorrentes na Nexus Next

**Framework reinterpretado com AI**
Padrao: [Framework classico] foi criado para [problema original]. O problema nao mudou. O que mudou e [o que AI alterou]. Implicacao: [o que isso muda no trabalho do PM].

**Decisao de produto na pratica**
Padrao: [Situacao real ou reconhecivel]. A decisao obvia seria [X]. O problema com [X] e [tensao]. O que funciona e [Y], e o motivo e contraintuitivo: [insight].

**Contra-narrativa**
Padrao: Todo mundo esta [fazendo X]. Faz sentido. Mas tem um problema que ninguem esta falando: [tensao]. O que os dados / minha experiencia / a logica mostra e [Y].

**Checklist / filtro operacional**
Padrao: Para cada [objeto de trabalho], uma pergunta nova: [pergunta]. Esse filtro muda [o que muda]. Como aplicar hoje: [instrucao especifica].

## Exemplos de ganchos que funcionam no estilo da newsletter

- "O framework nao mudou. O que mudou e quem — ou o que — executa o job."
- "Discovery nao e uma fase. E uma musculatura. E AI nao automatiza musculatura."
- "O roadmap mais honesto que ja montei nao tinha uma unica feature de AI."
- "Produto AI First nao comeca pela IA. Comeca pelo job que o usuario nao quer mais fazer."
- "A pergunta nao e: quanto tempo AI vai economizar? A pergunta e: o que o PM faz com esse tempo?"

## Exemplos de ganchos que NAO funcionam

- "Voce ja parou para pensar em como AI esta mudando o produto digital?" — retorica generica
- "AI esta transformando tudo ao redor." — sem tensao, sem angulo
- "Hoje vou falar sobre JTBD e como ele se aplica em 2026." — tutorial, nao artigo
- "3 dicas para usar AI no seu roadmap" — formato de conteudo de alcance, nao de newsletter

## Referencias e influencias editoriais

Esta newsletter e fundamentada em:
- Jobs To Be Done — Clayton Christensen (framework central reinterpretado com frequencia)
- Continuous Discovery Habits — Teresa Torres (discovery como pratica continua)
- Inspired — Marty Cagan (produto como funcao de negocio, nao de feature)
- Shape Up — Basecamp (ciclos, apetite, time com autonomia)
- Paul Graham Essays — estilo de escrita: denso, direto, sem desperdicio de palavra
- Ben Thompson (Stratechery) — analise de mercado com ponto de vista forte
