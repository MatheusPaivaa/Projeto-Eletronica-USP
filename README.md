# Projeto de uma Fonte de Tensão Ajustável 🔋🔌
Desenvolvido para a disciplina Eletônica para Computação - SSC0180.

## Situação Inicial:

   Construção de uma fonte retificadora que consiga transformar corrente alternada (A/C) de 127V em corrente contínua (D/C). Além disso, deve ser possível ajustar a sua tensão em uma faixa de 3V até 12V, com capacidade de 100mA. 

**Fonte de Tensão (Tomada)** = Tensão AC de 127V, operando a uma frequência de 60Hz. 

## Componentes:

- **Chave:** A chave é um componente elétrico que permite controlar o fluxo de corrente em um circuito. Neste caso, a chave será utilizada para ligar e desligar a fonte de tensão ajustável.

- **Fusível:** O fusível é um dispositivo de segurança que protege o circuito contra correntes excessivas. Ele é projetado para queimar e interromper o fluxo de corrente caso haja uma sobrecarga, evitando danos ao circuito e prevenindo possíveis curtos-circuitos.

- **Transformador:**  O transformador é um dispositivo que permite ajustar a tensão de entrada para uma tensão desejada na saída. Neste caso, o transformador será utilizado para converter a tensão de entrada (da rede elétrica) para uma tensão adequada ao funcionamento da fonte de tensão ajustável.

- **Pote de Diodo:**  pote de diodo é um componente eletrônico que consiste em um diodo semicondutor conectado a um potenciômetro. Ele é utilizado para ajustar a tensão de saída da fonte de tensão de forma contínua, permitindo selecionar valores entre 3V e 12V.

- **Capacitor:** O capacitor é um componente eletrônico que armazena energia em forma de carga elétrica. Neste caso, ele pode ser utilizado para suavizar as variações de tensão e reduzir o ruído na saída da fonte de tensão ajustável.

- **LED:** O LED (Light Emitting Diode) é um dispositivo que emite luz quando a corrente elétrica passa por ele. Ele pode ser utilizado para indicar visualmente a presença de tensão na saída da fonte de tensão ajustável.

- **LM317T:** O LM317T é um regulador de tensão ajustável. Ele é um circuito integrado que permite controlar a tensão de saída de um circuito, de acordo com a tensão de referência e os valores dos componentes conectados a ele. Neste caso, o LM317T será utilizado como o regulador de tensão principal da fonte.

- **Potênciometro:** O potenciômetro é um resistor ajustável que permite controlar a resistência em um circuito. Ele será utilizado para ajustar a tensão de saída da fonte de tensão ajustável, juntamente com o pote de diodo.

- **Resistores:** Os resistores são componentes eletrônicos que têm a função de limitar a corrente elétrica em um circuito. Eles são utilizados para ajustar o valor da resistência em um determinado ponto do circuito, garantindo que a corrente elétrica seja adequada para o funcionamento correto dos componentes conectados.

- **Placa de Fenolite:** A placa de fenolite cobreado 10x5 é um material utilizado na fabricação de placas de circuito impresso (PCBs). Ela possui uma base de fenolite resistente e isolante, com uma camada de cobre em uma ou ambas as faces. Essa placa será usada como base para a PCB da fonte de tensão ajustável, permitindo a montagem dos componentes eletrônicos e a conexão entre eles por meio de trilhas de cobre.

## Escolha dos componentes:
| Quantidade    | Componentes   | Especificações | Valor R$  |
| :-------------: |:-------------:| :-------------: |---------:|
| 1x | Fusível 1A | | |
| 1x | Porta Fusível | | |
| 1x | Chave Gangorra | | |
| 1x | Transformador | | |
| 1x | Ponte de Diodo | | |
| 1x | Capacitor 470uF | | |
| 1x | Capacitor 100nF | | |
| 1x | Resistor 5.6K Ω ||
| 1x | Resistor 330 Ω ||
| 1x | Resistor 270 Ω ||
| 1x | LED Vermelho ||
| 1x | LM317 ||
| 1x | Potênciometro 2k ||
| 1x | Placa de Fenolite 10x5 |Não precisa ser cobreada de ambos os lados|
| **Total**:     |               | | R$ 0,00 |

## Imagem do circuito (Falstad):

![alt text](https://github.com/MatheusPaivaa/Projeto-Eletronica-USP/blob/eec0d95450828fd655cb8d53a3ad551c8c3bbbaa/circuito_falstad.png "Imagem falstad")

Link do circuito no Falstad: [Falstad](https://tinyurl.com/22zg2rbu)

## Imagem do circuito (Eagle):
Adicionar imagens...

## Funcionamento:

- **Documento em PDF:** [PDF](https://docs.google.com/document/d/1-9Oya-yLFN3rCFs4--Uhrb7HC6HWyEKhkQ9YGcFjMBw/edit?usp=sharing)

- **Vídeo explicativo:**

## Alunos:
Matheus Paiva Angarola - **12560982** ([Github](https://github.com/MatheusPaivaa))

Nelly Vanesa Mollo Cossio -  **13684860**

Renato Calacina Spessotto - **14605824** ([Github](https://github.com/renatocspessotto))

Vinícius Felisberto dos Reis - **13695390** ([Github](https://github.com/viniciusfreiss))

## Conclusão:
Por meio desse projeto, aprendemos sobre os princípios da retificação de corrente, transformação de tensão, regulagem de tensão e proteção elétrica. Também compreendemos a importância dos componentes utilizados e como eles interagem para garantir o funcionamento adequado da fonte de tensão ajustável. Esses conhecimentos podem ser aplicados em projetos futuros envolvendo eletrônica e alimentação de dispositivos que requerem tensões específicas.

## Agradecimentos:
Agradecemos ao grandioso professor Eduardo do Valle Simões, **o Poderoso**.
