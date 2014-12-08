Version mat�rielle 1.2
======================

Modifications
-------------
Cette version reprend toutes les caract�ristiques de la version [initiale][1] en y ajoutant les fonctionnalit�s suivantes :

- Ajout d'un contr�leur d'entr�es sortie I2C [MCP23017][10] pour lib�rer les I/O du Spark Core
- Possibilit� de mettre deux types de relais dont un [avec contact NO + NF][5]
- Possibilit� de mettre un emetteur r�cepteur sans fil de type [RFM12B][6], [RFM69CW][7], [RFM69HW][8] ou [RFM69CW][9] 433Mhz ou 868MHz
- Possibilit� de mettre un [r�cepteur 433MHz][4] pour r�cup�rer par exemple les trames des capteurs de temp�rature Or�gon Scientific
- Ajout d'un connecteur I2C ET SPI pour des afficheurs OLED de type [I2C][2] ou [SPI][3]
- Ajout d'un connecteur de type Grove I2C
- Ajout d'une LED 3mm (d�portable ou non) sur le boitier 
- Ajout de pin out disponibles sur toutes les pattes du Spark Core

Description D�taill�e
=====================

**Schematic**  
![schematic](https://raw.github.com/thibdct/programmateur-fil-pilote-wifi/master/Mat%C3%A9riel/1.2/ProgrammateurFilPilote_1.2_Schematic.png)


**Boards**  
<img src="https://raw.github.com/thibdct/programmateur-fil-pilote-wifi/master/Mat%C3%A9riel/1.2/ProgrammateurFilPilote_1.2_Board.png" alt="board" width="30%" height="30%">&nbsp;
<img src="https://raw.github.com/thibdct/programmateur-fil-pilote-wifi/master/Mat%C3%A9riel/1.2/ProgrammateurFilPilote_1.2_Recto.png" alt="top" width="30%" height="30%">&nbsp;
<img src="https://raw.github.com/thibdct/programmateur-fil-pilote-wifi/master/Mat%C3%A9riel/1.2/ProgrammateurFilPilote_1.2_Verso.png" alt="bottom" width="30%" height="30%">


[1]: https://github.com/thibdct/programmateur-fil-pilote-wifi/blob/master/README.md
[2]: http://www.ebay.com/itm/291216700457
[3]: http://www.ebay.com/itm/141371873602
[4]: http://www.ebay.com/itm/290935235157
[5]: http://www.seeedstudio.com/depot/index.php?main_page=opl_info&opl_id=136

[6]: http://www.anarduino.com/details.jsp?pid=142
[7]: http://www.anarduino.com/details.jsp?pid=145
[8]: http://www.anarduino.com/details.jsp?pid=136
[9]: http://www.anarduino.com/details.jsp?pid=122
[10]: http://www.adafruit.com/product/732

