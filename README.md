# Frontend Mentor - Solução do perfil de links sociais

Esta é uma solução para o [desafio do perfil de links sociais no Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

## Sumário

- [Visão Geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Autor](#autor)

## Visão Geral

### O desafio

Os usuários devem ser capazes de:
- Visualizar estados de hover (passar o mouse) e foco em todos os elementos interativos da página.
- Ver um layout responsivo que se adapta a diferentes tamanhos de tela.

### Screenshot
DESKTOP
![Screenshot da minha solução desktop](/assets/images/social-links-profile-frontend-mento.vercel.app_.png)

MOBILE
![Screenshot da minha solução mobile](/assets/images/social-links-profile-frontend-mento.vercel.app_(iPhone%2014%20Pro%20Max).png)


### Links

- URL da Solução: [https://github.com/JenniferEvan/Social-Links-Profile---Frontend-Mentor](https://github.com/JenniferEvan/Social-Links-Profile---Frontend-Mentor)
- URL do Site ao Vivo: [https://social-links-profile-frontend-mento.vercel.app/](https://social-links-profile-frontend-mento.vercel.app/)

## Meu processo

### Construído com

- Marcação HTML5 Semântica
- Propriedades personalizadas de CSS (Variáveis)
- Flexbox para centralização e layout do card
- Importação de fontes locais com @font-face

### O que eu aprendi

Neste projeto, foquei em organizar o CSS utilizando variáveis no `:root` para garantir a consistência das cores do guia de estilo. Também aprendi a transformar links de lista em botões clicáveis de largura total usando `display: block`.

Exemplo de código que gostei de fazer:

```css
/* Organização das cores com variáveis CSS */
:root {
  --green: hsl(75, 94%, 57%);
  --grey-700: hsl(0, 0%, 20%);
  --grey-800: hsl(0, 0%, 12%);
}

/* Transformando o link em um botão que ocupa todo o espaço */
.menus ul li a {
    display: block;
    text-align: center;
    background-color: var(--grey-700);
    transition: 0.3s;
}

Desenvolvimento contínuo
Pretendo continuar explorando o uso de Flexbox e Grid para layouts mais complexos e aprimorar meus conhecimentos em acessibilidade web.

## Autor
- GitHub: [Jennifer Evangelista](https://github.com/JenniferEvan)
- Frontend Mentor: [@JenniferEvan](https://www.frontendmentor.io/profile/JenniferEvan)