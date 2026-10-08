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
1. Gerar primeiro o **antes**.
2. **Nível 1** = edição do antes. **Nível 2** = edição do nível 1. **Nível 3** = edição do nível 2. As mudanças se acumulam.
3. Cada nível em **duas vistas**: frontal e aérea, sempre partindo da imagem anterior da mesma vista.
4. Estrutura intocável: forma do telhado, janelas, portas, pilares, escada, árvores e casas vizinhas.
5. **Nível 1 só pode mostrar o que cabe num fim de semana.** Se exagerar, o produto perde credibilidade.
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
| 12 casas × 4 estados × 2 vistas | 96 |
| 24 combinações de cores (mesma casa-base) | 24 |
| Partes da fachada (detalhes) | a definir |
| **Total mínimo** | **120** |

## Nome dos arquivos
`casaNN-estilo_vista_estado.png`

Exemplos:
- `casa01-craftsman_frontal_antes.png`
- `casa01-craftsman_aerea_n1.png`
- `casa06-queenslander_frontal_n3.png`
- `paleta03_frontal.png`

## Revisão de cada imagem
- [ ] Estrutura igual à imagem anterior
- [ ] Mudanças compatíveis com o nível
- [ ] Sem deformações, objetos soltos ou manchas
- [ ] Escada, janelas e portas com a mesma quantidade de elementos
- [ ] Luz coerente (dia, luminárias apagadas)
- [ ] Sem texto, marcas ou números

## Foto real na demonstração
Na seção "Your home first", usar **uma foto real** (casa própria, de parente ou amigo, com permissão), sem número, placa ou pessoas. Mostra que o método funciona com uma foto comum.

## Transparência
- No guia: *All images are AI-generated illustrations.*
- Nos vídeos: rótulo de IA da plataforma.
