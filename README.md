# Portfólio · Iago Cotias

Hub central do portfólio. Site estático (HTML, CSS e JS, sem build).
Cada projeto tem um card com vídeo teaser e link para o seu próprio estudo de caso.

## Rodar localmente
Abra `index.html` no navegador, ou sirva com:

```bash
npx serve .
```

## Adicionar um novo projeto
1. Gere um teaser curto (versão muda em loop) e coloque em `media/`.
2. Duplique um card `article.proj` no `index.html`.
3. Aponte o link "Ver estudo de caso" para o LP daquele projeto.

## O que confirmar antes de publicar
- URL do LP do HomeCare (link "Ver estudo de caso" no card).
- Seu LinkedIn (link `in` no hero).
- Nome e textos, se quiser ajustar.

## Deploy no Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com, Add New, Project, Import o repositório.
3. Preset Other, build vazio, output `.`, Deploy.
