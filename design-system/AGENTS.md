# Casaco de Férias — design system

Pacote do design system da marca de roupas Casaco de Férias: estampas autorais produzidas sob demanda pela Reserva INK (impressão DTG em área localizada, sem estampa corrida).

## Leia primeiro
1. `README.md` — o guia da marca: conceito, voz, cor, tipografia, ilustração, marca e acessibilidade.
2. `tokens/tokens.json` — a fonte de verdade de cores, tipografia, espaçamento e cantos. Cada token tem uma nota de uso.
3. `components/<Nome>/README.md` — regras de cada peça (personagem, submarca, aplicações, padronagens, formatos de estampa, dispositivos de texto).

## Estrutura
```
README.md                     guia da marca
tokens/tokens.json            tokens (tema "areia" = Papel, tema "noite")
tokens/tokens.css             as mesmas variáveis em CSS (:root e [data-theme="noite"]) + classes .t-<estilo>
components/<Nome>/README.md   regras
components/<Nome>/preview.html exemplo visual; abra no navegador (carrega ../../tokens/tokens.css)
assets/logo/                  logo empilhado, em linha e curto, em tinta, papel e cobalto (SVG)
assets/submarca/              personagem na espreguiçadeira em traço vazado (SVG)
assets/personagem/            poses do personagem com fundo transparente (PNG)
assets/ilustracoes/giz/       ilustrações pintadas em giz (SVG com filtro; renderizam em navegador)
assets/ilustracoes/linha/     as mesmas ilustrações só em traço (SVG simples, para corte, bordado, vetor)
assets/padronagens/           quatro padronagens pintadas (SVG 716×716)
referencia/kit-da-marca-v2.html  o kit completo como referência visual
```

## Regras que não podem quebrar
- Use sempre os tokens; não invente hex. Nomes: `papel`, `areia`, `tinta`, `tinta-suave`, `linha`, `cobalto`, `on-cobalto`, `rosa`, `tomate`, `on-tomate`, `piscina`, `jardim`, `on-jardim`, `tangerina`, `gema`, `terra`, `caramelo`, `lilas`, `foco`.
- Texto respeita 4.5:1. `piscina` não leva texto pequeno; `tomate` só leva texto a partir de 18px negrito.
- O logo é desenho, não fonte: use os SVG de `assets/logo/`, nunca recrie digitando. Não estique, não recolore fora de tinta/papel/cobalto, não aplique sombra.
- Submarca: só linha escura (`tinta` ou `cobalto`) sobre fundo claro, interior vazado. Tamanho mínimo 56px; abaixo disso use o logo.
- Personagem: use os PNG como estão. Não deforme, não troque as cores da gola ou dos botões, não ponha texto por cima.
- Cantos retos por padrão (`radius-0`); sem sombra, sem degradê.
- Textos em português do Brasil, tom seco de documento oficial, sem exclamação e sem emoji.

## Fontes
Fraunces (família `editorial`) e Archivo (família `institucional`) vêm do Google Fonts:
`https://fonts.googleapis.com/css2?family=Archivo:wght@400;500;700&family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,600;1,9..144,400&display=swap`
