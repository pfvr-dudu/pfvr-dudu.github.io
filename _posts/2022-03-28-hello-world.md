---
layout: post
title: Hello World
subtitle: Afinal, tudo precisa começar por algum lugar
gh-repo: ens.rolim/pfvr-dudu
gh-badge: [star, fork, follow]
tags: [Teste, Hello World]
comments: true
---

Este é um post demo para documentar como escrever posts usando Markdown. Ele também serve como mural de como as funcionalidades funcionam com o Tema. Não pretendo excluir esse arquivo, pois ele é muito útil pra mim no processo de montar as postagens. :+1: :+1: :+1: :octocat:

**Texto Negrito**, *Texto Itálico*, ~Riscado~, `Código` e ``Código com uma ` no meio``

> Bloco de texto
>
> Com várias linhas

## Título 2

Uma tabela inútil (mas não tão inútil assim):

| Número | Próximo número | Número anterior |
| :----- |:---: | ---: |
| Cinco | Seis | Quatro |
| Dez | Onze | Nove |
| Sete | Oito | Seis |
| Dois | Três | Um |

---
...
<< e >>

Listas Ordenadas:

1. Primeiro elemento
2. Segundo elemento
1. Terceiro elemento
1. Quarto elemento

Listas não Ordenadas:

+ Primeiro elemento
* Segundo elemento
- Terceiro elemento
+ Quarto elemento

Curte um crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

E um crepe centralizado?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Um pedaço de código-fonte:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

E aqui com o realce de código ativado:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

E aqui o mesmo código com linhas habilitadas:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Caixinhas
Existe também a opção de se adicionar caixas de notificação, avisos e error, assim:

### Notificação

{: .box-note}
**Nota:** Esta é uma caixa de notificação.

### Aviso

{: .box-warning}
**Warning:** Essa é uma caixa de avisos.

### Erro

{: .box-error}
**Error:** Esta é uma caixa de erro!
