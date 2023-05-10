<h1 align="center">Objetivo</h1>
  <p>O objetivo deste projeto foi construir um botão com a funcionaldiade "ler mais" e "ler menos" para realizar as ações que o próprio nome sugere. Neste projeto é possível visualizar 10 linhas de parágrafos, mas mostramos apenas 5. Se você clicar para <b>ler mais</b> poderá ver o conteúdo completo e o conteúdo suspenso; quando clicar em <b>ler menos</b> verá o texto fechado e apenas 5 linhas do parágrafo.</p>
<br>  
<h3 align="center">Sobre o código</h3>
  <p>Toda funcionalidade através do Javascript foi estruturada inteiramente com o uso do DOM (Document Object Model) como é possível perceber no fragmento do documento index.js abaixo:</p>
  
  ```
  const readMoreBtn = document.querySelector(".read-more-btn");
  const text = document.querySelector(".text");
  ```
  <li>No código acima podemos perceber a manipulação dos seletores através  do <code>document.querySelector</code>. Neste primeiro momento armazenamos em nossas variáveis os valores dos especificados seletores. Saiba um pouco mais sobre <b>.querySelector( )</b> através da documentação da <a href="https://developer.mozilla.org/pt-BR/docs/Web/API/Document/querySelector">mdn.</a></li>
