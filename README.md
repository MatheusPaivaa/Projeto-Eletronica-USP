# Projeto de uma Fonte de Tensão Ajustável 🔋🔌
Desenvolvido para a disciplina Eletônica para Computação - SSC0180.

## Situação Inicial:
<p align="justify">
   Construção de uma fonte retificadora que consiga transformar corrente alternada (A/C) de 127V em corrente contínua (D/C). Além disso, deve ser possível ajustar a sua tensão em uma faixa de 3V até 12V, com capacidade de 100mA. 
</p>

**Fonte de Tensão (Tomada)** = Tensão AC de 127V, operando a uma frequência de 60Hz. 

<p align="center">
   <img align="center" text-align="center" width="100%" src="https://github.com/MatheusPaivaa/Projeto-Eletronica-USP-Fonte/blob/main/circuito_placa.jpeg">
</p>

## Componentes:
<p align="justify">
   
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
     
</p>

## Escolha dos componentes:
| Quantidade    | Componentes   | Especificações | Valor R$  |
| :-------------: |:-------------:| :-------------: |---------:|
| 1x | Fusível | Ter entre 500mA e 1A | [R$ 0,28](https://www.baudaeletronica.com.br/produto/fusivel-de-vidro-5x20-1a-250v.html?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp5Sxrgsf60tlAU9u5QhNWYG0R35PylPx-_qWipXBIDDYr2j4A1A07MaAkH7EALw_wcB) |
| 1x | Porta Fusível | Qualquer um que caiba os fusíveis | [R$ 1,20](https://www.eletrogate.com/porta-fusivel-5x20-as06) |
| 1x | Chave Gangorra | Nenhuma especificação | [R$ 1,90](https://www.eletrogate.com/chave-gangorra-com-2-terminais) |
| 1x | Transformador | Ser bivolt 18+18v 200mA | [R$ 30,00](https://produto.mercadolivre.com.br/MLB-1253943633-transformador-trafo-1818v-200ma-bivolt-eletronica-_JM?matt_tool=54307261&matt_word=&matt_source=google&matt_campaign_id=14302215582&matt_ad_group_id=134553712308&matt_match_type=&matt_network=g&matt_device=c&matt_creative=539425529689&matt_keyword=&matt_ad_position=&matt_ad_type=pla&matt_merchant_id=109546415&matt_product_id=MLB1253943633&matt_product_partition_id=1802672036537&matt_target_id=pla-1802672036537&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp4hW0EBX6HRP9Uj2QjMKqJsE4l4tpOUBI0-lfe-B3txkHnP4clOqH0aAvrCEALw_wcB) |
| 1x | Ponte de Diodo | Ponte de no minimo 1A | [R$ 1,90](https://www.eletrogate.com/diodo-retificador-1n4007-10-unidades) | 
| 1x | Capacitor 470uF | Mínimo de 25V | [R$ 2,52](https://www.eletrogate.com/capacitor-eletrolitico-470uf-x-50v) | 
| 1x | Capacitor 100nF | Mínimo de 25V | [R$ 1,50](https://www.eletrogate.com/capacitor-poliester-metalizado-100nf-x-400v) | 
| 1x | Resistor 5.6K Ω | Mínimo de 1/2 W | [R$ 0,14](https://www.baudaeletronica.com.br/produto/resistor-5k6-5-12w.html?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp5CTnlTcv_SXmWS0936PVifASlhihgp2nK68jjVNHb5WTJyzJOC-A4aAsyPEALw_wcB) | 
| 1x | Resistor 330 Ω | Nenhuma especificação |  [R$ 0,15](https://www.baudaeletronica.com.br/produto/resistor-330r-5-12w.html?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp6LTgxlzKlQzP8OG1qwbUi-pRDTfwrr8GBb4G2EgDIJDS_ZiTXR77oaAt3fEALw_wcB) | 
| 1x | Resistor 270 Ω | Nenhuma especificação | [R$ 0,06](https://www.baudaeletronica.com.br/produto/resistor-270r-5-14w.html?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp5dzqc7nJxamPnkRmK0ISQRLekSq5iHG57d6UQyDzV3kf1I064oqqwaAo5wEALw_wcB) | 
| 1x | LED | Qualquer cor| [R$ 0,28](https://www.eletrogate.com/led-difuso-5mm-vermelho) | 
| 1x | LM317T | Precisa ter proteção térmica contra sobrecarga | [R$ 4,66](https://www.eletrogate.com/regulador-de-tensao-lm317t?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gad=1&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp4LUtSc4i2jF2vUsj5UuvrAT6JthlVBOmPZs0Q1tjJtL9VysCA3Gb4aAvvcEALw_wcB) | 
| 1x | Potênciometro | Ser linear de 2K (2000Ω) | [R$ 2,90](https://www.baudaeletronica.com.br/produto/potenciometro-linear-de-2k-2000o.html?utm_source=Site&utm_medium=GoogleMerchant&utm_campaign=GoogleMerchant&gclid=Cj0KCQjwwISlBhD6ARIsAESAmp5KTr9R6PPlQAROR0ZM9oR2QJWyrjBfZsBuH9pEPyW6QhfppATZPosaArgnEALw_wcB) | 
| 1x | Placa de Fenolite 10x5 | Não precisa ser cobreada de ambos os lados | [R$ 4,60](https://www.baudaeletronica.com.br/produto/placa-de-fenolite-virgem-15x5-cm.html) | 
| **Total**:     |               | | R$ 57,89 |

Data de consulta: 02/07/2023

## Imagem do circuito (Falstad):

![alt text](https://github.com/MatheusPaivaa/Projeto-Eletronica-USP/blob/eec0d95450828fd655cb8d53a3ad551c8c3bbbaa/circuito_falstad.png "Imagem falstad")

Link do circuito no Falstad: [Falstad](https://tinyurl.com/22zg2rbu)

## Imagem do circuito (Eagle):
![alt text](https://github.com/MatheusPaivaa/Projeto-Eletronica-USP-Fonte/blob/main/circuito2.png "Imagem EAGLE 1")

<p align="center">
   <img align="center" text-align="center" width="65%" src="https://github.com/MatheusPaivaa/Projeto-Eletronica-USP-Fonte/blob/main/circuito%204.png">
</p>

<p align="center">
   <img align="center" text-align="center" width="100%" src="https://github.com/MatheusPaivaa/Projeto-Eletronica-USP-Fonte/blob/main/circuito_solda.jpeg">
</p>

## Funcionamento:

- **Documento em PDF:** [PDF](https://docs.google.com/document/d/1-9Oya-yLFN3rCFs4--Uhrb7HC6HWyEKhkQ9YGcFjMBw/edit?usp=sharing)

- **Vídeo explicativo:** [Vídeo](https://www.youtube.com/watch?v=-PUwLhJURaA)

## Alunos:
Matheus Paiva Angarola - **12560982** ([Github](https://github.com/MatheusPaivaa))

Nelly Vanesa Mollo Cossio -  **13684860**

Renato Calacina Spessotto - **14605824** ([Github](https://github.com/renatocspessotto))

Vinícius Felisberto dos Reis - **13695390** ([Github](https://github.com/viniciusfreiss))

## Conclusão:
<p align="justify">
Por meio desse projeto, aprendemos sobre os princípios da retificação de corrente, transformação de tensão, regulagem de tensão e proteção elétrica. Também compreendemos a importância dos componentes utilizados e como eles interagem para garantir o funcionamento adequado da fonte de tensão ajustável. Esses conhecimentos podem ser aplicados em projetos futuros envolvendo eletrônica e alimentação de dispositivos que requerem tensões específicas.
</p>

## Agradecimentos:
Agradecemos ao grandioso professor Eduardo do Valle Simões, **o Poderoso**.
