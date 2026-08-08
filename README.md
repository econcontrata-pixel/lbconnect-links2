# Página de redirecionamento — LB Connect

Página HTML simples que redireciona automaticamente para um número de WhatsApp,
sem gerar preview/card de link (diferente de encurtadores como TinyURL/Bitly).

## Como usar

1. Abra `index.html`
2. Troque o número `5511991218165` (aparece em 2 lugares: na tag `meta` e no `script`) pelo número real de destino
3. Suba esse arquivo para o GitHub Pages (veja instruções abaixo)

## Publicar no GitHub Pages (gratuito)

1. Crie uma conta em https://github.com (se ainda não tiver)
2. Clique em "New repository"
   - Nome: `lbconnect-links` (ou o nome que quiser)
   - Deixe como **Público**
   - Clique em "Create repository"
3. Na tela do repositório, clique em "uploading an existing file"
4. Arraste o arquivo `index.html`
5. Clique em "Commit changes"
6. Vá em **Settings** (dentro do repositório) → **Pages** (menu lateral)
7. Em "Branch", selecione `main` e pasta `/root` → clique em **Save**
8. Aguarde 1-2 minutos. O GitHub vai gerar uma URL tipo:
   ```
   https://seu-usuario.github.io/lbconnect-links/
   ```
9. Essa é a URL que você usa no botão do template, no lugar do link do TinyURL
