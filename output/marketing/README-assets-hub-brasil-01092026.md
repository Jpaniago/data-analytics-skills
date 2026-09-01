# Assets visuais — Relatório do Contexto Macroeconômico do Brasil (IAEconomia)

**Edição:** 01/09/2026
**Fonte:** `relatoriohubbrasilcontexto01092026iaeconomia2.pdf` (20 páginas)
**Gerado em:** 01/09/2026 via Artlist / Higgsfield

## Direção criativa

O relatório é organizado por um paradoxo explícito: a fase mais benigna do ciclo
(inflação corrente em mínimas, cortes de juros antecipados, risco-país em mínima,
real apreciado) convivendo com a fragilidade fiscal correndo por fora (dívida bruta
subindo quase quatro pontos no ano). O mesmo número — o juro real de ~9,2 p.p. —
é prêmio para o investidor e fardo para o Tesouro.

Os assets traduzem essa tensão em duas partes, unidas por uma linguagem visual
comum: mesma lente (35mm anamórfico, f/2.8), mesma paleta (sombras teal-azul /
índigo contra altas-luzes âmbar) e um mesmo motivo gráfico — uma linha luminosa
que **desce** na Parte 1 e **sobe** na Parte 2.

Sem texto, números, logotipos ou pessoas nas imagens: os dados ficam no relatório,
não na arte.

---

## Foto 1 — Parte 1: a fase benigna

**Ancoragem no relatório:** IPCA a 4,44% em doze meses (menor variação mensal do
ano em julho, +0,07%; prévia de agosto em deflação de 0,40%); Selic cortada a
14,00% em 06/08; CDS 5Y a 119,76 pb, mínima da série; PTAX a R$ 5,1816
(apreciação de ~4,7% no ano); reservas de US$ 374,4 bilhões.

- **Arquivo sugerido:** `foto-01-fase-benigna-desinflacao-cortes.png`
- **Modelo:** Seedream 5.0 Pro (text-to-image)
- **Settings:** `aspect_ratio: 16:9`, `quality: 2k`, `num_images: 1`
- **generationId:** `01a05ba3-822b-78c8-a09e-0105b61db4d6`

**Prompt:**

> Cinematic editorial photograph for a macroeconomic report cover. Wide elevated
> view of the São Paulo financial district at first light — the glass towers of
> Avenida Faria Lima emerging from low blue mist, warm amber sunrise grazing the
> upper floors. Across the middle of the frame, integrated into the architecture
> as reflected light on the glass facades, a single luminous line descends in a
> smooth easing curve from upper left toward lower right, like a falling index
> rendered in glowing amber light. Cool teal-blue shadows against warm amber
> highlights, deep clean contrast, calm and controlled mood, a sense of pressure
> releasing. Shot on 35mm anamorphic, f/2.8, shallow depth of field, fine film
> grain, high dynamic range. No text, no letters, no numbers, no logos, no
> people, no screens, no user interface, no charts with labels. Photorealistic,
> sharp, premium financial editorial aesthetic.

---

## Foto 2 — Parte 2: o contrapeso fiscal

**Ancoragem no relatório:** DBGG a 82,51% do PIB em julho (ante 78,64% em
dezembro de 2025 — alta de quase quatro pontos em sete meses, terceiro recorde
mensal consecutivo); conta de juros em 8,67% do PIB; déficit nominal em 9,34% do
PIB contra primário de apenas 0,67%; DLSP em 60,57% do PIB.

- **Arquivo sugerido:** `foto-02-contrapeso-fiscal-divida-juros.png`
- **Modelo:** Seedream 5.0 Pro (text-to-image)
- **Settings:** `aspect_ratio: 16:9`, `quality: 2k`, `num_images: 1`
- **generationId:** `01a05ba3-909a-7ecb-990a-21f01004ed25`

**Prompt:**

