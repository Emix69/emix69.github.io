---
layout: post
title:  "Come fare post in Markdown"
date:   2018-12-18
desc: "Piccola Guida per scrivere post in Markdown"
keywords: "Jalpc,Jekyll,gh-pages,website,blog,easy"
categories: [Guide]
tags: [Guide,Markdown,Jekyll]
icon: icon-html
---

Jekyll implemente nativamente il linguaggio di markup denominato [markdown](http://markdowntutorial.com/), puoi scrivere comodamente i tuoi posts sfruttando la semplicità di markdown ([ti consiglio di perdere cinque minuti con questo breve tutorial](http://markdowntutorial.com/)).

Puoi dare direttamente un occhio anche [guida](https://guides.github.com/features/mastering-markdown/) fornita da GitHub! 

Ah, volendo puoi scrivere anche in HTML, Jekyll lo supporta benissimo.

Ti faccio qualche esempio, bisogna solamente imparare a utilizzare un po' di caratteri _strani_:

**Due asterischi all'inzio e alla fine per scrivere in grassetto**

## Puoi creare paragrafi sfruttando due hashtag 

Creare una tabella è molto semplice, utilizza le sbarrette

| Numero | Prossimo numero | Numero precedente |
| :------ |:--- | :--- |
| Cinque | Sei | Quattro |
| Dieci | Undici | Nove |
| Sette | Otto | Sei |
| Due | Tre | Uno |


Piccola pausa? In effetti abbiamo lavorato tanto, ce la meritiamo.

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Spero ti sia piacuta,ecco un po' di codice:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Umh ... un po' brutto, forse meglio evidenziarlo:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

## Boxes
Ecco come aggiungere alcuni box

### Notification

{: .box-note}
**Note:** Questa è una semplice notifica.

### Warning

{: .box-warning}
**Warning:** Un piccolo "spoiler".

### Error

{: .box-error}
**Error:** Qua mi sa che c'è qualche errore.

PS: ci sono le [emoji](https://www.webfx.com/tools/emoji-cheat-sheet/) 
