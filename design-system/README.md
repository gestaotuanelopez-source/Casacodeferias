Casaco de Férias é a roupa de quem leva o descanso a sério. Camisetas, moletons e suéteres com estampas autorais, produzidos sob demanda pela Reserva INK. Público unissex, adulto, com repertório. O humor é seco: um casaco que tira férias com toda a calma do mundo, textos com cara de documento oficial.

## O conceito em uma linha

A Reserva INK não produz casaco. Então **o casaco vive dentro da estampa**: o personagem da marca é o próprio casaco (azul, gola rosa, dois botões laranja), flagrado numa situação de férias ou de ócio. A camiseta veste um casaco.

## Voz e texto

- Escreva como uma instituição: legenda de museu, aviso de hotel, formulário, placa. Frases curtas, ponto final, sem exclamação.
- A piada nunca é explicada. Se a frase precisa de contexto para funcionar, ela não entra.
- O riso vem do contraste entre imagem e texto, não de trocadilho.
- Sem palavrão, sem gíria de internet, sem meme datado, sem emoji.
- Sem personagens, marcas ou logos de terceiros, em nenhuma peça ou campanha.
- Trate o cliente por "você". A marca fala na primeira pessoa do plural só em textos institucionais ("Fechamos para balanço interno").
- Caixa-alta só no estilo `carimbo`. Títulos em caixa de frase.

Exemplos de tom:

| Faz | Não faz |
| --- | --- |
| "Leva casaco para Salvador." | "Sou friorento kkk" |
| "Departamento de Assuntos Não Urgentes" | "Segunda-feira, eu te odeio" |
| "Nº 07 — Algodão sobre pessoa, 2026." | "Camiseta divertida e estilosa!" |
| "Chega ao aeroporto com 3 horas de antecedência." | "Viajar é viver" |

## Os três pilares e como cada um aparece

- **Estética** → o personagem casaco (componente `Personagem`) e as padronagens (grupo `Padronagens`).
- **Fazer parte** → séries de "tipos" de pessoa por pequenos comportamentos, numeradas como peças de catálogo (`legenda`). O cliente coleciona o seu tipo.
- **Levantar uma bandeira** → o ócio como posição, dito por carimbos e placas (componente `DispositivosDeTexto`). Nunca em tom de manifesto.

## Cor

Paleta v2: as cores do personagem (cobalto, rosa, tomate) misturadas com tons de férias e de terra.

- **Base**: fundo `papel`, fundo secundário `areia`, texto e traço `tinta`, secundário `tinta-suave`.
- **Marca**: `cobalto` é o casaco (campo grande, fundo de campanha, texto por cima em `on-cobalto`). `rosa` é a gola e a cor do logo. `tomate` são os botões: acento, preço, destaque; nunca texto pequeno.
- **Férias**: `piscina` (céu, água; só área grande), `jardim` (cenário, texto em `on-jardim`), `tangerina` (fruta, sol), `gema` (luz, fundo alegre).
- **Terra e acento**: `terra` e `caramelo` para peças e fundos mais quentes e escuros; `lilas` é um detalhe por arte, no máximo.
- Proporção de uso aproximada: `papel` 26%, `rosa` 18%, `cobalto` 16%, `tinta` 12%, o resto dividido entre as cores de férias e terra.
- No máximo quatro cores da paleta numa estampa, além da cor da malha.
- Duplas que funcionam: `rosa` + `cobalto`, `jardim` + `tangerina`, `piscina` + `gema`, `terra` + `tomate`, `tangerina` + `rosa`, `cobalto` + `gema`, `lilas` + `jardim`, `caramelo` + `rosa`.
- Tema **Noite** (fundo azul-noite) serve para site em modo escuro e peças de campanha noturnas. Os acentos clareiam; o texto sobre eles usa os tokens `on-…`.

### Cor da malha

A cor da camiseta faz parte da arte. Antes de aprovar uma estampa, teste-a sobre cada malha em que ela será vendida:

