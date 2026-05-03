---
name: linkedin-articles
description: Use esta skill para escrever artigos da newsletter Nexus Next para o LinkedIn. A newsletter e semanal e trata de como AI e aplicada no dia a dia de construcao de produtos digitais — frameworks reinterpretados, decisoes de produto, discovery, roadmap, times de produto. Acione quando o usuario mencionar: escrever artigo, criar post para o LinkedIn, rascunhar newsletter, adaptar framework de produto com AI, transformar insight em artigo, revisar texto do LinkedIn, criar imagem de capa, gerar copy para post ou criar legenda para postagem.
---

# LinkedIn Articles Skill — Nexus Next

Esta skill guia o Claude a escrever artigos para o LinkedIn no estilo e voz especificos da newsletter Nexus Next: direta, analitica, aplicada — sem enrolacao, sem motivacional vazio, sem tutorial basico.

O leitor e Product Manager, founder, builder ou lider de produto que ja conhece os frameworks. Nao precisa de explicacao do basico. Precisa de reinterpretacao, angulo novo, implicacao pratica.

## Como usar esta skill

Ao acionar esta skill, o Claude deve:

- Perguntar o tema central ou insight que o usuario quer explorar esta semana
- Identificar o angulo — qual e a virada, o paradoxo ou a reinterpretacao que ancora o artigo
- Propor a estrutura antes de escrever (gancho + desenvolvimento + implicacao pratica)
- Escrever no estilo e voz documentados abaixo
- Apresentar o artigo pronto para revisar — nao um rascunho, um texto ja no nivel de publicacao

## Mapa do fluxo

```
ACIONAR SKILL
     |
     v
PERGUNTAR INSIGHT/TEMA DA SEMANA
     |
     v
PROPOR VIRADA (ANGULO CENTRAL)
  aprovado? ──nao──> revisar angulo
     |
    sim
     v
ESCREVER ARTIGO (350-600 palavras)
     |
     +──────────────────────────────+
     |                              |
     v                              v
GERAR COPY DO POST            GERAR PROMPT DE IMAGEM
(SEO + Copywriting)           (1920x1080 — Nexus Next)
     |                              |
     v                              v
ENTREGAR PACOTE COMPLETO: artigo + copy + prompt de imagem
```

## Voz e identidade editorial

A newsletter se chama Nexus Next. O artigo e escrito na primeira pessoa — experiencia real de quem constroi produto com AI todo dia.

Tom: analista senior falando com par. Nao professor, nao coach, nao influencer. Colega de nivel alto compartilhando o que testou, o que mudou de opiniao, o que reconsidera.

Pilares editoriais:

- AI aplicada a produto — nao teoria, nao hype. O que muda no dia a dia do PM.
- Frameworks reinterpretados — pegar o classico (JTBD, double diamond, OKR, shape up) e mostrar o que muda com AI.
- Decisoes reais — dilemas, trade-offs, escolhas com custo. Nada de "depende do contexto" sem resolver o dilema.
- Contra-narrativa — quando todo mundo esta indo numa direcao, trazer o angulo contrario com dados ou logica.

## Etapas detalhadas

### Etapa 1 — Coleta de contexto

**Quando usar:** antes de qualquer escrita

**Perguntas de contexto:**
- Qual e o insight ou tema da semana?
- Tem um framework classico envolvido? Qual?
- Qual e a virada — o que muda, o que contradiz, o que surpreende?
- Ha uma experiencia propria que ancora o argumento?

**Output:** angulo proposto em 2-3 linhas para aprovacao antes de escrever

---

### Etapa 2 — Artigo (350-600 palavras)

**Quando usar:** apos aprovacao do angulo

**Arquitetura base:**

GANCHO (1-3 linhas)
Uma afirmacao provocadora, um paradoxo ou uma virada que forca o leitor a continuar. Nao e uma pergunta retorica generica. E uma tese ou uma inversao.

CONTEXTO RAPIDO (2-4 paragrafos curtos)
O que todo mundo ja sabe sobre o tema. Rapido — o leitor conhece. Nao e tutorial. Termina com a tensao: "Funciona bem. Mas tem uma camada que ninguem atualizou ainda."

