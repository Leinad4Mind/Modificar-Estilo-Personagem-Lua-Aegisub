Modificar-Estilo-Personagem-Lua-Aegisub
=======================================

Um simples lua que permite de forma automática alterar o estilo de determinado personagem, sem ter que o fazer manualmente.
Caso contrário teria de fazer uma selecção pelo personagem ou pelo estilo e depois alterar.


Por fazer
-----------------
* Creio que já está tudo feito, mas estarei disposto a melhorar se houver dicas para tal.


Como instalar
--------------

Load Automático

1. Transferir modificar_estilo_personagem.lua
2. Colocar esse ficheiro na pasta _autoload_ situada dentro da pasta _automation_ que por sua vez está presenta na sua pasta de instalação do aegisub


Load Manual

1. Transferir modificar_estilo_personagem.lua e guarde-o onde bem desejar
2. Com o Aegisub aberto, quando desejar usá-lo terá de clicar em Automatização -> Automatização...
3. Clicar de seguida em _Adicionar_ e ir ao local onde se encontra o modificar_estilo_personagem.lua


Como usar
---------

A primeira janela dessa macro, permite-nos de forma simples ver todos os estilos que temos, e escolhemos o estilo que pretendemos.
Na caixa de texto em baixo, serve apenas para escrever o tal estilo que escolhemos na listagem. Depois de escrever seleciona-se esse texto e copia-se.
Ora este passo apenas serve caso não saibamos de cor o estilo ou como escrevê-lo. Apenas para isso, caso saibamos de cor, podemos fazer logo "OK".
Portanto só serve de ajuda.

A 2º Janela é a mais importante, na caixa de texto coloca-se o texto copiado da 1º, ou escreve-se o estilo caso saibamos de cor.
Seleccionamos também o Personagem que vamos alterar o estilo. Clicamos depois em "Modificar" e todas as linhas daquele personagem irão ficar com o estilo escolhido.
