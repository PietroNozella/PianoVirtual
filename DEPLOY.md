# 🚀 Instruções de Deploy na Vercel

## ✅ O que já foi feito

1. ✅ Criado `index.html` na raiz (arquivo principal do piano)
2. ✅ Criado `.gitignore` para ignorar arquivos desnecessários
3. ✅ Criado `vercel.json` com configuração otimizada
4. ✅ Inicializado repositório Git
5. ✅ Feito commit inicial de todos os arquivos
6. ✅ Atualizado README.md com estrutura correta

## 📝 Próximos Passos na Vercel

### Se você ainda NÃO fez push para o GitHub:

1. **Criar repositório no GitHub** (se ainda não criou):
   - Acesse https://github.com/new
   - Nome sugerido: `PianoVirtual`
   - Deixe VAZIO (não adicione README, .gitignore ou license)
   - Clique em "Create repository"

2. **Conectar e fazer push**:
   ```bash
   git remote add origin https://github.com/SEU_USUARIO/PianoVirtual.git
   git branch -M main
   git push -u origin main
   ```

### Se você JÁ vinculou o repositório na Vercel:

1. **Fazer push das mudanças**:
   ```bash
   git remote -v  # Verificar se o remote já existe
   git branch -M main  # Renomear branch para main (se necessário)
   git push -u origin main  # Ou: git push -u origin master
   ```

2. **A Vercel vai detectar automaticamente** as mudanças e fazer o deploy!

### Configurações na Vercel (verificar):

1. Acesse seu projeto na Vercel: https://vercel.com/dashboard
2. Vá em **Settings** → **General**
3. Verifique se:
   - **Root Directory**: `.` (raiz do projeto)
   - **Framework Preset**: `Other`
   - **Build Command**: deixe vazio
   - **Output Directory**: deixe vazio

4. A Vercel deve servir automaticamente o `index.html`!

## 🌐 URL do Projeto

Após o deploy, sua URL será algo como:
- `https://seu-projeto.vercel.app`

## 🔧 Solução de Problemas

### Se o deploy falhar:

1. **Verifique os logs** no dashboard da Vercel
2. **Confirme que o arquivo `index.html` está na raiz** do repositório
3. **Verifique se o `vercel.json` está correto**

### Se a página não carregar:

1. Certifique-se de que o repositório está público no GitHub
2. Verifique se não há erros no console do navegador (F12)
3. O Tone.js precisa carregar via CDN - certifique-se de ter conexão com internet

## 📱 Testar Localmente

Antes do deploy, você pode testar localmente:

1. Abra o arquivo `index.html` diretamente no navegador
2. Ou use um servidor local:
   ```bash
   # Com Python
   python -m http.server 8000
   
   # Com Node.js (npx)
   npx http-server
   ```

3. Acesse: http://localhost:8000

## ✨ Está tudo pronto!

Agora é só fazer o push e a Vercel vai fazer o deploy automaticamente! 🎹🎉
