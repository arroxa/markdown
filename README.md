<p align="center"><img width="100px" src="https://github.com/arroxa/grunt/raw/master/src/img/icon_arroxa.png" alt="logo arroxa"></p>

# Arroxa com Markdown
[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](http://thompsonemerson.mit-license.org/)

# Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

```
H1
======

H2
------
```

H1
======

H2
------


***


# Ênfases
```
itálico, com *asteriscos* ou _sublinhados_.

Negrito, com **asteriscos** ou __sublinhados__.

Tachado com ~~tiles~~.

Combinando ênfases com **asteriscos, _sublinhados_ e ~~tiles~~**.
```

itálico, com *asteriscos* ou _sublinhados_.

Negrito, com **asteriscos** ou __sublinhados__.

Tachado com ~~tiles~~.

Combinando ênfases com **asteriscos, _sublinhados_ e ~~tiles~~**.


***


# Lista

```
1. Lista de itens ordenadas
2. item
  1. sub-item ordenado
3. item
  * sub-item não ordenado
    * sub-item de um sub-item
4. item.
```

1. Lista de itens ordenadas
2. item
  1. sub-item ordenado
3. item
  * sub-item não ordenado
    * sub-item de um sub-item
4. item.

```
* Lista não ordenada usando asteriscos
- sinal menos
+ ou sinal de mais
```

* Lista não ordenada usando asteriscos
- sinal menos
+ ou sinal de mais


***


# Links
```
[eu sou um link](https://github.com/arroxa)

[link com titulo/title](https://github.com/arroxa "Arroxa")

URLs em colchetes automaticamente são transformadas em links https://github.com/arroxa ou <https://github.com/arroxa>
```

[eu sou um link](https://github.com/arroxa)

[link com titulo/title](https://github.com/arroxa "Arroxa")

URLs em colchetes automaticamente são transformadas em links https://github.com/arroxa ou <https://github.com/arroxa>


***


# Blockquotes
```
> São blocos bastantes utilizados para da um diferencial ou chamar atenção.

> Quebrei a linha e aproveito pra dizer que também podemos usar textos *itálicos*, **negitos** ou até mesmo ~~riscados/tachados~~ :wink:.
```

> São blocos bastantes utilizados para da um diferencial ou chamar atenção.

> Quebrei a linha e aproveito pra dizer que também podemos usar textos *itálicos*, **negitos** ou até mesmo ~~riscados/tachados~~ :wink:.


***


# Imagens
```
Inline:
![texto alt](https://avatars1.githubusercontent.com/u/17159828?v=3&s=80 "Logo Arroxa")

Referência:
![texto alt][logo]

[logo]: https://avatars1.githubusercontent.com/u/17159828?v=3&s=80 "Logo Arroxa"
```

Inline:
![texto alt](https://avatars1.githubusercontent.com/u/17159828?v=3&s=80 "Logo Arroxa")

Referência:
![texto alt][logo]

[logo]: https://avatars1.githubusercontent.com/u/17159828?v=3&s=80 "Logo Arroxa"


***


# Códigos & Destacados
```
`códigos` inline tem usa-se `backticks em torno`.
```
`códigos` inline tem usa-se `backticks em torno`.
***

```
  ` ` ` javascript
  function arroxa(a, b){
    console.log(a + b);
  }
  arroxa(10, 10);
  ` ` `
```
```javascript
function arroxa(a, b){
  console.log(a + b);
}
arroxa(10, 10);
```
***

```
  ` ` ` css
  .arroxa {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  ` ` `
```
```css
.arroxa {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
```
***

```
  ` ` ` html
  <header>
    <h1>Arroxa</a>
    <nav>
      <a href="#" title="">link 1</a>
      <a href="#" title="">link 2</a>
      <a href="#" title="">link 3</a>
    </nav>
  </header>
  ` ` `
```
```html
<header>
  <h1>Arroxa</a>
  <nav>
    <a href="#" title="">link 1</a>
    <a href="#" title="">link 2</a>
    <a href="#" title="">link 3</a>
  </nav>
</header>
```
***

```
  ` ` `
  quando nenhuma linguagem é indicadas não destaque de sintaxe. :/
  ` ` `
```
```
quando nenhuma linguagem é indicadas não destaque de sintaxe. :/
```

***

# Tabelas

Nas tabelas podemos usar dois pontos para alinhas colunhas.
```
| Esquerda    | Centro     | Direita    |
| ----------- |:----------:| ----------:|
| texto       | texto      | texto      |
| texto       | texto      | texto      |
```

| Esquerda    | Centro     | Direita    |
| ----------- |:----------:| ----------:|
| texto       | texto      | texto      |
| texto       | texto      | texto      |

É necessário pelo menos 3 traços para que haja um cabeçalho. Também não é obrigado ter as barras de fora, o negocio pode ficar feio mesmo.
E por fim, você também pode usar Markdown dentro da tabela.

```
Itálico | Negrito | Tachado
--- | --- | ---
*texto* | **texto** | ~~texto~~
```

Itálico | Negrito | Tachado
--- | --- | ---
*texto* | **texto** | ~~texto~~


***


# Linhas

Para definir uma linha precisamos ter três ou mais...

```
---
```
---

Hífens

```
***
```
***

Asteriscos

```
___
```
___

Sublinhados


***


# HTML Inline

O bacana do Markdown é que também podemos usar `tags html`
```
<p align="center">
  texto centralizado
</p>
```
<p align="center">
  texto centralizado
</p>


<br>
***
<br>

#### Para saber mais sobre Markdown
Link da [Documentação](https://daringfireball.net/projects/markdown/)
