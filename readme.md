# Landing Page Flex/Grid
Desenvolvimento de landing page utilizando como base técnicas de flex e grid.

## Desafio

Os usuários precisam:

- Ver e interagir com o projeto em qualquer tamanho de tela, de forma adaptável.
- Identificar e interagir com os elementos em foco.
- Visualizar indicador de possível rolagem de tela.

## Captura de tela em uso

[<img src='./src/images/agencia-dula.gif' alt='Gif da Tela do Projeto Agência Dula'>](https://omarcerqueira.github.io/landing-page-com-grid-agencia-dula/)

## Tecnologias Utilizadas

- HTML
- CSS

### Desenvolvimento

- Marcação e semântica de HTML
- Propriedades customizadas de CSS
- Flexbox
- CSS Grid

### Aprendizado

Durante a contrução do projeto foi necessário, primeiramente, a análise do que poderia ser feito e de que forma seria feito. Desafios foram superados à proporção que o projeto ía tomando forma. Propriedades CSS como before e after foram aperfeiçoadas e utilizadas de forma a incrementar bastante o desenvolvimento. Assim como a flexbox e a css grid, que também foram utilizadas e aperfeiçoadas de forma à agregarem bastante ao conhecimento sobre a utilização dessa ferramenta. Outra técnica do css de extrema importância que foi utilizada e aprimorada foi a propriedade position.

### Como Utilizar

- Passe o mouse sobre o logotipo.
- Passe o mouse sobre o menu e clique em alguma opção. 
- Deslize com o mouse sobre as imagens dos projetos e veja a transformação acontecer.
- Clique em alguma sessão e vá direto pra ela.
- Escolha uma rede social e clique para ser direcionado até a página.

    - Trechos de código:

```html
<label for="menu-hamburguer">
                    <div class="menu">
                        <span class="hamburguer"></span>
                    </div>
                </label>
```
```html
<div class="item">
            <h3>Título</h3>

            <p>Lorem, ips </p>

            <a href="#" class="botao-saiba-mais">Saiba Mais</a>
        </div>
```
```html
<div class="project">
            <a href="#">
                <img src="./src/images/tomatoes.jpg" alt="Tomates">
            </a>
        </div>
```
```css
.projects .project a:hover img{
    opacity: 0.8;
    transform: scale(0.9);
    border-radius: 50px;
}
```
```css
.footer {
    grid-area: footer;
    background-color: aquamarine;
    display: flex;
    flex-direction: column;
    text-align: center;
    padding: 100px 0;
}
```

## Autor

- LinkedIn - [Omar Cerqueira](https://www.linkedin.com/in/omar-cerqueira-b83317226/)
- Github - [OmarCerqueira](https://github.com/OmarCerqueira)
- WhatsApp - 71 98201-1524

## Agradecimentos

Gratidão eterna ao pessoal do Dev em Dobro por me acompanhar nessa incrível jornada do mundo da tecnologia.

- Site - [Dev Quest](https://devemdobro.com)
- LinkedIn - [Dev em Dobro](https://www.linkedin.com/company/dev-em-dobro/)
- Discord - [Guilda Dev em Dobro](https://discord.com/channels/821364094878613524/821364094878613528)
- Github - [devemdobro](https://github.com/devemdobro)