# 🍯 Colmeia Atendimento Rural

## Deploy no Vercel (5 minutos)

### 1. Crie o repositório no GitHub
- Acesse github.com → New repository → nome: `colmeia-app`
- Faça upload de todos os arquivos desta pasta

### 2. Deploy no Vercel
- Acesse vercel.com → Add New Project → Import do GitHub
- Selecione o repositório `colmeia-app`
- Em **Environment Variables**, adicione:
  - `VITE_ANTHROPIC_KEY` = sua chave da Anthropic (começa com `sk-ant-`)
- Clique em **Deploy**

### 3. Pronto!
Você receberá um link tipo `colmeia-app.vercel.app`

## Como obter a chave Anthropic
- Acesse console.anthropic.com
- API Keys → Create Key
- Copie e cole no Vercel

## Como conectar ao Google Sheets
Após o deploy, siga as instruções dentro do app:
- Aba "🔗 Google Sheets" mostra o código do Apps Script
- Cole o script na sua planilha
- Implantar como App da Web com acesso público
- Cole a URL no campo do app
