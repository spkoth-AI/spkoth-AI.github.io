# spkoth-AI.github.io

Páginas públicas do app **Caderno de Confidências** (EP05).

- `convite/index.html`: abre o convite no app e mostra o código. Não mostra nomes, capa nem nenhum dado do caderno; só lê o código do endereço (`?c=K7QM4XPA`).
- `confirmado/index.html`: volta dos links dos e-mails do app (confirmar cadastro e nova senha, DP-029). No celular Android leva o código de uso único para o app; no computador avisa que o e-mail foi confirmado (ou pede para abrir a nova senha no celular); link vencido explica como pedir outro. Não guarda nem envia nada.
- `.well-known/assetlinks.json`: autoriza o app `br.com.cadernodeconfidencias` a abrir os links `https://spkoth-ai.github.io/convite` direto (Android App Links). Hoje com a impressão da chave de desenvolvimento; incluir a da chave de publicação antes da Play Store.
- `.nojekyll`: para o GitHub Pages publicar a pasta `.well-known`.

Nada aqui é segredo: é um repositório público.
