# 🏥 Clínica Saúde — Landing Page

Uma landing page moderna e responsiva para uma clínica de saúde. Desenvolvida com **HTML5** e **CSS3 puro**, com arquivos separados por linguagem.

## 🌟 Características

- ✅ HTML e CSS separados
- ✅ Design responsivo (desktop, tablet e mobile)
- ✅ Sem dependências externas (apenas Google Fonts)
- ✅ Cards com hover effects
- ✅ Formulário de agendamento
- ✅ Navegação sticky

## 🗂️ Estrutura do Projeto

```
clinica-saude-landing/
├── index.html    # HTML semântico
├── style.css     # Estilos CSS
└── README.md     # Este arquivo
```

## 📄 Seções da Página

- **Navbar** - Menu fixo com logo e navegação
- **Hero** - Apresentação principal com estatísticas
- **Serviços** - 6 serviços com imagens e descrições
- **Diferenciais** - 6 motivos para escolher a clínica
- **Equipe** - 6 profissionais fictícios com especialidades
- **Contato** - Formulário de agendamento + informações
- **Footer** - Links, endereço e horários

## 🚀 Como Executar

**Opção 1: Abrir localmente**
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

**Opção 2: Clonar repositório**
```bash
git clone https://github.com/henriquesebben/landing-page.git
cd clinica-saude-landing
# Abrir index.html no navegador
```

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização responsive (Grid, Flexbox)
- **Google Fonts** - Tipografia (Inter)
- **Unsplash** - Imagens dos serviços

## 🎯 Navegação

- 🏠 **Logo** - Volta ao início
- 📋 **Serviços** - Seção de serviços
- 👥 **Equipe** - Mostra profissionais
- ⭐ **Diferenciais** - Motivos para nos escolher
- 📞 **Agendar Consulta** - Formulário de contato

## ⭐ Requisitos Atendidos

- ✅ Título correto na aba do navegador
- ✅ Múltiplas imagens responsivas
- ✅ Descrições completas dos 6 serviços
- ✅ Equipe com 6 profissionais (foto, nome, cargo)
- ✅ Hierarquia de títulos (H1, H2, H3)
- ✅ Formulário com: Nome, E-mail, Cidade, Estado
- ✅ **HTML e CSS em arquivos separados**
- ✅ Design moderno e responsivo

## 👨‍💻 Autor

**Henrique Sebben**

