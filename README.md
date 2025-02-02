# Projeto: Controle de LEDs e Interrupções no RP2040

✅ Arquivo principal: contagem.cEste é o arquivo de código-fonte principal, responsável por toda a lógica do projeto.

## 📋 Descrição do Projeto
Este projeto tem como objetivo consolidar conceitos de interrupções em microcontroladores, debouncing de botões, e controle de LEDs comuns e endereçáveis WS2812 utilizando a placa de desenvolvimento BitDogLab e o microcontrolador RP2040.

## 🎯 Objetivos
- Compreender o funcionamento e a aplicação de interrupções (IRQ).
- Implementar debouncing via software para evitar o bouncing dos botões.
- Controlar LEDs comuns e LEDs WS2812.
- Utilizar resistores de pull-up internos nos botões de acionamento.
- Desenvolver um projeto funcional que combine hardware e software.

## ⚙️ Funcionalidades Implementadas
1. 🔴 O LED vermelho do LED RGB pisca continuamente 5 vezes por segundo.  
2. ⬆️ O botão A (GPIO 5) incrementa o número exibido na matriz de LEDs WS2812.  
3. ⬇️ O botão B (GPIO 6) decrementa o número exibido na matriz de LEDs WS2812.  
4. 🔢 Os números de **0 a 9** são exibidos na matriz 5x5 de LEDs WS2812 com efeitos visuais em estilo digital.  

## 🧰 Componentes Utilizados
- **Placa BitDogLab** com microcontrolador RP2040  
- **Matriz 5x5 de LEDs WS2812** (conectada à GPIO 7)  
- **LED RGB** (conectado às GPIOs 11, 12 e 13)  
- **Botão A** (conectado à GPIO 5)  
- **Botão B** (conectado à GPIO 6)  

## 📡 Configuração de Hardware
- **GPIO 5:** Botão A  
- **GPIO 6:** Botão B  
- **GPIO 7:** Matriz WS2812  
- **GPIOs 11, 12, 13:** LED RGB  

## 📝 Instruções de Uso
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/Davileao10/Contagem)

2. Compile o arquivo: contagem.c usando o Pico SDK:
bash
mkdir build && cd build
cmake ..
make

3. Faça o upload do binário para o RP2040.
Pressione os botões A e B para testar as funcionalidade



