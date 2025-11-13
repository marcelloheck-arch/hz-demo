# 🚀 Deploy Rápido no Vercel

## Método 1: CLI do Vercel (Recomendado)

```bash
# 1. Navegar até a pasta demo
cd demo-site

# 2. Instalar Vercel CLI (se não tiver)
npm install -g vercel

# 3. Login no Vercel
vercel login

# 4. Deploy
vercel

# 5. Deploy para produção
vercel --prod
```

## Método 2: GitHub + Vercel (Automático)

```bash
# 1. Criar repositório no GitHub
# 2. Push dos arquivos da pasta demo-site
git init
git add .
git commit -m "Demo HZ Personalizados"
git remote add origin https://github.com/SEU_USUARIO/hz-demo
git push -u origin main

# 3. Ir para vercel.com
# 4. Conectar repositório GitHub
# 5. Deploy automático!
```

## Método 3: Upload Direto

1. Acesse: https://vercel.com
2. Clique em "New Project"
3. Faça upload da pasta `demo-site`
4. Deploy automático!

## 📋 Checklist Final

- [ ] Arquivos na pasta `demo-site`:
  - [ ] `index.html` (página principal)
  - [ ] `vercel.json` (configuração)
  - [ ] `package.json` (metadata)
  - [ ] `styles.css` (estilos extras)
  - [ ] `README.md` (documentação)

- [ ] Deploy realizado com sucesso
- [ ] Link funcionando
- [ ] Simulação de chat operacional
- [ ] Design responsivo

## 🎯 URL Esperada

Após deploy: `https://nome-do-projeto.vercel.app`

## 🛠️ Personalização

Para personalizar:
1. Edite `index.html`
2. Modifique cores em `styles.css`
3. Atualize textos e produtos
4. Faça novo deploy

## 📱 Teste Mobile

Certifique-se de testar em:
- [ ] Chrome Desktop
- [ ] Chrome Mobile
- [ ] Safari Mobile
- [ ] Edge Desktop

## 🎉 Pronto!

Seu demo estará online em poucos minutos!

**Link para compartilhar com o cliente:** 
`https://seu-projeto.vercel.app`