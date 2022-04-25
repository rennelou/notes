_"When creating synthesizable code (RTL), you should write two types of code: behavioral RTL (leaf-level logic inference, sub-blocks) and structural code (blocks) -- each exclusively in its own architecture." - Xilinx_

Sempre pareceu poluído misturar instâncias de sub-blocos com descrição de [[rtl]].
Primeiro porque [[instâncias ocupam muitas linhas de código junto com a criação de muitos 'signals']], dificultando a leitura do código [[rtl]].
Ao mesmo tempo, o estilo misturado de código [[induz o 'designer' a acoplar conceitos pelo comodismo de criar um grande bloco que soluciona uma especificação do [[application domain]].
A xilinx recomenda separar em dois estilos de código: [[VHDL behavioral code style]] e [[VHDL structural code style]]

[[VHDL coding style]]