Fonte de tensão 3V-12V 100mA
============================
Explicação do trabalho
----------------------
Projeto de uma Fonte de Tensão ajustável entre 3V a 12V com capacidade de 100mA

Circuito feito no falstad
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
| Ponte de diodos | 4 x [0.10](https://www.baudaeletronica.com.br/diodo-1n4007.html) = 0.40|
| Diodo Zener | [0.09](https://www.baudaeletronica.com.br/diodo-zener-bzx55c-13v-0-5w.html) |
|Resistor de 87Ω (36Ω + 51Ω)|  [0.06](https://www.baudaeletronica.com.br/resistor-36r-5-1-4w.html) + [0.06](https://www.baudaeletronica.com.br/resistor-51r-5-1-4w.html) = 0.12| 
|Resistor de 560Ω| [0.06](https://www.baudaeletronica.com.br/resistor-560r-5-1-4w.html) | 
|Resistor de 2274Ω (18Ω + 56Ω + 2200Ω)| [0.06](https://www.baudaeletronica.com.br/resistor-18r-5-1-4w.html) + [0.06](https://www.baudaeletronica.com.br/resistor-56r-5-1-4w.html) + [0.06](https://www.baudaeletronica.com.br/resistor-2k2-5-1-4w.html) = 0.18| 
|Capacitor | [0.43](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-25v.html) |
