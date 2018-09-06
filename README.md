# Irrigação e monitoramento de horta escolar

## Sumário
    
- [Materiais](#mat)
    - [Lista de materiais 1](#l1)
    - [Lista de materiais 2](#l2)

- [Instalação do plugin ESP8266 no Arduino IDE](#ins)

- [Levantamento das opções de serviços online para IoT](#lev)
    
- [Referências](#ref)

<a name="mat"></a>

# Materiais
Abaixo tabelas contendo a relação dos materiais essenciais para a execução do projeto, nela são apresentados os preços médios dos componentes, podendo variar um pouco dependendo da loja.

<a name="l1"></a>

## Lista de materiais 1

Esta lista é composta pelos elementos necessários para o projeto caso a opção de placa de desenvolvimento for o Arduino, necessitando assim de um módulo adicional para Wifi.

<div align="center">

Material                    |   Preço (R$) |   Imagem
--------------------------- | ------------ | ---------
Protoboard                  |    12,90     | <img src="https://bit.ly/2NUPGHz" width="150">
Válvula solenóide 1/2' 12v  |    40,10     | <img src="https://bit.ly/2M2vyRO" width="150">
Arduino UNO R3 + Cabo USB   |    50,00     | <img src="https://bit.ly/2NXXMig" width="150">   
Módulo Relé 12v 10A         |    10,00     | <img src="https://bit.ly/2PJ16hT" width="150"> 
Módulo Wifi                 |    26,90     | <img src="https://bit.ly/2NnZ8WC" width="150">
Sensor de umidade           |    8,50      | <img src="https://bit.ly/2MOfmsJ" width="150">
**Total**                   |  **148,40**  | 

</div>

**OBS.:** Na tabela de preços não foram considerados os valores de frete, pois existe a possibilidade de se comprar mais de um componente na mesma loja, aproveitando-se o mesmo valor para entrega.

<a name="l2"></a>

## Lista de materiais 2

Esta segunda lista é composta pelos mesmos itens da lista anterior, porém com a escolha do ESPduino como placa de desenvolvimento, descartando assim a necessidade de um módulo específico para Wifi.

<div align="center">

Material                    |   Preço (R$) |   Imagem
--------------------------- | ------------ | -----------
Protoboard                  |    12,90     |  <img src="https://bit.ly/2NUPGHz" width="150">
Válvula solenóide 1/2' 12v  |    40,10     |  <img src="https://bit.ly/2M2vyRO" width="150">           
ESPduino + Cabo USB         |    50,00     |  <img src="https://bit.ly/2MPFGCK" width="150">
Módulo Relé 12v 10A         |    10,00     |  <img src="https://bit.ly/2PJ16hT" width="150">           
Sensor de umidade           |    8,50      |  <img src="https://bit.ly/2MOfmsJ" width="150">
**Total**                   |  **121,50**  |

</div>

<a name="ins"></a>

# Instalação do plugin ESP8266 no Arduino IDE 

Conforme pode ser visualizado nas listas de materiais, o projeto utilizando o ESPduino sai um pouco mais em conta e, aliado a maior facilidade para estruturar o circuito, o mesmo foi escolhido como placa de prototipação para este trabalho. Porém a interface e o ambiente de programação continuam os mesmos, bastando apenas instalar o plugin do ESP8266 no Arduino IDE, conforme as instruções a seguir:

 1 - No Arduino IDE, abra o menu "Arquivo > Preferências" e em seguida, no campo "URLs Adicionais para gerenciadores de Placas" adicione o seguinte link: http://arduino.esp8266.com/stable/package_esp8266com_index.json


2 - Acesse o menu "Ferramentas > Placa > Gerenciador de Placas" e em seguida procure por "esp8266 Community" e instale-o.

3 - Reinicie o Arduino IDE e a opção "ESPduino" já estará entre as placas disponíveis.

<a name="lev"></a>

# Levantamento das opções de serviços online para IoT

Plataforma   | Necessário instalação | Dashboard configurável | Usabilidade  | Português
------------ | --------------------- | ---------------------- | ------------ | ----------- 
[Thingsboard](https://thingsboard.io) | Não | Sim | Mais complexo que as demais | Não
[Kaa](https://www.kaaproject.org/)| Sim | Pouco | Média | Não
[Thinger.io](https://thinger.io/)| Não | Sim | Fácil | Não
[DeviceHive](https://devicehive.com/)| Sim | O acesso ao dashboard depende de outro serviço | complexo | Não
[ThingSpeak](https://thingspeak.com/)| Não | Pouco | Simples | Não


<a name="ref"></a>

# Referências
- **Tabela de preços**
    - [Arduino UNO R3 (opção 1)](https://produto.mercadolivre.com.br/MLB-862950618-arduino-uno-rev3-r3-atmega328-cabo-usb-pino-frete-gratis-_JM)
  
    - [Arduino UNO R3 (opção 2)](https://www.filipeflop.com/produto/placa-uno-r3-cabo-usb-para-arduino/)

    - [Módulo relé](http://www.eletrodex.com.br/modulo-rele-12v-1-canal.html)

    - [Módulo Wifi](https://www.filipeflop.com/produto/modulo-wifi-esp8266-esp-01/)

    - [Válvula solenóide](http://www.baudaeletronica.com.br/valvula-solenoide-para-agua-12v-180-x-va-03.html)

    - [Protoboard (opção 1)](https://www.filipeflop.com/produto/protoboard-400-pontos/)

    - [Protoboard (opção 2)](http://www.baudaeletronica.com.br/protoboard-400-pontos.html?gclid=CjwKCAjwur7YBRA_EiwASXqIHJfLQC7Y4bfSoZTcU87FsD_o5kYMzUsRtGt2SVEZ2ZyFM0Mx_qRLmRoCvfIQAvD_BwE)

    - [Sensor de umidade (opção 1)](http://www.baudaeletronica.com.br/sensor-de-umidade-do-solo.html?gclid=CjwKCAjwur7YBRA_EiwASXqIHPphmgn0vv3pC13p7f3pVw-wCMckJj3rR62Af6DRpE01LQ1eX6BgfxoCOZ4QAvD_BwE)

    - [Sensor de umidade (opção 2)](https://www.filipeflop.com/produto/sensor-de-umidade-do-solo-higrometro/)
    
    - [ESPduino](https://www.amazon.com/ESPDuino-Development-Compatible-Arduino-ESP8266/dp/B078MYY3C1) 
