# Monitoramento e controle - Esteira de Materiais

desenvolvolvilmento de um Sistema Supervisório (utilizando o InduSoft Web Studio e comunicação via OPC) para monitoramento e controle de uma planta de Esteira de Materiais.

### A planta:

![alt text](https://online.ucl.br/assets/courseware/v1/6ed4a3633da5d81bf49b65d9f7ece27b/asset-v1:UCLx+11684+2022-2+type@asset+block/esteira.jpg)

A planta conta com vários elementos sensores e atuadores. Para esse supervisório, os seguintes elementos serão utilizados:


- Barreiras óticas b1 e b3;
- Sensor fotoelétrico;
- Sensor capacitivo;
- Motor;
- Botoeira de emergência.


Os sensores, fotoelétrico e capacitivo, serão utilizados pelo PLC para identificação do tipo de peça que está sendo transportada. Esta informação será fornecida através de uma variável do PLC para o Sistema Supervisório.

### Features:

- A tela do supervisório deverá apresentar uma representação fidedigna da planta em questão.
- Alarmes devem ser considerados (em especial o de acionamento da botoeira de emergência).
- Deve haver comandos de partida e parada da planta.
- Totalizadores devem ser previstos.