VIRADA — O INSIGHT CENTRAL (2-4 paragrafos)
A reinterpretacao. O que mudou. O angulo que o artigo defende. E aqui que a tese e desenvolvida. Direto, sem rodeios.

BREAKDOWN PRATICO (3 itens numerados com 01. 02. 03.)
Tres filtros, tres perguntas, tres passos — algo acionavel. Cada item: titulo em negrito ou em texto separado + 2-3 linhas de desenvolvimento. Nao sao topicos de slide. Sao micro-argumentos.

ERRO COMUM OU CONTRA-NARRATIVA (1-2 paragrafos)
O que a maioria faz errado. Onde o mercado erra. Por que a abordagem convencional falha. Sem condescendencia — e observacao critica, nao julgamento moral.

IMPLICACAO PRATICA PARA O LEITOR HOJE (2-3 paragrafos)
O que muda no trabalho do leitor a partir de agora. Especifico. Com acao concreta. Nao e "pense nisso". E "faca isso, olhe isso, pergunte isso".

ASSINATURA DA NEWSLETTER (1-2 linhas)
Sempre encerra com variacao de:
"Toda semana trago [algo] aqui na Nexus Next, [adjetivo], sem enrolacao."
Ou: "Se esse framework te ajudou, tem mais como esse toda semana na Nexus Next."

---

### Etapa 3 — Copy do post no LinkedIn (SEO + Copywriting)

**Quando usar:** apos artigo aprovado — gerar copy separada para a postagem que acompanha o artigo

**O que e:** o post e diferente do artigo. E a vitrine. O que aparece no feed antes do "ver mais". Precisa parar o scroll, gerar curiosidade e converter para o clique ou engajamento.

**Estrutura do copy do post:**

LINHA 1 — HOOK VISUAL (antes do "ver mais")
A linha mais importante. Precisa parar o scroll. Estrategias:
- Afirmacao contraintuitiva: "Todo PM usa discovery errado. E eu usei tambem."
- Numero + promessa especifica: "3 perguntas que mudaram como eu escrevo PRD com AI."
- Tensao reconhecivel: "Voce tem o roadmap. A AI tem o contexto. Mas ninguem alinhou os dois."
- Pergunta provocadora (so se for especifica): "O que acontece quando a spec e lida pela AI, nao pelo time?"

PARAGRAFO DE CONTEXTO (3-5 linhas)
Expande o hook. Nao entrega a resposta ainda. Cria tensao. Usa frases curtas. Leva o leitor para o "ver mais".

CORPO DO POST (5-8 paragrafos curtos)
Desenvolve o argumento em blocos de 1-3 linhas. Usa espacamento generoso. Pode incluir lista numerada (01. 02. 03.) se for acionavel. Tom igual ao artigo: par, nao professor.

CTA FINAL (1-2 linhas)
Especifico. Provoca acao ou reflexao concreta. Evitar: "o que voce acha?" generico. Preferir: "Se voce usa [X], testa isso hoje." ou "Deixa nos comentarios qual parte do seu [objeto] ainda nao tem spec."

HASHTAGS (so no final, fora do corpo)
Maximo 3-5. Sempre tematicas, nao de alcance generico. Exemplos: #produtodigital #AIFirst #ProductManagement #NexusNext #descoberta

**Regras de copywriting e SEO para o post:**

- Palavra-chave principal nas primeiras 2 linhas (ex: "discovery", "PRD", "roadmap com AI")
- Frases de 8 a 15 palavras no maximo — legibilidade mobile first
- Cada paragrafo tem no maximo 3 linhas — espacamento e leitura rapida
- Sem bold excessivo — maximo 2 usos para enfase cirurgica
- Sem emojis — exceto se o usuario pedir explicitamente
- Tom conversacional mas preciso — nao informal demais, nao corporativo
- Densidade de palavra-chave organica: mencionar o conceito central 2-3x sem forcar
- Sem clickbait vazio — o hook promete o que o post entrega
- Call to action deve ser especifico e baixo atrito

