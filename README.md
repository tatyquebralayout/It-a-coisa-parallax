# 🎈 Tutorial Parallax: Recriando a Cena de "It: A Coisa"

![GitHub repo size](https://img.shields.io/github/repo-size/tatyquebralayout/It-a-coisa-parallax)
![GitHub language count](https://img.shields.io/github/languages/count/tatyquebralayout/It-a-coisa-parallax)
![GitHub top language](https://img.shields.io/github/languages/top/tatyquebralayout/It-a-coisa-parallax)

## 📖 Introdução

Bem-vindo ao tutorial que recria uma das cenas mais icônicas do cinema de terror usando HTML e CSS puro! Neste projeto, vamos implementar um efeito parallax para dar vida à famosa cena do balão vermelho de "It: A Coisa", onde o sinistro Pennywise atrai suas vítimas com um balão flutuante contra o cenário sombrio de Derry.

Este guia é ideal para:
- Desenvolvedores web iniciantes que querem aprender efeitos CSS avançados
- Entusiastas de CSS interessados em técnicas de animação
- Fãs de horror que também programam! 🎈

### O Que é Efeito Parallax?

O efeito parallax é uma técnica de design onde elementos em diferentes camadas se movem em velocidades distintas, criando uma ilusão de profundidade 3D. Pense nele como as camadas de um teatro:
- O cenário ao fundo (a cidade) move-se lentamente
- Os elementos do meio (o palhaço) têm movimento intermediário
- Os elementos frontais (os balões) movem-se mais rapidamente

## 🎯 Objetivos do Projeto

1. Recriar a atmosfera sombria de Derry usando CSS
2. Implementar um efeito parallax suave e responsivo
3. Criar animações fluidas para os balões e elementos
4. Aprender técnicas avançadas de CSS

## 🛠️ Conceitos Técnicos Fundamentais

### Sistema de Perspectiva 3D
```css
.wrapper {
    perspective: 1000px;
    position: absolute;
    width: 600px;
    height: 400px;
    transform-style: preserve-3d;
}
```

### Arquitetura de Camadas

Nossa cena é dividida em três camadas principais:

1. **Camada de Fundo: A Cidade de Derry**
2. **Camada Intermediária: Pennywise**
3. **Camada Frontal: Os Balões Vermelhos**

## 📁 Estrutura do Projeto

```
📂 projeto_parallax
├── 📂 assets
│   ├── 🖼️ palhaco.png
│   ├── 🖼️ balao.png
│   └── 🖼️ cidade.png
├── 📄 index.html
└── 📄 styles.css
```

## 🚀 Como Começar

1. Clone o repositório:
```bash
git clone https://github.com/tatyquebralayout/It-a-coisa-parallax.git
```

2. Abra o arquivo `index.html` no seu navegador
3. Passe o mouse sobre a cena para ver a magia acontecer!

## 💻 Tecnologias Utilizadas

- HTML5
- CSS3 (Animações e Transformações)
- Técnicas de Parallax
- Perspectiva 3D

## 📱 Responsividade

O projeto é totalmente responsivo e se adapta a diferentes tamanhos de tela:
```css
@media (max-width: 768px) {
    .wrapper {
        width: 100%;
        height: 300px;
    }
}
```

## 🤝 Como Contribuir

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovoEfeito`)
3. Commit suas mudanças (`git commit -m 'Adicionando novo efeito'`)
4. Push para a branch (`git push origin feature/NovoEfeito`)
5. Abra um Pull Request

## 📚 Recursos Adicionais

- [MDN Web Docs - CSS Perspective](https://developer.mozilla.org/pt-BR/docs/Web/CSS/perspective)
- [CSS-Tricks - Guia Parallax](https://css-tricks.com/parallax-scrolling-tutorial/)
- [Can I Use - Suporte Browser](https://caniuse.com/?search=perspective)

## 👥 Créditos

- Inspirado no filme "It: A Coisa" (2017)
- Design original por [@Frankslaboratory](https://github.com/frankslaboratory)


---







