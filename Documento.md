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

-   Usar tags semânticas: header, main, section, article, footer
-   Sempre usar alt em imagens
-   Manter identação organizada
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
    margin: 0;   /* Espaço externo */
    padding: 0;  /* Espaço interno */
}

.caixa {
    width: 200px;
    height: 100px;
    border: 1px solid black; /* Borda */
    border-radius: 8px;      /* Cantos arredondados */
}
```

## Flexbox

``` css
.container {
    display: flex;
    justify-content: center; /* Alinha no eixo principal (horizontal por padrão) */
    align-items: center;     /* Alinha no eixo transversal (vertical por padrão) */
    gap: 10px;               /* Espaçamento entre os itens */
}
```

## Grid

``` css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Duas colunas com tamanhos iguais */
    gap: 20px;
}
```

## Variáveis CSS

``` css
:root {
    --cor-primaria: #0056b3;
}

.botao {
    background-color: var(--cor-primaria);
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
## Estruturas de Dados

``` javascript
// Arrays (Listas)
const frutas = ["Maçã", "Banana", "Laranja"];
console.log(frutas[0]); // Maçã

// Objetos
const usuario = {
    nome: "Bruno",
    time: "Grêmio",
    ativo: true
};
console.log(usuario.time); // Grêmio
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

- GET: Buscar/Ler dados.
- POST: Enviar dados.
- PUT; Editar/Atualizar dados.
- DELETE: Deletar dados.

------------------------------------------------------------------------

# Conclusão

Eu te amo Grêmio
