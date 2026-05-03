# artigos-linkedin

Agent de escrita de artigos para LinkedIn — newsletter **Nexus Next** sobre AI aplicada a construcao de produtos digitais.

## Skill Disponivel

### linkedin-articles

Skill que guia o Claude a escrever artigos no estilo e voz especificos da Nexus Next:

- Direta, analitica, sem enrolacao
- Frameworks classicos reinterpretados com AI
- Tom de par para par — nao professor, nao coach
- Estrutura consistente com variacao de conteudo

Link direto: [linkedin-articles/SKILL.md](.agents/skills/linkedin-articles/SKILL.md)

## Sobre a Nexus Next

Newsletter semanal que trata de como AI e aplicada no dia a dia de construcao de produtos digitais: discovery, roadmap, frameworks de produto, decisoes de time, produto AI First.

O leitor e PM, founder ou builder que ja conhece os frameworks. O artigo nao explica o basico — reinterpreta, desafia, aplica.

## Estrutura dos artigos

Todos os artigos seguem a mesma arquitetura base:

| Bloco | O que faz |
|-------|-----------|
| Gancho | Tese provocadora ou inversao — 1 a 3 linhas |
| Contexto rapido | O que todos ja sabem — termina com a tensao |
| Virada | O insight central — a reinterpretacao |
| Breakdown 01/02/03 | Tres filtros, perguntas ou passos acionaveis |
| Erro comum | O que a maioria faz errado |
| Implicacao pratica | O que muda no trabalho do leitor hoje |
| Assinatura Nexus Next | Sempre presente ao final |

## Como usar no Claude

1. Acesse o link da skill acima
2. Copie o conteudo completo do arquivo
3. No Claude, crie um **Project** e cole em **Custom Instructions** ou **Project Knowledge**
4. Para cada artigo, informe o insight ou tema da semana — o Claude pergunta o angulo antes de escrever
5. O Claude entrega o artigo ja no nivel de publicacao, nao um rascunho

## O que a skill faz automaticamente

- Mantem a voz e o tom da Nexus Next sem precisar lembrar a cada conversa
- Aplica as regras de formatacao (paragrafos curtos, numeracao 01/02/03, sem emojis)
- Evita os erros mais comuns: adjetivos hiperbolicos, conclusao que repete a tese, gancho retorico generico
- Inclui sempre a assinatura da newsletter
- Quando recebe notas ou rascunho solto, reescreve no estilo — nao edita levemente
