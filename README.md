# Título:
Trava Eletrônica e RFID

# Descrição
Sistema de abertura de caixa usando uma mini trava elétrica solenoide, Arduino e leitor RFID.

# Pré-requisitos
Para o circuito da trava eletrônica com RFID vamos utilizar o seguinte material:
1x Mini trava elétrica Solenoide 12V
1x Módulo Relé 5V 1 Canal
1x Kit módulo leitor RFID Mrfc522 Mifare
1X LED Verde
1X LED Vermelho
2x Resistores 1Kohm
1x Placa UNO R3
1x fonte de 9-12V

# Funcionamento
A trava elétrica solenoide funciona aplicando uma tensão de 12V em seus terminais. Então o pino da trava é recolhido, mantendo-se na posição enquanto a tensão estiver sendo aplicada. Quando não há tensão, o pino volta ao seu estado normal. A trava foi testada também com uma fonte de 9V e notou-se apenas que a força de recolhimento foi reduzida, mas não impediu o funcionamento.

Como o Arduino trabalha em seus pinos apenas com 5V e uma corrente relativamente baixa (20mA) para acionamento de dispositivos, um relé pode ser usado para acionar dispositivos que requerem mais de 5V e correntes maiores como é o caso da trava elétrica solenoide. A trava elétrica solenóide precisa de 12V e 600mA para funcionar corretamente.

# Uso
Usado para abertura de caixa usando uma mini trava elétrica solenoide, Arduino e leitor RFID.

# Créditos
Projeto formulado pelos alunos do Centro Federal de Educação Tecnológica de Minas Gerais do curso de Eletrotécnica, sobre a tutela do professor Epaminondas Lage. 
