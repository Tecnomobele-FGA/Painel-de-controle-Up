# Painel-de-controle-Up
Processo para hackear o painel de controle do Up através do barramento CAN.

# 1. Hardware
 
Para o início deste projeto foi necessário identificar as conexões e pinagens da comunicação CAN bus no painel de controle, assim como a sua devida alimentação para garantir o seu 
funcionamento. Assim, foi desmontado o painel com o intuido de identificar os transcivers para a comunicação CAN. Esse processo pode ser observado nas seguintes imagens:

![](Figuras/Painel_up1.jpeg)
 
![](Figuras/Painel_up2.jpeg)   

As demais imagens podem ser observadas [aqui](https://github.com/Tecnomobele-FGA/Modulo-luzes/tree/master/fotos).
# 1.1 Conexões

Identificados os pinos para a comunicação CAN e a alimentação do painel, utilizou-se um conector especifico para o protocolo CAN, o DB9.
As pinagems dos conectores foram organizados e acoplados da seguinte forma:

![](Figuras/db9_cann.PNG)  
![](Figuras/painel_pin.PNG)
![](Figuras/painel_pin.jpeg)


| pino - DB9 | Painel | 
|:----------:|:------:|        
| 1          |    -   |         
| 2  CAN Low |   29   |        
| 3   GND    |   16   |         
| 4          |    -   |         
| 6          |    -   |    
| 7 CAN High |   28   |        
| 8          |    -   |        
| 9   12V    |  32,31 |        