**Output esperado:** bloco de texto pronto para colar no LinkedIn, com as hashtags ao final separadas

---

### Etapa 4 — Prompt de imagem de capa (1920x1080)

**Quando usar:** junto com o artigo ou separadamente quando o usuario pedir a imagem de capa

**O que e:** um prompt completo e detalhado para geracao de imagem via ferramentas como Midjourney, DALL-E, Ideogram ou Adobe Firefly. O prompt segue o padrao visual da Nexus Next.

**Paleta de cores Nexus Next (Claude brand colors adaptados):**
- Background: off-white parchment (#F5F0E8) com textura grain sutil
- Accent primario: coral-laranja (#CF6247)
- Accent secundario: violeta (#7B5EA7)
- Texto: charcoal escuro (#1A1A1A)
- Elementos suaves: cinza (#AAAAAA)
- Superficies highlight: areia (#EDE8DE)
- Divisores: cinza quente claro (#D5CFC6)

**Template de prompt de imagem — adaptar para cada artigo:**

```
Create a horizontal widescreen infographic at 1920x1080 pixels (16:9 ratio), designed for LinkedIn article cover or presentation slide.

The subject is "[TITULO DO ARTIGO]" — [descricao conceitual de uma linha do que o artigo defende].

COLOR PALETTE — Claude brand colors:
- Background: warm off-white parchment (#F5F0E8) with subtle grain texture
- Primary accent: Claude coral-orange (#CF6247)
- Secondary accent: Claude violet (#7B5EA7)
- Text: deep charcoal (#1A1A1A)
- Muted elements: soft grey (#AAAAAA)
- Highlight surfaces: sand (#EDE8DE)
- Divider lines: light warm grey (#D5CFC6)

LAYOUT — three horizontal columns, separated by thin warm dividers

LEFT COLUMN — [Nome da coluna esquerda — contexto ou problema]
Header label (small caps, coral): [LABEL DA COLUNA]
Large serif quote centered: "[citacao central ou afirmacao que resume a coluna]"
Attribution below in small italic grey: [— atribuicao ou fonte]
Below the quote, a simple visual: [descricao do elemento visual — pilha de documentos, diagrama, seta]
Small caption at bottom of column: "[frase curta de fechamento da coluna]"

CENTER COLUMN — [Nome da coluna central — virada / insight dominante]
Background: soft sand (#EDE8DE) with coral left and right border lines — this column is the visual anchor
Header label (small caps, violet): [LABEL DA COLUNA CENTRAL]
Large bold statement in two lines: "[afirmacao central do artigo em 2 linhas]"
Below, three filter rows — each with an icon, label and short description:
Row 1 — icon: [descricao do icone] (coral) | Label: [label] | Description: [descricao curta]
Row 2 — icon: [descricao do icone] (violet) | Label: [label] | Description: [descricao curta]
Row 3 — icon: [descricao do icone] (coral-muted) | Label: [label] | Description: [descricao curta]
Divider line below the rows, then a bold callout box in coral:
"[frase de impacto — a principal implicacao pratica do artigo]"

RIGHT COLUMN — [Nome da coluna direita — exercicio ou aplicacao]
Header label (small caps, coral): [LABEL DA COLUNA]
Title: [titulo da coluna]
Three clean numbered rows, each with a checkbox-style icon:
01 → [primeiro item] | Sub: [descricao curta]
02 → [segundo item] | Sub: [descricao curta]
03 → [terceiro item] | Sub: [descricao curta]
Small italic note at bottom of column: "[nota final de fechamento]"

BOTTOM STRIP — full width, dark charcoal (#1A1A1A) background, light text. Three elements centered horizontally:
- Left: small tag "[temas do artigo separados por pontos]" in coral
- Center: NEXUS NEXT — por Cams in white, bold, slightly larger
- Right: "[mes ano]" in light grey italic

VISUAL STYLE:
- Editorial, warm, professional — not corporate slide deck, not cold tech aesthetic
- Center column slightly elevated with a subtle shadow to create hierarchy
- Typography: strong bold serif for main statements, clean sans-serif for labels and descriptions
- Icons: minimal line-style, consistent weight, no fill except for accent color highlights
- Generous padding inside each column — content breathes
- Paper grain texture on background
- NO: dark backgrounds on main area, neon, gradients, 3D effects, robot imagery, neural network visuals

Dimensions: exactly 1920x1080 pixels, horizontal orientation.
```

**Instrucoes para o Claude ao gerar o prompt de imagem:**

- Substituir todos os campos entre colchetes [ ] com conteudo especifico do artigo
- A coluna esquerda representa o problema ou o contexto tradicional (o que todo mundo ja conhece)
- A coluna central e o insight — deve ter o maior peso visual e a afirmacao mais forte do artigo
- A coluna direita e a acao — o que o leitor faz a partir de hoje
- O bottom strip deve sempre manter: "NEXUS NEXT — por Cams" no centro
- O tag de temas deve refletir as palavras-chave principais do artigo (maximo 4 temas)
- A descricao conceitual de uma linha deve capturar a tese do artigo, nao apenas o titulo

---

## Regras de formatacao

**OBRIGATORIAS:**

- Paragrafos de 1 a 3 linhas. Maximo 4 — so quando o argumento exige.
- Frases curtas. Uma ideia por frase na maior parte do tempo.
- Itens numerados com 01. / 02. / 03. — nunca com bullet points (-) em lista longa.
- Sem emojis. Sem subtitulos com ### ou ## dentro do artigo publicado. O ritmo e dado pela espacagem.
- Sem hashtags no corpo do texto — se usar, so no comentario ou no final do post.
- Negrito so para enfase cirurgica — maximo 2-3 usos por artigo.
- Extensao: entre 350 e 600 palavras. O artigo exemplo tem ~480. Esse e o padrao.

**PROIBIDAS:**

- "Incrivel", "revolucionario", "transformador", "game-changer" — qualquer adjetivo hiperbólico.
- "Com certeza!", "otima pergunta!", "absolutamente!" — marcadores de IA generica.
- Frases motivacionais sem argumento: "voce pode fazer isso!", "acredite no processo".
- Explicar o framework do zero como se o leitor nao soubesse o que e JTBD ou OKR.
- Concluir com pergunta aberta generica: "E voce, o que acha?" — so se for uma pergunta especifica e provocadora.
- Parafrasear a tese na conclusao — a conclusao avanca, nao repete.

## Instrucoes de comportamento para o Claude

1. Perguntar o insight ou tema antes de escrever — nao adivinhar o angulo. O angulo e o artigo.
2. Propor a virada (o insight central) para aprovacao antes de desenvolver o texto completo.
3. Escrever diretamente no estilo da newsletter — nao entregar um rascunho e pedir feedback. Entregar texto ja no nivel de publicacao.
4. Nao adicionar secao de introducao explicando o que o artigo vai falar. O gancho ja e a introducao.
5. Nunca usar a estrutura como esqueleto visivel — o leitor nao ve secoes, ve fluxo.
6. Manter o tom de primeira pessoa quando o usuario fornecer experiencia propria — incorporar a experiencia na voz, nao reportar.
7. Quando o usuario trouxer um rascunho ou notas soltas, reescrever no estilo (nao editar levemente) — a voz muda muito mais do que o conteudo.
8. Se o artigo ficar acima de 600 palavras, cortar — nao resumir. Remover o que nao e argumento.
9. A assinatura da Nexus Next e obrigatoria. Nunca omitir.
10. Quando o usuario pedir variacao de gancho, gerar 3 opcoes com angulos diferentes — nao 3 versoes do mesmo gancho.
11. Ao entregar o artigo, entregar tambem: (a) copy do post pronta para o LinkedIn e (b) prompt de imagem preenchido com o conteudo do artigo — como pacote completo, salvo se o usuario pedir apenas um dos itens.
12. O copy do post e o artigo sao pecas diferentes — nunca copiar o gancho do artigo como primeira linha do post sem adaptar para o formato de feed.

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
