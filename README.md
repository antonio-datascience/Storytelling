# Storytelling-CEUB-2025

**Atividade Storytelling** — Sob orientação do Professor Fabio Guimaraes — Ciência de Dados e Machine Learning, CEUB (2025).  
Esta pasta contém duas versões do projeto:
- `Storytelling-CEUB-2025-react/` — aplicativo React (Vite) com tema escuro (minimalista corporativo). Recomendado para visualização local e deploy dinâmico.
- `Storytelling-CEUB-2025-static/` — página estática `index.html` pronta para GitHub Pages (tema escuro).

---

## Conteúdo
- `Storytelling-CEUB-2025-react/` (projeto Vite + React)
  - `src/StorytellingDashboard.jsx` — componente principal
  - `src/styles.css` — estilos dark minimalista corporativo
  - `package.json` e `vite.config.js`

- `Storytelling-CEUB-2025-static/index.html` — página única pronta para publicação

---

## Deploy rápido

### GitHub Pages (estático)
1. Crie um repositório no GitHub (por exemplo, `Storytelling-CEUB-2025`).
2. Copie os arquivos dentro de `Storytelling-CEUB-2025-static/` para a raiz do repositório (ou apenas `index.html` se preferir).
3. Commit & push para a branch `main`.
4. No GitHub: *Settings → Pages* → selecione `main` branch e pasta `/ (root)` → **Save**.
5. Aguarde alguns minutos. O site ficará disponível em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

### Vercel (dinâmico - recomenda recomendado para o React)
1. Crie uma conta em https://vercel.com/ e conecte ao seu GitHub.
2. Importe o repositório com `Storytelling-CEUB-2025-react` (ou todo o repositório com a pasta React).
3. Configurações padrões do Vercel detectam Vite/React automaticamente. Deploy será automático a cada *push*.
4. Opcional: configurar domínio personalizado nas configurações do projeto.

### Netlify (dinâmico)
1. Crie conta em https://app.netlify.com/ e clique em *New site from Git*.
2. Conecte ao repositório GitHub que contém o projeto React.
3. Para *build command* use: `npm run build` e *publish directory*: `dist`.
4. Deploy automático após push para a branch configurada.

---

## Instruções para rodar localmente (React)
```bash
cd Storytelling-CEUB-2025-react
npm install
npm run dev
# abra http://localhost:5173
```

## Créditos
Atividade Storytelling — Sob orientação do Professor Fabio Guimaraes — Ciência de Dados e Machine Learning CEUB — 2025

---
Gerado em: 2025-11-11T00:30:31.425920 UTC
