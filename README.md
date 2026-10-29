# Cruzadinha do Terror 🎃

Cruzadinha de Halloween com 13 filmes de terror do catálogo do Looke.

**Jogar:** https://fe-arantes.github.io/CrosswordPuzzle/

> Protótipo independente — não é uma ação oficial do Looke.

## O que tem

- Grade 10×14 com as 13 palavras cruzadas e pistas variadas (personagem, cena, curiosidade de produção).
- Lista de pistas, avanço automático para a próxima palavra e navegação por teclado (setas, Tab, Enter, espaço).
- Ao acertar uma palavra: um morcego sai de cada letra e a ilustração do filme é liberada.
- Palavra completa e errada: as letras tremem e ficam vermelhas, sem avançar.
- Cronômetro, contador de dicas e progresso salvo no navegador.
- Tela final com link para cada filme no Looke e botão "Desafiar amigos" (compartilhamento nativo no celular, menu próprio no desktop).

## Arquivos

- `index.html` — a página inteira, sem dependências externas.
- `cruzadinha-og.jpg` — imagem de prévia (1200×630) usada quando o link é compartilhado.

## Ajustes rápidos no `index.html`

- `WORDS` — palavras, pistas, posição na grade e link de cada filme (`url`).
- `SHARE_URL` — link enviado no compartilhamento; vazio usa o endereço da própria página.
- `<meta name="robots" content="noindex, nofollow">` — mantém a página fora dos buscadores; remova se virar ação oficial.
