# Título:
Trava Mecânica e RFID

# Descrição
Sistema de abertura de caixa usando uma mini trava mecânica, Arduino e leitor RFID.

# Pré-requisitos
Para o circuito da trava mecânica com RFID vamos utilizar o seguinte material:

1x Fechadura Mecânica

1x Kit módulo leitor RFID Mrfc522 Mifare

1x Placa UNO R3

1x Servo Motor

1x Dobradiça 

1x fonte de 9-12V

Fios variados

# Funcionamento
A trava mecânica funciona aplicando uma tensão de 12V em seus terminais. Então o pino da trava é recolhido, mantendo-se na posição enquanto a tensão estiver sendo aplicada. Quando não há tensão, o pino volta ao seu estado normal. A trava foi testada também com uma fonte de 9V e notou-se apenas que a força de recolhimento foi reduzida, mas não impediu o funcionamento.

Como o Arduino trabalha em seus pinos apenas com 5V e uma corrente relativamente baixa (20mA) para acionamento de dispositivos, um relé pode ser usado para acionar dispositivos que requerem mais de 5V e correntes maiores como é o caso da trava elétrica solenoide. A trava elétrica solenóide precisa de 12V e 600mA para funcionar corretamente.

# Uso
Usado para abertura de caixa usando uma mini trava elétrica mecânica, Arduino e leitor RFID.

# Créditos
Projeto formulado pelos alunos Thales Fernandes, Lucas de Paula Martins, Guilherme Moreira, Lucas Luiz, Isis Yasmin e Andre Nassif do Centro Federal de Educação Tecnológica de Minas Gerais do curso de Eletrotécnica, sobre a tutela do professor Epaminondas Lage.