- GitHub: [@henriquesebben](https://github.com/henriquesebben)
- Repositório: [landing-page](https://github.com/henriquesebben/landing-page)

## 📞 Suporte

Dúvidas ou bugs? Abra uma [issue](https://github.com/henriquesebben/landing-page/issues) no GitHub!

---

**Versão:** 2.0  
**Status:** ✅ Produção
# 🏥 Clínica Saúde — Landing Page

Uma landing page moderna, profissional e totalmente responsiva para uma clínica de saúde. Desenvolvida com **HTML5 semântico** e **CSS3 puro**, com arquivos separados por linguagem.

## 🌟 Características

- ✅ **HTML e CSS Separados** - Estrutura limpa e profissional
- ✅ **Design Responsivo** - Otimizado para desktop, tablet e mobile
- ✅ **Performance Otimizada** - Sem dependências externas (apenas Google Fonts)
- ✅ **Paleta Profissional** - Cores médicas e humanizadas
- ✅ **Componentes Modernos** - Cards com hover effects e animações suaves
- ✅ **Acessível** - Semântica HTML correta e navegação intuitiva
- ✅ **Formulário Completo** - Agendamento com validação básica

## 🗂️ Estrutura do Projeto

```
clinica-saude-landing/
├── index.html          # Estrutura HTML semântica
├── style.css           # Estilos CSS (separado)
└── README.md           # Este arquivo
```

## 📄 Seções da Página

| Seção | Descrição |
|-------|-----------|
| **Navbar** | Menu sticky com logo e navegação |
| **Hero** | Apresentação principal com CTA e estatísticas |
| **Serviços** | 6 serviços com imagens e descrições |
| **Diferenciais** | 6 motivos para escolher a clínica |
| **Equipe** | 6 profissionais fictícios com especialidades |
| **Contato** | Formulário de agendamento + informações |
| **Footer** | Links, endereço e horários |

## 🎨 Design & Cores

```css
Cor Primária:  #1d6fb8 (Azul confidente)
Cor Secundária: #27ae60 (Verde esperança)
Acentuação:    #e8f4fd (Azul claro)
Texto:         #1a2332 (Azul escuro)
Muted:         #5a6a7e (Cinza profissional)
```

## 🚀 Como Usar

### Visualizar a Página

**Opção 1: Abrir diretamente**
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

**Opção 2: Clonar repositório**
```bash
git clone https://github.com/henriquesebben/landing-page.git
cd clinica-saude-landing
# Abrir index.html no navegador
```

## 🔧 Como Customizar

### Mudar as Cores Principais
Edite as variáveis CSS no topo do arquivo `style.css`:
```css
:root {
  --primary: #seu-codigo;
  --primary-dark: #seu-codigo;
  /* demais cores */
}
```

### Adicionar um Novo Serviço
Duplique este bloco em `index.html`:
```html
<div class="service-card">
  <img src="url-da-imagem" alt="Descrição" />
  <div class="content">
    <div class="service-icon">🎯</div>
    <h3>Nome do Serviço</h3>
    <p>Descrição completa do serviço...</p>
  </div>
</div>
```

### Atualizar Informações de Contato
Procure pela seção `<!-- FORMULÁRIO -->` e atualize:
- Telefone
- E-mail
- Endereço
- Convênios

## 💻 Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|---|---|---|
| HTML | 5 | Estrutura semântica |
| CSS | 3 | Estilização responsive |
| Google Fonts | - | Tipografia (Inter) |
| Unsplash | - | Imagens dos serviços |

## 📱 Responsividade

**Breakpoint principal:** 768px

| Device | Comportamento |
|--------|---------------|
| Desktop (>768px) | Layout 2 colunas, hero com imagem |
| Mobile (<768px) | Layout stackado, hero com ajustes |

## ⭐ Requisitos Atendidos

- ✅ Título correto na aba do navegador
- ✅ Múltiplas imagens responsivas
- ✅ Descrições completas dos serviços (6 serviços)
- ✅ Equipe com 6 profissionais (foto, nome, cargo)
- ✅ Hierarquia de títulos (H1, H2, H3)
- ✅ Formulário com campos: Nome, E-mail, Cidade, Estado
- ✅ **HTML e CSS em arquivos separados** ✨
- ✅ Design moderno e profissional
- ✅ Totalmente responsivo

## 🎯 Navegação

Use os links na navbar para navegar:
- 🏠 **Logo** - Volta ao início
- 📋 **Serviços** - Seção de serviços
- 👥 **Equipe** - Mostra os profissionais
- ⭐ **Diferenciais** - Por que nos escolher
- 📞 **Agendar Consulta** - Formulário de contato

## 📊 Compatibilidade

Testado e funciona em:
- ✅ Chrome/Chromium (versões recentes)
- ✅ Firefox (versões recentes)
- ✅ Safari (versões recentes)
- ✅ Edge (versões recentes)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Como Contribuir

1. Faça um Fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Melhorias Sugeridas

- [ ] Integrar formulário com backend (Node.js, Python, etc)
- [ ] Adicionar animações com CSS/JavaScript
- [ ] Implementar dark mode
- [ ] Adicionar página de blog
- [ ] SEO optimization (meta tags, schema)
- [ ] Integração com Google Analytics

## 📄 Licença

MIT License - Veja LICENSE para detalhes.

## 👨‍💻 Autor

**Henrique Sebben**

- GitHub: [@henriquesebben](https://github.com/henriquesebben)
- Repositório: [landing-page](https://github.com/henriquesebben/landing-page)

## 📞 Suporte

Encontrou um bug? Abra uma [issue](https://github.com/henriquesebben/landing-page/issues) no GitHub!

---

**Versão:** 2.0 (HTML e CSS separados)  
**Última atualização:** Abril 2026  
**Status:** ✅ Produção

2. Abra o arquivo no navegador:
```bash
# Windows
start clinica-saude-landing/index.html

# Mac
open clinica-saude-landing/index.html
```

Ou simplesmente dê **duplo clique** no arquivo `index.html`.

> Não é necessário instalar nada — a página é 100% estática.
