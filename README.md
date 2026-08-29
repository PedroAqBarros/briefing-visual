# Briefing Visual — site

Site de uma página só (`index.html`) com o formulário de briefing, pronto para ser hospedado de graça no GitHub Pages.

## Antes de publicar

Abra `index.html`, procure por `WHATSAPP_NUMBER` (perto do final do arquivo, dentro da tag `<script>`) e troque pelo seu número, só números, com código do país e DDD:

```js
const WHATSAPP_NUMBER = "5562900000000"; // 55 + DDD + número
```

## Publicar no GitHub Pages (grátis)

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New repository**. Dê um nome, ex.: `briefing-visual`. Deixe como **Public**. Crie.
3. Na página do repositório, clique em **Add file → Upload files**.
4. Arraste os arquivos `index.html` e a pasta `assets` (com `logo.png` dentro) para dentro da janela e clique em **Commit changes**.
5. Vá em **Settings → Pages** (menu lateral esquerdo).
6. Em "Build and deployment", em **Source**, selecione **Deploy from a branch**.
7. Em **Branch**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
8. Aguarde 1-2 minutos. O GitHub vai mostrar o link do site, algo como:
   `https://SEU-USUARIO.github.io/briefing-visual/`

Esse link é o que você envia para o cliente preencher o briefing.

## Como funciona o botão final

- **Salvar e enviar no WhatsApp**: baixa uma cópia `.txt` das respostas no computador/celular do cliente e abre o WhatsApp já com a mensagem pronta para enviar para o seu número.
- **Baixar cópia (.txt)**: só salva o arquivo, sem abrir o WhatsApp.

Nenhuma resposta é enviada para nenhum servidor — tudo acontece no navegador do próprio cliente.
