# PostAllTon 📡
> **Um clique. Todas as redes.**

App de publicação simultânea em múltiplas redes sociais.  
Powered by [Ayrshare API](https://ayrshare.com).

---

## 🚀 Deploy na Vercel (passo a passo)

### 1. Pré-requisitos
- [Node.js 18+](https://nodejs.org) instalado
- Conta gratuita no [GitHub](https://github.com)
- Conta gratuita na [Vercel](https://vercel.com)

### 2. Instalar dependências
```bash
npm install
```

### 3. Testar localmente
```bash
npm run dev
```
Acesse `http://localhost:5173`

### 4. Subir para o GitHub
```bash
git init
git add .
git commit -m "PostAllTon v1.0"
git branch -M main
# Crie um repositório em github.com, depois:
git remote add origin https://github.com/SEU_USUARIO/postallton.git
git push -u origin main
```

### 5. Publicar na Vercel
1. Acesse [vercel.com](https://vercel.com) → **Add New Project**
2. Conecte sua conta GitHub
3. Selecione o repositório `postallton`
4. Clique em **Deploy** — pronto!

Seu app estará online em:
`https://postallton.vercel.app`

---

## 💰 Como monetizar

### Opção A — Hotmart / Kiwify (recomendado para Brasil)
1. Crie um produto digital na [Kiwify](https://kiwify.com.br)
2. Defina 3 planos: Básico R$19/mês · Pro R$49/mês · Business R$99/mês
3. Adicione os links de checkout nos botões de cada plano no app

### Opção B — Stripe (pagamentos internacionais)
1. Crie produtos no [Stripe Dashboard](https://dashboard.stripe.com)
2. Use o Stripe Payment Links para cada plano
3. Substitua os links nos botões da página de planos

### Opção C — Integração com Ayrshare Profiles
Para múltiplos clientes (plano Business):
1. Crie um **Profile** para cada cliente no Ayrshare
2. Use a `profileKey` na chamada da API
3. Cada cliente tem suas próprias redes conectadas

---

## 🌐 Idiomas suportados
- 🇧🇷 Português
- 🇺🇸 Inglês
- 🇪🇸 Espanhol
- 🇫🇷 Francês

---

## 📁 Estrutura do projeto
```
postallton/
├── public/
│   └── favicon.svg
├── src/
│   ├── App.jsx      ← App completo (landing + planos + painel)
│   └── main.jsx     ← Entry point React
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🔑 Configuração da API Key
1. Acesse [app.ayrshare.com](https://app.ayrshare.com)
2. Registre-se e conecte suas redes em **Social Accounts**
3. Copie sua API Key do painel
4. No app, acesse **Credenciais** e cole a chave

---

© 2026 PostAllTon. Todos os direitos reservados.
