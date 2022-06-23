Passagem de dados com handshake, sinais de valid e ready. O bom uso é em filas onde o dado só é enviado para frente

Ação esperada, sinais de start e done. 

Start, sinal de start que incia uma serie de operações numa maquina de estados. A maquina de estado somente ler o sinal de start quando estiver no estado inicial. E somente sai do estado incial quando chega um pulso de start