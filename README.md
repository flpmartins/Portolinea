# Portolinea Pinturas - Landing Page

Landing page profissional e moderna para a empresa Portolinea Pinturas, especializada em pintura residencial e industrial.

## 📋 Sobre o Projeto

Landing page desenvolvida com foco em conversão, apresentando os serviços de pintura residencial e industrial da Portolinea Pinturas. O design é clean, moderno e transmite profissionalismo e confiança.

## 🎨 Características

- **Design Responsivo**: Totalmente adaptável para desktop, tablet e mobile
- **Header Fixo**: Navegação sempre visível durante o scroll
- **Animações Suaves**: Microinterações e transições para melhor experiência
- **Otimizado para Conversão**: CTAs estratégicos com links diretos para WhatsApp
- **Performance**: Código limpo, sem dependências externas (exceto Google Fonts)
- **Acessibilidade**: Estrutura semântica e navegação por teclado

## 🎯 Identidade Visual

### Cores
- **Azul Escuro** (#1a3a5f): Cor principal, transmite confiança e profissionalismo
- **Gradiente Quente**: Vermelho (#e63946) → Laranja (#f77f00) → Amarelo (#fcbf49)
- **Fundo**: Branco e cinza claro para um visual clean

### Tipografia
- **Fonte Principal**: Inter (Google Fonts)
- Hierarquia clara com diferentes pesos (300, 400, 500, 600, 700)

## 📁 Estrutura de Arquivos

```
Portolinea/
├── index.html          # Estrutura HTML semântica
├── style.css           # Estilos e design system
├── script.js           # Interações e funcionalidades
├── logo.png            # Logo da empresa
└── README.md           # Documentação do projeto
```

## 🚀 Como Usar

### Visualização Local

1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em um navegador moderno
3. Pronto! A página está funcionando localmente

### Personalização

#### Alterar Número do WhatsApp
Procure por `5511999999999` no arquivo `index.html` e substitua pelo número real da empresa.

#### Alterar Área de Atuação
Edite a seção do footer no `index.html`:
```html
<p>São Paulo e Região Metropolitana</p>
```

#### Ajustar Cores
As cores estão definidas como variáveis CSS no início do arquivo `style.css`:
```css
:root {
    --azul-escuro: #1a3a5f;
    --gradient-primary: linear-gradient(135deg, #e63946 0%, #f77f00 50%, #fcbf49 100%);
    /* ... */
}
```

## 📱 Seções da Página

1. **Header**: Navegação fixa com logo e menu
2. **Hero Section**: Apresentação principal com CTA e ilustração SVG
3. **Serviços**: Cards com os 4 principais serviços oferecidos
4. **Diferenciais**: 4 pontos que destacam a empresa
5. **Prova de Confiança**: Números de experiência, projetos e clientes
6. **CTA Final**: Chamada final para ação com link do WhatsApp
7. **Footer**: Informações de contato e área de atuação

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: 
  - Flexbox e Grid
  - Variáveis CSS
  - Gradientes
  - Animações e transições
- **JavaScript (Vanilla)**: 
  - Menu mobile
  - Scroll suave
  - Animações ao scroll
- **SVG**: Ilustração do rolo de pintura

## 📦 Dependências

- **Google Fonts**: Fonte Inter (carregada via CDN)

## 🌐 Compatibilidade

- Chrome (últimas versões)
- Firefox (últimas versões)
- Safari (últimas versões)
- Edge (últimas versões)
- Navegadores mobile (iOS Safari, Chrome Mobile)

## 📝 Funcionalidades JavaScript

- **Menu Mobile**: Toggle do menu em dispositivos móveis
- **Scroll Suave**: Navegação suave entre seções
- **Animações ao Scroll**: Elementos aparecem conforme o usuário rola a página
- **Header com Scroll**: Efeito sutil no header ao fazer scroll

## 🎨 Customização do SVG

O SVG do rolo de pintura está localizado na seção Hero. Para personalizar:
- Edite o elemento `<svg>` no `index.html`
- Ajuste cores, tamanhos e posicionamento conforme necessário

## 📞 Contato

Para personalizar os links de contato:
- **WhatsApp**: Edite os links `https://wa.me/...` no HTML
- **Área de Atuação**: Edite a seção do footer

## 📄 Licença

Este projeto foi desenvolvido para a Portolinea Pinturas.

## 👨‍💻 Desenvolvimento

- Código limpo e comentado
- Estrutura semântica
- Boas práticas de acessibilidade
- Performance otimizada
- Design responsivo mobile-first

---

**Desenvolvido com foco em conversão e experiência do usuário** 🎨
