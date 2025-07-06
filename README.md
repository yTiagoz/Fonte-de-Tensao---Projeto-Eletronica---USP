## Fonte-de-Tensao---Projeto-Eletronica---USP

## Projeto realizado para a disciplina de Eletronica



## Objetivo

Construir uma fonte de tensão ajustável entre 3V - 12V com capacidade de 100mA


## Componentes utilizados

Quantidade | Componentes | Custo R$
--- | --- | ---
1 | Ponte de Diodos | R$3.90
1 | Capacitor | R$1.00
1 | Diodo Zener | R$0.50
1 | Potenciômetro | R$7.00
1 | Transistor | R$0.50
1 | Resistor 5W 100R | R$1.90
4 | Resistores | R$0.28


## Função de cada componente utilizado

* Ponte de diodo: Transforma a corrente de alternada, com frequência de 60Hz, para corrente contínua, com 120Hz, por meio de 4 diodos, sendo o diodo um componente que permite a passagem de corrente para apenas uma direção.  

* Capacitor: Componente que armazena energia elétrica, liberando corrente quando a tensão da fonte é menor que a tensão interna. Serve como capacitor de filtragem no projeto, suavizando as variações de tensão.

* Diodo Zener: Seu funcionamento é semelhante ao do diodo comum, no entanto, permite a passagem de corrente até certo ponto. Responsável por controlar a tensão máxima.

* Resistores: Presentes em todo o circuito para limitar a corrente e evitar danos aos dispositivos.

* Potenciômetro: Serve para regular a tensão da fonte, que varia entre 3V e 12V.

* Transistor: Amplifica a corrente pequena que chega à sua base para uma corrente máxima de 100mA, atuando como uma parte final do circuito.

## Imagem do circuito
![image](https://github.com/user-attachments/assets/6c96fd4a-c17d-491f-af33-f593f55da168)


## Cálculo do capacitor

Vfonte = 127 x raiz(2) = 179,6V => Tensão máxima =~ 180V
Razão do transformador = 7 => 180/7 = 25,71V (Tensão de Pico 1)
Vdiodo = 0,7V => Tensão de Pico 2 = (Tensão de Pico 1) - 0,7 x 2 = 24,31V

Buscando um Ripple de 10%:
Ripple = Vpico x 0,1 = 2,431 V

Capacitor
f = 2 x 60Hz = 120Hz
C = i/f x Ripple => C = 0,115/(120 x 2,431) => Capacitância mínima para o circuito é de 394,21 uF



## Link do circuito no Falstad
[Link Falstad](https://tinyurl.com/29j4x7qe)


## PCB da Fonte
![image](https://github.com/user-attachments/assets/42262ae2-c2b7-4f5b-a95d-58f3422a1c0e)




## Vídeo de explicação YT
[Link YT](https://youtube.com/shorts/zovsuaQ34ok?feature=share)


[Explicando o projeto](https://www.youtube.com/watch?v=4OP18t41a2M&ab_channel=LeonardoBiondoBertho)



## Alunos
### Tiago Kenzo Ogawa
### Leonardo Biondo Bertho
### Matheus Araujo Alves
