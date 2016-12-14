# Freestyle Sensor Libre

Este projeto destina-se a popularizar os estudos na área de monitoramento de Glicose. É usado como base o sensor da empresa FreeStyle. Este sensor tem um custo muito alto no Brasil, já que não há concorrência.
O objetivo aqui não é copiar o sensor para produzir no Brasil e nem violar nenhuma patente. A idéia é apenas que engenheiros brasileiros se interessem por esta área que é muito potencial e devido a falta de concorrência permite que empresas que detem o monopólio não se preocupem distribuir esses produtos de forma mais acessível.

Ao longo do tempo publicarei Esquemáticos, Firmware e métodos para cálculo de Glicóse a partir do Chip [RF430TAL152H](http://www.ti.com/product/RF430FRL152H/technicaldocuments) da Texas através do ADC.
OBS> O microcontrolador usado neste produto é o RF430TAL152H, a Texas comercializa com o nome RF430RFL152H. Essa sutil diferença aparentava ser apenas uma nomenclatura para distinguir o lote dedicado a este produto. Entretanto, analisando o circuito elétrico, as conexões dos pinos do microcontrolador não parecem ser iguais. Isso pode dificultar a utilização do hardware original para testes de firmware, mas não impedir.


Quem estiver interessado em colaborar entre em contato.

Abaixo segue a descrição do sensor feita pelo fabricante:

## Sensor

O sensor do FreeStyle Libre foi projetado para ser fácil de aplicar e usar. Pequeno e discreto.

IMPORTANTE: O Sistema Flash de Monitoramento FreeStyle Libre é indicado para medir níveis da glicose no fluído intersticial em adultos com 18 anos ou mais.

Como usar o sensor do FreeStyle Libre

#### Aplique o sensor
O sensor do FreeStyle Libre deve ser aplicado na parte posterior superior do braço com um dispositivo simples e descartável chamado "aplicador". Quando o sensor é aplicado, um pequeno filamento estéril e flexível é inserido sob a pele. Ele permanece fixo no local graças a uma camada adesiva.

#### Escaneie o sensor
Para fazer a leitura da glicose, basta escanear o sensor com o leitor – um processo rápido e indolor3 que leva apenas 1 segundo. Essa leitura fornece mais informações do que o monitoramento realizado através de tiras de teste de glicose sanguínea, sem a necessidade das rotineiras picadas no dedo1. O sistema FreeStyle Libre também oferece um software que gera relatórios concisos para auxiliar na análise dos dados da glicose.

#### Faça a leitura
Cada leitura do sensor fornece dados atualizados da glicose, o histórico glicêmico das últimas 8 horas e uma seta de tendência mostrando se a glicose está subindo, baixando ou mudando lentamente. O leitor é capaz de ler o sensor mesmo através da roupa2.


##Hardware

![Screenshot](HW-FreestyleSensorLibre/draw_1116_1.png)

##Fita de Leitura
![Screenshot](HW-FreestyleSensorLibre/draw_1116-40.png)

##Trabalhos usados como Referência:

[Andrade, Arnaldo César Dantas dos Santos. "Desenvolvimento de Dispositivo Eletrônico e Sensor Plasmônico para Detecção de Glicose." (2013).](http://repositorio.ufpe.br/handle/123456789/12213)

[Santos, Jaciara Cássia de Carvalho. Imobilização da enzima glicose oxidase em filmes nanoestruturados para aplicação em biossensores. Diss. Universidade de São Paulo, 2012.](http://www.teses.usp.br/teses/disponiveis/76/76131/tde-11102012-163617/en.php)

[Moreira, Cleumar S., et al. "Biossensores: Tecnologia e Aplicações." V Congresso Norte Nordeste de Pesquisa e Inovação [online]. 2010.](http://www.biologia.seed.pr.gov.br/arquivos/File/biotecnologia/biosensores.pdf)

##Hardware de Prototipação Rápido (LaunchPad)

[RF430FRL152HEVM](http://www.ti.com/tool/RF430FRL152HEVM)

![Screenshot](http://www.ti.com/diagrams/med_rf430frl152hevm_rf430frl152hevm-1.jpg)

O módulo de avaliação RF430FRL152HEVM é uma plataforma de desenvolvimento autônoma que pode ser usada para avaliar os recursos e o desempenho do transponder de sensor NFC RF430FRL15xH compatível com ISO 15693. A placa de avaliação pode ser alimentada por uma bateria, por USB ou por indução de RF a partir de um leitor ou smartphone NFC com capacidade de exibição. O código de aplicativo incorporado na ROM gerencia a comunicação de RF e as leituras de sensores para fornecer a máxima flexibilidade na configuração do dispositivo. Os programadores podem configurar taxas de amostragem, limiares de medição e alarmes. A memória não volátil universal de 2kByte (FRAM) permite o armazenamento de dados, bem como a extensão e o ajuste do código da aplicação. Para uma maior expansão, a placa de avaliação é compatível com vários BoosterPacks do ecossistema de protótipos rápidos LaunchPad de baixo custo da TI, como o Sensor Hub BoosterPack que oferece conectividade para sensores adicionais.

O módulo de avaliação pode ser usado para avaliar o Transponder de Sensor NFC para uma variedade de aplicações tais wearables e patches de saúde e fitness.

![Screenshot](https://www.element14.com/community/dtss-images/uploads/devtool/diagram/large/9e1865ffe1909dbc011ffe36c0c5c85e.png)



