# Painel MAL

Painel com estatísticas da lista de animes do MyAnimeList (usuário MestreYodan), instalável como app (PWA).

- Lista: vem do XML exportado do MAL (embutido no `index.html`; dá para carregar um XML novo pelo botão do app).
- API Jikan: confere os totais atuais do perfil e busca gêneros, estúdios e nota média do MAL. Se falhar, o app segue só com o XML.

## Publicar no GitHub Pages
1. Suba todos os arquivos desta pasta na raiz do repositório.
2. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
3. Em 1–2 minutos o app fica em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Instalar no Android
Abra o link no Chrome → menu ⋮ → **Instalar app** (ou o botão "Instalar app" no canto da tela).