> Cinematic editorial photograph for a macroeconomic report, matching palette and
> lens to a dawn cityscape companion image. Wide low-angle view of Brasília's
> Esplanada dos Ministérios at dusk — the modernist concrete colonnade and the
> twin towers of the National Congress against a deepening indigo sky, the last
> amber light raking across the columns. Across the middle of the frame,
> integrated as reflected light on concrete and glass, a single luminous line
> climbs in a steepening curve from lower left toward upper right, like a rising
> stock of debt rendered in glowing amber light. The column shadows lengthen and
> stack into depth, conveying accumulated weight bearing down. Cool indigo
> shadows against warm amber highlights, heavier contrast, solemn and
> load-bearing mood. Shot on 35mm anamorphic, f/2.8, shallow depth of field, fine
> film grain, high dynamic range. No text, no letters, no numbers, no logos, no
> people, no screens, no user interface, no charts with labels. Photorealistic,
> sharp, premium financial editorial aesthetic.

---

## Vídeo — contexto inteiro (PENDENTE: requer assinatura Artlist)

**Conceito:** um plano contínuo que atravessa as duas partes. A curva de luz âmbar
desce sobre as torres na alvorada, atinge o ponto mais baixo, sustenta uma batida e
**reverte** — subindo e ganhando inclinação enquanto a cena se transforma na
colunata modernista ao entardecer. É o paradoxo da edição em um movimento só:
o alívio corrente e a conta que sobe por trás dele.

Implementado como interpolação start-frame → end-frame usando as duas fotos acima,
o que garante coerência total de paleta e lente com os stills.

- **Arquivo sugerido:** `video-contexto-integral-paradoxo.mp4`
- **Modelo pretendido:** Kling 2.5 Turbo Pro I2V (1080p) — alternativas: Kling 1.6
  Pro I2V (1080p), Seedance 2.0 Mini I2V (720p, suporta áudio)
- **Settings:** `duration: 10`, `resolution: 1080p`, `aspect_ratio: 16:9`
- **startFrame:** generationId `01a05ba3-822b-78c8-a09e-0105b61db4d6` (Foto 1)
- **endFrame:** generationId `01a05ba3-909a-7ecb-990a-21f01004ed25` (Foto 2)

**Prompt:**

> Single continuous cinematic move, no cuts, for the opening of a macroeconomic
> report. The camera drifts slowly forward and to the right as dawn mist thins
> over the glass towers; the descending line of amber light reaches its lowest
> point, holds for a beat, then reverses — bending upward and steepening as the
> scene transitions into the modernist concrete colonnade at dusk, columns
> stacking into depth while the curve climbs out of frame. Continuous slow
> parallax, deliberate and unhurried pace, subtle atmospheric haze and gentle
> light bloom. Cinematic color throughout: cool teal-blue to deep indigo shadows
> against warm amber highlights.

**Negative prompt:**

> text, letters, numbers, captions, subtitles, watermark, logo, user interface,
> labeled charts, people, fast cuts, camera shake, flicker, warping, distortion

**Bloqueio:** todos os grupos de modelos de vídeo de uso geral (Kling 1.6, Kling
2.5, Seedance 2.0 Mini) exigem assinatura Artlist. Os únicos modelos de vídeo
cobertos pelo trial gratuito são Heygen Avatar4 e Omnihuman — geradores de avatar
falante, inadequados para este plano. Nenhuma geração gratuita de vídeo foi
consumida.

---

## Nota sobre os arquivos binários

Os PNGs não puderam ser gravados neste diretório: a política de rede do ambiente
de execução remoto nega CONNECT para os hosts de CDN da Artlist
(`cms-toolkit-artifacts.artlist.io`, `mcp.artlist.io` — HTTP 403). As imagens
existem e estão acessíveis pela conta Artlist através dos `generationId` acima.
Baixe-as de uma máquina sem essa restrição e salve neste diretório com os nomes
de arquivo sugeridos.
