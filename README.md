***

# 📱 Página de Login Responsiva

Uma página de login moderna e elegante com design responsivo, animações suaves e interface intuitiva. Desenvolvida com HTML5, CSS3 e ícones do Material Design.

## ✨ **Demonstração**
[

## 🎨 **Características Principais**

- **Design Moderno**: Interface limpa com paleta de cores harmoniosa (verde #49a09d + lilás #5f2c82)
- **Responsivo**: Funciona perfeitamente em desktop e mobile
- **Animações Suaves**: Transições CSS com `transition-timing-function: ease`
- **Campos Inteligentes**: Inputs com ícones e foco animado
- **Efeitos Hover**: Botões interativos com feedback visual
- **Acessibilidade**: Labels ocultos e placeholders descritivos

## 📁 **Estrutura do Projeto**

```
projeto-login/
│
├── index.html          # Página principal
├── estilo/
│   ├── stylenew.css    # Estilos principais
│   └── mediaquery.css  # Media queries responsivas
├── imagens/
│   └── back-print.jpg  # Imagem de fundo
└── README.md           # Este arquivo
```

## 🛠️ **Tecnologias Utilizadas**

```html
HTML5 | CSS3 | Material Icons | Flexbox | CSS Grid
```

## 🚀 **Como Usar**

1. **Clone/Download** o projeto
2. **Adicione sua imagem** em `imagens/back-print.jpg`
3. **Configure o backend** (altere `action="cadastro.php"` para seu endpoint)
4. **Abra** `index.html` no navegador

## 💻 **Funcionalidades Implementadas**

### Campos de Input Animados
```css
div.campo input {
    transform: translateY(-12px);
    background-color: #94cfcd;
}
div.campo input:focus-within {
    background-color: white;
}
```

### Botões Interativos
- Botão **Entrar**: Verde (#49a09d) → Hover (#2d6462)
- Link **Esqueci senha**: Borda verde com hover colorido

## 📱 **Responsividade**
O arquivo `mediaquery.css` garante adaptação perfeita para:
- Desktop (> 768px)
- Tablet (481px - 768px) 
- Mobile (< 480px)

## 🔧 **Customização Rápida**

### Alterar Cores
```css
/* Paleta atual */
--verde: #49a09d;
--lilas: #5f2c82;
--cinza-escuro: #2d6462;
--claro: #94cfcd;
```

### Adicionar Nova Imagem
Substitua `back-print.jpg` na pasta `imagens/`

## 🔗 **Links Úteis**
- [Material Icons](https://fonts.google.com/icons)
- [Live Preview](https://your-project-link.com)

## 👨‍💻 **Autor**
**Joaquim Eliseu Menianga (Progresso)**  
🗺️ Luanda, Angola  
💻 Desenvolvedor Web | Python | FullStack  

***

**⭐ Star este repositório se gostou do projeto!**

***

Gostaria de adicionar alguma seção específica ou modificar alguma informação do autor?

---
