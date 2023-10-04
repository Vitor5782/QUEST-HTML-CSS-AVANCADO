# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Índice

- [Visao geral](#visao-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Como pensei ao construir](#como-pensei-ao-construir:)
  - [Construi com](#construi-com:)
  - [O que pude aprender](#o-que-pude-aprender:)
  - [Sites pesquisados](#sites-pesquisados:)
- [Autor](#autor:)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Ver o layout ideal da página dependendo do tamanho da tela do dispositivo.
- Ver os estados de foco para todos os elementos interativos na página.

### Screenshot

![ScreenshotDesktop](./src/gifs/ScreenshotDesktop.gif)
![ScreenshotMobile](./src/gifs/ScreenshotMobile.gif)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## Como pensei ao construir:
Todo o body tem uma imagem de fundo
uma div de imagem
uma div com alguns elementos tais:
h1
p
button
um footter com 3 botões de rede sociais
No footer do frontendmentor usar a font-size 11px
Estilização dos elementos
Primeiro temos que mudar o fundo do body por uma cor que está no var e uma img
depois vamos fazer o famoso de cima na esquerda para baixo e direita.


### Construi com:

- HTML Semantico
- CSS Propriedades de estilos
- Flexbox
- CSS Grid
- CSS Pseudo-Classes

### O que pude aprender:

Aprendi a como utilizar o grid-areas e pude construir meu html de forma semantica e ordenada.

```html
<body>
  <main>
    <header class="logo">
      <a href="#">
        <img src="src/images/logo.svg" alt="logo">
      </a>
      ....
```
```css
.introducao .botao {
    color: var(--bg-color);
    border-radius: 40px;
    margin: 40px;
    width: 150px;
    height: 50px;
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
    transition: 0.5s ease-in-out;
    font-size: 1.5rem;
    cursor: pointer;
}
```

### Sites pesquisados:

- [Example resource 1](https://www.freecodecamp.org/portuguese/news/tutorial-de-tamanho-de-imagem-de-fundo-em-css-como-inserir-uma-imagem-de-fundo-de-pagina-inteira/#:~:text=A%20magia%20acontece%20com%20a,caso%2C%20todo%20o%20html%20) - Nessa pesquisa pude ententer o uso do background e algumas propriedades que foram utilizadas.
- [Example resource 2](https://getcssscan.com/css-box-shadow-examples) - Neste site, pude encontrar a melhor sombra que se assemelhava ao desing desejado.

## Autor:

- Frontend Mentor - [@Vitor5782](https://www.frontendmentor.io/profile/Vitor5782  target="_blank")
- Github - [@Vitor5782](https://github.com/Vitor5782  target="_blank")