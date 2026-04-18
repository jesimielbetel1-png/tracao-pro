# Tração Pro — Sistema de Mentoria

Sistema de gestão de mentoria empresarial com suporte a PWA (iOS e Android).

## Como publicar no GitHub Pages

### 1. Criar repositório
1. Acesse github.com e crie uma conta (gratuito)
2. Clique em **New repository**
3. Nome: `tracao-pro`
4. Marque como **Public**
5. Clique em **Create repository**

### 2. Subir os arquivos
Faça upload de todos esses arquivos para o repositório:
- `index.html` ← sistema principal
- `manifest.json` ← configuração PWA
- `sw.js` ← service worker (offline)
- `icon-192.svg` ← ícone do app
- `icon-512.svg` ← ícone grande

### 3. Ativar GitHub Pages
1. No repositório, clique em **Settings**
2. No menu lateral, clique em **Pages**
3. Em **Source** selecione **Deploy from a branch**
4. Em **Branch** selecione **main**
5. Clique em **Save**
6. Aguarde 2 minutos

### 4. Acessar
Sua URL será: `https://SEU_USUARIO.github.io/tracao-pro`

### 5. Instalar no celular

**Android (Chrome):**
- Acesse a URL no Chrome
- Toque nos 3 pontinhos → "Adicionar à tela inicial"

**iPhone/iPad (Safari):**
- Acesse a URL no Safari
- Toque em Compartilhar (ícone de seta)
- "Adicionar à Tela de Início"

## Atualizar o sistema sem perder dados
1. Baixe o novo `index.html` do Claude
2. Faça upload para o repositório (substitui o antigo)
3. O GitHub Pages atualiza em ~2 minutos
4. **Os dados ficam no Google Sheets — nunca são perdidos**

## Senha padrão
`tracao2026`

Para trocar a senha, edite a linha no index.html:
```
const SENHA = 'tracao2026';
```

## Banco de dados
Google Sheets — URL configurada no sistema.
