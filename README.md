# Portfólio - Simei Thander

Portfólio pessoal inspirado no Visual Studio Code, desenvolvido com HTML e Tailwind CSS.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Framework CSS utilitário (via CDN)
- **JavaScript (Vanilla)** - Interatividade e navegação suave
- **Google Fonts (Roboto)** - Tipografia

## 📁 Estrutura do Projeto

```
simeithander.github.io/
├── index.html          # Página principal
├── images/             # Imagens e assets
│   ├── favicon.ico
│   └── vscode.png
└── README.md           # Este arquivo
```

## 🎨 Características

### Layout VS Code
- **Barra de Menu Superior**: Menu com links não funcionais (File, Edit, Selection, etc.)
- **Activity Bar**: Barra lateral esquerda com ícones de atividades
- **Explorer Sidebar**: Painel lateral com árvore de arquivos navegável
- **Área de Conteúdo**: Seções principais do portfólio
- **Status Bar**: Barra de status inferior

### Funcionalidades

- **Navegação Suave**: Scroll suave ao clicar nos arquivos do Explorer
- **Destaque de Arquivo Ativo**: O arquivo correspondente à seção visível é destacado automaticamente
- **Scrollbar Customizado**: Scrollbar personalizado no estilo VS Code
- **Design Responsivo**: Layout adaptável

### Seções

1. **Início** (`inicio.md`)
   - Apresentação pessoal
   - Resumo profissional
   - Principais competências

2. **Carreira Profissional** (`carreira-profissional.md`)
   - Histórico completo de experiências profissionais

3. **Formação** (`formacao.md`)
   - Formação acadêmica
   - Certificações

4. **Contato** (`contato.md`)
   - Email
   - LinkedIn
   - GitHub

## 🎨 Paleta de Cores (VS Code Dark Theme)

- **Fundo Principal**: `#1e1e1e`
- **Sidebar**: `#252526`
- **Menu Bar**: `#2d2d30`
- **Status Bar**: `#252526`
- **Texto**: `#cccccc`
- **Texto Secundário**: `#858585`
- **Destaque**: `#4ec9b0`
- **Bordas**: `#3e3e42`

## 📝 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/simeithander/simeithander.github.io.git
```

2. Abra o arquivo `index.html` no navegador ou sirva via servidor local:
```bash
# Com Python
python -m http.server 8000

# Com Node.js (http-server)
npx http-server
```

3. Acesse `http://localhost:8000` no navegador

## 🔧 Personalização

### Adicionar Nova Seção

1. Adicione um novo item no Explorer (sidebar):
```html
<div class="file-item" onclick="scrollToSection('nova-secao')">
  <svg class="file-icon" viewBox="0 0 16 16" fill="currentColor">
    <path d="M13 6l-5-5v4H3v7h10V6zM2 4h6V0l6 6v8H2V4z" />
  </svg>
  <span>nova-secao.md</span>
</div>
```

2. Adicione a seção no conteúdo principal:
```html
<section id="nova-secao" class="min-h-screen p-8">
  <!-- Conteúdo da seção -->
</section>
```

3. Atualize o mapeamento no JavaScript:
```javascript
const sectionFileMap = {
  // ...
  'nova-secao': 'nova-secao.md',
};
```

### Modificar Cores

As cores podem ser alteradas diretamente nas classes Tailwind ou no CSS customizado no `<style>` do HTML.

## 🌐 Deploy

Este portfólio está configurado para GitHub Pages. Basta fazer push para a branch `main` e o site será publicado automaticamente em:
```
https://simeithander.github.io
```

## 📄 Licença

Este projeto é de uso pessoal.

## 👤 Autor

**Simei Thander**
- Email: simeithander@gmail.com
- LinkedIn: [simei-thander-96096987](https://www.linkedin.com/in/simei-thander-96096987)
- GitHub: [@simeithander](https://github.com/simeithander)

---

Desenvolvido com ❤️ inspirado no Visual Studio Code

