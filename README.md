# Mommentu — Gestão de Studio

## Como publicar no Vercel (passo a passo)

### Passo 1 — Coloque seu código aqui
Abra o arquivo `src/App.jsx` e substitua todo o conteúdo pelo seu arquivo .jsx original.

### Passo 2 — Suba para o GitHub
1. Acesse github.com e faça login
2. Clique em **"New repository"** (botão verde)
3. Nome do repositório: `mommentu`
4. Deixe como **Public**
5. Clique em **"Create repository"**
6. Na próxima tela, clique em **"uploading an existing file"**
7. Arraste TODOS os arquivos desta pasta (exceto a pasta `node_modules`)
8. Clique em **"Commit changes"**

### Passo 3 — Conecte ao Vercel
1. Acesse vercel.com e faça login com o GitHub
2. Clique em **"Add New Project"**
3. Selecione o repositório `mommentu`
4. Deixe todas as configurações padrão (Vercel detecta Vite automaticamente)
5. Clique em **"Deploy"**
6. Aguarde ~2 minutos

### Pronto!
Seu site estará no ar em um endereço como: `mommentu.vercel.app`

---

## Estrutura do projeto
```
mommentu/
├── index.html          ← página principal
├── package.json        ← configurações do projeto
├── vite.config.js      ← configuração do Vite
├── .gitignore          ← arquivos ignorados pelo Git
└── src/
    ├── main.jsx        ← ponto de entrada (não mexa)
    └── App.jsx         ← SEU CÓDIGO VAI AQUI ← ← ←
```
