# 🧳 Perfil de Viagens - Travelgram

![Travelgram Logo](assets/icons/Logo.svg)

## 📋 Descrição

Este projeto é uma recriação responsiva de um perfil de viagens inspirado no design do Figma, desenvolvido durante a trilha Fullstack da Rocketseat. O projeto apresenta um perfil de usuário com galeria de fotos de viagens, totalmente responsivo para dispositivos móveis e desktop.

## 🎨 Design Original

- **Figma Community**: [Perfil de Viagens](https://www.figma.com/community/file/1392188119249243534/perfil-de-viagens)
- **Designer**: Comunidade Figma
- **Recriado por**: Leonardo Bruchez durante a trilha Fullstack da Rocketseat

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade
- **CSS Grid** - Layout responsivo
- **CSS Custom Properties** - Variáveis CSS para design system
- **Media Queries** - Breakpoints responsivos

### Design System
- **Fonte**: Poppins (Google Fonts)
- **Cores**: Sistema de cores com variáveis CSS
- **Espaçamentos**: Sistema de padding e margin consistente
- **Breakpoints**: Mobile-first com breakpoint em 80em (1280px)

## 📱 Layouts e Responsividade

### Mobile First (≤1280px)
- **Container**: Largura máxima de 360px
- **Grid**: Layout em coluna única
- **Navegação**: Logo + ícones de busca e perfil
- **Perfil**: Imagem, biografia e estatísticas em coluna
- **Galeria**: Imagens em grid de 1 coluna
- **Footer**: Centralizado

### Desktop (≥1280px)
- **Container**: Largura máxima de 80rem (1280px)
- **Grid**: Layout em 3 colunas para perfil, 4 colunas para galeria
- **Navegação**: Adiciona links "Explorar" e "Minhas viagens"
- **Perfil**: Layout horizontal com imagem, biografia e estatísticas
- **Galeria**: Grid de 4 colunas com espaçamento otimizado
- **Footer**: Distribuído com espaço entre elementos

## 🏗️ Estrutura do Projeto

```
Perfil-de-viagens-responsivo/
├── assets/
│   ├── icons/          # Ícones SVG (Logo, busca, localização, etc.)
│   ├── images/         # Imagens de viagens (12 fotos)
│   └── profile-pic.svg # Foto de perfil
├── styles/
│   ├── global.css      # Reset CSS e variáveis globais
│   ├── utility.css     # Classes utilitárias e grid
│   ├── nav.css         # Estilos da navegação
│   ├── section.css     # Estilos das seções principais
│   ├── footer.css      # Estilos do rodapé
│   └── index.css       # Arquivo principal que importa todos os estilos
└── index.html          # Estrutura HTML principal
```

## 🎯 Funcionalidades

- **Perfil de Usuário**: Exibe informações pessoais e estatísticas de viagem
- **Galeria de Fotos**: Grid responsivo com 12 imagens de viagens
- **Navegação Responsiva**: Adapta-se entre mobile e desktop
- **Design System**: Sistema de cores e tipografia consistente
- **Layout Adaptativo**: Transições suaves entre breakpoints

## 🔧 Como Executar

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITORIO]
```

2. Abra o arquivo `index.html` em seu navegador

3. Ou use um servidor local:
```bash
# Com Python
python -m http.server 8000

# Com Node.js
npx serve .
```

## 📱 Breakpoints

- **Mobile**: < 1280px (80em)
- **Desktop**: ≥ 1280px (80em)

## 🎨 Sistema de Cores

```css
:root {
  --brand-color: #EF5F4C;           /* Cor principal */
  --bg-color: #FFFFFF;              /* Fundo */
  --surface-color: #F5F5F5;         /* Superfícies */
  --text-color-primary: #313131;    /* Texto principal */
  --text-color-secondary: #6C6C6C;  /* Texto secundário */
}
```

## 📚 Aprendizados

Este projeto demonstra:
- **Mobile First**: Desenvolvimento responsivo começando pelo mobile
- **CSS Grid**: Uso avançado de grid para layouts complexos
- **Design System**: Organização de estilos com variáveis CSS
- **Media Queries**: Breakpoints eficientes para diferentes dispositivos
- **Componentização**: Separação de estilos por funcionalidade

## 👨‍💻 Desenvolvido por

Leonardo Bruchez - Estudante da trilha Fullstack da Rocketseat

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Nota**: Este projeto foi desenvolvido como exercício educacional durante a trilha Fullstack da Rocketseat, recriando um design do Figma com foco em responsividade e boas práticas de CSS.
