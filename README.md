Descrição do Projeto

Este projeto foi desenvolvido para automatizar o controle de iluminação em fábricas e galpões, proporcionando eficiência energética e conveniência operacional. Utilizamos uma placa Blackboard da Robocore, que é compatível com Arduino e ideal para projetos eletrônicos devido à sua robustez e características. O sistema foi projetado para acionar e desligar lâmpadas conectadas a partir de um sensor infravermelho (IR) , controlado remotamente.

Componentes Utilizados:
Placa Blackboard da Robocore: Atuoso como o microcontrolador principal para gerenciar a lógica de funcionamento e comunicação entre os dispositivos.
Sensor Infravermelho (IR): Permite a recepção de comandos do controle remoto, identificando sinais específicos para desligar ou desligar as lâmpadas.
Controle Remoto: Enviado com o sensor IR, utilizado para enviar os comandos de acionamento.
Relés de Potência: Responsáveis ​​por conectar e desconectar o circuito das lâmpadas à rede elétrica, conforme os comandos recebidos pela placa Blackboard.
Lâmpadas de Alta Eficiência: Garantiram boa iluminação e economia de energia.
Fonte de Alimentação: fornece energia estável para o sistema.
Funcionamento do Sistema:
Recepção do Sinal IR: O sensor infravermelho recebe o sinal emitido pelo controle remoto. Cada botão do controle remoto está configurado para enviar um código único.
Processamento do Comando: A placa Blackboard decodifica o sinal recebido e identifica se o comando é para ligar ou desligar as lâmpadas.
Ação dos Relés: Dependendo do comando, o relé correspondente é acionado, conectando ou desconectando as lâmpadas do circuito elétrico.
Feedback Visual: Um LED na placa sinalizando que o comando foi recebido e executado com sucesso, permitindo monitoramento em tempo real.

O software desenvolvido IDE 2.3.3
