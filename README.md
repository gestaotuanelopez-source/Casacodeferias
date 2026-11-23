# Casaco de Férias

A roupa de quem leva o descanso a sério. Estampas autorais produzidas sob demanda pela Reserva INK.

O guia completo da marca está em [`design-system/README.md`](design-system/README.md). Comece por ele.

## Estrutura

```
design-system/          guia da marca, tokens, componentes, logo, submarca, personagem, ilustrações, padronagens
  README.md             guia: conceito, voz, cor, tipografia, ilustração, marca
  AGENTS.md             resumo das regras que não podem quebrar
  tokens/               cores, tipografia, espaçamento (JSON e CSS)
  components/           regras e preview de cada peça
  assets/               SVG e PNG prontos para uso
  referencia/           kit da marca v2 (abrir no navegador)
personagem/folhas/      folhas de giro do personagem (8 ângulos por pose) e a submarca em traço
instagram/perfis/       foto de perfil em 9 fundos da paleta
instagram/posts/dia-01/ posts publicados no dia 1: logo, "oi, cheguei." e o carrossel de estreia (8 slides)
```

## Pendências do material

- **Personagem em alta resolução:** as poses têm de 230 a 440 px (cerca de 3,7 cm impressos). Para estampa de 25 cm são necessários originais com pelo menos 3000 px no lado maior, ou vetor.
- **Tipografia dos títulos:** o guia indica Fraunces; os posts do dia 1 usam um letreiro arredondado. Definir qual vale.
- **Padronagens:** o guia cita cinco e a "Listra Toldo" como principal; o pacote tem quatro (guarda-roupa, pomar, botão e mar, bagagem).
- **Área de estampa:** `FormatosDeEstampa` fala em 27 × 36 cm (a confirmar); a Reserva INK limita a largura a 25 cm.
- **Submarca:** os nomes de arquivo citados no componente (`espreguicadeira-traco-*`) diferem dos arquivos em `assets/submarca/` (`submarca-traco-*`).
- **Óculos:** o componente `Personagem` diz `gema`; a arte usa verde.
