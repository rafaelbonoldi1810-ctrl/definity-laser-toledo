# Deploy na Vercel — Definity Laser Toledo

Site estático. Nada para compilar.

## Opção 1: arrastar e soltar
1. Baixe a pasta `deploy` (botão de download no chat).
2. Acesse vercel.com/new, aba **Deploy without Git**.
3. Arraste a pasta `deploy` inteira. Pronto.

## Opção 2: CLI
```bash
npm i -g vercel
cd deploy
vercel --prod
```

## Opção 3: GitHub
1. Suba o conteúdo de `deploy` na raiz de um repositório.
2. Na Vercel: New Project > importe o repo.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: `.`
4. Deploy.

## Conteúdo
- `index.html` — a landing page
- `support.js` — runtime necessário (não remover)
- `assets/` — logo e fotos
- `vercel.json` — headers de cache

## Depois do deploy
- Domínio: Project Settings > Domains.
- WhatsApp, e-mail, Instagram e endereço estão no código (`index.html`, bloco `data-props`).
