# Daniel Marques - Link Tree

Página pessoal estilo linktree moderna e responsiva.

## 🚀 Deploy no GitHub Pages

### 1. Criar repositório
- Nome: `antonovoleg.github.io`
- Visibilidade: Public
- Adicione estes arquivos ao repositório

### 2. Configurar DNS do domínio

No seu provedor de DNS (onde registrou danielmarques.org), adicione:

**Registros A:**
```
Type: A   Name: @   Value: 185.199.108.153
Type: A   Name: @   Value: 185.199.109.153
Type: A   Name: @   Value: 185.199.110.153
Type: A   Name: @   Value: 185.199.111.153
```

**Registro CNAME:**
```
Type: CNAME   Name: www   Value: antonovoleg.github.io
```

### 3. Ativar GitHub Pages

1. Vá em Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / `root`
4. Custom domain: `danielmarques.org`
5. ✅ Enforce HTTPS

### 4. Aguardar propagação

DNS pode levar de 5 minutos a 48 horas para propagar.

---

## ✏️ Personalização

### Editar seus links

No arquivo `index.html`, substitua:

**Instagram:**
```html
<a href="https://instagram.com/SEU_INSTAGRAM" ...>
```

**LinkedIn:**
```html
<a href="https://linkedin.com/in/SEU_LINKEDIN" ...>
```

**Email:**
```html
<a href="mailto:SEU_EMAIL@exemplo.com" ...>
```

**WhatsApp:**
```html
<a href="https://wa.me/5561999999999" ...>
```
> Formato: 55 + DDD + número (sem espaços, traços ou parênteses)

**Twitter/X:**
```html
<a href="https://twitter.com/SEU_TWITTER" ...>
```

### Trocar foto do perfil

**Opção 1:** Use sua própria imagem
```html
<img src="sua-foto.jpg" alt="Daniel Marques">
```

**Opção 2:** Mantenha o avatar gerado automaticamente (atual)

### Adicionar/remover links

**Para adicionar novo link:**
```html
<a href="SEU_LINK" class="link" target="_blank">
    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
        <!-- Ícone SVG aqui -->
    </svg>
    <span>Nome do Link</span>
</a>
```

**Para remover:** Delete o bloco `<a>...</a>` completo do link indesejado

### Mudar cores

No arquivo `style.css`, altere as variáveis:

```css
:root {
    --primary: #6366f1;        /* Cor principal */
    --primary-dark: #4f46e5;   /* Cor hover */
    --bg: #0f172a;             /* Fundo da página */
    --card-bg: #1e293b;        /* Fundo dos cards */
    --text: #f8fafc;           /* Cor do texto */
    --text-muted: #cbd5e1;     /* Texto secundário */
}
```

### Editar bio

No `index.html`:
```html
<p class="bio">Assessor Parlamentar | Senado Federal | Tech & Aviation</p>
```

---

## 🎨 Features

✅ Design moderno e minimalista  
✅ Totalmente responsivo (mobile-first)  
✅ Animações suaves  
✅ Efeitos hover interativos  
✅ Gradientes modernos  
✅ Dark theme  
✅ Performance otimizada  
✅ SEO friendly  

---

## 📱 Redes suportadas

- Instagram
- LinkedIn
- GitHub
- Email
- WhatsApp
- Twitter/X
- (Fácil adicionar mais)

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis CSS, gradientes, animações)
- Google Fonts (Inter)
- Feather Icons (SVG)

---

## 📝 Licença

Livre para uso pessoal.

---

**Desenvolvido para Daniel Marques**  
Senado Federal | Brasília, DF
