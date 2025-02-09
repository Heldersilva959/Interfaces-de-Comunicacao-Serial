<h1 align="center">EmbarcaTech - Atividade sobre Interfaces de Comunicação Serial com RP2040 UART, SPI e I2C</h1>


Enunciado: 
Para consolidar a compreensão dos conceitos sobre o uso de interfaces de comunicação serial no RP2040 e explorar as funcionalidades da placa de desenvolvimento BitDogLab, propõe-se a seguinte tarefa individual prática. 

Objetivos:

- Compreender o funcionamento e a aplicação de comunicação serial em microcontroladores.
- Aplicar os conhecimentos adquiridos sobre UART e I2C na prática.
- Manipular e controlar LEDs comuns e LEDs endereçáveis WS2812.
- Fixar o estudo do uso botões de acionamento, interrupções e Debounce.
- Desenvolver um projeto funcional que combine hardware e software.

Materiais utilizados:

Neste projeto, são utilizados os seguintes componentes conectados à placa BitDogLab:
1) Matriz 5x5 de LEDs (endereçáveis) WS2812, conectada à GPIO 7.
2) LED RGB, com os pinos conectados às GPIOs (11, 12 e 13).
3) Botão A conectado à GPIO 5.
4) Botão B conectado à GPIO 6.
5) Display SSD1306 conectado via I2C (GPIO 14 e GPIO15).

Lista de requisitos:

- Todas as funcionalidades relacionadas aos botões devem ser implementadas utilizando rotinas de interrupção (IRQ).
- É obrigatório implementar o tratamento do bouncing dos botões via software.
- O projeto deve incluir o uso de LEDs comuns e LEDs WS2812, demonstrando o domínio de diferentes tipos de controle. 
- A utilização de fontes maiúsculas e minúsculas demonstrará o domínio do uso de bibliotecas, o entendimento do princípio de funcionamento do display, bem como, a utilização do protocolo I2C
- Visa observar a compreensão sobre a comunicação serial via UART.
- O código deve estar bem estruturado e comentado para facilitar o
entendimento.

Tecnologias:

1. Git e Github;
2. VScode;
3. Linguagem C;
4. Simulador Wokwi;
5. Placa de desenvolvimento BitDogLab

Funcionalidades Implementadas:
1. Pressionar o botão A alterna o estado do LED RGB Verde (ligado/desligado) e mostra no display SSD1306 seu estado atual.
2. Pressionar o botão B alterna o estado do LED RGB Azul (ligado/desligado) e mostra no display SSD1306 seu estado atual.
3. Cada caractere digitado no Serial Monitor é exibido no display SSD1306, independente se ela é minuscula ou maiuscula.
4. Quando um número entre 0 e 9 for digitado, esse número é exibido, também, na matriz 5x5 WS2812.


Desenvolvedor:
 
<table>
  <tr>
    <td align="center"> <sub><b> Helder Araujo Silva </b></td>
    </tr>
</table>

Video de demonstração: https://youtube.com/shorts/hIlwD626k4s?feature=share