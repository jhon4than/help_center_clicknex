# Central de Ajuda CLICKNEX

Central de Ajuda completa para a plataforma SaaS CLICKNEX, desenvolvida com HTML, CSS e JavaScript puro seguindo o conceito Mobile First.

## 🚀 Características

- **Mobile First**: Design responsivo que prioriza dispositivos móveis
- **Dark Mode**: Interface moderna com tema escuro
- **Sem Frameworks**: Apenas HTML, CSS e JavaScript puro
- **Segurança**: Implementação de boas práticas de segurança web
- **Acessibilidade**: Código semântico e acessível
- **Performance**: Otimizado para carregamento rápido

## 📁 Estrutura de Arquivos

```
/
├── index.html          # Página principal
├── css/
│   └── style.css      # Estilos (Mobile First)
├── js/
│   └── app.js         # JavaScript (funcionalidades)
├── assets/
│   ├── img/           # Imagens
│   └── icons/         # Ícones
└── README.md          # Documentação
```

## 🎨 Cores

- **Cor Principal**: #00267E (Azul da logo CLICKNEX)
- **Cor Secundária**: #003399
- **Background**: #0d1117 (Dark)
- **Texto**: #e6edf3

## ⚙️ Configuração

As configurações globais estão centralizadas no arquivo `js/app.js`:

```javascript
const CONFIG = {
    systemName: "CLICKNEX",
    crmUrl: "https://crm.clicknex.com.br/",
    supportEmail: "suporte@clicknex.com.br",
    version: "1.0.0"
};
```

## 🎯 Funcionalidades

### Navegação
- Menu lateral responsivo
- Menu hamburguer no mobile
- Navegação SPA (sem reload)
- Scroll spy automático

### Busca
- Campo de busca na documentação
- Sanitização de entrada
- Resultados em tempo real

### Interatividade
- Botão "Isso foi útil?"
- Copiar link da página
- Links rápidos
- Feedback do usuário

### Segurança
- Sanitização de inputs
- `rel="noopener noreferrer"` em links externos
- Sem uso de `innerHTML` com dados do usuário
- Event listeners ao invés de inline handlers
- Preparado para CSP (Content Security Policy)

## 📱 Responsividade

### Mobile (< 768px)
- Menu lateral deslizante
- Layout em coluna única
- Busca oculta (pode ser adicionada)

### Tablet (768px - 1023px)
- Menu lateral fixo
- Busca visível
- Layout otimizado

### Desktop (1024px+)
- Menu lateral esquerdo fixo
- Painel direito com TOC
- Layout completo de 3 colunas

## 🔧 Personalização

### Variáveis CSS

Todas as cores e dimensões estão em variáveis CSS no `:root`:

```css
:root {
    --color-primary: #00267E;
    --color-bg: #0d1117;
    --header-height: 60px;
    --sidebar-width: 280px;
    /* ... */
}
```

### Adicionar Nova Seção

1. Adicione o item no menu (sidebar):
```html
<a href="#nova-secao" class="nav-item" data-section="nova-secao">
    <svg>...</svg>
    Nova Seção
</a>
```

2. Adicione a seção no conteúdo:
```html
<section id="nova-secao" class="content-section">
    <h1>Nova Seção</h1>
    <p>Conteúdo...</p>
</section>
```

## 🌐 Navegadores Suportados

- Chrome/Edge (últimas 2 versões)
- Firefox (últimas 2 versões)
- Safari (últimas 2 versões)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Licença

© 2024 CLICKNEX. Todos os direitos reservados.

## 🤝 Suporte

Para suporte técnico, entre em contato:
- Email: suporte@clicknex.com.br
- Portal: https://crm.clicknex.com.br/

## 🔄 Versão

Versão atual: 1.0.0
