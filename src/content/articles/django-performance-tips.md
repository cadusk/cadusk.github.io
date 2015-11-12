Title: Django Performance tips
Date: 2010-12-03 10:20
Category: Hacking
Tags: Django, Performance
Authors: Carlos Cardoso

Encontrei este post com dicas simples de como melhorar a performance do seu
aplicativo desenvolvido com Django.

São dicas realmente objetivas e apesar de o artigo mencionar Django 1.6,
deve funcionar para versões posteriores sem problemas.

[Django performance post - by Frank Wiles](http://www.revsys.com/blog/2015/may/06/django-performance-simple-things/)

Dicas:
------

1. Persistent Data Connections
2. Template Loading
3. Django Sessions Optimization
4. select_related() and prefetch_related() methods

O objetivo principal é diminuir a quantitdade desnecessária de hops ao banco de
dados e sistema de arquivos usando mais cache e reaproveitamento de recursos em
memória.

Tenha certeza de utilizar essas dicas na hora de implementar um novo site
Django.
