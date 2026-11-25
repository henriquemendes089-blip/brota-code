# code.brotaweb.com

Endereços fixos da Brota Web para QR codes impressos. O QR guarda só o endereço; o destino muda aqui, sem imprimir de novo.

| Endereço | Onde está | Leva para |
|---|---|---|
| `code.brotaweb.com/panfleto` | `panfleto/index.html` | WhatsApp da Brota (API Brota Web) com "Olá! Acabei de escanear o código QR da Brota Web e gostaria de ver na prática como a IA pode fazer meu negócio crescer." |
| `code.brotaweb.com` (e qualquer outro) | `index.html` e `404.html` | brotaweb.com |

## Trocar o destino
No arquivo do endereço, troque o link nas 3 linhas marcadas com `DESTINO` e suba a mudança. Em 1 ou 2 minutos o QR já leva para o novo destino.

## QR novo para outro uso
Crie uma pasta com o nome (por exemplo `cartao/index.html`, copiando a do panfleto) e gere o QR de `https://code.brotaweb.com/cartao`.

## Como funciona
- GitHub Pages deste repositório, com o domínio `code.brotaweb.com` (arquivo `CNAME`).
- No DNS do brotaweb.com (Hostinger): registro CNAME `code` → `henriquemendes089-blip.github.io`.
- Para mudar de lugar (por exemplo, para a Hostinger), aponte o `code` para lá e recrie as mesmas páginas. O QR continua o mesmo.
