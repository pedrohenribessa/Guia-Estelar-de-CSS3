# Combinators

Combinadores, pois eles trabalham para buscar e combinar seletores a fim de aplicar uma estilização

## Descendant combinator

* Identificado por um espeço entre os seletores
* Busca um elemento dentro de outro

```css
body artcle h2
```

## Child combinator

* Identificado pelo sinal `>` entre dos seletores
* Seleciona somente o elemento que é filho direto do pai
* Elementos depois do filho direto serão desconsiderados

```css
body > ul > li
```

## Adjet sibling combinator

* Identificado pelo sinal `+` entre dois seletores
* Seleciona somente o elemento do lado direto que é irmão direto na hierarquia

```css
h1 + p
```

## General sibling combinator

* Identificado pelo sinal `~` entre dois seletores
* Seleciona todos os elementos irmãos

```css
h1 ~ p
```

## Utilizando combinadores

```css
ul > li[class="red"]
```

## Dica

* Seletores muito específicos tendem a causar dificuldades no reuso das regras de estilização dos elementos
* Muitas vezes, um simples uso de classes, torna o trabalho muito mais eficiente.