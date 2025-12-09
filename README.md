# Landing Page de Evento — Pasta `20_Lading_Page`

Esta pasta contém uma landing page responsiva de exemplo para um evento de aniversário. Substitua os textos de placeholder (data, nome, endereço) pelas suas informações.

Arquivos principais:
- `index.html` — página principal
- `styles.css` — estilos responsivos
- `Design sem nome (1).png` — imagem usada no hero (já está na pasta)

Publicação

Escolha um dos provedores: Vercel, Netlify, GitHub Pages ou Cloudflare Pages. Recomendo **Vercel** ou **Netlify** para deploy estático simples.

Passos gerais (Git + Vercel):

1. Inicialize um repositório (se ainda não houver) e faça commit:

```
git init ; git add . ; git commit -m "Landing page de aniversário"
```

2. Crie um repositório no GitHub e envie (substitua a URL remota):

```
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git ; git branch -M main ; git push -u origin main
```

3. No Vercel (https://vercel.com) — faça login, clique em "New Project", conecte ao repositório e deploy. Vercel detecta projetos estáticos automaticamente.

Alternativa — Netlify:

1. No Netlify (https://app.netlify.com) clique em "Add new site" → "Import from Git" e conecte ao repositório. Configure o branch `main` e o diretório de build (padrão é `/`).

GitHub Pages (opção sem CI):

1. No GitHub vá em `Settings` → `Pages` e escolha o branch `main` e a pasta `/ (root)` para publicar. O site ficará disponível em `https://SEU_USUARIO.github.io/SEU_REPO/`.

Substituições recomendadas antes do deploy:
- Atualize `index.html` com sua data real (`id="event-date"`) e seu nome (`id="host-name"`).
- Se quiser, substitua a imagem por outra (nome de arquivo ou pasta `images/`).
- Para um formulário RSVP real, conecte um serviço backend ou use integração com ferramentas como Netlify Forms.

Se quiser, eu posso:
- Fazer essas substituições (insira sua data e nome)
- Preparar o repositório para deploy (ex.: adicionar `vercel.json` ou `netlify.toml`)
- Orientar o deploy passo a passo no serviço que você escolher
