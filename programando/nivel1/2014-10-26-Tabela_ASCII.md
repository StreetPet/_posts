---
permalink: /ascii/
title: Tabela ASCII
categories: [logicadeprogramacao]
excerpt: O nome ascii é a breviação para American Standard Code for Information Interchange, foi criada com base no idioma inglês e foi codificada sobre 7 bits, sendo 128 códigos existêntes inicialmente.
layout: article
tags: [ascii, Tabela ascii, Arduino, Linguagem,  C, C++, Programação]
share: true
toc: true
feature:
 index: true
 category: true
comments: true
ads: 
 show: true
tagcloud: true
coinbase:
  show: true
---

A tabela possui em seu formato original, caractéres codificados como números de 0 a 9, letras de a até z
minúsculas e maiúsculas, simbolos de pontuação básicos comumente usados, códigos de controle, usados até 
hoje em impressores matriciais, criados na época dos teletipos, além de espaço.

Como dito a tabela foi criada para uso com teletipos e seu primeiro uso data de 6 de outubro de 1960.
Sendo o primeira versão do padrão lançado em 1963, a maior revisão foi em 1967, e a mais atual revisão
em 1986, atualmente utilizamos uma versão de 256 bytes, acrescida de caracteres utilizados em outros 
idiomas em especial de origem latina.

A tabela ascii atualmente somente peder em uso para a tabela de caracteres UTF-8 conhecido como Conjunto
de caracter UTF-8 (ou CharSet UTF-8).

Abaixo apresentamos a tabela básica, que de maior interesse para uso com o Arduino, e a seguir a extensão da tabela. 

## Porque Conhecer a Tabela ascii?

Conhecer a tabela ascii é fundamental para qualquer programador, e sem dúvida para o programador
que irá lidar com microcontrolador e com linguagens de baixo nível, aquelas linguagens que irão lidar
mais intimamente com bits e bytes.

O conhecimento da tabela ascii demonstra, intimidade com conceitos técnicos e fundamentais para tal 
atuação e permite o uso de padrões e facilidade de compreenção do protocolo adotado para comunicação
em seus equipamentos.

Além disso caso tais equipamentos venham a demandar comunicação com equipamentos de terceiros, sem dúvida
a adoção da tabela ascii para envio de controle e caracteres que irão compor informação serão fundamental
para a manutenção desta comunicação sem complicações e reinvenções desnecessárias.

## Conhecendo a Tabela
 
Inicialmente apresento a tabela indexa com números hexadecimais, e na segunda tabela com números décimais.

### Tabela indexada por números hexadecimal

|      | 0x00 | 0x01 | 0x02 | 0x03 | 0x04 | 0x05 | 0x06 | 0x07 | 0x08 | 0x09 | 0x0A | 0x0B | 0x0C | 0x0D | 0x0E | 0x0F |      | 
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | -----|
| 0x00 | [NUL](/ascii/000-null) | [SOH](/ascii/001-soh) | [STX](/ascii/002-stx) | [ETX](/ascii/003-etx) | [EOT](/ascii/004-eot) | [ENQ](/ascii/005-enq) | [ACK](/ascii/006-ack) | [BEL](/ascii/007-bel) | [BS](/ascii/008-bs)  | TAB | LF  | VT  | FF  | CR  | SO  | SI  | 0x0F | 
| 0x10 | DLE  | DC1  | DC2  | DC3  | DC4  | NAK  | SYN  | ETB  | CAN  | EM   | SUB  | ESC  | FS   | GS   | RS   | US   | 0x1F |
| 0x20 |      | !    | "    | #    | $    | %    | &    | '    | (    | )    | *    | +    | ,    | -    | .    | /    | 0x2F |
| 0x30 | 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | :    | ;    | <    | =    | >    | ?    | 0x3F |
| 0x40 | @    | A    | B    | C    | D    | E    | F    | G    | H    | I    | J    | K    | L    | M    | N    | O    | 0x4F |
| 0x50 | P    | Q    | R    | S    | T    | U    | V    | W    | X    | Y    | Z    | [    | \    | ]    | ^    | _    | 0x5F |
| 0x60 | `    | a    | b    | c    | d    | e    | f    | g    | h    | i    | j    | k    | l    | m    | n    | o    | 0x6F |
| 0x70 | p    | q    | r    | s    | t    | u    | v    | w    | x    | y    | z    | {    | \|   | }    | ~    |      | 0x7F |


### Tabela indexada por números decimal

|     | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 000 | NUL | SOH | STX | ETX | EOT | ENQ | ACK | BEL | BS  | TAB | 009 |
| 010 | LF  | VT  | FF  | CR  | SO  | SI  | DLE | DC1 | DC2 | DC3 | 019 |
| 020 | DC4 | NAK | SYN | ETB | CAN | EM  | SUB | ESC | FS  | GS  | 029 |
| 030 | RS  | US  |     | !   | "   | #   | $   | %   | &   | '   | 039 |
| 040 | (   | )   | *   | +   | ,   | -   | .   | /   | 0   | 1   | 049 |
| 050 | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | :   | ;   | 059 |
| 060 | <   | =   | >   | ?   | @   | A   | B   | C   | D   | E   | 069 |
| 070 | F   | G   | H   | I   | J   | K   | L   | M   | N   | O   | 079 |
| 080 | P   | Q   | R   | S   | T   | U   | V   | W   | X   | Y   | 089 |
| 090 | Z   | [   | \   | ]   | ^   | _   | `   | a   | b   | c   | 099 |
| 100 | d   | e   | f   | g   | h   | i   | j   | k   | l   | m   | 109 |
| 110 | n   | o   | p   | q   | r   | s   | t   | u   | v   | w   | 119 |
| 120  | x   | y   | z   | {   | \|  | }   | ~   |     |     |     | 129 |

## Tabela Extendida

A tabela ASCII em seu modelo original não atende a todos os idiomas, já que foi 
criada para o idioma Inglês, então para resolver esta cararência, foi criada o 
conceito de página de código.

Quem é do tempo do DOS, e inclusive UNIX e Xenix, deve se lembrar das configurações 
relativas á Code-Page, a mais usada no Brasil foi a 850.

Bem tais páginas de código definem como será composta a extensão da tabela ASCII, 
esta extensão são so codigos presentes nas posições 128 até 255.

Na imagens abaixo estão presente duas extensões, da tabela ASCII, usei imagens
devido o fato de alguns códigos não serem possíveis reproduzir no navegador. As 
extensões abaixo são para a ANSI e OEM.

#### A TAbela ASCII OEM

A tabela abaixo foi criada para uso com terminais físicos, e somente foi usado 
no DOS, veja que ela é composta além de acentos por simbolos capazes de montar 
paineis na tela, simulando asim janelas, ou agrupamentos de informações.
<figure>
<img src="{{ site.url }}/images/logica_programacao/ascii_oem-500x290.gif" />
<figcaption>Extensão da Tabela ASCII OEM</figcaption>
</figure>

#### A Tabela ASCII ANSI

A tabela ANSI extende a tabela ASCII de forma mais focado nos caracteres, atendendo
um maior número de linguagens, foi amplamente adotada nas primeiras versões do
MS Windows, e também pelas diversas versões Unix, incluindo Xenix e o atual Linux.
<figure>
<img src="{{ site.url }}/images/logica_programacao/ascii_ansi-500x289.gif" />
<figcaption>Extensão da Tabela ASCII ANSI</figcaption>
</figure>


<a href="/cursoarduino/" class="btn-success">Este trabalho é mantido com os cursos oferecidos no <br />
Curso Arduino Minas!</a>
