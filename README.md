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
| `assets/bancada.jpg` | Imagem 5 · bancada (4:3, em cor) |

## A confirmar com o cliente
- Horário de funcionamento (seção Turnê marca "a confirmar")
- Link do Booksy (`BOOKSY` no primeiro `<script>`; hoje cai numa busca do Booksy)
- (34) 3257-5427 ativo no WhatsApp Business
- Nomes/funções da equipe e quem é o "Magrelo"; autorização dos depoimentos com nome
- Se a casa serve cerveja (citada só dentro do depoimento real)
- Bordô exato a partir do logo original (`--bordo` no `:root`)
