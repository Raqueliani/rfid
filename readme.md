Projeto Arduino Controle de Acesso RFID

Bastante pensado em projetos de automação residencial com Arduino, o esquema para controle de acesso RFID oportuniza a você e a todos os seus familiares ainda maior segurança já que possibilita a abertura de portas de maneira rápida e simples, onde basta passar o cartão em frente ao leitor RFID para liberar a fechadura.

O sistema de comunicação para transferência de dados do sistema RFID utiliza ondas de rádio, nas quais cada tag emite uma sequência de números como um código exclusivo para cada chaveiro, cartão ou qual for o acessório como, por exemplo, o código do cartão {118, 157, 177, 171, 241} o qual veremos mais a frente em nosso projeto.

Devido a sua comunicação por sistema de rádio, vale lembrar que os equipamentos utilizados junto ao módulo RFID RC522 possuem uma frequência específica de trabalho que é de 13,56Mhz e suporta cartões do tipo Mifare1 S50, Mifare1 S70 Mifare Ultralight, Mifare Pro e Mifare DESFire.

Desenvolvido com o intuito de proporcionar um sistema de controle de acesso mais seguro e de fácil utilização, o Controle de Acesso RFID conta com um exclusivo sistema eletrônico capaz de monitorar as tags aproximadas do módulo RFID e liberar somente aqueles as quais já estiverem determinadas e autorizadas no código raiz de seu projeto, visando melhorar a visibilidade dos sistemas de leitura, incluímos ao projeto com Display 16×2 que indica quando o cartão é lido.

Sendo capaz de realizar a leitura de todo acessório de frequência igual a 13,56Mhz, neste projeto utilizamos um chaveiro e um cartão para cadastrar em nosso sistema, pode observar que quando alguém não autorizado tenta entrar com seu cartão não cadastrado o sistema não libera nossa Fechadura Elétrica.

Porém, quando um cartão autorizado é aproximado ao sistema RFID o mesmo libera a corrente de energia do relé e acaba por acionando a Fechadura Elétrica, que por mais que seja um equipamento de corrente contínua, necessita de uma relé já que sua alimentação é dada através de 12V e 800mA.



Produtos Utilizados no Projeto

1 Arduino UNO + Cabo USB AB;
1 Kit RC522 Leitor RFID;
1 Módulo Relé 1 Canal;
1 Display LCD 16×2;
1 Potenciômetro;
1 Fechadura Elétrica 12V;
1 Fonte de Alimentação 12V 1A.

