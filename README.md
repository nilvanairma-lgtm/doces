# Cardápio Dolce Passione

Cardápio digital estático (HTML/CSS/JS puro, sem build) da **Dolce Passione – Doces Artesanais**.

- WhatsApp: +55 47 9 8873-0425
- Instagram: [@dolce.passione01](https://instagram.com/dolce.passione01)
- E-mail: dolcepassionedoces@gmail.com

## Estrutura
- `index.html` – página completa (produtos, preços e layout)
- `img/` – fotos dos produtos
- `assets/` – logo, favicon e imagem de compartilhamento
- `vercel.json` – cache e cabeçalhos de segurança

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com → **Add New → Project** → importe o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios. Clique em **Deploy**.

## Editar produtos e preços
Edite a lista `C` no início do `<script>` em `index.html`. Cada item é `[nome, descrição, preço]`.
O nome da foto fica no objeto `IMG` (nome do produto → `img/NN.jpg`).
