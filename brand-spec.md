# Brand spec — Upsell 2 (Lista de Compras)

Identidade herdada do **Upsell 1 (Cardápio 30 Dias)**. Os dois prints
foram anexados como referência, mas não podem ser lidos visualmente neste
ambiente; os tokens abaixo são codificados **a partir do briefing textual
explícito do proprietário** (paleta laranja + verde + branco, fonte bold
arredondada, visual direto e de conversão).

## Rastreamento da fonte

- `msusrmdr-image.png` — print 1 do Upsell 1 (não lido: sem suporte a imagem)
- `msusrv90-image.png` — print 2 do Upsell 1 (não lido: sem suporte a imagem)
- `msusnkc4-image.png` — imagem do produto (usada na seção 4 da página)

## Tokens de cor (OKLch)

| Papel            | Hex       | OKLch                        |
| ---------------- | --------- | ---------------------------- |
| `--bg`           | `#FFFFFF` | `oklch(1 0 0)`               |
| `--surface`      | `#FFFFFF` | `oklch(1 0 0)`               |
| `--fg`           | `#232B33` | `oklch(0.28 0.02 235)`       |
| `--muted`        | `#5C6670` | `oklch(0.5 0.015 235)`       |
| `--border`       | `#EDECE9` | `oklch(0.95 0.004 90)`       |
| `--accent`       | `#F4781F` | `oklch(0.68 0.16 45)` (laranja — badge, seal) |
| `--green`        | `#28A745` | `oklch(0.66 0.14 145)` (CTA, preço novo) |
| `--green-dark`   | `#1F8338` | `oklch(0.57 0.13 145)`       |
| `--danger`       | `#D9322B` | `oklch(0.55 0.2 25)` (barra de alerta) |
| `--beige`        | `#FFF4E3` | `oklch(0.97 0.03 90)` (fundo do seal) |

## Tipografia

- **Display + corpo:** `"Nunito", -apple-system, system-ui, sans-serif`
  (fonte bold arredondada; usa-se 700–900, com 900 nos momentos de conversão)
- **Mono:** `ui-monospace, "JetBrains Mono", monospace`

## Postura de layout

1. Mobile-first: coluna única centrada (max ~ 460–480px), página curta, sem nav.
2. Barra de alerta vermelha fixa no topo (uppercase, branco, ícone de alerta à esquerda).
3. Cantos arredondados generosos (imagem, badge, CTA) + sombra suave só na imagem.
4. Orçamento de acento: verde = CTA + preço novo; laranja = badge + seal;
   vermelho = só barra de alerta. Um flourish único: pulse leve no CTA.
5. Sem seções extras, sem botões decorativos — tudo aponta para a conversão.