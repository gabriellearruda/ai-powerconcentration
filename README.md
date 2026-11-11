# A IA concentrando o poder na mão de poucos

Explicador editorial, trilíngue (PT / EN / ES), sobre concentração extrema de poder habilitada por IA: os mecanismos que levam a ela, um cenário ilustrativo de como poderia se desenrolar, indicadores para acompanhar a tendência e intervenções já em pauta para reduzir o risco.

Site de página única, sem build step e sem dependências de backend: é um único arquivo `index.html` autossuficiente (HTML + CSS + JS embutidos).

## Conteúdo

- **O essencial** — resumo em um minuto do que está em jogo, por que agora e o que já dá para fazer
- **O que é** — como o poder, hoje distribuído, poderia se concentrar de forma sem precedentes
- **Mecanismos** — três forças que se reforçam (forças econômicas, interferência epistêmica, tomadas de poder), com um diagrama interativo do ciclo de reforço e outro mostrando como as três se combinam numa tomada de poder entrincheirada
- **Cenário ilustrativo** — linha do tempo estilizada (2029 → 2032 → 2035) com um medidor de concentração de poder
- **Tendências** — painel de indicadores (Figura 1) sobre o que ainda está distribuído e o que está concentrando
- **O que fazer** — intervenções já em pauta, em ordem de detectar → verificar → impedir → proteger
- **Fontes** — links para os artigos e podcasts usados como base

## Fontes e referências

Conteúdo construído a partir de:

- [Extreme power concentration](https://80000hours.org/problem-profiles/extreme-power-concentration/) — 80,000 Hours (Rose Hadshar, 2025)
- [More People Should Be Working on Extreme AI-Driven Power Concentration Right Now](https://www.formationresearch.org/blog/extreme-power-concentration) — Formation Research (2026)
- [AI-Enabled Coups: How a Small Group Could Use AI to Seize Power](https://www.forethought.org/research/ai-enabled-coups-how-a-small-group-could-use-ai-to-seize-power) — Forethought (Davidson, Finnveden, Hadshar, 2025)
- [Human Takeover Might Be Worse than AI Takeover](https://www.forethought.org/research/human-takeover-might-be-worse-than-ai-takeover) — Forethought (Tom Davidson, 2025)
- [Katja Grace vs Tom Davidson: an AI risk debate](https://80000hours.org/podcast/episodes/katja-grace-vs-tom-davidson-ai-risk-debate/) — 80,000 Hours Podcast
- [Tom Davidson on AI-enabled human power grabs](https://80000hours.org/podcast/episodes/tom-davidson-ai-enabled-human-power-grabs/) — 80,000 Hours Podcast

## Como usar

Abra `index.html` direto no navegador, ou sirva a pasta com qualquer servidor estático:

```bash
python3 -m http.server 8000
# depois acesse http://localhost:8000
```

## Deploy

Publicado via **Vercel**, direto deste repositório: basta importar o repo em [vercel.com/new](https://vercel.com/new) e aceitar as configurações padrão (é um site estático, sem build step; `index.html` já está na raiz). O `vercel.json` incluído apenas ativa URLs limpas. Qualquer push na branch `main` gera um novo deploy automaticamente.

## Idiomas

O seletor PT / EN / ES no cabeçalho troca todo o conteúdo da página (o texto nos três idiomas vive em um único objeto JavaScript embutido no `index.html`) e lembra a escolha do leitor via `localStorage`.

## Status

Versão preliminar para discussão, feita como protótipo para uma possível candidatura ao BlueDot Impact Rapid Grants.
