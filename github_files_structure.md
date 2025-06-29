# Rock Burguers - Arquivos para GitHub

## 📁 Estrutura do Projeto

```
rockburguers/
├── index.html          # Página principal
├── README.md           # Documentação do projeto
├── CNAME               # Configuração do domínio personalizado
└── .github/
    └── workflows/
        └── deploy.yml  # Workflow para deploy automático
```

## 🚀 Instruções de Instalação

### 1. Criar o Repositório no GitHub
1. Acesse [github.com](https://github.com)
2. Clique em "New repository"
3. Nome do repositório: `rockburguers`
4. Marque como "Public"
5. Clique em "Create repository"

### 2. Fazer Upload dos Arquivos
1. Faça upload de todos os arquivos para o repositório
2. Ou clone o repositório e adicione os arquivos:
```bash
git clone https://github.com/SEU_USUARIO/rockburguers.git
cd rockburguers
# Adicione os arquivos aqui
git add .
git commit -m "Initial commit - Rock Burguers website"
git push origin main
```

### 3. Configurar GitHub Pages
1. Vá para Settings > Pages
2. Source: "Deploy from a branch"
3. Branch: "main"
4. Folder: "/ (root)"
5. Clique em "Save"

### 4. Configurar Domínio Personalizado
1. No painel do GitHub Pages
2. Custom domain: `rockburguers.fun`
3. Marque "Enforce HTTPS"

### 5. Configurar DNS (no seu provedor de domínio)
Adicione estes registros DNS:
```
CNAME   www   SEU_USUARIO.github.io
A       @     185.199.108.153
A       @     185.199.109.153
A       @     185.199.110.153
A       @     185.199.111.153
```

## 📱 Recursos do Site

- ✅ Design responsivo (mobile-first)
- ✅ Animações suaves
- ✅ Botão WhatsApp flutuante
- ✅ Menu interativo
- ✅ SEO otimizado
- ✅ Performance otimizada
- ✅ Compatível com todos os navegadores

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts
- Responsive Design

## 📞 Contatos Configurados

- **Telefone**: (47) 3326-1270
- **WhatsApp**: (47) 99699-6721
- **Instagram**: @rockburguersbnu
- **Facebook**: @rockburguersbnu

## 🎯 Funcionalidades

1. **Hero Section**: Apresentação impactante
2. **Cardápio**: Menu completo com preços
3. **Sobre**: História desde 2009
4. **Serviços**: Delivery, balcão, consumo local
5. **Contato**: Informações e localização

## 🔧 Personalização

Para personalizar o site:
1. Edite o arquivo `index.html`
2. Modifique as cores no CSS (variáveis CSS)
3. Atualize as informações de contato
4. Adicione novas seções conforme necessário

## 📈 Analytics

O site está preparado para Google Analytics. Adicione seu código de tracking no `<head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🚀 Deploy

O site será automaticamente deployado quando você fizer push para o repositório. Aguarde alguns minutos para que as alterações sejam refletidas.

---

**Rock Burguers BNU** - Tradição desde 2009 🍔🤘