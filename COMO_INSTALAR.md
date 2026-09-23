# Exploradores da Quarta Colônia — instalação

## Jeito mais fácil no Android
1. Publique esta pasta em um endereço HTTPS (por exemplo, GitHub Pages).
2. Abra o endereço no Google Chrome do celular.
3. Toque em **Instalar aplicativo** quando o botão aparecer, ou abra o menu ⋮ e escolha **Instalar aplicativo** / **Adicionar à tela inicial**.
4. Depois da primeira abertura, o app pode funcionar sem internet para os recursos que foram armazenados pelo service worker.

## No computador
Abra o endereço HTTPS no Chrome/Edge e use o ícone de instalação na barra de endereço ou o menu do navegador.

## Importante
Abrir `index.html` diretamente pelo explorador de arquivos (`file://`) permite testar o conteúdo, mas não é o caminho correto para instalar uma PWA. Para instalação, use HTTPS ou um servidor local (`localhost`).

## Publicação simples pelo GitHub Pages
1. Crie um repositório no GitHub.
2. Envie **todo o conteúdo desta pasta**, mantendo `index.html` na raiz.
3. No repositório, abra **Settings → Pages**.
4. Escolha a publicação a partir da branch principal e da pasta raiz (`/root`).
5. Abra a URL HTTPS gerada no celular.
6. Instale o aplicativo pelo Chrome.

## Observação sobre o logotipo
A tela de abertura utiliza o logotipo oficial do Geoparque por endereço externo. Assim, a interface funciona offline, mas o logotipo pode não aparecer se o aparelho estiver totalmente sem internet antes de o recurso ter sido armazenado pelo navegador.
