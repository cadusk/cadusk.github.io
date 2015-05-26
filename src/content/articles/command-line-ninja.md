Title: Command Line Ninja
Date: 2015-05-25 21:32
Category: Shell
Tags: Command Line, History
Authors: Carlos Cardoso

Este artigo ensina o básico da linha de comando, e dá dicas de produtividade
com ferramentas e teclas de atalho que libertam o poder da linha de comando em
suas mãos.

[Artigo
original](http://lifehacker.com/5743814/become-a-command-line-ninja-with-these-time-saving-shortcuts)

Atalhos básicos
===============

- **setas para cima/baixo**: navega pelos últimos comandos registrados no seu
  histórico. Você ainda pode editar o comando selecionado antes de executá-lo
  novamente.

- **Ctrl+esquerda e Ctrl+direita**: permite navegar para frente e para trás
  pelos argumentos/parametros da linha de comando, tornando fácil alcançar um
  parametro que precisa ser modificado.

- **Ctrl+A e Ctrl+E**: pula para o início ou final da linha de comando.

- **Ctrl+U**: limpa completamente a linha de comando para que se possa começar
  do zero.

- **Ctrl+K**: limpa a linha a partir da posição do cursor até o final.

- **Ctrl+W**: apaga palavras para trás da posição do cursor.

- **Ctrl+R**: esse atalho abre um prompt que permite pesquisar o histórico de
  comandos. Por exemplo, para recuperar a linha de comando utilizada para
  imprimir a data atual do sistema, vc pode tentar a combinação "Ctrl+R date".
  Daí pra frente basta navegar com as setas para cima e para baixo para ver
  todas as opções de comandos que contém o texto 'date'.

- **Tab**: expande comandos ou argumentos. Por exemplo, vc pode digitas
  o comando `cd ~/Des` e pressionar tab para que o nome do diretório seja
  expandido para você, com o comando pronto para ser confirmado: `cd
  ~/Desktop`.

Usando seu histórico de forma inteligente
=========================================

- **`!!`**: repete o último comando executado. Diferente de navegar pelas
  setas, o `!!` é substituído na sua linha de comando pelo último comando
  digitado, assim, imagine o seguinte cenário: vc tenta executar um comando que
  acaba resultando em problema por falta de permissão `apt-get update`. Para
  executá-lo novamente com privilégios de super usuário basta `sudo !!` e BAM!

- **`!$`**: reaproveitar os parametros do último comando também é um sacrifício
  para quem não conhece o `!$`. Imagine que você precisa criar uma nova pasta
  e imediatamente entrar nela. Com `mkdir /tmp/uma/nova/pasta` e em seguida vc
  pode simplesmente usar `cd !$` para reutilizar no comando `cd` os parametros
  do comando `mkdir` utilizado anteriormente.

Conclusão
========

Existem muitas outras ferramentas, como expansions, replacements e aliases que
podem tornar sua vida muito mais fácil com suas tarefas diárias na frente da
"telinha preta".

De uma olhada no artigo original, com o link lá no começo do post, para
conhecer mais detalhes quando já estiver craque com os básicos.

Boa sorte
