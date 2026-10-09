# Produção de imagens

## Ferramenta
- Candidatas: **GPT Image 2** (usada nas imagens da casa 01) e **Nano Banana**.
- Requisito: editar a partir de uma imagem enviada mantendo a estrutura.
- Fazer o teste comparativo abaixo e **usar só uma ferramenta no produto inteiro**.
- Confirmar nos termos do plano que o uso comercial é permitido.

### Teste comparativo (mesma imagem, mesmo prompt de nível 1)
| Critério | GPT Image | Nano Banana |
|---|---|---|
| Janelas, porta, telhado e árvore iguais? | | |
| Mudou só o que foi pedido? | | |
| Parece foto real? | | |
| Objetos deformados ou detalhes estranhos? | | |
| Mesmo ângulo e enquadramento? | | |

## Regras de geração
1. Gerar primeiro o **antes**, nas vistas frontal e aérea.
2. **Nível 1** = edição do antes frontal. **Nível 2** = edição do nível 1. **Nível 3** = edição do nível 2. As mudanças se acumulam.
3. **Vista aérea só no antes e no nível 3.** O nível 3 aéreo usa duas imagens: o antes aéreo (ângulo) e o nível 3 frontal (acabamento). Prompt em `produto/04-houses/README.md`.
4. Estrutura intocável: forma do telhado, janelas, portas, pilares, escada, árvores e casas vizinhas.
5. **Nível 1 só pode mostrar o que está na receita.** Casas 01 e 06 têm nível 1 de dois fins de semana; as demais, um.
6. Sem pessoas, texto, marcas, números de casa ou placas de carro.
7. Luz de dia: luminárias apagadas.

## Estilo base para prompts
```
Realistic photo, soft natural daylight, same camera angle and framing as the
source image, no people, no text, no logos, no house numbers.
```

## Quantidade
| Item | Imagens |
|---|---|
| 12 casas × 6 (antes ×2, nível 1, nível 2, nível 3 ×2) | 72 |
| Casa 01 já pronta (antes ×2, nível 3 ×2) | -4 |
| 24 combinações de cores (mesma casa-base) | 24 |
| Partes da fachada (detalhes) | 8 |
| 10 quick wins (grade de recortes) | 1 |
| Before you list (vista da rua) | 1 |
| Foto real para "Your home first" | 1 (foto, não gerada) |
| **Total a gerar** | **102** |

Antes eram 126. A redução vem da vista aérea só no antes e no nível 3.

## Nome dos arquivos
`casaNN-estilo_vista_estado.png`

Exemplos:
- `casa01-craftsman_frontal_antes.png`
- `casa01-craftsman_frontal_n1.png`
- `casa06-queenslander_aerea_n3.png`
- `paleta03_frontal.png`

## Revisão de cada imagem
- [ ] Estrutura igual à imagem anterior
- [ ] Mudanças iguais às da receita do nível
- [ ] Sem deformações, objetos soltos ou manchas
- [ ] Escada, janelas e portas com a mesma quantidade de elementos
- [ ] Luz coerente (dia, luminárias apagadas)
- [ ] Sem texto, marcas ou números

## Foto real na demonstração
Na seção "Your home first", usar **uma foto real** (casa própria, de parente ou amigo, com permissão), sem número, placa ou pessoas. Ver `docs/07-teste-prompts-fotos-reais.md`.

## Transparência
- No guia: *All images are AI-generated illustrations.*
- Nos vídeos: rótulo de IA da plataforma.
