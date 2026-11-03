# Product Preview Card

Componente responsivo de apresentação de produto, desenvolvido
como desafio do Frontend Mentor para praticar HTML semântico,
CSS e imagens responsivas.

## Prévia

![Prévia do projeto](./images/preview.png)

## Links

- Site publicado: [Ver projeto](https://github.com/4Leuuu/product-preview-card)
- Desafio: [Frontend Mentor](https://www.frontendmentor.io/learning-paths/building-responsive-layouts--z1qCXVqkD/challenge/65e71e1c17e502f0b6ce64b0/start)

## Tecnologias

- HTML5 semântico
- CSS com propriedades personalizadas
- Flexbox e Grid
- Abordagem mobile first
- Elemento picture para imagens responsivas

## Como executar

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

Abra o arquivo `index.html` no navegador ou use a extensão
Live Server no VS Code.

## O que aprendi

Aprendi a usar o elemento picture para apresentar imagens
diferentes conforme a largura da tela:

```html
<picture>
  <source
    media="(min-width: 768px)"
    srcset="./images/image-product-desktop.jpg"
  >
  <img
    src="./images/image-product-mobile.jpg"
    alt="Bottle of Gabrielle Essence perfume by Chanel"
  >
</picture>
```

Também pratiquei a abordagem de mobile first.
