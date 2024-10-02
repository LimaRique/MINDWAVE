OBJETIVO:
Este projeto tem como objetivo desenvolver um carrinho controlado via Bluetooth, cuja movimentação é baseada em sinais de atividade cerebral. Utilizando um Arduino como controlador principal, o carrinho se movimenta conforme os dados de atividade cerebral recebidos, ajustando o movimento com esses sinais, no qual quando a concentração (atividade cerebral) é maior que um limite pré-determinado, o carrinho se movimenta. A intenção do projeto é criar uma interface mente-máquina, onde o usuário pode influenciar diretamente o comportamento do carrinho por meio de seus níveis de atividade cerebral. 

INTENS NECESSÁRIOS:
Arduino Uno (ou outro modelo compatível)
Módulo Bluetooth HC-05 (para comunicação com o dispositivo)
Ponte H L298N (para controlar os motores)
2 Motores DC
Protoboard
Fonte de alimentação (para os motores e Arduino)
Fios jumpers, incluindo macho/fêmea (para as conexões)
Dispositivo de medição de atividade cerebral (neste projeto foi utilizado o MINDWAVE da Neurosky)
Bateria 9 volts e o conector para o árduino
4 pilhas AA e o suporte
Chassi do carrinho, da para improvisar com mdf
Rodas apropiadas para os 2 motores DC, e uma rodinha giratória

ETAPAS:
1-Montagem do Carrinho: Para isso, basta montar um carrinho como se fosse um carrinho básico com módulo bluetooth, segue o link: https://www.youtube.com/watch?v=OornqssB-dU (OBS: No vídeo a alimentação está sendo apenas usada uma pilha, nesse carrinho basta usar as 4 pilhas AA no suporte para alimentar a Ponte-H e a bateira 9v para alimentar o arduíno.
2-Montagem do código no arduíno que já está arquivado no repositório
3-Conecção do Módulo Bluetooth com o MindWave, use o código nomeado como PAIRING, segue o link para a conecção: https://www.youtube.com/watch?v=uKK5_U6l27E (OBS: Quando for passar o código para o arduíno e testar os comandos AT, retire o módulo bluetooth antes de alimentar o arduíno e então reconecte novamente invertendo os pinos RX e TX, não use os pinos 10 e 11 como indica o vídeo, use o RX e TX invertidos. (OBS: Você vai saber que está conectado quando os comandos AT derem "OK" e quando o módulo piscar 2 vezes entre intervalos de uns 3 segundos.
4- Após os Testes dos Comandos AT, passe o código do carrinho para o arduíno, assim o seu projeto já estará pronto. 
OBS: CASO O CARRINHO APENAS GIRE E NÃO ANDE PARA FRENTE, INVERTA A CONECÇÃO DOS MOTORES COM A PONTE-H, CASO O PROLEMA SEJA EM QUE UM MOTOR ESTÁ MAIS RÁPIDO QUE O OUTRO, APENAS TROQUE O CÓDIGO PARA QUE AJUSTE O NÍVEL DE VELOCIDADE DE CADA UM MOTOR ATÉ QUE ESTEJA ADEQUADO. 

Este projeto foi fruto de um trabalho árduo do projeto de uma feira cultural de escola técnica, aproveitem! 

 


