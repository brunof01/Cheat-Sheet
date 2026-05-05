### Bruno Eduardo Fortes
# Cheat Sheet de HTML, CSS e JavaScript!
# Tópicos

- HTML
- CSS
- JavaScript

## Para que serve esse documento?

Documento para referencias e curiosidades sobre os conceitos, sintaxes e boas práticas de **HTML, CSS e JavaScript**.

# HTML

## Estrutura básica

``` html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <h1>Olá mundo!</h1>
</body>
</html>
```

## Tags mais usadas

### Texto e estrutura

``` html
<div>: Container genérico para agrupar elementos (bloco).
<span>: Container genérico para elementos de linha (inline).
<h1> a <h6>: Títulos, sendo <h1> o mais importante.
<p>: Parágrafos de texto.
<a href="...">: Links (âncoras).
<img src="..." alt="...">: Imagens (sempre use o atributo alt para acessibilidade).
<form>, <input>, <button>, <label>: Elementos de formulário.
```

### Links e imagens

``` html
<a href="https://google.com">Ir para o Google</a>
<img src="imagem.jpg" alt="Descrição da imagem">
```

### Formulários

``` html
<form>
    <input type="text" placeholder="Digite algo">
    <input type="email">
    <button type="submit">Enviar</button>
</form>
```

## Boas práticas HTML

-   Usar tags semânticas: header, main, section, article, footer\
-   Sempre usar alt em imagens\
-   Manter identação organizada\
-   Evitar excesso de div

------------------------------------------------------------------------

# CSS

## Seletores

``` css
p { color: red; }
.minha-classe { color: blue; }
#meu-id { color: green; }
div > p { color: purple; }
```

## Propriedades essenciais

``` css
body {
    color: #333;
    font-size: 16px;
    margin: 0;
    padding: 0;
}
```

## Flexbox

``` css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

## Grid

``` css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
```

## Boas práticas CSS

-   Evitar !important\
-   Preferir classes\
-   Usar mobile-first

------------------------------------------------------------------------

# JavaScript

## Variáveis

``` javascript
let nome = "João";
const idade = 25;
```

## Funções

``` javascript
function soma(a, b) {
    return a + b;
}
```

## DOM

``` javascript
const titulo = document.querySelector("h1");
titulo.textContent = "Novo título";
```

## Evento

``` javascript
document.querySelector("button").addEventListener("click", () => {
    alert("Clicou!");
});
```

------------------------------------------------------------------------

# Outros

## Cache

``` javascript
localStorage.setItem("nome", "Bruno");
```

## HTTP

GET, POST, PUT, DELETE

------------------------------------------------------------------------

# Conclusão

Eu te amo Grêmio
