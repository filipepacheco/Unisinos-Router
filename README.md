# Unisinos-Router

OBJETIVO

Desenvolvimento dos conceitos adquiridos na disciplina de Redes de Computadores: Internetworking, Roteamento e Transmissão, tais como endereçamento e roteamento da camada três do modelo OSI. Além disso, estimular a desenvoltura e apresentação oral do aluno.

METODOLOGIA

O trabalho deve ser realizado de forma individual com as seguintes definições:

● A apresentação deve ser realizada durante 15 minutos no dia 27/04/2023. Será realizado um sorteio para a ordem dos trabalhos.

● O código deve ser disponibilizado no GitHub e informado no Moodle até às 19h do dia 27/04/2023.

● A nota deste trabalho faz parte do GA.

DEFINIÇÃO

Implementar um roteador simulado com quatro interfaces de redes utilizando um algoritmo dinâmico. Pacotes IP simulados de uma máquina remota são enviados para um roteador usando uma de suas quatro interfaces de rede. Estes pacotes devem ser gerados com as seguintes informações em cada pacote: 

(i) endereço IP de origem, 

(ii) endereço IP de destino, 

(iii) TTL e

(iv) TOS.

Pacotes de roteamento devem ser enviados e recebidos para a comunicação entre os roteadores, informando o status das rotas dinamicamente. Os pacotes de roteamento devem possuir as seguintes informações:

(i) rede de destino,

(ii) interface de saída,

(iii) métrica (a ser definida pelo aluno segundo o algoritmo estado do enlace). 

Com o auxílio de uma tabela de roteamento, utilizando o algoritmo estado de enlace, deve-se encaminhar os pacotes para as interfaces corretas ou até mesmo descartar os pacotes. Com isso, cada interface simulada tem uma fila de entrada do roteador. A interface consome pacotes desta fila. Esses pacotes serão lidos e encaminhados para uma interface de acordo com a indicação registrada na tabela de roteamento atual. 

O roteador simulado deve:

• Analisar e validar as informações do cabeçalho do pacote IP.

• Analisar e validar as informações do protocolo de roteamento.

• Interpretar as funções necessárias de acordo com as informações dos cabeçalhos dos pacotes.

• Entregar os pacotes às interfaces indicadas na tabela de roteamento.

• Poder escolher entre o algoritmo Vetor a Distância e o algoritmo estado de enlace
