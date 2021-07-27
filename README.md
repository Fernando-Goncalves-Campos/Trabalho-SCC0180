Fonte de tensão 3V-12V 100mA
============================
Explicação do trabalho
----------------------
Projeto de uma Fonte de Tensão ajustável entre 3V a 12V com capacidade de 100mA

Circuito feito no Falstad
-------------------------
![Captura de Tela (1)](https://user-images.githubusercontent.com/87579931/126045063-12144ff7-f878-428f-88e6-ecbaba2d2934.png)

### Link para o projeto no [Falstad](https://tinyurl.com/yeowb335)


Materiais utilizados na fonte
-----------------------------

| Componentes        | Função                | 
| -------------------|:---------------------:|
| Ponte de diodos    | Tranformar a corrente alternada em corrente contínua | 4 x [0.10](https://www.baudaeletronica.com.br/diodo-1n4007.html) = 0.40|
| Diodo Zener     | Manter a potência em 13V      | [0.09](https://www.baudaeletronica.com.br/diodo-zener-bzx55c-13v-0-5w.html)  |
| Resistores | Proteger outros componentes de receberem correntes muito altas e auxiliar na regulação da voltagem e da corrente que chega ao final|  
| Capacitor | Manter a potência do circuíto acima de um valor desejado evitando com que ela ocile entre 0 e o valor máximo |
| Transistor | Ligar 3 fios (fonte de corrente, fonte de tensão e saída) e auxiliar na regulação da saída | 
| Potenciometro | Permitir a mudança da potência final |
| Tranformador | Reduzir a tensão da rede para uma tensão que não seja danosa para os demais componentes |


Custo para a produção da fonte
------------------------------

| Peça    | Preço          |
|---------|----------------|
| Ponte de diodos | 4 x [R$0,09](https://www.baudaeletronica.com.br/diodo-1n4007.html) = R$0,36|
| Diodo Zener | [R$0,08](https://www.baudaeletronica.com.br/diodo-zener-bzx55c-13v-0-5w.html) |
|Resistor de 87Ω (36Ω + 51Ω)|  [R$0,05](https://www.baudaeletronica.com.br/resistor-36r-5-1-4w.html) + [R$0,05](https://www.baudaeletronica.com.br/resistor-51r-5-1-4w.html) = R$0,10| 
|Resistor de 560Ω| [R$0,05](https://www.baudaeletronica.com.br/resistor-560r-5-1-4w.html) | 
|Resistor de 2274Ω (18Ω + 56Ω + 2200Ω)| [R$0,05](https://www.baudaeletronica.com.br/resistor-18r-5-1-4w.html) + [R$0,05](https://www.baudaeletronica.com.br/resistor-56r-5-1-4w.html) + [R$0,05](https://www.baudaeletronica.com.br/resistor-2k2-5-1-4w.html) = R$0,15| 
|Capacitor | [R$0,41](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-25v.html) |
|Transistor | [R$0,14](https://www.baudaeletronica.com.br/transistor-npn-bc817-smd.html) |
|Potenciometro | [R$1,99](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html) |
|Transformador | [R$10,90](https://www.casasbahia.com.br/transformador-12-12vac-70ma-8034-hayonik-1502002061/p/1502002061?utm_medium=Cpc&utm_source=google_freelisting&IdSku=1502002061&idLojista=19709) |
|Total | R$14,18 |


Projeto no Eagle
----------------

### Schematic
![Captura de Tela (75)](https://user-images.githubusercontent.com/87579931/126046275-5aec4878-94b7-4436-8784-32f443e190cf.png)

### PCB
![Captura de Tela (76)](https://user-images.githubusercontent.com/87579931/127191377-c511acb4-1fff-48a8-b285-e3c022e1df3d.png)

Vídeo explicando a fonte
------------------------
[Link](https://drive.google.com/file/d/1hAxHXjWOhURsR3___K-J_CEMgJh5acg8/view?usp=sharing)
