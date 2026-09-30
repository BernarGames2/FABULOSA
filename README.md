# Fabulosa Barbearia — landing page

Página única (`index.html`), CSS inline, GSAP + ScrollTrigger via CDN e Google Fonts (Anton, Fraunces, Space Mono, DM Sans) com fallback de sistema.

## Imagens (coloque em `assets/`)
Enquanto o arquivo não existir, aparece um placeholder bordô com o rótulo da imagem.

| Arquivo | Uso |
|---|---|
| `assets/logo.png` (ou troque para .svg no HTML) | Logo original do cliente — não redesenhar |
| `assets/hero.jpg` | Imagem 1 · barbeiro finalizando a barba (4:5, recebe duotone via CSS) |
| `assets/interior.jpg` | Imagem 2 · interior (4:3, em cor) |
| `assets/equipe.jpg` | Imagem 3 · equipe (4:5, duotone) |
| (mini-perfis) | Recortes via CSS de `assets/equipe.png`: Rodrigo à esquerda, Luiz à direita |

## A confirmar com o cliente
- Prints do Google/Booksy com nome para trocar "Cliente" nos depoimentos 2 e 3
- Bordô exato a partir do logo original (`--bordo` no `:root`)
- Logo original (SVG ou PNG grande)
