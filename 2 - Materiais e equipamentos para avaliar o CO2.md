Para avaliar o CO2 produzido por sementes, utilizar um sensor MHZ19B conectado a um controlador Wemos D1.

Etapas de preparação:

1. Instalar o sensor internamente na tampa de um recipiente de poliestireno transparente (13 x 13 x 9 cm; 700 mL de capacidade), dotada de anel de vedação de silicone com 3 abas. O controlador deve ser instalado em um Case transparente sobre a tampa.
2. Conectar por cabos (Jumper de 20 cm) o sensor e o controlador. A alimentação de energia foi feita nos pinos "5V" e "GND" (neutro) do controlador, enquanto a recepção e a transmissão dos dados foram feitas nos pinos RX_PIN "13" e TX_PIN "15", respectivamente.
3. Conectar o controlador ao computador por um cabo USB-MiniUSB (fornecido pelo vendedor).

Sistema Arduino:

4. Instalar no computador o sistema Arduíno 1.8.19 (https://docs.arduino.cc/software/ide-v2/tutorials/getting-started/ide-v2-downloading-and-installing/).
5. Abrir o sistema Arduino no computador e baixar as Bibliotecas (ver na aba Ferramentas): "MHZ19.h"; "ESP8266WiFi.h"; "ThingSpeak.h"; "WiFiClient.h".
6. Na aba Ferramentas, selecionar a Porta de conexão do controlador, a Placa "LOLIN(WeMos)D1 R1" e marcar a opção "115200" na Upload Speed.
7. Calibrar o sensor por 20 minutos em ambiente aberto, utilizando o código disponível na Biblioteca MH-Z19 (https://github.com/WifWaf/MH-Z19).
8. Criar uma conta e um canal no Site ThingSpeak (https://thingspeak.mathworks.com), para registrar os dados das leituras de CO₂ de forma remota.
9. Abrir o código apresentado no projeto do GitHub (CO2-Sensor_MHZ19B-WemosD1_-_Online.ino) e substituir as informações indicadas nos //Comentários.
10. Carregar o código no controlador e aguardamos, até o envio dos dados de forma correta para o canal criado do ThinkSpeak a cada 5 minutos.

Preparação do Recipiente:

11. Fazer a assepsia do recipiente com Álcool 70%.
12. Depositar o substrato no interior do recipiente. O substrato deve ser constituído por duas folhas de papel mata-borrão (10,4 x 10,4 cm), umedecidas com água destilada, com volume equivalente a 2,5 vezes a massa do papel, conforme recomendado para testes de germinação nas Regras para Análise de Sementes (https://wikisda.agricultura.gov.br/pt-br/Laborat%C3%B3rios/Metodologia/Sementes/RAS_2025/cap_4_Germinacao_rev_1).

Preparação da amostra:

13. Deve-se a homogeneizar amostra, para a obtenção de uma subamostra de trabalho constituída por 25 sementes.
17. As sementes devem ser colocadas no interior do recipiente de poliestireno transparente, sobre o papel umedecido.
