# 🥗 Landing Page - Nutricionista Clínica

Template profissional de landing page para nutricionistas, desenvolvido com HTML5, CSS3 e JavaScript puro. Design moderno, responsivo e otimizado para conversão de clientes.

![Status](https://img.shields.io/badge/Status-Pronto%20para%20Produção-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📋 Índice

- [Características](#-características)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Seções da Landing Page](#-seções-da-landing-page)
- [Funcionalidades JavaScript](#-funcionalidades-javascript)
- [Design System](#-design-system)
- [Personalização](#-personalização)
- [Hospedagem Gratuita](#-hospedagem-gratuita)
- [SEO e Performance](#-seo-e-performance)
- [Suporte](#-suporte)

---

## ✨ Características

### 🎨 Design Moderno
- **Dark Mode** com paleta de cores profissional (verde saúde + coral)
- **Animações suaves** usando AOS (Animate On Scroll)
- **Efeitos visuais** com hover, transitions e gradientes
- **Totalmente responsivo** (mobile-first design)

### 🚀 Performance
- Carregamento rápido com código otimizado
- Imagens modernas no formato `.avif`
- Preconnect para fontes e CDNs
- CSS e JavaScript minificáveis

### 💼 Conversão
- Call-to-Actions estratégicos
- Integração direta com WhatsApp
- Links para redes sociais
- Formulário de contato preparado

### 📱 Mobile-Friendly
- Menu hambúrguer funcional
- Layout adaptativo para todos os dispositivos
- Touch-friendly buttons e navegação
- Imagens otimizadas para mobile

---

## 🛠 Tecnologias Utilizadas

### Core
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna com variáveis CSS, Grid e Flexbox
- **JavaScript (Vanilla)** - Interatividade sem dependências pesadas

### Bibliotecas Externas
- **AOS (Animate On Scroll)** - Animações ao rolar a página
  - CDN: `unpkg.com/aos@2.3.1`
  - Documentação: [michalsnik.github.io/aos](https://michalsnik.github.io/aos/)

- **Google Fonts** - Tipografia profissional
  - Poppins (sans-serif) - Texto geral
  - Merriweather (serif) - Títulos e destaques

### Ícones
- **SVG Icons** customizados inline
- Ícones vetoriais para melhor qualidade e performance

---

## 📁 Estrutura do Projeto

```
projeto-nutricionista/
│
├── index.html          # Página principal
├── style.css           # Estilos globais
├── script.js           # Funcionalidades JavaScript
│
├── assets/
│   ├── icons/
│   │   └── redcross.svg    # Logo/ícone principal
│   │
│   └── img/
│       ├── img01.avif      # Imagem hero
│       ├── img02.avif      # Imagem especialidades
│       └── img03.avif      # Imagem contato
│
└── README.md           # Este arquivo
```

### Arquivos Principais

#### `index.html`
Estrutura HTML5 semântica com:
- Meta tags para SEO (description, keywords, author)
- Open Graph para redes sociais
- Twitter Cards
- Favicon SVG
- Estrutura de header fixo
- 4 seções principais (Hero, Sobre, Especialidades, Contato)
- Footer com créditos
- Botão de scroll to top

#### `style.css`
CSS moderno utilizando:
- **CSS Variables** (Custom Properties) para design system
- **CSS Grid** e **Flexbox** para layouts responsivos
- **Media Queries** para 4 breakpoints (1200px, 968px, 640px, 480px)
- **Animations** e **Transitions** suaves
- **Gradientes** e **Sombras** para profundidade
- Estilização de componentes reutilizáveis

#### `script.js`
JavaScript organizado com:
- Inicialização modular (DOMContentLoaded)
- Smooth scroll para navegação
- Menu mobile funcional
- Sistema de acordeão para especialidades
- Scroll effects (header shadow, back to top)
- Utilitários (BMI calculator, validação, etc.)
- Event listeners otimizados

---

## 📄 Seções da Landing Page

### 1. 🦸‍♀️ Hero Section
- Título impactante com destaque gradiente
- Subtítulo descritivo
- Dois CTAs (Agendar + Conhecer)
- Imagem profissional da nutricionista
- Layout em duas colunas (desktop) / empilhado (mobile)

### 2. 👩‍⚕️ Sobre Mim
- História e credenciais
- 4 cards estatísticos animados:
  - Anos de experiência
  - Vidas transformadas
  - Registro profissional (CRN)
  - Dedicação aos pacientes
- Horário de atendimento com ícone
- Layout em duas colunas com texto e stats

### 3. 💚 Especialidades
- Imagem ilustrativa full-width
- 3 cards de especialidades com acordeão:
  - **Emagrecimento Saudável** (6 serviços detalhados)
  - **Nutrição Esportiva** (6 serviços detalhados)
  - **Saúde Metabólica** (6 serviços detalhados)
- Cada card tem ícone SVG, descrição e lista expandível
- CTA final para agendamento

### 4. 📞 Contato
- Imagem de contato full-width
- 4 cards de contato interativos:
  - **WhatsApp** (link direto com número)
  - **Email** (mailto link)
  - **Instagram** (link externo)
  - **Endereço** (informativo, sem link)
- Hover effects com elevação e brilho

### 5. 🔝 Footer
- Logo e nome da marca
- Créditos do desenvolvedor
- Link para GitHub
- Design minimalista

### Componentes Extras
- **Header fixo** com logo, navegação e CTA
- **Menu mobile** com ícone hambúrguer animado
- **Botão scroll to top** que aparece após 500px de scroll

---

## ⚙️ Funcionalidades JavaScript

### Inicialização
```javascript
initAOS()              // Ativa animações AOS
setupSmoothScroll()    // Scroll suave para âncoras
setupScrollEffects()   // Efeitos no scroll (header, botão)
setupAreaToggles()     // Acordeão das especialidades
setupMobileMenu()      // Menu hambúrguer mobile
checkClinicHours()     // Verifica horário de funcionamento
```

### Principais Funções

#### Smooth Scroll
Navegação suave ao clicar em links âncora (#), com offset para o header fixo.

#### Mobile Menu
Menu responsivo que abre/fecha com animação do ícone hambúrguer.

#### Acordeão (Toggles)
Sistema de expansão/contração para os detalhes das especialidades, fechando outros cards ao abrir um novo.

#### Scroll Effects
- Header ganha sombra após 50px de scroll
- Botão "voltar ao topo" aparece após 500px
- Active nav link baseado na seção visível

#### Utilitários
- `calculateBMI()` - Calculadora de IMC
- `validateContactForm()` - Validação de formulário
- `isValidEmail()` e `isValidPhone()` - Validadores
- `formatPhone()` - Formatação de telefone brasileiro

---

## 🎨 Design System

### Paleta de Cores
```css
/* Backgrounds */
--bg: #0f172a            /* Fundo principal (azul escuro) */
--bg-secondary: #1e293b  /* Fundo secundário */
--bg-card: #1e293b       /* Fundo dos cards */

/* Textos */
--text: #f1f5f9          /* Texto principal (branco suave) */
--text-secondary: #cbd5e1 /* Texto secundário (cinza claro) */

/* Brand Colors */
--primary: #10b981       /* Verde saúde (principal) */
--primary-dark: #059669  /* Verde escuro */
--primary-light: #34d399 /* Verde claro */
--accent: #fb923c        /* Coral (acento) */
--accent-dark: #f97316   /* Coral escuro */

/* Semânticas */
--success: #22c55e       /* Verde sucesso */
--warning: #fbbf24       /* Amarelo aviso */
--danger: #ef4444        /* Vermelho perigo */
```

### Tipografia
- **Títulos**: Merriweather (serif) - Elegante e profissional
- **Corpo**: Poppins (sans-serif) - Moderna e legível
- **Tamanhos**:
  - Hero: 4rem (desktop) → 2rem (mobile)
  - Section titles: 3.5rem → 2rem
  - Body: 1.05rem
  - Lead text: 1.3rem

### Espaçamento
```css
--radius: 16px        /* Border radius padrão */
--radius-lg: 24px     /* Border radius grande */
--max-width: 1400px   /* Largura máxima do conteúdo */
```

### Sombras e Efeitos
```css
--shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.4)
--shadow-md: 0 4px 16px rgba(0, 0, 0, 0.5)
--shadow-lg: 0 10px 40px rgba(0, 0, 0, 0.6)
--shadow-glow: 0 0 30px rgba(16, 185, 129, 0.3)  /* Brilho verde */
```

### Animações
- Transição padrão: `0.4s cubic-bezier(0.4, 0, 0.2, 1)`
- Fade in left/right para hero section
- Hover com elevação (translateY) e brilho
- AOS animations: fade-up com delays escalonados

---

## 🔧 Personalização

### 1. Informações do Profissional
**No `index.html`, alterar:**
- Linha 11-16: Meta descriptions e keywords
- Linha 19-24: Open Graph (título, descrição, URL, imagem)
- Linha 35: Title da página
- Linha 64: Nome da marca no header
- Linha 89: Título hero
- Linha 91-93: Subtítulo hero
- Linha 109-127: Texto "Sobre Mim"
- Linha 131-150: Estatísticas (anos, pacientes, CRN)
- Linha 155-157: Horário de atendimento

### 2. Especialidades
**Linhas 177-312 no `index.html`:**
- Substituir os 3 cards de especialidades
- Editar títulos, descrições e listas de serviços
- Trocar ícones SVG se necessário

### 3. Contato
**Linhas 338-409 no `index.html`:**
- **WhatsApp**: href="https://wa.me/55**SEUNUMERO**"
- **Email**: href="mailto:**seuemail@dominio.com**"
- **Instagram**: href="https://www.instagram.com/**seuusuario**/"
- **Endereço**: Atualizar endereço completo

### 4. Cores e Branding
**No `style.css` (linhas 1-25):**
```css
:root {
  --primary: #10b981;        /* Cor principal */
  --accent: #fb923c;         /* Cor de acento */
  --bg: #0f172a;             /* Fundo escuro */
  /* ... outras variáveis */
}
```

### 5. Imagens
Substituir os arquivos em `assets/img/`:
- `img01.avif` - Foto profissional (600x600px recomendado)
- `img02.avif` - Imagem especialidades (1200x400px)
- `img03.avif` - Imagem contato (1200x400px)
- `redcross.svg` - Logo/ícone (pode usar PNG/JPG também)

**Formato recomendado**: AVIF ou WebP para melhor compressão
**Alternativa**: JPG com qualidade 80-85%

---

## 🌐 Hospedagem Gratuita

Este projeto é 100% estático (HTML/CSS/JS) e pode ser hospedado gratuitamente em diversas plataformas. Aqui está o guia completo:

---

### 🚀 Opção 1: Vercel (RECOMENDADO)

**Vantagens:**
- Deploy automático do GitHub
- HTTPS gratuito
- CDN global ultra-rápido
- Domínio customizado gratuito

**Passos:**

1. **Criar conta no GitHub** (se não tiver)
   - Acesse [github.com](https://github.com) e crie uma conta gratuita

2. **Criar repositório**
   - Clique em "New repository"
   - Nome: `nutricionista-landing-page`
   - Deixe público
   - Clique em "Create repository"

3. **Upload dos arquivos**
   - Na página do repositório, clique em "uploading an existing file"
   - Arraste todos os arquivos do projeto (index.html, style.css, script.js, pasta assets)
   - Commit: "Initial commit"

4. **Deploy na Vercel**
   - Acesse [vercel.com](https://vercel.com)
   - Clique em "Sign Up" e escolha "Continue with GitHub"
   - Clique em "Import Project"
   - Selecione seu repositório `nutricionista-landing-page`
   - Clique em "Deploy"
   - **Pronto!** Sua URL estará disponível em segundos: `seu-projeto.vercel.app`

5. **Domínio customizado (opcional)**
   - Na Vercel, vá em "Settings" > "Domains"
   - Adicione seu domínio (ex: `draanapaula.com.br`)
   - Siga as instruções para configurar DNS

---

### 🎯 Opção 2: Netlify

**Vantagens:**
- Drag & drop (arrastar e soltar)
- Deploy instantâneo
- Formulários gratuitos
- HTTPS automático

**Passos:**

1. **Método Rápido - Drag & Drop**
   - Acesse [netlify.com](https://netlify.com)
   - Crie uma conta gratuita
   - Na página inicial, arraste a **pasta do projeto inteira** para a área "Want to deploy a new site without connecting to Git?"
   - **Pronto!** URL gerada: `random-name-123.netlify.app`

2. **Método GitHub (automatizado)**
   - Siga os passos 1-3 da Vercel
   - No Netlify, clique em "New site from Git"
   - Escolha GitHub e autorize
   - Selecione o repositório
   - Deploy settings: deixe tudo padrão
   - Clique em "Deploy site"

3. **Customizar domínio**
   - Vá em "Domain settings"
   - Clique em "Add custom domain"
   - Configure seu DNS com os nameservers do Netlify

---

### ⚡ Opção 3: Cloudflare Pages

**Vantagens:**
- CDN mais rápido do mundo
- DDoS protection gratuito
- Analytics incluído
- Unlimited bandwidth

**Passos:**

1. **Criar conta**
   - Acesse [pages.cloudflare.com](https://pages.cloudflare.com)
   - Crie conta gratuita

2. **Upload pelo GitHub**
   - Siga passos 1-3 da Vercel (criar repo GitHub)
   - No Cloudflare Pages, clique "Create a project"
   - Connect to Git > Escolha GitHub
   - Selecione o repositório
   - Build settings: deixe tudo vazio (é site estático)
   - Clique em "Save and Deploy"

3. **Upload direto (sem Git)**
   - Clique em "Create a project" > "Direct Upload"
   - Arraste a pasta do projeto
   - Nome do projeto
   - Deploy

**URL gerada**: `seu-projeto.pages.dev`

---

### 📦 Opção 4: GitHub Pages

**Vantagens:**
- Totalmente gratuito
- Integrado ao GitHub
- Simples e direto

**Passos:**

1. **Upload no GitHub**
   - Siga passos 1-3 da seção Vercel
   - Certifique-se que o arquivo principal se chama `index.html`

2. **Ativar GitHub Pages**
   - No repositório, vá em "Settings" (topo direito)
   - Scroll até "Pages" (menu lateral esquerdo)
   - Em "Source", escolha "main" branch
   - Clique em "Save"
   - Aguarde 1-2 minutos

3. **Acessar site**
   - URL será: `https://seuusuario.github.io/nutricionista-landing-page`
   - Aparecerá um link verde quando pronto

**Limitação**: Apenas 1 site por repositório, domínio menos customizável.

---

### 🌍 Comparação Rápida

| Plataforma | Velocidade | Facilidade | Domínio Custom | Melhor Para |
|------------|------------|------------|----------------|-------------|
| **Vercel** | ⚡⚡⚡⚡⚡ | 🟢 Fácil | ✅ Sim, grátis | Profissionais |
| **Netlify** | ⚡⚡⚡⚡ | 🟢 Muito Fácil | ✅ Sim, grátis | Iniciantes |
| **Cloudflare** | ⚡⚡⚡⚡⚡ | 🟡 Médio | ✅ Sim, grátis | Performance |
| **GitHub Pages** | ⚡⚡⚡ | 🟢 Fácil | ⚠️ Limitado | Portfólios |

---

### 🔗 Conectar Domínio Próprio

**Passo a passo geral** (funciona para todos):

1. **Comprar domínio** em:
   - Registro.br (Brasil)
   - Namecheap
   - GoDaddy
   - Google Domains

2. **Configurar DNS**:
   - Vá no painel do seu registrador de domínio
   - Adicione os nameservers ou records DNS fornecidos pela plataforma
   - **Vercel/Netlify**: Adicione registro A ou CNAME
   - **Cloudflare**: Use nameservers do Cloudflare

3. **Aguardar propagação** (4-48h, geralmente 15min)

4. **Configurar HTTPS**
   - Todas as plataformas oferecem SSL/HTTPS automático e gratuito

---

### 📊 Atualizar o Site

**Se usar GitHub + Vercel/Netlify/Cloudflare:**
1. Edite os arquivos localmente
2. Commit no GitHub:
   ```bash
   git add .
   git commit -m "Atualização"
   git push
   ```
3. Deploy automático em 30 segundos!

**Se usar Drag & Drop (Netlify):**
1. Arraste os arquivos novamente
2. Nova versão no ar instantaneamente

---

## 🎯 SEO e Performance

### Meta Tags Incluídas
- ✅ Title e Description otimizados
- ✅ Keywords relevantes
- ✅ Open Graph (Facebook, LinkedIn)
- ✅ Twitter Cards
- ✅ Favicon SVG

### Performance
- ✅ Preconnect para fontes e CDNs
- ✅ Loading lazy para imagens não críticas
- ✅ CSS e JS minificáveis
- ✅ Formato AVIF para imagens (80% menor que JPG)

### Checklist Pré-Deploy
- [ ] Testar em Chrome, Firefox, Safari
- [ ] Testar responsividade (mobile, tablet, desktop)
- [ ] Verificar todos os links (WhatsApp, email, Instagram)
- [ ] Trocar informações de exemplo por dados reais
- [ ] Otimizar imagens (< 500KB cada)
- [ ] Testar performance no [PageSpeed Insights](https://pagespeed.web.dev/)

---

## 📈 Melhorias Futuras (Opcionais)

- [ ] Adicionar Google Analytics
- [ ] Integrar com Calendly para agendamentos
- [ ] Sistema de depoimentos/avaliações
- [ ] Blog com artigos de nutrição
- [ ] Calculadora de IMC interativa
- [ ] Chatbot com FAQ
- [ ] Formulário de contato com envio de email
- [ ] Galeria antes/depois (com autorização)

---

## 🆘 Suporte

### Problemas Comuns

**1. Imagens não aparecem**
- Verificar se os caminhos estão corretos: `./assets/img/img01.avif`
- Conferir se as imagens foram enviadas junto com os arquivos

**2. Animações não funcionam**
- Verificar se o CDN do AOS está carregando
- Checar console do navegador (F12) para erros

**3. Menu mobile não abre**
- Testar em dispositivo real ou DevTools do Chrome
- Verificar se o script.js está carregando

**4. Links de contato não funcionam**
- WhatsApp: usar formato correto `https://wa.me/5511999999999`
- Email: usar `mailto:seu@email.com`

### Recursos Úteis
- [MDN Web Docs](https://developer.mozilla.org/) - Documentação HTML/CSS/JS
- [Can I Use](https://caniuse.com/) - Compatibilidade de navegadores
- [W3C Validator](https://validator.w3.org/) - Validar HTML
- [Lighthouse](https://developers.google.com/web/tools/lighthouse) - Auditoria de performance

---

## 📜 Licença

Este projeto está sob a licença MIT. Você pode usar, modificar e distribuir livremente para fins comerciais ou pessoais.

---

## 👨‍💻 Créditos

**Desenvolvido por**: Guilherme Ribeiro  
**GitHub**: [github.com/devgbr86](https://github.com/devgbr86)  
**Ano**: 2025

---

## 🎉 Conclusão

Este template foi cuidadosamente desenvolvido para oferecer uma solução completa, profissional e fácil de personalizar para nutricionistas que desejam uma presença online de qualidade.

**Características principais:**
- ✅ Design moderno e atraente
- ✅ 100% responsivo
- ✅ SEO otimizado
- ✅ Performance excelente
- ✅ Fácil personalização
- ✅ Hospedagem gratuita

**Perfeito para:**
- 🥗 Nutricionistas clínicos
- 💪 Nutricionistas esportivos
- 👨‍⚕️ Profissionais de saúde
- 🏢 Agências que atendem este nicho

**Próximos passos:**
1. Personalize as informações
2. Troque as imagens
3. Ajuste as cores se desejar
4. Faça deploy em uma das plataformas
5. Compartilhe sua URL!

---

**🚀 Pronto para lançar sua presença online profissional!**

Se tiver dúvidas ou precisar de suporte, consulte a seção de problemas comuns ou abra uma issue no GitHub.