- Malha clara (branca, off-white): todas as cores da paleta; traço em `tinta`.
- Malha escura (preta, marinho): troque o traço `tinta` por `papel`; mantenha `tomate`, `rosa`, `gema`; evite `cobalto` e `jardim`, que somem no fundo.
- Malha colorida: só artes que já foram desenhadas para aquela cor. A malha pode ser o "casaco" ou o "céu" da cena.

As cores exatas de malha da Reserva INK precisam ser confirmadas com amostra física.

## Tipografia

- **Fraunces** (família `editorial`) é a voz da marca: `display` para o nome e temporadas, `titulo` para seções, `frase` (itálico) para a frase da estampa.
- **Archivo** (família `institucional`) é a voz do documento: `carimbo` em caixa-alta e espaçado, `corpo` para texto corrido, `legenda` para numeração e créditos.
- Nunca misture as duas na mesma linha. A graça está na troca de voz entre o título editorial e o carimbo seco.
- Ambas são Google Fonts; carregue pelo Google Fonts no site e incorpore na arte final da estampa (contorne o texto antes de enviar à INK).

## Ilustração

- Estampa = ilustração de traço manual (giz, guache, linha). A pintura editorial hiper-real fica só na campanha.
- Regras do personagem: componente `Personagem`.
- O traço é sempre `tinta` (malha clara) ou `papel` (malha escura).
- Ilustrações pintadas em giz, como o personagem: chapa de cor riscada na diagonal, levemente fora do registro, com traço fino em `tinta` por cima e bordas um pouco irregulares. Sem degradê, sem sombra.
- Uma ideia por estampa. Uma frase, no máximo.

## Campanha e fotografia

- Pintura editorial ou foto de estúdio, com fundo chapado de uma cor da paleta (de preferência `cobalto`, `jardim` ou `rosa`).
- Modelo sem sorriso, de perfil ou com óculos escuros. Pose parada.
- Cena de férias levada a sério: praia com casaco, aeroporto, rede, fila de museu, piscina de hotel.
- Imagem gerada por IA só com esta paleta, estas padronagens e estes enquadramentos; nada de logo de terceiros (verifique roupas e calçados).

## Formato, espaço e cantos

- Formatos de estampa: componente `FormatosDeEstampa`.
- Espaçamento em `space-1` a `space-16`. Margem interna mínima da arte: `space-6` na escala de tela.
- Cantos retos (`radius-0`) em tudo. `radius-etiqueta` só na etiqueta de bagagem; `radius-pill` em selos e poá.
- Sem sombra, sem degradê. Profundidade vem de sobreposição de blocos de cor.

## Marca

- **Logo**: letreiro próprio em caixa baixa, traço único e pontas redondas. Duas letras carregam os sinais da marca: o "a" de casaco é um cabide e o "é" de férias leva uma etiqueta de bagagem. Versão principal empilhada, com o "a" e o "é" no mesmo eixo vertical. Os desenhos estão no canvas "Casaco de Férias — Logotipo e sinais".
- **Submarca**: o personagem na espreguiçadeira em traço vazado, só linha e fundo (componente `Submarca`). Abaixo de 48 px, o casaco de pé acenando.
- Logo em `tinta` sobre `papel`, `rosa` ou `gema`, e em `papel` sobre `cobalto` ou `jardim`.
- Submarca só com linha escura (`tinta` ou `cobalto`) sobre fundo claro. Linha clara sobre fundo escuro não se usa.
- Os estilos de texto `display` e `titulo` ainda usam Fraunces. O letreiro do logo é desenho, não fonte: não o reproduza digitando.

## Foco e acessibilidade no site

- Anel de foco: `foco` (2px sólido, afastado 2px), ≥ 6.9:1 sobre `papel` nos dois temas.
- Todo texto do site respeita 4.5:1; os pares aprovados estão nas notas de cada token.
