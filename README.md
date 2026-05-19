# TI Sem Fronteira - Landing Page

Landing page estática pronta para subir no GitHub e fazer deploy na Vercel.

## Como rodar localmente

```bash
npm install
npm run dev
```

Depois acesse o endereço exibido no terminal, normalmente:

```bash
http://localhost:5173
```

## Como enviar para o GitHub

```bash
git init
git add .
git commit -m "Landing page TI Sem Fronteira"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
git push -u origin main
```

## Como publicar na Vercel

1. Acesse sua conta na Vercel.
2. Clique em **Add New Project**.
3. Selecione o repositório do GitHub.
4. A Vercel deve detectar como **Vite** automaticamente.
5. Build Command: `npm run build`.
6. Output Directory: `dist`.
7. Clique em **Deploy**.

## Observação

O arquivo principal é `index.html`. O site não precisa de banco de dados nem variáveis de ambiente.
