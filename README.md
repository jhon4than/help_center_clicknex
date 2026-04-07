# 📚 Central de Ajuda CLICKNEX

> Sistema de documentação técnica e tutoriais com tema dark minimalista e ícones Lucide

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Version](https://img.shields.io/badge/version-2.1.0-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)]()

---

## 🎯 Sobre o Projeto

Central de Ajuda do CLICKNEX - Documentação técnica completa com design profissional, ícones SVG e foco em experiência do usuário.

### ✨ Características

- 🎨 **Tema Dark Minimalista** - Design limpo e profissional
- 🎭 **Ícones Lucide** - Ícones SVG vetoriais em todas as páginas
- 📱 **Totalmente Responsivo** - Funciona em todos os dispositivos
- ⚡ **Carregamento Dinâmico** - Páginas carregadas sob demanda
- 📑 **Sumário Automático** - Navegação inteligente por tópicos
- 🔍 **Sistema de Busca** - Encontre conteúdo rapidamente
- 👍 **Sistema de Feedback** - Melhoria contínua
- 🎬 **Animações Suaves** - Efeitos visuais modernos

---

## 🚀 Início Rápido

### Pré-requisitos

Você precisa de um servidor HTTP local. Escolha uma opção:

- Python 3.x
- Node.js
- PHP
- VS Code com Live Server

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/clicknex-help-center.git
cd clicknex-help-center
```

2. **Inicie o servidor**

**Opção 1: Python (Recomendado)**
```bash
python -m http.server 8000
```

**Opção 2: Node.js**
```bash
node server.js
```

**Opção 3: Windows (Auto-detecta)**
```bash
# Duplo clique em:
iniciar-servidor.bat
```

3. **Acesse no navegador**
```
http://localhost:8000
```

---

## 📁 Estrutura do Projeto

```
clicknex-help-center/
├── index.html              # Página principal com Lucide CDN
├── css/
│   └── style.css          # Tema dark + estilos de ícones
├── js/
│   └── app.js             # Carregamento dinâmico + init Lucide
├── pages/                 # 40+ páginas com ícones Lucide
│   ├── modulos/          # 8 módulos do sistema
│   ├── diretrizes/       # 7 políticas e diretrizes
│   ├── api/              # 2 documentações de API
│   ├── vendas/           # 5 páginas de vendas
│   ├── projetos/         # 4 páginas de projetos
│   ├── atendimento/      # 6 páginas de atendimento
│   ├── inteligencia/     # 3 páginas de inteligência
│   ├── equipes/          # 3 páginas de equipes
│   ├── sistema/          # 6 páginas de sistema
│   ├── agenda/           # 2 páginas de agenda
│   └── dashboard/        # 1 página de dashboard
└── imgs/                  # Imagens e screenshots
```

---

## 🎨 Design System

### Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Fundo Principal | `#0a0a0a` | Background |
| Fundo Secundário | `#141414` | Cards e containers |
| Texto Principal | `#e8e8e8` | Títulos e texto |
| Texto Secundário | `#a0a0a0` | Descrições |
| Destaque | `#1e3a8a` | Links e botões |
| Destaque Hover | `#2563eb` | Hover states |
| Borda | `#2a2a2a` | Separadores |

### Ícones Lucide

Todos os ícones são SVG da biblioteca Lucide, garantindo:
- ✅ Escalabilidade perfeita
- ✅ Tamanho reduzido (CDN)
- ✅ Consistência visual
- ✅ Fácil customização

**Tamanhos de ícones:**
- Hero: 56px (container 96x96px)
- Module: 48px (container 80x80px)
- Card: 36px (container 64x64px)
- Nav: 20px

### Princípios de Design

- ✅ Minimalismo - Apenas o essencial
- ✅ Legibilidade - Contraste WCAG AAA
- ✅ Consistência - Sistema de design unificado
- ✅ Responsividade - Mobile First
- ✅ Acessibilidade - Ícones com labels

---

## 🛠️ Tecnologias

- **HTML5** - Semântico e acessível
- **CSS3** - Flexbox, Grid, Variáveis, Animações
- **JavaScript** - Vanilla ES6+
- **Lucide Icons** - Biblioteca de ícones SVG (CDN)
- **Fetch API** - Carregamento dinâmico

---

## 📊 Estatísticas

| Métrica | Valor |
|---------|-------|
| Páginas HTML | 40+ |
| Ícones Lucide | 50+ diferentes |
| Linhas CSS | ~900 |
| Linhas JavaScript | ~700 |
| Tempo de carregamento | <1s |
| Contraste WCAG | AAA |
| Container centralizado | 1000px max-width |

---

## 🎭 Ícones Implementados

### Por Módulo

**Vendas**: briefcase, target, building-2, package, tag  
**Sistema**: smartphone, globe, list, code-2, search, settings  
**Equipes**: user, shield, building-2  
**Atendimento**: message-square, send, file-text, users, bot, cpu  
**Projetos**: folder, check-square, file-text, key  
**Inteligência**: activity, git-branch, bar-chart-3  
**Agenda**: calendar, bar-chart-3  
**Dashboard**: layout-dashboard  

### Páginas Principais

**Central de Ajuda**: help-circle, zap, shield-check, palette  
**Conheça**: rocket, palette, shield-check, bot, bar-chart-3  
**Pré-requisitos**: settings, database, zap, hard-drive, wifi, server  
**Suporte**: wrench, ticket, clock, timer, check-circle, x-circle  
**API Oficial**: plug, check-circle, alert-triangle  

---

## 🔧 Desenvolvimento

### Adicionar Nova Página com Ícones

1. **Criar arquivo**
```bash
pages/modulos/nova-pagina.html
```

2. **Estrutura com ícones Lucide**
```html
<div class="module-header">
    <div class="module-icon">
        <i data-lucide="rocket"></i>
    </div>
    <h1>Título</h1>
    <p class="module-description">Descrição</p>
</div>

<div class="content-text">
    <h2>Tópico 1</h2>
    <p>Conteúdo...</p>
    
    <div class="info-cards">
        <div class="info-card">
            <div class="card-icon">
                <i data-lucide="zap"></i>
            </div>
            <h3>Título do Card</h3>
            <p>Descrição</p>
        </div>
    </div>
</div>
```

3. **Adicionar no mapeamento** (`js/app.js`)
```javascript
const PAGE_MAP = {
    'nova-pagina': 'modulos/nova-pagina.html',
}
```

4. **Adicionar no menu** (`index.html`)
```html
<a href="#nova-pagina" class="nav-item" data-section="nova-pagina">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none">
        <path d="..." stroke="currentColor" stroke-width="1.5"/>
    </svg>
    Nova Página
</a>
```

### Ícones Disponíveis

Consulte a biblioteca completa em: [lucide.dev/icons](https://lucide.dev/icons)

Ícones mais usados no projeto:
- `rocket`, `zap`, `shield-check`, `settings`
- `message-square`, `users`, `folder`, `calendar`
- `bar-chart-3`, `database`, `smartphone`, `globe`

---

## 📱 Responsividade

### Breakpoints

- **Desktop** (> 1200px) - Layout 3 colunas (sidebar + content + toc)
- **Tablet** (768px - 1200px) - Layout 2 colunas (sidebar + content)
- **Mobile** (< 768px) - Layout 1 coluna (menu hamburguer)

### Container Centralizado

Todo conteúdo é centralizado com `max-width: 1000px` para melhor legibilidade em telas grandes.

### Testes

Testado em:
- ✅ Chrome/Edge (Desktop & Mobile)
- ✅ Firefox (Desktop & Mobile)
- ✅ Safari (Desktop & iOS)
- ✅ Android Chrome

---

## 🎬 Animações e Efeitos

- **fadeInUp**: Entrada suave de cards
- **pulse**: Animação de ícones no hover
- **shimmer**: Efeito de loading
- **Transições**: cubic-bezier para suavidade
- **Hover effects**: Transform e box-shadow

---

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

### Diretrizes

- Use ícones Lucide para consistência
- Mantenha o container centralizado (max-width: 1000px)
- Siga a paleta de cores definida
- Teste em múltiplos dispositivos
- Documente mudanças no DOCUMENTACAO-COMPLETA.md

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👥 Equipe

- **Desenvolvimento** - Equipe CLICKNEX
- **Design** - Equipe CLICKNEX
- **Conteúdo** - Equipe CLICKNEX

---

## 📞 Suporte

- 📧 Email: suporte@clicknex.com.br
- 🌐 Portal: https://crm.clicknex.com.br/
- 📚 Docs: [DOCUMENTACAO-COMPLETA.md](DOCUMENTACAO-COMPLETA.md)

---

## 🎯 Changelog

### v2.1.0 (Atual) - Refatoração UI com Lucide Icons
- ✅ Implementados ícones Lucide em 40+ páginas
- ✅ Container centralizado (max-width: 1000px)
- ✅ Efeitos visuais modernos (animações, hover, transições)
- ✅ Substituição completa de emojis por SVG
- ✅ Melhoria na consistência visual
- ✅ +300 linhas de CSS para animações

### v2.0.0 - Tema Dark Minimalista
- ✅ Redesign completo com tema dark
- ✅ Carregamento dinâmico de páginas
- ✅ Sumário automático
- ✅ Sistema de busca
- ✅ Responsividade total

---

## 🚀 Roadmap

### v2.2.0 (Próxima)
- [ ] Modo claro (opcional)
- [ ] Busca avançada com filtros
- [ ] Breadcrumbs melhorados
- [ ] Mais animações

### v3.0.0 (Futuro)
- [ ] Sistema de comentários
- [ ] Versionamento de docs
- [ ] Exportar para PDF
- [ ] Tradução multi-idioma
- [ ] PWA (Progressive Web App)

---

## ⭐ Agradecimentos

Obrigado por usar a Central de Ajuda CLICKNEX!

Se este projeto foi útil, considere dar uma ⭐

**Bibliotecas utilizadas:**
- [Lucide Icons](https://lucide.dev) - Ícones SVG lindos e consistentes

---

**Versão**: 2.1.0  
**Última atualização**: 07/04/2026  
**Status**: ✅ Ativo
