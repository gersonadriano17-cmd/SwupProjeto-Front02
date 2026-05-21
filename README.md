# Swup — Transições de Página

Projeto feito para explorar o [Swup](https://swup.js.org), uma biblioteca JavaScript que adiciona transições animadas entre páginas de forma simples e sem frameworks.

---

## Por que o Swup?

Navegar entre páginas normalmente causa aquele flash branco sem graça. O Swup resolve isso substituindo o conteúdo da página com animações CSS, dando uma sensação de aplicação moderna sem precisar de React ou Vue.

Vale muito a pena dar uma olhada: **[swup.js.org](https://swup.js.org)**

---

## O que tem no projeto

- Duas páginas com navegação animada entre elas
- Transição com fade + deslizamento vertical
- Implementação mínima — menos de 5 linhas de JavaScript
- CSS comentado com uma segunda animação de overlay pronta pra testar

---

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## Como rodar

Abra o `index.html` em um servidor local. Por causa do `import` do Swup, não funciona abrindo o arquivo direto no navegador — use a extensão **Live Server** no VS Code.

---

## Como funciona em 3 linhas

```js
import Swup from 'https://unpkg.com/swup@4?module';
const swup = new Swup();
// pronto. o resto é CSS.
```

O Swup detecta os links da página, intercepta a navegação e aplica as classes `is-animating`, `is-leaving` e `is-rendering` no `<html>` — você só precisa estilizar essas classes no CSS.

---

## Autor

Gerson Adriano — [gersonadriano17@gmail.com](mailto:gersonadriano17@gmail.com)
